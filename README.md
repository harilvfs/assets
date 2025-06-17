reference : this topic is basically start from [here](https://github.com/ratatui/ratatui/pull/1905#issuecomment-2973657343) you can have a view first.

tl;dr

basically i am having a conversation with @joshka and @orhun about using bun instead of npm.

### what is bun?

if you haven’t heard of bun, it’s a javascript runtime, packager, bundler, test runner kind of all in one.  
it’s designed to be much faster than npm and other tools.  
i will not take more long about the intro, you can view [bun site](https://bun.sh/) and [bun github](https://github.com/oven-sh/bun).

### benchmark or basically test

i have tested this on my machine and honestly, i didn't see a huge diff in `npm run build` vs `bun run build`. sometimes npm is faster, sometimes bun.

but there is a clear improvement in `bun install`. it’s much faster at installing packages.

so basically i am convinced with bun when it comes to package installation.

but for deployment, build matters more. i deployed this through cloudflare and surprisingly npm finished the build faster than bun:

| command | time |
|---------|---------|
| `npm run build (cloudflare)` | 3.32 minutes |
| `bun run build (cloudflare)` | 4.12 minutes |  

(*this may be because the build process doesn’t depend much on npm or bun directly; it’s mostly astro and third-party tools underneath, which may not be well-optimized for bun yet. and i don't see a clear installation or guide for bun on [starlight's site](https://starlight.astro.build/getting-started/) this might be a part of it.*)

but when it comes to installing packages, bun certainly wins:

| npm install | bun install |
|------------|---------|
| ![2025-06-16_21-26](https://github.com/user-attachments/assets/0f314a84-994b-4c12-bae9-1c80603c3267) | ![2025-06-16_21-38](https://github.com/user-attachments/assets/e2e020eb-8a59-4d9f-bd93-f51ba7a796d7) |  

### kind of summary

the main reason we don't see much diff in build is because the build process is mostly performed by astro, not bun or npm directly.

but in a big project like this, we want contributors especially new contributors to have a better experience.  
installing packages faster and using a more efficient tool can make a big difference in development(daily development).

i'm not saying we should use it immediately or ignoring that “just works” is often enough.  
but we should at least consider a more efficient tool if we want the best experience for contributors or for maintainerr too.

all opinions and arguments are welcome! please share them in the comments.  
thank you


> [!CAUTION]
> **This is for archival purposes only. Please do not use or modify this content.**

<br>

<p align="center">
<a href="https://discord.com/invite/8NJWstnUHd">
<img src="https://invidget.switchblade.xyz/8NJWstnUHd" width="350">
</a>
</p>

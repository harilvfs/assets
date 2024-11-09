<div align="center">

<img src="https://github.com/harilvfs/carch/blob/main/preview/penguin.png" />
</div>

# Carch Documentation

**Carch** is a user-friendly Bash script that simplifies the setup process for Arch and Arch-based Linux systems. This documentation serves as a guide for using, contributing to, and understanding the features of Carch.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Script Overview](#scripts)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Code of Conduct](#code-of-conduct)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

## Introduction

<img src="https://github.com/harilvfs/carch/blob/main/docs/assets/introduction.png"/>

Carch aims to automate and streamline the initial setup of Arch Linux, making it easier for users to configure their systems efficiently. The script encompasses various setup tasks, including package installations, theme configurations, and window manager setups.

## Features

<img src="https://github.com/harilvfs/carch/blob/main/docs/assets/feature.png"/>

- **Easy Setup:** Quick and straightforward installation of essential packages.
- **TUI Navigation:** A text-based user interface that enhances user experience.
- **Multiple Scripts:** Automate the setup of various environments, including Dwm and Hyprland.
- **Active Development:** Continuous updates and new features based on community feedback.

![Carch Screenshots](https://github.com/harilvfs/carch/raw/main/preview/carch.gif)

## Installation

<img src="https://github.com/harilvfs/assets/blob/main/carch/installation.png" width="50" /> 

To install Carch, execute the following command in your terminal:

```bash
bash <(curl -L https://chalisehari.com.np/carch)
```

## Usage

<strong>Simply run Carch by entering carch in your terminal.</strong>
```bash
carch
```

> [!Tip]
> You don't need to run the installation script every time. You can run it once, and then simply type carch in your terminal whenever you want to automatically execute the Carch script.

## Scripts

<img src="https://github.com/harilvfs/assets/blob/main/carch/terminal.png" width="50" /> 

<strong>*Carch comes with the following scripts to configure various aspects of your Arch-based system:*</strong>

### Dwm Setup
- Quickly sets up the Dwm window manager with a single-click script, using my customized configuration.

### Hyprland Setup
- Installs the Hyprland compositor along with my pre-configured dotfiles for a streamlined setup.

### i3wm Setup
- Installs and configures i3, providing a lightweight and efficient window management experience.

### Install Fonts
- Downloads and installs a variety of Nerd Fonts for improved readability and aesthetics in terminal applications.

### Install LTS Kernel
- Installs the Long-Term Support (LTS) kernel for enhanced stability and extended support.

### Install Packages
- Installs a curated selection of essential packages to establish a fully functional environment.

### Setup Alacritty
- Configures the Alacritty terminal emulator using my preferred settings for optimal performance.

### Setup AUR
- Installs AUR (Arch User Repository) helpers, like Paru or Yay, to simplify package management.

### Setup Fastfetch
- Configures Fastfetch to display detailed system information quickly and attractively in the terminal.

### Setup GRUB
- Customizes the GRUB bootloader with improved aesthetics and settings for a more polished boot experience.

### Setup Kitty
- Sets up the Kitty terminal emulator with advanced features and custom configurations.

### Setup Neovim
- Installs and configures Neovim for an enhanced, efficient code editing environment.

### Setup Picom
- Installs and configures the Picom compositor to enable window transparency, shadows, and other visual effects.

### Setup Rofi
- Configures Rofi as a powerful application launcher and window switcher, improving workflow efficiency.

### Setup SDDM
- Configures the SDDM (Simple Desktop Display Manager) for a streamlined and visually appealing login experience.

### Setup Themes & Icons
- Installs and applies a set of themes and icons to enhance the look and feel of your desktop.

### SwayWM Setup
- Installs and configures the Sway window manager, optimized for Wayland environments.

### Wallpapers
- Installs a selection of wallpapers for a personalized desktop aesthetic.

<br>

## Roadmap
<img src="https://github.com/harilvfs/assets/blob/main/carch/roadmap.png" width="50" /> 

For information on upcoming features and improvements, check the full roadmap here: 

**[View the Roadmap](https://github.com/harilvfs/carch/blob/main/roadmap.md)**

## Contributing
<img src="https://github.com/harilvfs/assets/blob/main/carch/contribute.png" width="50" /> 

Contributions are welcome! To contribute to Carch

Please refer to the **[CONTRIBUTING.md](https://github.com/harilvfs/carch/blob/main/.github/CONTRIBUTING.md)** for more details.

## Code of Conduct
<img src="https://github.com/harilvfs/assets/blob/main/carch/code-of-conduct.png" width="50" /> 

We strive to create a welcoming environment for all contributors. Please read our **[Code of Conduct](https://github.com/harilvfs/carch/blob/main/.github/CODE_OF_CONDUCT.md)** to ensure a positive experience for everyone involved.

## License
<img src="https://github.com/harilvfs/assets/blob/main/carch/licensing.png" width="50" /> 

Carch is licensed under the **Apache-2.0 License**. For more details, see the **[LICENSE](LICENSE)** file.

## Contact
<img src="https://github.com/harilvfs/assets/blob/main/carch/communicate.png" width="50" /> 

If you have any questions or suggestions, feel free to reach out via:

- 📧 Email: [harilvfs@chalisehari.com.np](mailto:harilvfs@chalisehari.com.np)
- GitHub: [harilvfs](https://github.com/harilvfs)

## Acknowledgments
<img src="https://github.com/harilvfs/assets/blob/main/carch/contributors.png" width="50" />

We thank everyone who has contributed to making **Carch** better. Your feedback and contributions are invaluable!

[![Contributors](https://contrib.rocks/image?repo=harilvfs/carch)](https://github.com/harilvfs/carch/graphs/contributors)

---

### Repository Structure

```bash
carch/
├── LICENSE
├── PKGBUILD
├── README.md
├── binarybuild.sh
├── build
│   └── carch
├── carch.desktop
├── clean.sh
├── clean.sh.x.c
├── cxfs.sh
├── cxfs.sh.x.c
├── docs
│   ├── assets
│   │   ├── carchp.png
│   │   ├── carchp1.png
│   │   ├── communicate.png
│   │   ├── contribute.png
│   │   ├── doc.png
│   │   ├── documentation.png
│   │   ├── feature.png
│   │   ├── installation.png
│   │   ├── licensing.png
│   │   └── roadmap.png
│   └── index.md
├── package.json
├── preview
│   ├── arch.png
│   ├── archi.png
│   ├── bash.png
│   ├── carch.gif
│   ├── carchp.png
│   ├── carchp1.png
│   ├── linux.png
│   ├── package.png
│   └── penguin.png
├── run
│   └── cleanrun.sh
├── run.sh
├── scripts
│   ├── Dwm Setup.sh
│   ├── Hyprland Setup.sh
│   ├── Install Fonts.sh
│   ├── Install LTS Kernal.sh
│   ├── Install Packages.sh
│   ├── README.txt
│   ├── Setup Alacritty.sh
│   ├── Setup Aur.sh
│   ├── Setup Fastfetch.sh
│   ├── Setup GRUB.sh
│   ├── Setup Kitty.sh
│   ├── Setup Neovim.sh
│   ├── Setup Picom.sh
│   ├── Setup Rofi.sh
│   ├── Setup SDDM.sh
│   ├── Setup Themes-Icons.sh
│   ├── SwayWM Setup.sh
│   ├── Wallpapers.sh
│   └── i3wm Setup.sh
├── setup.sh
└── setup.sh.x.c

```
---

Thank you for exploring Carch!



<div align="center">
<strong> Note: This is for archival purposes only. Please do not use or modify this content. </strong>
</div>
<br>

<div align="center">

<img src='https://github.com/harilvfs/assets/blob/main/harilvfs/linux.png' width="80"> <img src='https://github.com/harilvfs/assets/blob/main/harilvfs/terminsl.png' width="80"> <img src='https://github.com/harilvfs/assets/blob/main/harilvfs/listen.png' width="80"> 
</div>

<div align="center">

![Repo View](https://komarev.com/ghpvc/?username=aayushx402&style=for-the-badge&color=blueviolet)

<img src='https://github.com/harilvfs/assets/blob/main/github-gifs/mario.gif' width="500">
  
[![Join on Discord](https://discord.com/api/guilds/757266205408100413/widget.png?style=shield)](https://discord.gg/TAaVXT95)

<a href="chalisehari.com.np"><img alt="Visit the website" height="30" src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/documentation/website_vector.svg"></a>
<a href="https://discord.com/invite/8NJWstnUHd"><img alt="Discord Server" height="30" src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/social/discord-plural_vector.svg"></a>

 <a href="https://github.com/harilvfs">
       <picture>
           <source height="24px" media="(prefers-color-scheme: dark)" srcset="https://i.ibb.co/dMMmCrW/Git-Hub-Mark.png" />
           <img height="24px" src="https://i.ibb.co/9wV3HGF/Git-Hub-Mark-Light.png" />
       </picture>
   </a>&nbsp;&nbsp;&nbsp;
   <a href="https://discord.com/invite/8NJWstnUHd">
       <picture>
           <source height="24px" media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/13122796/178032563-d4e084b7-244e-4358-af50-26bde6dd4996.png" />
           <img height="24px" src="https://user-images.githubusercontent.com/13122796/178032563-d4e084b7-244e-4358-af50-26bde6dd4996.png" />
       </picture>
   </a>&nbsp;&nbsp;&nbsp;
   <a href="https://reddit.com/u/aayush-le">
       <picture>
           <source height="24px" media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/13122796/178032351-9d9d5619-8ef7-470a-9eec-2744ece54553.png" />
           <img height="24px" src="https://user-images.githubusercontent.com/13122796/178032351-9d9d5619-8ef7-470a-9eec-2744ece54553.png" />
       </picture>
   </a>&nbsp;&nbsp;&nbsp;
   <a href="https://t.me/harilvfs">
      <picture>
         <source height="24px" media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/13122796/178032213-faf25ab8-0bc3-4a94-a730-b524c96df124.png" />
         <img height="24px" src="https://user-images.githubusercontent.com/13122796/178032213-faf25ab8-0bc3-4a94-a730-b524c96df124.png" />
      </picture>
   </a>&nbsp;&nbsp;&nbsp;
   <a href="https://x.com/harilvfs">
      <picture>
         <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/93124920/270180600-7c1b38bf-889b-4d68-bd5e-b9d86f91421a.png">
         <img height="24px" src="https://user-images.githubusercontent.com/93124920/270108715-d80743fa-b330-4809-b1e6-79fbdc60d09c.png" />
      </picture>
   </a>&nbsp;&nbsp;&nbsp;
   <a href="https://www.youtube.com/@aayushchalese">
      <picture>
         <source height="24px" media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/13122796/178032714-c51c7492-0666-44ac-99c2-f003a695ab50.png" />
         <img height="24px" src="https://user-images.githubusercontent.com/13122796/178032714-c51c7492-0666-44ac-99c2-f003a695ab50.png" />
     </picture>
   </a>&nbsp;&nbsp;&nbsp;
   <a href="https://bsky.app/profile/chalisehari.com.np">
      <picture>
         <source height="25px" media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/harilvfs/assets/refs/heads/main/bluesky/Bluesky_app_icon.svg" />
         <img height="25px" src="https://raw.githubusercontent.com/harilvfs/assets/refs/heads/main/bluesky/Bluesky_app_icon.svg" />
     </picture>
   </a>
</div>

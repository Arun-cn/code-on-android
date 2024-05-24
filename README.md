![cover](cover.png)

# <h1 align="center">CODE ON ANDROID</h1>

This repository provides information and guides on the best ways and tools to code on Android. It covers both online and offline editors, including their features and setup instructions.

## Table of Contents
1. [Online Editors](#online-editors)
    - [IDEX](#idex)
    - [Repl.it](#repl-it)
2. [Offline Editors](#offline-editors)
    - [VS Code (VS Code Server)](#vs-code-(vs-code-server))
    - [Neovim](#neovim)
    - [Acode](#acode)
3. [Supporting Languages](#supporting-languages)
    - [Java](#java)
    - [JavaScript](#javascript)
    - [C/C++](#cc)
4. [Termux Setup](#termux-setup)
    - [Node.js](#nodejs)
    - [Code Server](#code-server)
    - [Neovim](#neovim-termux)

## Online Editors

### IDEX
IDEX is a powerful online editor that supports multiple languages and has a rich set of features for coding on Android.

- **Features:**
  - Syntax highlighting
  - Code completion
  - Integrated terminal
  - Git integration

### Repl.it
Repl.it is another versatile online editor that supports collaborative coding and has a user-friendly interface.

- **Features:**
  - Real-time collaboration
  - Multiple language support
  - Integrated console
  - Cloud-based

## Offline Editors

### VS Code ( VS Code Server )

VS Code is a popular code editor renowned for its extensive extensions and customization options.

### Pre-Requirements:
Ensure you have the following before proceeding:
- Latest Chrome browser
- Termux
- (Optional) Hackers Keyboard (best keyboard for efficient work)
- (Optional) External keyboard and mouse
- (Optional) Use tablet or external monitor or desktop modes on some phones like Samsung DeX, etc.

### Installation Guide:
1. Get Termux from F-Droid.
2. Run:
   ```sh
    pkg install tur-repo
    ```
4. Run:
   ```sh
   pkg install code-server
   ```
6. Start Code Server by simply running:
   ```sh
   code-server
   ```
8. Access VS Code in your Chrome browser using the provided local URL.

Enjoy coding with VS Code's powerful features and enhanced browsing experience, optimized for keyboard interactivity.

### Neovim
Neovim is a highly configurable text editor, ideal for power users.

- **Features:**
  - Modal editing
  - Highly customizable
  - Lightweight
  - Vim script support

#### Installation Guide:
1. Install Neovim:
    ```sh
    pkg install neovim
    ```
2. Configure Neovim using your `.config/nvim/init.vim` file.

### Acode
Acode is a lightweight code editor for Android with support for various languages and Git.

- **Features:**
  - Syntax highlighting
  - Git integration
  - Multiple tabs
  - FTP/SFTP support

## Supporting Languages

### Java
Install Java Development Kit (JDK) on Termux:
```sh
pkg install openjdk-17
```

## Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for more information on how to get started.

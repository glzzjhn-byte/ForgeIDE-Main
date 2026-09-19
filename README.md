<div align="center">
  <img src="https://raw.githubusercontent.com/glzzjhn-byte/IDE_Custom/v2/src/main/resources/ImagesAsset/GlzzLexiBear-Logo.png" alt="Forge IDE Logo" width="150" height="150"/>
  <h1>Forge IDE v2.0</h1>
  <p><strong>A modern, fast, and highly customizable IDE built for C++, Python, and Lua developers.</strong></p>
  
  <p>
    <a href="https://github.com/glzzjhn-byte/ForgeIDE-Main/releases/latest"><img src="https://img.shields.io/github/v/release/glzzjhn-byte/ForgeIDE-Main?style=flat-square&color=50FA7B" alt="Latest Release"></a>
    <a href="LICENSE.txt"><img src="https://img.shields.io/badge/License-Freeware-blue.svg?style=flat-square" alt="License"></a>
    <a href="https://github.com/glzzjhn-byte/ForgeIDE-Main/releases"><img src="https://img.shields.io/github/downloads/glzzjhn-byte/ForgeIDE-Main/total?style=flat-square" alt="Downloads"></a>
  </p>
</div>

<hr/>

## ?? Overview

**Forge IDE** is a lightweight yet incredibly powerful integrated development environment tuned for modern polyglot development. Built by a solo developer, it features blazing-fast performance, deep OS integration, and cutting-edge **local offline AI assistance** to supercharge your workflow.

## ? What's New in V2.0!

The V2.0 update brings massive architectural changes to Forge IDE, transforming it from a simple C++ editor into an intelligent, agentic workspace:

- ?? **Agentic AI Chatbot**: The built-in AI chatbot can now actively code *for* you. Click the new **Apply** button on any AI-generated code block to instantly inject or replace code directly inside your editor.
- ?? **Dynamic AI Model Manager**: You are no longer locked to hardcoded models! The new Model Manager detects your PC's RAM, recommends the best model (like codegemma:2b), and automatically manages the download of both Chat and Autocomplete (-base) models via Ollama.
- ?? **Visual Breakpoint Debugger**: The debugger has been entirely overhauled. You can now set breakpoints simply by clicking the line numbers in the editor margin (spawning a visual red dot ?). 
- ?? **Python & Lua Support**: We've expanded beyond C++! Forge IDE now officially supports Python script execution and debugging (via debugpy), as well as Lua syntax and compilation.
- ??? **Standalone System Diagnostics**: IDE background logs and AI engine status are now cleanly separated into a dedicated *System Diagnostics Logger* window, keeping your application's run terminal completely clean.

## ??? Core Features

- **Native Windows Experience**: Packaged with a private Java runtime environment. Requires zero external dependencies. Install it and start coding immediately.
- **Intelligent Syntax Highlighting**: Real-time syntax tracking with full support for C/C++, Python, and Lua.
- **Plugin Architecture**: Deep IPC (Inter-Process Communication) plugin system. Extend the IDE safely with external tools without risking core stability.
- **Built-in Compiler Management**: Seamless integration with MinGW/g++ and Python interpreters. Compile and run your code with a single click.

## ?? Installation

1. Go to the [Releases page](https://github.com/glzzjhn-byte/ForgeIDE-Main/releases/latest).
2. Download the latest CppForgeIDE_Installer_v2.exe.
3. (Optional) Verify the .sig GPG signature using Kleopatra or Gpg4win to ensure file integrity.
4. Run the installer. 
> *Note: Since this is an indie application, Windows SmartScreen may show an "Unknown Publisher" warning. Click **More Info** -> **Run Anyway**.*

## ?? Security & Verification

We take supply chain security seriously. Every release is mathematically signed with GPG.

1. Download our Public Key (available in this repository).
2. Download the .exe and .sig files from the latest release.
3. Verify the installer against the signature to ensure it has not been tampered with.

## ?? License

This software is distributed as **Freeware**. It is not open-source, but it is completely free to use for personal, educational, and commercial purposes. 

Please read the LICENSE.txt file for more details regarding data collection, telemetrics, and liability.

<div align="center">
  <sub>Built with ?? by GlzzLexiBear Co.</sub>
</div>

# 🎮 grandchase-mac - Play GrandChase Classic on Apple Silicon

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/Emaminor818/grandchase-mac/releases)

This project allows users to play GrandChase Classic on macOS computers with Apple Silicon processors. It removes the need for paid software like CrossOver. The setup uses a combination of Wine, Proton, DXVK, and MoltenVK to translate Windows game instructions into a format that macOS understands.

## 🛠 Prerequisites

Before you start, ensure your computer meets these requirements:

* An Apple Silicon Mac (M1, M2, or M3 series chip).
* macOS version 13.0 or newer.
* At least 10GB of free disk space on your internal drive.
* An active Steam account with GrandChase Classic added to your library.
* A stable internet connection for the initial setup.

## 📥 Download and Setup

Follow these steps to prepare your system and run the game.

1. Visit the [official release page](https://github.com/Emaminor818/grandchase-mac/releases) to download the latest version of the application.
2. Select the file ending in `.dmg` to download the installer.
3. Open the downloaded file once the transfer completes.
4. Drag the GrandChase icon into your Applications folder as prompted.
5. Open the GrandChase application from your Applications folder.

Your first launch may take a few minutes. The software verifies your system files and configures the translation layers during this time. Do not close the window while the progress bar shows activity.

## ⚙️ Configuring Steam

The software relies on your Steam installation. Follow these steps to ensure the game links correctly:

1. Launch the Steam application on your Mac.
2. Log in using your existing account credentials.
3. Locate GrandChase Classic in your Library.
4. If you have not installed the game yet, click the blue Install button inside Steam.
5. Once the game download finishes, return to the grandchase-mac application.
6. Select the "Link Steam" button from the main menu.
7. Point the file selector to the location where your Steam library stores its game data.

## 🚀 Performance Tips

You might experience minor stutters during the first time you enter a mission. This happens while the system compiles shaders. You can improve performance by following these steps:

* Close background applications like web browsers or video editors before you play.
* Keep your Mac plugged into power while running the game.
* Ensure you installed the latest version of the macOS operating system.
* Reduce graphic settings inside the in-game menu if the frame rate drops.

## 🛡 Security and Privacy

This project uses open-source components to allow Windows applications to run on your Mac. It does not modify your personal files outside of the game folder. It only interacts with the specific files required to launch the game. You remain in control of your data at all times.

## 🔍 Troubleshooting Common Issues

Use this list if the game fails to start or behaves in an unexpected way.

### The application will not open
If macOS prevents the application from opening, right-click the file and select Open. Confirm your choice in the pop-up window. This bypasses security settings for software not downloaded directly from the App Store.

### The game screen stays black
Return to the main menu of the grandchase-mac application. Select the "Reset Graphics Cache" option. Quit the game and relaunch it. This clears old configuration files that might conflict with your current setup.

### The game closes during login
Check your internet connection. GrandChase requires a consistent connection to the game servers. If your internet is stable, verify your game files through Steam. To do this, right-click GrandChase in Steam, select Properties, choose Installed Files, and select Verify integrity of game files.

## 📚 Technical Details

This software bridges the gap between Windows and macOS using the following components:

* **Wine-Proton:** Translates Windows system calls to macOS instructions.
* **DXVK:** Converts Windows graphics instructions (DirectX) into a language your Mac hardware understands (Vulkan).
* **MoltenVK:** Allows the Vulkan code to talk to your Mac's graphics hardware through the Apple Metal framework.

These tools work together in the background. You do not need to interact with them directly. The installation process handles all necessary settings automatically.

## 📌 Frequently Asked Questions

**Will this software trigger an anti-cheat ban?**
GrandChase Classic allows play through this method as it strictly handles the translation of the game files. It does not inject code into the game process or modify memory to provide an unfair advantage.

**Can I use a controller?**
Yes. Steam handles controller recognition. If your controller works in Big Picture mode on Steam, it will work in the game.

**Does this software cost money?**
No. This project remains free and open-source. Never pay for copies of this software from third-party sites. Always use the official link provided here.

**How do I update the game?**
Updates occur through Steam automatically. If a major update changes how the game runs, check the release page again to see if a new version of the grandchase-mac tool is available.

**Can I run other Windows games with this?**
This tool is specifically designed for GrandChase Classic. While the underlying technology supports other games, this application only configures the requirements for this specific title. 

## 📝 Support

If you encounter persistent issues, check the release page for updates. The developer publishes fixes based on community feedback. Ensure you describe your Mac model and the specific error message you see when you ask for help. Providing this information helps resolve issues faster.
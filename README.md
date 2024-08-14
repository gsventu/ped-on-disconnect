# 🚀 Ped Sleep on Quit Script for FiveM

Welcome to the **Ped Sleep on Quit** script for FiveM, a tool designed to enhance your server's roleplay experience by adding immersive features for disconnected players. 

## 📝 Overview

When a player disconnects from the server, their ped (character) will be saved at the exact location and automatically transition into a sleeping animation. This creates a more immersive environment where players don't just vanish. Additionally, the script includes configurable options for added realism and security.

## 🎯 Features

- **Automatic Ped Handling**: Upon disconnection, the player's ped is saved and animated to sleep at their last known location.
- **Configurable Options**: Easily toggle options for freezing the ped in place and enabling godmode for protection.
- **Secure Implementation**: Built-in anti-cheat measures to prevent exploitation.
- **Automatic Ped Removal**: Automatically removes the saved ped when the player reconnects to ensure seamless gameplay.

## ⚙️ Configuration

### `config.lua`

This file allows you to configure key options:

```lua
Config = {}

-- Set to true to freeze the ped so it won't react to aiming or other actions
Config.FreezePed = true

-- Set to true to enable godmode so the ped can't be harmed
Config.PedGodmode = true
```

- **FreezePed**: Prevents the ped from reacting to nearby actions (like aiming).
- **PedGodmode**: Makes the ped invincible to damage.

## 🚀 Installation

- **Download the Script**: Clone or download the repository to your resources folder in your FiveM server.
- **Add to Server Config**: Add start ped_sleep_on_quit to your server.cfg.
- **Customize**: Adjust the settings in config.lua as needed.
- **Restart Server**: Restart your FiveM server to apply the changes.

## 🛡️ Security
The script includes basic security measures, such as:

- **Resource Name Validation**: Ensures the script only runs under the correct resource name.
- **Player ID Validation**: Validates player IDs before performing any actions.
- **Anti-Cheat Event Logging**: Logs and potentially cancels suspicious activities.

## 🤝 Contributing
Contributions are welcome! If you have suggestions, feel free to fork the repository, make your changes, and submit a pull request.

## 📧 Contact
For any questions or support, feel free to reach out via discord.
My discord: bakajlando2

# AntiAfkFarm - Multi-Account Verification Challenge Plugin

**Author:** macronis  
**Version:** 1.0.0  
**API:** PaperMC 1.20+ / 1.21+

## 📋 Description

AntiAfkFarm is a sophisticated PaperMC plugin designed to detect and prevent multi-account abuse by challenging players who connect from the same IP address. When multiple accounts are detected from a single IP, players must complete an interactive verification challenge to prove they are legitimate users.

## ✨ Features

### 🎯 Core Features
- **Intelligent IP Tracking**: Automatically detects when multiple accounts connect from the same IP
- **Interactive Challenge GUI**: Players must click randomized red glass panes in a 6×9 inventory
- **Configurable Challenge**: Customize time limits, pane counts, and ban durations
- **LuckPerms Integration**: Grants 5-hour temporary bypass permissions to verified players
- **Dual Challenge Mode**: Option to challenge both accounts or only the new connection
- **Admin Commands**: Force challenges, check status, and reload configuration
## 📦 Requirements

- **Server**: PaperMC 1.20+ or 1.21+
- **Java**: 17 or higher
- **Dependencies**:
- LuckPerms (required for bypass permission system)
  
## 🚀 Installation

1. Download the latest `AntiAfkFarm-1.0.0.jar` from releases
2. Place the jar file in your server's `plugins/` folder
3. Ensure LuckPerms is installed
4. Restart or reload your server
5. Configure `plugins/AntiAfkFarm/config.yml` to your preferences
6. Reload the plugin with `/mv reload`

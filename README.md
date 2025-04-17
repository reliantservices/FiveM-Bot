<div align="center">
  <h1>🎮 FiveM Discord Bot</h1>
  <p>A powerful, feature-rich Discord bot designed specifically for FiveM gaming communities</p>
  
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
  [![Discord](https://img.shields.io/discord/1324549263044378754?color=7289da&label=Discord&logo=discord&logoColor=white)](https://discord.gg/reliantt)
  [![Stars](https://img.shields.io/github/stars/reliantservices/FiveM-Bot?style=social)](https://github.com/reliantservices/FiveM-Bot/stargazers)
</div>

---

## 📋 Table of Contents
- [Features](#-features)
- [Requirements](#-requirements)
- [Installation](#-installation)
- [Configuration](#-configuration)
- [Commands](#-commands)
- [Support](#-support)
- [Contributing](#-contributing)
- [License](#-license)

## 🚀 Features

### 🛡️ Administration
- **Auto Roles**
  - Automatic role assignment on join
  - Role hierarchy management
  - Configurable role sets
- **Status Blacklist**
  - Automated moderation of user statuses
  - Configurable actions (ban/kick/role)
  - Pattern matching support
- **Mass Management**
  - Bulk member unbanning
  - Message purging with filters
  - Role management tools

### 🎮 FiveM Integration
- **Server Management**
  - Real-time server status monitoring
  - Automated restart notifications
  - Player count tracking
  - Server information display
- **Tebex Integration**
  - Purchase verification
  - Transaction logging
  - Automated role assignment
  - Store analytics
- **Gang System**
  - Priority management
  - Territory control
  - Gang statistics

### 🤝 Community Tools
- **Application System**
  - Custom application forms
  - Staff review process
  - Application tracking
  - Automated responses
- **Verification**
  - Multiple verification methods
  - Anti-bot protection
  - Role integration
  - Custom workflows
- **Staff Feedback**
  - Rating system
  - Performance tracking
  - Feedback analytics
  - Staff leaderboards

### 📢 Content Management
- **Sticky Messages**
  - Persistent channel messages
  - Rich embed support
  - Dynamic updates
- **Custom Embeds**
  - Interactive components
  - Dynamic content
  - Template system
- **Welcome System**
  - Custom welcome images
  - Dynamic messages
  - Multi-channel support

## 💻 Requirements

### System Requirements
- Node.js 18.0.0 or higher
- MongoDB 4.4 or higher
- Discord.js v14
- FiveM Server

### Recommended Specs
- 1GB RAM minimum
- Dual-core processor
- Stable internet connection

## 📥 Installation

1. **Clone the Repository**
```bash
git clone https://github.com/reliantservices/FiveM-Bot.git
cd FiveM-Bot
```

2. **Install Dependencies**
```bash
npm install
```

3. **Configure Environment**
```bash
cp .env.example .env
# Edit .env with your settings
```

4. **Start the Bot**
```bash
npm start
```

## ⚙️ Configuration

### Essential Settings
```env
DISCORD_TOKEN=your_bot_token
MONGODB_URI=your_mongodb_uri
FIVEM_SERVER_IP=your_server_ip
TEBEX_SECRET=your_tebex_secret
```

### Optional Features
```env
WELCOME_CHANNEL=channel_id
LOGS_CHANNEL=channel_id
VERIFICATION_ROLE=role_id
```

## 🎯 Commands

### Administrative
- `/autoroles setup` - Configure auto role system
- `/status_blacklist add` - Add blacklisted terms
- `/mass-unban` - Bulk unban members

### FiveM Related
- `/server status` - Check server status
- `/tebex verify` - Verify purchases
- `/gang priority` - Manage gang priorities

### Community
- `/applications create` - Create application forms
- `/verify setup` - Configure verification
- `/staff feedback` - Manage staff ratings

### Content
- `/sticky create` - Create sticky messages
- `/embed builder` - Create rich embeds
- `/welcome customize` - Customize welcome messages

## 🤝 Support

- [Join Our Discord](https://discord.gg/reliantt)
- [Documentation](https://your-docs-url.com)
- [Issue Tracker](https://github.com/reliantservices/FiveM-Bot/issues)

## 👥 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Credits

- **Lead Developer**: [Reliant]
- **Special Thanks**: Discord.js Team, FiveM Community

---

<div align="center">
  <p>Made with ❤️ for the FiveM Community</p>
  <p>© 2025 Reliant Services. All rights reserved.</p>
</div>

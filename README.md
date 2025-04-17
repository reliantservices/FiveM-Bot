<div align="center">
  <h1>🎮 FiveM Discord Bot</h1>
  <p>A powerful, feature-rich Discord bot designed specifically for FiveM gaming communities</p>
  
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
  [![Discord](https://img.shields.io/discord/528409370623737857?color=7289da&label=Discord&logo=discord&logoColor=white)](https://discord.gg/reliantt)
  [![Stars](https://img.shields.io/github/stars/reliantservices/FiveM-Bot?style=social)](https://github.com/reliantservices/FiveM-Bot/stargazers)
</div>

---

## 🤝 Purchase
- **Source Code** - 80$
- **Lifetime** - 25$
- **Monthly** - 10$
- [Join Our Discord](https://discord.gg/reliantt)
- [Website](https://reliant.mysellauth.com/)
- [Issue Tracker](https://github.com/reliantservices/FiveM-Bot/issues)


## 📋 Table of Contents
- [Features](#-features)
- [Requirements](#-requirements)
- [Commands](#-commands)
- [Purchase](#-purchase)
- [License](#-license)

## 🚀 Features

### 🛡️ Administration
- **Auto Roles**
  - Automatic role assignment on join
  - Role hierarchy management
  - Configurable role sets
  - Commands: `/autoroles create`, `/autoroles list`, `/autoroles delete`
  - Persistent configuration through MongoDB

- **Status Blacklist**
  - Automated moderation of user statuses
  - Configurable actions (ban/kick/role)
  - Pattern matching support
  - Commands: `/status_blacklist add`, `/status_blacklist del`, `/status_blacklist list`
  - Real-time status monitoring with Discord Presence intent

- **Mass Management**
  - Bulk member unbanning with `/mass-unban`
  - Message purging with filters using `/purge`
  - Administrator permission enforcement

- **Branding Customization**
  - Custom bot status with `/branding status` (Playing, Watching, Listening, Competing, Streaming)
  - Custom embed colors with `/branding colour`
  - Custom embed footers with `/branding footer`
  - Consistent branding across all bot embeds

### 🎮 FiveM Integration
- **Server Restart Notifications**
  - Automated restart notifications
  - TXAdmin webhook integration
  - Customizable notification embeds with `/restarts embed`
  - Server connection information display
  - Setup with `/restarts setup`

- **Tebex Integration**
  - Purchase verification with `/verify`
  - Transaction lookup with `/lookup`
  - Transaction logging
  - Automated role assignment
  - Setup with `/tebex setup`

- **Gang Priority System**
  - Complete gang management system
  - Priority slot allocation and tracking
  - Gang creation with `/gang create`
  - Gang upgrades with `/gang upgrade`
  - Gang lookup with `/gang lookup`
  - Gang listing with `/gang list`
  - Gang deletion with `/gang delete`
  - Priority management with `/prio add` and `/prio remove`
  - Strike system with `/strike add`, `/strike remove`, and `/strike view`
  - Setup with `/gangpriority setup`

### 🤝 Community Tools
- **Application System**
  - Preset application forms:
    - Staff Application (11 questions)
    - EMS Application (10 questions)
    - Police Application (14 questions)
    - Mechanic Application (10 questions)
    - Partnership Application (4 questions)
    - Event Application (4 questions)
  - Multi-stage application process for forms with many questions
  - Staff review process with accept/deny functionality
  - Application tracking and management
  - Automated role assignment for accepted applicants
  - DM notifications for applicants
  - Commands: `/applications create`, `/applications delete`, `/applications multi`

- **Verification System**
  - Four verification methods:
    - Simple Verification - One-click button verification
    - FiveM Passport - Integration with FiveM identity
    - Emoji Captcha - Verification using emoji selection
    - Image Captcha - Verification using image-based captcha
  - Customizable verification embeds with `/verification embed`
  - Role assignment upon verification
  - Setup with `/verification setup`

- **Staff Feedback**
  - Public rating system for staff members
  - Upvote/downvote functionality with `/staff upvote` and `/staff downvote`
  - Reason tracking for feedback
  - Feedback wall for transparency
  - Optional feedback logging channel
  - Setup with `/feedback setup`

- **Community Polls**
  - Create polls with `/poll start`
  - End polls with results using `/poll end`
  - Vote tracking and analytics
  - Customizable poll questions

### 📢 Content Management
- **Sticky Messages**
  - Pin important messages that stay at the bottom of channels
  - Rich embed support with customization
  - Status management (active/paused) with `/stickymessage status`
  - Create with `/stickymessage create`
  - Delete with `/stickymessage delete`
  - Form-based creation with fields for:
    - Message Content
    - Embed Title
    - Embed Description
    - Embed Image

- **Custom Embeds**
  - Interactive embed creation with `/embed generate`
  - Edit existing embeds with `/embed edit`
  - Rich formatting options
  - Color customization
  - Image and thumbnail support
  - Field customization

- **Welcome System**
  - Custom welcome images with server background
  - User profile picture integration
  - Dynamic welcome messages with variables:
    - {member.mention} - Mentions the new member
    - {member.username} - Username of the new member
    - {member.id} - ID of the new member
    - {guild.name} - Name of the server
    - {guild.id} - ID of the server
    - {memberCount} - Current member count
  - Setup with `/welcome setup`

- **Keyword Responses**
  - Create custom responses to specific keywords with `/keyword create`
  - Delete keyword responses with `/keyword delete`
  - List all keyword responses with `/keyword list`
  - Rich embed support for responses

- **Vanity Roles**
  - Reward members for promoting your server in their status
  - Customizable notification system (channel, DM, or both)
  - Automatic role assignment
  - Setup with `/vanityroles setup`
  - Customizable embeds with `/vanityroles embed`

### 🔧 Utility Features
- **Help System**
  - Comprehensive help command with `/help`
  - Detailed command explanations
  - Category-based help navigation
  - Interactive help menu with buttons

## 💻 Requirements

### System Requirements
- Node.js 18.0.0 or higher
- MongoDB Atlass or Compass
- Discord.js
- FiveM Server ( Optional )

### Discord Bot Requirements
- Message Content Intent
- Server Members Intent
- Presence Intent (for vanity roles)

### Recommended Specs
- 1GB RAM minimum
- Dual-core processor
- Stable internet connection


## 🎯 Commands

### Administrative
- `/autoroles create` - Create a new auto role
- `/autoroles list` - List all auto roles
- `/autoroles delete` - Delete an auto role
- `/status_blacklist add` - Add a keyword to the status blacklist
- `/status_blacklist del` - Remove a keyword from the status blacklist
- `/status_blacklist list` - List all blacklisted keywords
- `/mass-unban` - Unban all members from your server
- `/purge` - Delete a specified amount of messages
- `/branding status` - Set the bot's status
- `/branding colour` - Set the color for all embeds
- `/branding footer` - Set the footer for all embeds

### FiveM Related
- `/restarts setup` - Setup the Restarts Module
- `/restarts embed` - Customize the restart notification embed
- `/tebex setup` - Set up the Tebex verification system
- `/lookup` - Look up a Tebex transaction
- `/verify` - Verify a Tebex transaction
- `/gangpriority setup` - Setup the gang priority system
- `/gang create` - Create a new gang
- `/gang upgrade` - Upgrade a gang
- `/gang lookup` - Look up a gang
- `/gang list` - List all gangs
- `/gang delete` - Delete a gang
- `/prio add` - Add priority to a user
- `/prio remove` - Remove priority from a user
- `/strike add` - Add a strike to a gang
- `/strike remove` - Remove a strike from a gang
- `/strike view` - View strikes for a gang

### Community
- `/applications create` - Create an application panel
- `/applications delete` - Delete an application panel
- `/applications multi` - Create a multi-panel with multiple applications
- `/verification setup` - Setup the Verification Module
- `/verification embed` - Customize the verification embed
- `/feedback setup` - Setup the Staff Feedback system
- `/staff upvote` - Upvote a staff member
- `/staff downvote` - Downvote a staff member
- `/poll start` - Start a new poll
- `/poll end` - End an existing poll

### Content
- `/stickymessage create` - Create a new sticky message
- `/stickymessage delete` - Delete a sticky message
- `/stickymessage status` - Change the status of a sticky message
- `/embed generate` - Generate a new embed
- `/embed edit` - Edit an existing embed
- `/welcome setup` - Setup the welcome system
- `/keyword create` - Create a new keyword response
- `/keyword delete` - Delete a keyword response
- `/keyword list` - List all keyword responses
- `/vanityroles setup` - Setup the Vanity Roles Module
- `/vanityroles embed` - Customize the vanity notification embed

### Help
- `/help` - Get detailed help information about commands

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

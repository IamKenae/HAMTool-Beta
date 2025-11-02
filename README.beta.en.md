# HAMTool Beta - Amateur Radio Tool Software (Testing Version)

<div align="center">

![HamTool Logo](public/icon.png)

**⚠️ Experimental Features Testing Version - For Testing Purposes Only**

[🌐 English](./README.beta.en.md) | 🇨🇳 简体中文](./README.beta.zh-CN.md)

[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-blue.svg)](#downloads)
[![Version](https://img.shields.io/badge/Version-Beta-orange.svg)](../../releases)
[![Stability](https://img.shields.io/badge/Stability-Unstable-red.svg)](#beta-version-information)

[📥 Downloads](#downloads) • [✨ Features](#features) • [⚠️ Important Warnings](#important-warnings) • [📖 User Guide](#user-guide) • [📄 License](#license) • [📞 Contact Us](#contact-us)

</div>

## ⚠️ Important Warnings

**This is a BETA test version of HAMTool containing features under development.**

- **🚨 Stability Warning**: Beta versions may contain serious bugs, data loss risks, or application crashes
- **💾 Data Isolation**: Beta versions use separate databases, completely isolated from stable versions
- **🔄 Data Migration**: Supports importing data from stable to beta versions, but reverse migration is not supported
- **🐛 Bug Reporting**: Please report issues at [HAMTool-Beta Repository](https://github.com/IamKenae/HAMTool-Beta/issues)
- **⚠️ Use at Your Own Risk**: Do not use beta versions in production environments or with important data

**Intended for testing users willing to accept risks!**

## 📖 Project Overview

HAMTool Beta is a modern desktop application designed specifically for amateur radio enthusiasts (HAM), integrating comprehensive QSO log management, call sign queries, QTH location management, and other core features. Built with Electron + Vue 3 technology stack, it provides cross-platform support and an elegant user interface. The software supports multi-language internationalization, dark mode switching, offering HAMs a professional, efficient, and convenient user experience.

**Note: This is a Beta version containing experimental features and may experience instability.**

## ✨ Features

### 🎯 Core Features (Beta Testing)
- **📝 QSO Log Management** - Complete QSO recording, editing, searching, and statistical analysis
- **📚 Callbook Management** - Built-in call sign database with fast queries and batch management
- **🌍 QTH Location Services** - Intelligent location input supporting Pinyin, Chinese, and detailed regional data
- **💾 Database System** - Multi-database support with backup/restore and version conflict handling
- **🔄 Data Import Functionality** - Supports importing data from stable HAMTool to Beta versions for testing

### 🎨 User Experience
- **🌍 Multi-Language Support** - Supports Simplified Chinese and English, extensible for more languages
- **🌙 Dark Mode** - Supports automatic and manual light/dark theme switching
- **📱 Responsive Design** - Adapts to different screen sizes, supports mobile access
- **⚡ High Performance** - Built with Electron + Vue 3 for smooth operation
- **🔒 Data Security** - Local data storage with privacy protection and automatic backup

### 🚀 Experimental Features
- **📤 Data Import/Export** - Supports JSON and Excel formats with CC BY-NC-SA 4.0 license protection
- **🔍 Advanced Search & Filter** - Multi-condition filtering, sorting, and full-text search
- **📈 Statistical Analysis** - QSO data statistics and chart visualization
- **🌐 Web Sync Service** - Lab feature supporting LAN access and data synchronization
- **🏷️ Multiple Operation Modes** - Roll call mode and personal QSO recording mode
- **🆕 New Feature Preview** - Early access to features currently under development

### 🛠️ Beta Features
- **🔧 Independent Update Channel** - Beta versions update independently, without affecting stable versions
- **📊 Database Isolation** - Beta version databases are completely isolated from stable versions
- **🌐 Internationalization Framework** - Complete i18n support with translator information display
- **🔌 Plugin Architecture** - Modular design for easy extensibility

## 📥 Downloads

### Beta Version Downloads

> **Note**: Beta versions include new features under development and may contain bugs. Use for testing purposes only.

Visit [HAMTool-Beta Releases](https://github.com/IamKenae/HAMTool-Beta/releases) to download the latest beta versions:

| Platform | File Name | Description |
|----------|-----------|-------------|
| 🪟 Windows | `HAMTool-Beta-Setup-x.x.x.exe` | Windows Installer |
| 🍎 macOS | `HAMTool-Beta-x.x.x.dmg` | macOS Disk Image |
| 🐧 Linux | `HAMTool-Beta-x.x.x.AppImage` | Linux Application Image |

### System Requirements

| Platform | Minimum Requirements | Recommended Configuration |
|----------|----------------------|---------------------------|
| 🪟 Windows | Windows 10 (1903) or higher | Windows 11 |
| 🍎 macOS | macOS 10.15 (Catalina) or higher | macOS 12 (Monterey) or higher |
| 🐧 Linux | Modern Linux distribution with AppImage support | Ubuntu 20.04+ / CentOS 8+ |

**Hardware Requirements**:
- **Memory**: Minimum 4GB RAM, recommended 8GB or more
- **Storage**: At least 500MB available space
- **Network**: Optional, for license verification and automatic updates

## 🚀 Quick Start

### Installation Notes

1. **Backup Stable Data**: Backup important stable version data before installing Beta version
2. **Independent Installation**: Beta can be installed alongside stable version without conflicts
3. **Data Isolation**: Beta versions use independent databases, won't affect stable version data

### First Time Setup

1. **License Activation**: Enter your license key on first launch
   - Community users can obtain free licenses from the activation website
   - Commercial users should contact support for commercial licensing

2. **Language Settings**: Choose your preferred interface language
   - Go to **Settings** → **Interface Language**
   - Select from available languages (Chinese/English)

3. **Database Setup**: Create your first QSO database
   - Go to **Database Management** → **New Database**
   - Enter a descriptive name for your database

### Importing Data from Stable Version

1. **Export from Stable**: Export JSON format data from stable HAMTool
2. **Import in Beta**: Use "Import from Stable Version" feature in Beta version
3. **Select Data**: Choose data types to import
4. **Verify Integrity**: Confirm import and verify data integrity

## 💾 Database Management

### Data Isolation Explanation

- **Independent Storage**: Databases created in Beta versions are completely independent from stable versions
- **Version Isolation**: Databases between different Beta versions are also isolated
- **Safety Mechanism**: Import operations don't affect source data
- **Testing Friendly**: Safely test new features without affecting stable data

### Data Import Process

1. **Export Preparation**: Export data needed for testing from stable version
2. **Beta Import**: Select "Import from Stable Version" in Beta version
3. **Data Selection**: Choose databases and record types to import
4. **Confirm Import**: Verify import results and data integrity

### Important Reminders

- **One-Way Import**: Only supports importing from stable to beta, reverse operation is not supported
- **Data Backup**: Recommended to backup Beta version data before testing
- **Version Compatibility**: Different Beta versions may have data format differences

## 📖 User Guide

### Basic Operations

1. **Add QSO Records**: Click **Log Management** → **Add New Record**
2. **Search Call Signs**: Use **Callbook Management** for quick call sign lookups
3. **Export Data**: Use **Import/Export** → **Export** to save your logs

### Beta Feature Testing

- **New Feature Experience**: Try experimental new features and provide feedback
- **Performance Testing**: Test performance of new features
- **Compatibility Verification**: Verify compatibility with different systems

## 🛠️ Technical Architecture

### Frontend Stack
- **Framework**: Vue 3 (Composition API) + Element Plus
- **Build Tool**: Vite + electron-vite
- **Styling**: Bootstrap 5 + Custom CSS + FontAwesome
- **Internationalization**: Vue I18n
- **State Management**: Vue 3 Reactive API

### Desktop Application
- **Framework**: Electron (latest version)
- **Packaging**: electron-builder
- **Auto Updates**: Independent Beta update channel
- **Cross-Platform**: Windows/macOS/Linux

### Data Storage
- **Local Database**: IndexedDB
- **Backup System**: JSON/Excel import/export
- **Version Management**: Database version control and migration
- **Data Isolation**: Beta version independent database system

## 📄 License

This software is distributed under a proprietary license. Please see the [LICENSE](LICENSE) file for details.

### License Types

#### 🆓 Community License (Free)
- ✅ **Non-Commercial Use**: Free for personal, educational, and research purposes
- 📊 **Excel Export**: Subject to CC BY-NC-SA 4.0 agreement, requires attribution
- 🌐 **Basic Features**: Includes all core functionality
- ⚠️ **Usage Restrictions**: Not for commercial purposes

#### 💼 Commercial License
- 💼 **Commercial Use**: Can be used in business environments and for profit
- 📊 **Unrestricted Export**: Excel export without additional license restrictions
- 🌐 **All Features**: Includes all advanced features and lab features

#### 🌐 Online License
- 🔧 **Advanced Features**: Includes Web Sync service and other lab features
- 📊 **Unrestricted Export**: Excel export without additional license restrictions
- 📊 **Cloud Services**: Online data synchronization and backup
- 🔄 **Auto Updates**: Automatic updates to latest version
- 📱 **Mobile Support**: Mobile-friendly web interface access

### Excel Export License Terms

According to Article 3 of the license, all Excel exports follow **CC BY-NC-SA 4.0**:

- **Attribution Required**: Must include "This Excel spreadsheet was recorded and generated using HamTool" with GitHub link
- **Non-Commercial**: May not be used for commercial purposes
- **Share-Alike**: Derivative works must use the same license

### Legal Terms

- 🔒 **Source Code**: Not open source, protected by copyright
- ⚖️ **Legal Jurisdiction**: Governed by laws of People's Republic of China
- 📧 **Contact**: License inquiries at imkenae@outlook.com

## 🐛 Beta Testing Guide

### Bug Reporting Process

1. **Confirm Repository**: All Beta version bugs must be reported at [HAMTool-Beta Issues](https://github.com/IamKenae/HAMTool-Beta/issues)
2. **Search for Duplicates**: Search for existing issues before reporting
3. **Detailed Description**: Provide detailed reproduction steps, screenshots, and error logs
4. **Environment Information**: Include OS version and Beta version number

### Prohibited Actions

- ❌ **Do not report Beta-related issues in the main repository**
- ❌ **Do not mention Beta version issues in the stable version repository**
- ❌ **Do not confuse Beta and stable version issues**
- ❌ **Do not use Beta versions in production environments**

### Recommended Practices

- ✅ **Use Test Data**: Avoid using real QSO data
- ✅ **Regular Backups**: Regularly backup Beta version test data
- ✅ **Detailed Feedback**: Provide detailed problem descriptions and reproduction steps
- ✅ **Participate in Discussions**: Participate in feature discussions in the Beta repository

### Testing Focus Areas

- **New Feature Validation**: Verify new features work as expected
- **Performance Testing**: Test performance of new features
- **Compatibility Testing**: Test compatibility in different environments
- **User Experience**: Evaluate user experience of new features

## 📝 Changelog

### Beta v3.0.0-b1 (2025-11-02) - Initial Beta Release 🆕
- 🌍 **Multi-Language Support**: Complete Chinese and English internationalization system
- 🔧 **Beta Version System**: Independent beta version release channel
- 📊 **Database Version Management**: Intelligent version conflict detection and resolution
- 📤 **Excel Export License**: CC BY-NC-SA 4.0 compliance and confirmation
- 🌐 **Web Sync Service**: Lab feature for LAN access support
- 🏷️ **Multi-Mode Operations**: Roll call mode and personal QSO recording mode
- 🎨 **UI Improvements**: Dark mode, theme switching, responsive design
- ⚡ **Performance Improvements**: Data processing speed and memory usage optimization

### Experimental Features Note
- **New Feature Preview**: Includes features currently under development
- **Feature Testing**: Requires user testing and feedback
- **Stability**: May experience instability
- **Compatibility**: May have compatibility differences with stable version

## 🗺️ Beta Testing Roadmap

### Current Testing Focus
- **Language Switching**: Verify Chinese and English interface switching functionality
- **Excel Export**: Test new license confirmation mechanism
- **Database Management**: Verify data import functionality from stable version
- **User Interface**: Test new interface elements and interactions

### Future Beta Versions
- **Map Visualization**: QTH location map display and heat maps
- **Device Integration**: Radio equipment control and data synchronization
- **Mobile Application**: Mobile web interface optimization
- **Cloud Sync**: Cloud data backup and synchronization services

### Stable Release Planning
- **Feature Stabilization**: Thoroughly tested features will be merged into stable version
- **Performance Optimization**: Performance improvements based on Beta testing feedback
- **Issue Resolution**: Fix issues discovered during Beta testing

## 🤝 Beta Testing Participation

### How to Participate

1. **Download Beta**: Download from [HAMTool-Beta Releases](https://github.com/IamKenae/HAMTool-Beta/releases)
2. **Install and Test**: Install and test in a testing environment
3. **Experience Features**: Try new features and share user experience
4. **Report Issues**: Report discovered issues in the Beta repository
5. **Provide Feedback**: Share usage suggestions and improvement ideas

### Testing Community

- **Beta Repository**: [HAMTool-Beta](https://github.com/IamKenae/HAMTool-Beta)
- **Issue Tracking**: [Beta Issues](https://github.com/IamKenae/HAMTool-Beta/issues)
- **Discussion Area**: [Beta Discussions](https://github.com/IamKenae/HAMTool-Beta/discussions)

## 🙏 Acknowledgments

Thank you to all amateur radio enthusiasts participating in Beta testing, especially:
- Users providing valuable testing feedback
- Testers helping to discover and report bugs
- Community members providing constructive suggestions for feature improvements
- Support and encouragement from the amateur radio community

---

<div align="center">

⚠️ **Thank you for participating in HAMTool Beta testing!**

**Remember: Beta versions are for testing only, use with caution!**

[📧 Contact Us](#contact-us) • [📄 License](#license) • [⭐ Support Project](../../stargazers)

Copyright © 2025 IamKenae (BG5EGG). All rights reserved.

Made with ❤️ for the HAM community

</div>
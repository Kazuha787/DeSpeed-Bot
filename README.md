# DeSpeed Auto Bot

An automated bot for managing multiple DeSpeed accounts with proxy support.

## 📢 Join Our Community

# Telegram Channel: .[Channel](https://t.me/Offical_Im_kazuha)
# GitHub Repository: [DepSpeed-Bot](https://github.com/Kazuha787/DeSpeed-Bot.git)

## ✨ Features

- Multi-account support
- Proxy support (HTTP, SOCKS4, SOCKS5)
- Auto-retry on failures
- Detailed logging
- Account earnings tracking
- Customizable harvest intervals

## 📋 Requirements

- Node.js 16.x or higher
- npm or yarn
- Valid 3DOS accounts

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/Kazuha787/DeSpeed-Bot.git
cd DeSpeed-Bot
```

2. Install dependencies:
```bash
npm install
```

## ⚙️ Configuration

- How to find Secret and Token? :
Generate Api Key on Web Dashboard - F12 - Aplication - Local Storage

1. Create configuration files:

   - `tokens.txt`: Add your bearer tokens (one per line, matching order with secrets)
   ```
   token1
   token2
   ```

   - `proxy.txt` (optional): Add your proxies (one per line)
   ```
   http://ip:port
   http://username:pass@ip:port
   socks4://ip:port
   socks5://username:pass@ip:port
   ```

## 🖥️ Usage

1. Start the bot:
```bash
npm start
```

2. Stop the bot:
   - Press `Ctrl + C` to gracefully shut down

## 🔧 Proxy Support

The bot supports multiple proxy protocols:
- HTTP/HTTPS
- SOCKS4
- SOCKS5

Proxy format examples:
```
http://1.2.3.4:8080
http://user:pass@1.2.3.4:8080
socks4://1.2.3.4:1080
socks5://user:pass@1.2.3.4:1080
1.2.3.4:8080  # Will be treated as HTTP proxy
```

## 📝 Logs

The bot provides detailed logging:
- Account status
- Earnings information
- Proxy usage
- Error messages
- Retry attempts

## ⚠️ Disclaimer

This bot is for educational purposes only. Use at your own risk. Make sure to comply with 3DOS's terms of service.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/new-feature`
3. Commit your changes: `git commit -am 'Add new feature'`
4. Push to the branch: `git push origin feature/new-feature`
5. Submit a pull request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💖 Support

If you find this bot helpful, please consider:
- Starring the repository
- Following our Telegram channel
- Contributing to the project

## 🙏 Acknowledgments

Special thanks to all contributors and the DeSpeed community!

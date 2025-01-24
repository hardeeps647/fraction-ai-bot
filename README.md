# Fraction AI Testnet BOT 🚀

## **Overview**
The Fraction AI Testnet BOT is designed to automate interactions on the Fraction AI platform, allowing users to efficiently manage agents and participate in battles. This guide will walk you through the setup process, key features, and usage.

---

## **Testnet Link**
🔗 [Fraction AI DApp](https://dapp.fractionai.xyz?referral=0FC0E11A)

---

## **How to Use the Platform**
1. **🔐 Connect Wallet** (Use a new or burner wallet for safety).
2. Navigate to the **📊 Dashboard**.
3. Go to the **🤖 My Agent** tab.
4. Click on **➕ + Create New Agent**.
   - Fill in the Starting Balance.
   - Fill in the System Prompt (can be generated with AI).
5. Navigate to **🗂️ My Agents**.
6. Enable Automation by clicking **✅ Enable Automation**.

> **⚠️ Note:** You will need some amount of $ETH on Sepolia. For additional Sepolia ETH, use the [Sepolia Testnet Bridge](https://testnetbridge.com/sepolia).

---

## **BOT Features**
- **👥 Multi-Account Support**
- **🔑 Private Key Integration**
- **🌐 Proxy Support**
- **🤝 Agent Matchmaking Automation**
- **⚙️ Easy Setup & Configuration**

---

## **Setup Instructions**
### **🐧 Linux**
1. Clone the project repository:
   ```bash
   git clone https://github.com/hardeeps647/fraction-ai-bot.git
   cd fraction-ai-bot
   ```
2. Install dependencies:
   ```bash
   npm install
   npm run setup
   ```
3. Configure accounts:
   ```bash
   nano accounts/accounts.js
   ```
4. Configure bot settings and proxy:
   ```bash
   nano config/config.js
   nano config/proxy_list.js
   ```
5. Start the bot:
   ```bash
   npm run start
   ```

### **🖥️ Windows**
1. Open Command Prompt or PowerShell.
2. Clone the project repository:
   ```bash
   git clone https://github.com/hardeeps647/fraction-ai-bot.git
   cd fraction-ai-bot
   ```
3. Install dependencies:
   ```bash
   npm install
   npm run setup
   ```
4. Configure accounts:
   - Navigate to `fraction-ai-bot` directory.
   - Edit `accounts/accounts.js`.
5. Configure bot settings and proxy:
   - Navigate to `config` and edit `config.js` and `proxy_list.js` (if using a proxy).
6. Start the bot:
   ```bash
   npm run start
   ```

---

## **Updating the Bot**
To update the bot, follow these steps:
1. Pull the latest changes:
   ```bash
   git pull
   ```
   or, if conflicts occur:
   ```bash
   git pull --rebase
   ```
2. If there is an error, run:
   ```bash
   git stash && git pull
   ```
3. Update dependencies:
   ```bash
   npm update
   ```
4. Restart the bot:
   ```bash
   npm run start
   ```

---

## **Important Notes**
- Always **📖 DYOR** (Do Your Own Research).
- **🛡️ Use a new wallet** to minimize risk. The developers are not responsible for any asset loss.

---

## **Additional Resources**
- **🔗 Testnet Bridge**: [https://testnetbridge.com/sepolia](https://testnetbridge.com/sepolia)
- **📂 GitHub Repository**: [Fraction AI Bot](https://github.com/hardeeps647/fraction-ai-bot)

---

Start automating your Fraction AI Testnet experience today! 🚀

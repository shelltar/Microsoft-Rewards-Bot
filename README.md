<a href="https://discord.gg/k5uHkx9mne">
  <img src="https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white&logoWidth=40" alt="Discord" />
</a>

# Microsoft Rewards Bot

## 🔔 Important Migration Notice

### ⚠️ The `main` branch has been deleted

If you're reading this message, it means the project structure has completely changed. Here's what happened:

---

## 📋 Migration History

### Before (Old System)

- **`main` branch**: Contained the script for the old Microsoft Rewards dashboard
- All users were based on this branch
- Automatic updates were pulled from `main`

### Phase 1: Legacy Branch Creation

To prepare for the new Microsoft Rewards dashboard:

1. We created the **`legacy` branch** for the old dashboard
2. We created the **`v4` branch** for the new dashboard
3. The `main` branch was temporarily modified to automatically redirect users to `legacy` via the auto-update system
4. This transition allowed all users to automatically migrate to the correct branch

### Phase 2: Main Branch Deletion (CURRENT)

After the majority of users migrated:

- **The `main` branch has been completely deleted**
- **The `v4` branch is now the main branch of the project**
- The `legacy` branch remains available for the old dashboard

---

## 🚀 What Should You Do?

### If You Were on the `main` Branch

**You must completely reinstall the bot**:

```bash
# 1. Backup your configuration files
# Copy your accounts.jsonc and config.jsonc files elsewhere

# 2. Completely delete the current folder
cd ..
rm -rf Microsoft-Rewards-Bot  # or manual deletion

# 3. Clone the appropriate branch

# For the old dashboard (Legacy):
git clone -b legacy https://github.com/LightZirconite/Microsoft-Rewards-Bot.git
cd Microsoft-Rewards-Bot

# For the new dashboard (V4) - See next section
git clone -b v4 https://github.com/LightZirconite/Microsoft-Rewards-Bot.git
cd Microsoft-Rewards-Bot

# 4. Restore your configuration files
# Place your accounts.jsonc and config.jsonc back in the new folder

# 5. Launch the bot
npm start
```

---

## 🆕 Microsoft Rewards Bot V4

### 🎯 New Era: Support for the New Microsoft Rewards Dashboard

Version 4 is a **complete rewrite** of the bot to support the new Microsoft Rewards interface.

### 📅 Release Date

- **Expected arrival**: In a few days
- **Official date**: Will be announced very soon
- **Free beta version**: Available to everyone at launch (full features)

### ✨ Why V4?

V4 development represents hundreds of hours of work:

- Complete code rewrite from scratch
- Support for the new Microsoft Rewards dashboard
- Modern and optimized architecture
- Active development and regular updates
- Dedicated technical support

---

## 💎 V4 Licensing Model

### Why is V4 Under a Paid License?

Active and continuous development of V4 requires considerable time investment. To ensure the project's sustainability and provide quality support, V4 adopts a licensing model.

### 📜 License Types

| Version      | Price | Duration  | Accounts  | Features             |
| ------------ | ----- | --------- | --------- | -------------------- |
| **Free**     | Free  | ∞         | 1 account | Limited features     |
| **Standard** | TBA   | 1 month   | Unlimited | All features         |
| **Annual**   | TBA   | 12 months | Unlimited | All features         |
| **Beta**     | Free  | Temporary | Unlimited | All (testing period) |

**Pricing**: Not yet announced, but deliberately **affordable and reasonable**.

### 💰 Why It's Not a Real Cost

**Main argument**: The bot generates Microsoft Rewards points convertible to money (gift cards, PayPal, etc).

- One account generates approximately **$10-15/month** in rewards
- The license pays for itself automatically through bot earnings
- **Ultimately, net cost = $0** (or even positive with multiple accounts)

### 🔒 Security and Transparency

V4 is proprietary with obfuscated code (anti-copy protection), but we commit to transparency:

✅ **Partial source code published progressively**

- Certain parts of the code will be made public
- Priority to project contributors
- Example: The login system will likely be open-source after release

✅ **No personal data collection**

- No hidden telemetry
- 100% local operation
- Your credentials never leave your machine

✅ **Complete free beta version**

- Full testing before purchase
- All features unlocked
- Community feedback welcome

---

## 🌿 Legacy Branch (Old Dashboard)

If your region still uses the old Microsoft Rewards dashboard:

**Clone Legacy**:

```bash
git clone -b legacy https://github.com/LightZirconite/Microsoft-Rewards-Bot.git
cd Microsoft-Rewards-Bot
npm start
```

**Features**:

- ✅ Old dashboard support
- ✅ 100% free and open-source
- ✅ Maintenance updates
- ⚠️ Fewer evolutions than V4

📖 **Complete documentation**: [See Legacy branch](https://github.com/LightZirconite/Microsoft-Rewards-Bot/tree/legacy)

---

## 🔗 Useful Links

- 💬 **[Discord](https://discord.gg/k5uHkx9mne)** — Community support and official announcements
- 📖 **[V4 Documentation](#)** — Available at release
- 📖 **[Legacy Documentation](https://github.com/LightZirconite/Microsoft-Rewards-Bot/tree/legacy)** — Complete Legacy guide
- 🐛 **[Report a Bug](https://github.com/LightZirconite/Microsoft-Rewards-Bot/issues)** — Help us improve the bot
- 🔄 **[Backup Repository](https://git.justw.tf/LightZirconite/Microsoft-Rewards-Bot)** — Backup mirror

---

## ⚖️ Disclaimer

> ⚠️ **Use at your own risk.**  
> Automation of Microsoft Rewards may lead to account suspension or bans.  
> This software is provided **for educational purposes only**.  
> The authors are not responsible for any actions taken by Microsoft.

---

## 🎉 Acknowledgments

A big thank you to all contributors and users who have supported this project from the beginning.

**V4 is coming soon — Stay tuned!** 🚀

---

<p align="center">
	Made with ❤️ by <a href="https://github.com/LightZirconite">LightZirconite</a> and <a href="https://github.com/LightZirconite/Microsoft-Rewards-Bot/graphs/contributors">contributors</a>
</p>

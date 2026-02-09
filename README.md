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
- **Free beta version**: Available to everyone at launch (full features, limited time)

### ✨ Why V4?

V4 development represents hundreds of hours of work:

- Complete code rewrite from scratch
- Support for the new Microsoft Rewards dashboard
- Modern and optimized architecture
- Active development and regular updates
- Dedicated technical support

---

## 💎 V4 Distribution Model

### Our Approach: Fair, Transparent & Community-Driven

After listening to community feedback, we've designed a model that balances project sustainability with openness and trust.

### 📐 The 3-Phase Plan

#### Phase 1 — Early Access (Launch → ~3 months)

At launch, V4 is distributed as a **closed-source, licensed product**.

- You need a licence key to use the bot
- All features are included with the licence
- A free beta period will be available at launch for testing

**Why?** You're getting early, exclusive access to the only bot that supports the new Microsoft Rewards dashboard. The licence funds the hundreds of hours of development that went into V4.

#### Phase 2 — Open Source Core (~3 months after launch)

After the early access period, the **core of the bot becomes fully open-source**.

- Daily Set, Desktop Search, Mobile Search — **free for everyone**
- The source code is published on GitHub — you can read every line
- Community contributions via pull requests are welcome
- **No licence required** for core features

**Why?** We believe in transparency. The code that handles your Microsoft credentials should be auditable by anyone. Trust is non-negotiable.

#### Phase 3 — Premium Plugin (Ongoing)

Advanced features are available as an **optional paid plugin** that extends the open-source core.

- Multi-account support
- Cluster parallelism
- All promotional activities (special promos, read-to-earn, daily streak, etc.)
- Webhook notifications (Discord, ntfy)
- Auto-redeem goals

The plugin is distributed as compiled bytecode and loaded by the core automatically.

**Why?** This is how the project sustains itself long-term. The core is free, the extras are paid. Simple, fair, and sustainable.

---

### 📜 License Types

| Version     | Price     | Duration  | Accounts  | Features                        |
| ----------- | --------- | --------- | --------- | ------------------------------- |
| **Beta**    | Free      | Temporary | Unlimited | All features (testing period)   |
| **Monthly** | ~$5/month | 1 month   | Unlimited | All features                    |
| **Annual**  | ~$40/year | 12 months | Unlimited | All features (~33% off)         |
| **Core**    | Free      | ∞         | 1 account | Daily set + searches (Phase 2+) |

**Pricing**: Deliberately **affordable and reasonable**. The bot earns you more than it costs.

### 💰 Why It's Not a Real Cost

**Main argument**: The bot generates Microsoft Rewards points convertible to money (gift cards, PayPal, etc).

- One account generates approximately **$10-15/month** in rewards
- The licence pays for itself from day one
- With multiple accounts, it's pure profit
- **Net cost = $0** (or positive)

---

### 🔒 Security & Trust Commitments

We heard your feedback loud and clear. Here's what we commit to:

#### ✅ Your Credentials Are Safe

- **Phase 2+**: All code that handles your Microsoft login is **open-source and auditable**
- 100% local operation — your credentials **never leave your machine**
- No hidden telemetry, no data collection, no phone-home beyond licence validation

#### ✅ The Code Will Be Open

- Core features go open-source after the early access period (~3 months)
- You will be able to read, audit, and contribute to the codebase
- Only the premium plugin remains closed-source (and it doesn't touch your credentials)

#### ✅ Free Beta at Launch

- Full access to all features during the beta period
- Test everything before deciding to purchase
- Community feedback actively shapes the product

#### ✅ Machine Binding, Not Account Binding

- Your licence is tied to your machine (up to 2 machines per key), not to specific Microsoft accounts
- Run as many Microsoft accounts as you want with one licence
- Docker support via `MACHINE_ID` environment variable

---

### 💬 Addressing Community Concerns

> **"Paying for earning is the issue"**
>
> We understand. That's why the core becomes free. Phase 1 is about early access, not permanent lock-in.

> **"I don't trust closed-source code with my accounts"**
>
> Neither would we. That's why the core goes open-source. Every line of credential-handling code will be public.

> **"There will be piracy"**
>
> The code is protected with V8 bytecode compilation. It's not impossible to crack, but it's hard enough that most people will prefer a $5/month licence over the effort.

> **"Why not just make it all free?"**
>
> Because Microsoft keeps changing their interface, and maintaining the bot takes real, ongoing work. Sustainable development needs sustainable funding.

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

- 💬 **[Discord](https://discord.gg/k5uHkx9mne)** — Community support, feedback, and official announcements
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

A big thank you to all contributors and users who have supported this project from the beginning. Your feedback directly shaped this distribution model — we listened.

**V4 is coming soon — Stay tuned!** 🚀

---

<p align="center">
	Made with ❤️ by <a href="https://github.com/LightZirconite">LightZirconite</a> and <a href="https://github.com/LightZirconite/Microsoft-Rewards-Bot/graphs/contributors">contributors</a>
</p>

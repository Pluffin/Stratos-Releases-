# Stratos — downloads

**Stratos** is an automated trading bot for **TopstepX** futures accounts. It trades an
Opening Range Breakout (ORB) strategy on index futures (default: MNQ) and runs as a
Windows desktop app with a web dashboard.

> 🆓 **Stratos is free.** Licenses are free too. If anyone asks you to pay for Stratos or a
> license key, it's a scam.

This repository only hosts the installers. The source code is not public.

## ⬇️ Download

Get the latest `Stratos Setup x.y.z.exe` from **[Releases](../../releases/latest)**.

## ✅ Requirements

- Windows 10 or 11 (64-bit)
- A **TopstepX** account with API access (ProjectX API key). Check TopstepX's current
  pricing and rules for API access and automated trading before you start.
- A free **Stratos license key** (see below)

## 🔑 Get a license key

1. Open an access request: **[Request Stratos access](https://github.com/Pluffin/access-requests/issues/new?template=request-access.yml&project=Stratos%20(ORB%20trading%20bot%20for%20TopstepX))**
2. Once it's approved, you'll get your key through the official channel (your GitHub issue or
   a private thread in the Penguin Colony Discord). Pluffin never sends keys or asks for
   anything by DM.

## 🛠 Install

1. Download `Stratos Setup x.y.z.exe` from Releases.
2. Run it. Windows may show **"Windows protected your PC"** because the installer isn't
   code-signed yet. Click **More info → Run anyway**.
3. Choose the install folder and finish the setup. A desktop shortcut is created.
4. Open Stratos and enter your **license key**. The trading engine won't start without it.
5. In **Profile**, add your TopstepX username and API key. They're encrypted on your PC and
   never leave it except to talk to TopstepX.
6. Set up your strategy in **Configs**, then start the bot from the **Dashboard**.

## ⚠️ Before trading real money

- **Start on a practice or Combine account**, never on a funded account first.
- Set the daily max loss, profit target and drawdown floor so they fit your account rules.
- Futures trading carries substantial risk of loss. Stratos is software, not financial advice,
  and past results don't guarantee future results.

## 💬 Support

Ask in the **Penguin Colony** Discord (AI Trading section) or open an issue in this repo.

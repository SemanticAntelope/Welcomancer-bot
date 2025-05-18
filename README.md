# 🛡️✨ Welcomancer: A Discord Welcome + Bouncer Bot

**Welcomancer** is a is a lightweight Discord bot built in Python using `discord.py`. Best for single guild servers with a focus on per-server customization. It combines the charm of a greeter with the vigilance of a digital bouncer.

---

## ✨ Features

*Server admins should be able to customize these features based on their needs, community context, and moderation philosophy. Whether you're running a private creative space or a semi-public community, **Welcomancer** is designed to be flexible without overwhelming you with configuration complexity.*

- 👋 **Sends a custom welcome message** to new members  
- 📬 **Optional DM-on-Join** with server rules or onboarding info  
- 🏷️ **Automatically assigns a default role** (e.g., `Members`)  
- ✅ **Optional reaction-based verification gate**  
- 🧼 **Customizable message moderation** (will deploy with basic English profanity filter with keyword auto-delete)  
- 🚷 **Anti-raid / join flood detection** *(currently planned)*  
- 📜 **Audit log for joins, bans, and kicks** *(currently planned)*
  
---
## 🌐 Deployment
Welcomancer is intended to run continuously, which mean hosting it on a platform that keeps the bot online 24/7. 
If you're new to deployment (like I was when I started this), some beginnger-freindly options include:

- [Railway](https://railway.com/pricing) – beginner-friendly with GitHub integration, hobby teir, discord bot templates and free-teir grant
- [Hostinger VPS](https://www.hostinger.com/tutorials/how-to-host-discord-bot) - Using Hosting VPS could be an option as Hostinger provides an easy to follow guide for `discord.py` bots. 
- Other VPS hosting - There are many options for virtual private servers, open a [discussion](https://github.com/SemanticAntelope/Welcomancer-bot/discussions/categories/general-discussion-about-welcomancer) to ask about other's experiences
>🐾🪶I'm still exploring the best options myself, so if you have feedback or run into issues deploying, feel free to open a discussion or issue. I'm learning too.
> ---
>⚠️Local execution (python welcomancer.py) is fine for development, but not suitable for production use unless you keep your machine on and connected 24/7.


---
## 📦 Setup

### 🛠️ Requirements

- Python 3.10+
- `discord.py` (v2.0+)
- `.env` file with your discord bot token and server info.


> ⚠️ **Important:** Never share your `.env` file, your bot token, or any server-specific IDs in public posts, GitHub repositories, or screenshots.  
> Treat your token like a password!🔐**if it gets leaked, your bot can be hijacked**, spammed, or used to damage your server.  
> 
> 💣If you're new to bot development, this is one of the most common beginner mistakes. **Don’t let it be yours.**

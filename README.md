# 🤖 AI News Agent (Make.com + Gemini)

This is a fully autonomous, 24/7 AI agent that monitors Google News for any keyword, uses Google's Gemini AI to instantly summarize the latest articles, and posts a smart, clean summary directly to a public Telegram channel.

The agent runs automatically every 15 minutes.

**➡️ Follow the agent's live updates here: [t.me/AINewsAgentEG](https://t.me/AINewsAgentEG)**

---

### 🛠️ Tech Stack (No-Code)

* **Platform:** [Make.com](https://www.make.com/) (formerly Integromat)
* **Data Source:** Google News via RSS Module
* **AI Model:** Google Gemini AI (via API)
* **Notification:** Telegram Bot

---



### ✨ The Result

You can see the agent running **live** and follow the latest AI news summaries in our Telegram channel:

**🔗 [t.me/AINewsAgentEG](https://t.me/AINewsAgentEG)**

Here is an example of the final message posted by the agent:

![Result in Telegram](result-telegram.png)

---

### ⚙️ How to Use (Replicate This Project)

You can easily replicate this entire project in your own Make.com account:

1.  **Get The Blueprint:** Download the `blueprint.json` file from this repository.
2.  **Get API Keys:**
    * **Google Gemini API:** Get your free API key from [Google AI Studio](https://aistudio.google.com/app/apikey).
    * **Telegram Bot:** Create a new bot using `@BotFather` on Telegram to get your Bot Token.
3.  **Create Telegram Channel:**
    * Create a new **Public Channel** on Telegram (like `t.me/AINewsAgentEG`).
    * Add your Bot (from Step 2) as an **Administrator** in the channel with `Post messages` permission.
    * Get the Channel's unique Chat ID (use the public username `@YourChannelName` or get the numerical ID like `-100...` by forwarding a message to `@userinfobot`).
4.  **Import to Make.com:**
    * Create a new scenario in Make.com.
    * Click the `...` (More) button at the bottom and select `Import Blueprint`.
    * Upload the `blueprint.json` file.
5.  **Configure Connections:**
    * Click on the `Google Gemini AI` module and add your API key.
    * Click on the `Telegram Bot` module, add your Bot Token, and paste your Channel's Chat ID.
6.  **Activate:**
    * Set the schedule (e.g., `Every 15 minutes`).
    * Toggle the `SCHEDULING` switch to **ON**.

---

### 🙏 Acknowledgements

Big thanks to **Youssef Elbadry** and **Instant Software Solutions Software Solution** for the amazing support and motivation! 🙌

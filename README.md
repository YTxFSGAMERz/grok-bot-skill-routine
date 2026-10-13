# 🌤️ Daily Campus Weather Forecast — Grok Bot Skill & Routine

[![MLH Challenge](https://img.shields.io/badge/MLH-Global%20Hack%20Week%20Challenge%204-orange.svg)](https://www.mlh.com/)
[![Trained on Grok Bot](https://img.shields.io/badge/Trained%20on-Grok%20Bot%20Cloud%20Computer-black.svg)](https://x.ai/)

Documentation and execution routine for **Daily Campus Weather Forecast**, a learned skill and automated routine created in **Grok Bot** for **MLH Global Hack Week: Hacktoberfest (Challenge 4: Teach Grok Bot Your First Task)**.

---

## 🎯 Skill Specification

* **Skill Name**: `Morning Campus Weather & Precipitation Forecast`
* **Trigger Task**: Extract today's temperature range, UV index, and chance of rain from a public forecast page.
* **Dynamic Variable (What changes each time)**: The target campus location / city name.

### 📋 Recorded Steps:
1. Open the browser on the bot's cloud computer and navigate to the public forecast service (`wttr.in/<location>` or weather forecast portal).
2. Input or substitute the dynamic `location` variable into the search or URL path.
3. Locate today's high temperature, low temperature, and precipitation percentage.
4. Format the findings into a clear morning briefing message.
5. Deliver the summary directly into the chat session without submitting or sending external forms.

---

## ⏰ Routine Configuration

* **Schedule**: Every weekday (Monday – Friday) at **7:30 AM**.
* **Action**: Executes the weather lookup skill and outputs the briefing in the chat.
* **Safety Rule**: Read-only display; do not submit forms or trigger external webhooks.
* **Routine Command Prompt**:  
  > *"Run that skill every weekday at 7:30am. Show me the forecast here. Don't send or submit anything."*

---

## 📝 MLH Submission Details

Use these exact fields when submitting to [MLH Challenge 4: Teach Grok Bot Your First Task](https://www.mlh.com/challenges/01a11d28-4c59-8dd2-84e3-90395ffcc7fd/submissions/new):

* **Project URL**:  
  `https://github.com/YTxFSGAMERz/grok-bot-skill-routine`

* **Two Sentences Required**:  
  > This skill opens a public weather forecast page to extract today's high temperature, weather condition, and chance of rain, dynamically updating the campus location variable on each run. The routine automatically executes every weekday at 7:30 AM and displays the formatted morning forecast directly in the chat without submitting external data.

* **Description (Markdown)**:  
  > ### Challenge 4: Teach Grok Bot Your First Task
  > 
  > Taught my persistent Grok Bot a new automated skill using the **Teach a Task** cloud computer interface, paired with a recurring routine.
  > 
  > **1. The Skill**:
  > - **Action**: Navigates to a public weather portal, reads the daily high/low temperatures, and evaluates precipitation risk.
  > - **Dynamic Parameter**: The location / campus query changes dynamically based on scheduled configurations.
  > 
  > **2. The Routine**:
  > - Configured to run automatically every weekday morning at 7:30 AM.
  > - Output is securely posted inside the bot's chat stream without posting or modifying external web pages.
  > 
  > **3. Verification**:
  > - The bot summarized the learned sequential steps in chat.
  > - Confirmed the scheduled card in the workspace **Routines** management tab.

* **Technologies Used**:  
  `Grok Bot`, `xAI`, `Browser Automation`, `Autonomous Routines`

* **Upload Screenshots**:  
  1. Screenshot of the bot’s summary of the skill (learned steps displayed in chat).  
  2. Screenshot of the confirmed routine card or the routine active under the **Routines** tab.

# 📩 Pingl – AI Email Campaigns From Your Phone  
A Convex Resend Hackathon Project  
Built by [gidavehub](https://github.com/gidavehub)

---

## 👋 Imagine This...

**Email campaigns feel like a chore.**  
You need a laptop. Multiple tools. Templates. Hours of setup — especially when you're trying to personalize messages for hundreds of employees or customers.

> 💭 *What if all of that was simplified into a mobile app?*

What if sending a fully customized, professional email to your whole team or customer base took **just three steps** — right from your phone — with **AI doing most of the work**?

---

## 🚀 What is Pingl?

**Pingl** is a mobile-first email campaign tool that helps businesses, teams, and creators send beautiful, AI-personalized messages from their phone. It removes the need for complex software, long setup, and multiple tools — and replaces it with a 3-step process:

1. Upload your contact data (file, link, or manual)
2. Choose an email UI template
3. Tap to send personalized emails using AI and **Convex Resend**

---

## ✨ Core Features

- ✅ **Mobile-First:** Built with React Native & Expo for iOS + Android
- 📂 **Flexible Data Input:** Upload a file, paste a DB link, or manually input data
- 🏷️ **Label-Based Targeting:** Group your contacts using tags/labels
- 🧠 **AI-Powered Content:** Gemini AI personalizes content using contact fields (e.g., name, job title)
- 💌 **HTML Email UI Templates:** Select from 10 beautifully crafted designs
- 🔁 **Smart Resend Logic:** Re-target unopened emails with AI-generated variations
- 📊 **Lightweight Analytics:** Track open rates, click rates, and resend suggestions
- 🔐 **No External Servers:** All data is handled within the app using Convex backend

---

## 📲 How It Works

### 1. Import Contacts
- Upload a `.csv` or `.xlsx` file with contact info (name, email, title, etc.)
- Paste a link to your database
- Manually input contacts in the app

### 2. Add Labels (Groups)
- Create label groups like `Marketing`, `HR`, `Customers`, `Beta Testers`
- Use these to send customized messages to each group

### 3. Select Template
- Choose from 10 clean HTML templates
- Customize headers, buttons, images, footers

### 4. Let AI Personalize It
- AI will generate custom messages like:
  > “Hi Sarah, congrats on your 3-year anniversary with the Marketing team!”

- The AI also writes subject lines, greetings, and CTAs based on the data.

### 5. Send & Resend
- Send emails via Convex Resend API
- Use smart logic to automatically resend unopened messages with new subject lines or copy

---

## 💡 Use Cases

- **HR Teams**: Work anniversary, onboarding, team updates
- **Startups**: New feature updates, investor outreach
- **Sales/Marketing**: Targeted product launches
- **Schools**: Notices to parents or students
- **Freelancers**: Invoice reminders, client updates

---

## 📦 Tech Stack

| Tech               | Purpose                             |
|--------------------|-------------------------------------|
| React Native + Expo| Mobile app development              |
| Convex             | Backend logic + resend feature      |
| Gemini AI          | Personalizing emails with LLMs      |
| AsyncStorage       | Session & user data persistence     |
| HTML/CSS           | Email templates                     |

---

## 🛠 Setup & Installation

1. Clone the repo:
```bash
git clone https://github.com/gidavehub/pingl.git
cd pingl

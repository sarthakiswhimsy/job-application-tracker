# 🎯 JobTrack — Job Application Tracker

A clean, fast, single-file job application tracker. No build step, no dependencies, no sign-up.
Track every application from wishlist to offer, and add your own custom fields to remember anything you want.

## ✨ Features

- **Board view** – Kanban-style columns with drag-and-drop between stages
- **List view** – sortable table with inline status changes
- **Pipeline stages** – Wishlist · Applied · Heard back · Interview · Selected · Rejected · Withdrawn
- **Custom fields** – add your own (text, number, date, link or dropdown), e.g. *Interview round*, *Tech stack*, *Referral*
- **Built-in details** – company, role, applied date, follow-up date, location, salary/CTC, source, contact, job link, 5-star priority, notes
- **Dashboard stats** – totals per stage and your response rate at a glance
- **Follow-up reminders** – overdue follow-ups are highlighted in red
- **Search, filter and sort** – by stage, date, company, priority or follow-up date
- **Export / import** – JSON backup and restore, plus CSV export for Excel or Google Sheets
- **Light and dark mode**, responsive on desktop and mobile

## 🔗 Live Demo

**👉 [Open JobTrack](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)**

## 💾 How your data is stored

Your data is saved in your browser's **localStorage** automatically after every change, and reloads each time you open the page.

| | |
|---|---|
| ✅ Persists across visits | on the same browser and device |
| ✅ Private | stays on your device, nothing is sent to a server |
| ❌ Not synced | other devices and browsers have their own separate data |
| ⚠️ Can be lost if | you clear site data, use private/incognito mode, or switch browsers |

> **Tip:** Use **Fields & Data → Export JSON** regularly to back up your data.
> To move to another device, export there and use **Import JSON** on the new one.

Anyone who opens your deployed GitHub Pages site gets their own empty tracker. Your data is never shared.

## 🧩 Using custom fields

1. Click **⚙ Fields & Data**.
2. Enter a field name, pick a type (for a dropdown, list its options separated by commas) and click **Add field**.
3. The field now appears in every application form, as a column in list view, and in CSV exports.

## 🛠 Customising

Everything lives in `index.html`:

- **Stages and colours:** edit the `ST` array near the top of the `<script>`.
- **Theme colours:** edit the CSS variables in `:root` at the top of the file.

## 📁 Project structure

```
├── index.html   # the entire app (HTML, CSS and JavaScript)
└── README.md
```

## 📄 License

Free to use and modify for personal projects.

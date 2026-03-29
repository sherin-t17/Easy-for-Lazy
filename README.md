# 🌸 Easy for Lazy

> **Your all-in-one personal productivity space — beautifully simple, mobile-first.**

Easy for Lazy is a fully offline, PWA-ready productivity app built with pure HTML, CSS, and JavaScript. No frameworks. No installs. No accounts. Just open it and go.

Designed for people who want to stay organised without the overwhelm — it works perfectly on your phone, tablet, and desktop with fully separate layouts for each.

---

## ✨ Features

### 🏠 Overview
- Personalised greeting with your name + time of day (Good morning / afternoon / evening)
- Live stats — Total Tasks, Pending, Due Today
- Daily motivational quote
- Today's habit checklist at a glance
- Upcoming events with countdown

### ✅ Tasks (Kanban Board)
- Three columns — **To Do**, **In Progress**, **Done**
- Drag & drop between columns (desktop) + move buttons (mobile)
- Add, edit, delete tasks
- Categories — Personal, Study, Exam, Event, Countdown
- Priority levels — High 🔴, Medium 🟡, Low 🟢
- Due dates + reminder time
- Progress bar per task (0–100%)
- Search, filter by priority, category, and due date

### 📅 Calendar
- Full monthly calendar view with desktop/mobile responsive sizing
- Click any date to open a day panel
- **Multiple entries per day** — each saved separately with timestamp
- Mood tracker per entry — 8 moods with emoji shown directly on the calendar cell
- Special occasion markers — 🎂 Birthday, 💍 Anniversary, 🎉 Celebration, 📌 Important
- Event category dots visible on calendar cells (colour-coded)
- Delete individual entries

### 🎉 Events
- Separate page for birthdays, anniversaries, work events, personal milestones
- Fields: Name, Category, Contact Name, Date, Reminder (1d / 3d / 1 week / 2 weeks), Yearly repeat
- **Recurring yearly events** — set once, auto-repeats every year
- **Live countdown** on every card — "🎉 Today!", "⏰ Tomorrow!", "⏳ In 12 days"
- Colour-coded cards by category
- Filter by Birthday / Anniversary / Work / Personal
- Events shown on calendar grid with coloured dots
- Event reminders via browser notification + in-app banner

### 🌱 Habits
- Daily and weekly habits
- Check off each day
- 7-day streak visualiser
- 🔥 Streak counter

### 📝 Notes
- Full mobile-style note app experience
- Title, body, tags (Personal, Study, Work, Exam, Event)
- Pin important notes 📌
- Search and filter by tag
- Date/time stamp on every note
- Create, edit, delete

### ⚙️ Settings
- Set your name (shown in greeting)
- Toggle browser notifications
- Toggle in-app reminder banners
- **PWA Background Personalisation** — choose a background when added to home screen:
  - Aesthetic illustrations (Castle 🏰, Flowers 🌸, Sky ☁️)
  - Minimal patterns (Dots, Waves, Lines)
  - Soft pastel colours (Lavender, Blush, Mint)
- Clear all data

### 💬 Feedback
- Star rating (1–5)
- Quick-tap feedback tags
- Optional message and email
- Saved locally for developers to review

---

## 📱 Mobile Support

Easy for Lazy is built **mobile-first**:

| Feature | Mobile | Desktop |
|---|---|---|
| Navigation | Bottom tab bar | Fixed sidebar |
| Calendar cells | Compact 46px | Spacious 72px |
| Kanban | Single column scroll | 3 columns |
| Notes | Single column | Auto-fill grid |
| Events | Full width cards | 2-column grid |
| Hamburger menu | ✅ | ❌ (sidebar always visible) |

Add to your home screen on iOS or Android for a full app-like experience with custom background.

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Storage | localStorage (fully offline) |
| Fonts | DM Serif Display + DM Sans (Google Fonts) |
| PWA | `apple-mobile-web-app-capable` meta tags |

**No frameworks. No dependencies. No build step.**

---

## 🚀 Getting Started

### Option 1 — Open directly
Download `index.html` and open it in any browser. That's it.

### Option 2 — Host on GitHub Pages
1. Fork this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your app is live at `https://yourusername.github.io/easy-for-lazy`

### Option 3 — Add to Home Screen (PWA)
1. Open the app URL in Safari (iOS) or Chrome (Android)
2. Tap **Share → Add to Home Screen** (iOS) or **⋮ → Add to Home Screen** (Android)
3. Pick your background in Settings before adding for a personalised look

---

## 💾 Data & Privacy

- **100% local** — all your data stays on your device in `localStorage`
- No servers, no accounts, no tracking
- Data persists across browser sessions
- Use **Settings → Clear All Data** to wipe everything

---

## 📁 Project Structure

```
easy-for-lazy/
└── index.html        # The entire app — single file
└── README.md         # This file
```

---

## 🎨 Design

- **Theme:** Purple Minimal — soft white-lavender backgrounds with deep purple accents
- **Fonts:** DM Serif Display (headings) + DM Sans (body)
- **Palette:**
  - Background: `#f8f5ff`
  - Surface: `#ffffff`
  - Accent: `#6b3fa0`
  - Text: `#1e1035`

---

## 🗺 Roadmap

- [ ] Dark mode toggle
- [ ] Export data as JSON backup
- [ ] Import data from JSON
- [ ] Shared events (for families/groups)
- [ ] More background options
- [ ] Task subtasks
- [ ] Weekly review summary

---

## 💬 Feedback

Found a bug? Have an idea? Use the **Feedback** tab inside the app — we read every response.

---

## 📄 License

MIT License — free to use, modify, and share.

---

<p align="center">Made with 💜 for people who just want things to be easy.</p>

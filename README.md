# 🌟 Life Helper

**Life Helper** is your all-in-one personal organization hub — replacing your phone's fragmented default apps with a single, unified, beautifully designed experience. Habits, reminders, tasks, notes, grocery lists, calendar, clocks, timers, and more — all connected, all aware of each other.

Built for **Android**, **iOS**, **Web**, **Windows**, **macOS**, and **Linux** — one codebase, every platform. Whether you're on your phone, browser, or desktop, Life Helper works natively everywhere.

> 🔗 **Related Project:** [Wishlist](https://github.com/ayehya2/wishlist) — a standalone price-tracking wishlist app that will be **fully integrated into Life Helper** in a future release. See the [integration roadmap](#-wishlist-integration-roadmap) below.

---

## 📱 Features

---

### 1. 🎯 Habit Tracker

Build better habits, break bad ones, and visualize your consistency over time.

#### Habit Types & Measurement Toggles
- **Boolean (Yes/No)** — Did you meditate today? ✅ / ❌
- **Count-based** — How many glasses of water? (e.g. target: 8)
- **Duration/Time-based** — How long did you exercise? (e.g. target: 30 min)
- **Weight/Measurement-based** — Log your weight, body fat %, waist size (kg, lbs, cm, inches — user selectable)
- **Numeric value** — Pages read, calories, steps (custom unit label)
- **Checklist habit** — Multiple sub-steps that all need completing (e.g. Morning Routine: brush teeth, stretch, journal)
- **Rating scale** — Rate mood, energy, sleep quality on 1–5 or 1–10 scale

#### Scheduling & Frequency
- Daily, specific days of the week, every X days, weekdays only, weekends only
- Monthly (e.g. review finances on the 1st of every month)
- X times per week (flexible — "3 times this week, any days")
- Custom intervals (every 3 days, every 2 weeks)
- Start date and optional end date per habit
- Pause a habit temporarily without losing streak history

#### Streaks & Progress
- **Current streak** and **longest streak** counters
- **GitHub-style heatmap** — full year grid of colored squares showing completion history
- **Calendar view** — month-by-month habit history
- **Weekly/Monthly summary cards** — success rate % per habit
- Partial credit for count/duration habits (e.g. did 15 min of 30 min goal = 50%)
- Grace period setting — miss one day without breaking streak (optional per habit)
- Streak freeze tokens — earn or manually grant streak protection

#### Reminders Per Habit
- Multiple reminder times per habit (e.g. morning + evening)
- Smart reminder — nudge only if not yet completed that day
- Snooze reminders (15 min, 1 hour, custom)
- Quiet hours — no habit reminders between set times

#### Analytics & Insights
- Success rate by day of week (see you always fail Mondays)
- Best time of day for completion
- Correlation between habits (did you exercise more on days you slept well?)
- Monthly progress report card
- Longest streak ever, total completions, total time logged
- Export data as CSV

#### Organization
- Color-code habits
- Custom emoji or icon per habit
- Group habits into stacks (Morning Stack, Evening Stack, Fitness Stack)
- Archive completed challenge habits without deleting
- Reorder habits via drag-and-drop

---

### 2. ✅ Tasks & To-Do Lists

A full-featured task manager that actually understands priority and context.

#### Task Types
- **Simple to-do** — one-off tasks with optional due date
- **Recurring tasks** — same recurrence options as habits (daily, weekly, custom)
- **Subtasks** — break any task into steps, track completion per step
- **Checklist tasks** — ordered steps that must be done in sequence
- **Timed tasks** — tasks with an estimated duration (integrates with calendar blocking)

#### Priority & Urgency
- **Eisenhower Matrix** sorting — Urgent/Important, Urgent/Not Important, Not Urgent/Important, Not Urgent/Not Important
- Manual priority: 🔴 Critical, 🟠 High, 🟡 Medium, 🟢 Low
- Auto-escalate priority as due date approaches
- Flag tasks for focus mode

#### Organization
- Multiple lists (Work, Personal, Errands, Shopping, Projects)
- Tags/labels with color coding
- Smart lists: Today, Upcoming, Overdue, Flagged, No Due Date
- Folders to group related lists
- Drag-and-drop task reordering within lists
- Swipe to complete, swipe to delete, swipe to reschedule

#### Due Dates & Scheduling
- Due date + optional due time
- All-day tasks vs. timed tasks
- Soft deadline vs. hard deadline toggle
- Reschedule to tomorrow / next week in one tap
- "Someday" bucket for tasks with no date

#### Task Details
- Rich text notes per task
- Attach images or files
- URL links (e.g. link a task to a website or document)
- Add to calendar from task
- Link a task to a habit (e.g. "Write blog post" linked to "Write daily" habit)

---

### 3. 🔔 Smart Reminders

Never forget anything — context-aware, location-aware, and time-aware.

#### Reminder Types
- **Time-based** — standard date + time reminder
- **Location-based** — triggers when you arrive at or leave a location ("remind me to buy milk when I arrive at the grocery store")
- **Context-aware** — "when I get home," "when I get to work," using saved locations
- **Person-based** — "remind me to ask John about the report next time I message him" (integrates with contacts)
- **Recurring reminders** — daily, weekly, monthly, custom intervals
- **Conditional reminders** — "remind me only if weather is bad" (integrates with weather)

#### Reminder Settings Per Item
- Title, notes, URL attachment
- Priority level
- Snooze options: 5 min, 15 min, 1 hour, 3 hours, tomorrow, next week, custom
- Persistent reminders — re-notify every X minutes until acknowledged
- Silent reminders — badge only, no sound
- Custom notification sound per reminder category

#### Smart Features
- Duplicate detection — warns if you create a very similar reminder
- Missed reminder summary — morning briefing includes everything you missed overnight
- Overdue reminder badge on app icon
- Bulk reschedule overdue reminders

---

### 4. 📅 Calendar

A full calendar that ties together tasks, habits, reminders, and events in one view.

#### Views
- Day view — hour-by-hour timeline
- 3-day view
- Week view
- Month view — with dot indicators for tasks, habits, events
- Agenda view — scrollable list of upcoming items
- Year view — overview of how busy each day is (heat-intensity colored)

#### Event Types
- One-time events
- Recurring events (daily, weekly, monthly, yearly, custom RRULE)
- All-day events
- Multi-day events
- Events with travel time (adds buffer before the event)

#### Event Details
- Title, description, location
- Start/end time or all-day toggle
- Color label
- Attachments (notes, links, images)
- Invitees (contacts)
- Alert/reminder: at time, 5 min, 15 min, 30 min, 1 hour, 1 day, custom before
- Second alert support

#### Calendar Management
- Multiple calendars (Personal, Work, Family, Birthdays)
- Per-calendar color coding
- Show/hide individual calendars
- **Sync with Google Calendar, Apple Calendar, Outlook** (two-way sync)
- Import .ics files
- Offline access — full calendar works without internet

#### Calendar Intelligence
- Tasks with due dates appear on calendar
- Habit completions reflected on calendar
- Time blocking — drag tasks onto calendar to schedule them
- Conflict detection — warns when events overlap
- Free/busy overview

---

### 5. 📝 Notes

Quick capture and long-form note-taking, always at your fingertips.

#### Note Types
- **Plain text notes**
- **Rich text notes** — bold, italic, underline, headings, bullet lists, numbered lists, quotes
- **Checklists** — tap to check off items inline
- **Voice notes** — record audio, auto-transcribed to text
- **Image notes** — capture a photo or attach from gallery, add captions
- **Handwritten notes** — draw or write with stylus/finger (canvas mode)
- **Code notes** — syntax highlighted code blocks (for developers)

#### Organization
- Folders and subfolders
- Tags with color labels
- Pin notes to top
- Favorites
- Archive (not delete)
- Trash with 30-day recovery

#### Search & Discovery
- Full-text search across all notes
- Search within tags, folders
- Search inside images (OCR text recognition)
- Recent notes, frequently accessed notes
- Sort by: date modified, date created, title, manually

#### Note Features
- Word count, character count, reading time estimate
- Share note as text, PDF, or image
- Lock note with biometrics/PIN
- Link notes to tasks ("attached note" on a task)
- Markdown support with live preview toggle
- Dark/light mode per note

---

### 6. 🛒 Lists (Shopping, Grocery, Packing & Custom)

Smart lists that understand what kind of items are inside them.

#### List Types
- **Grocery List** — items organized by store section (produce, dairy, bakery, etc.)
- **Shopping List** — items with prices, store names, links
- **Packing List** — items with quantity + checked-off packing state
- **Custom List** — any free-form list with a custom name and icon

#### Item Details Per List Type
- **Grocery items:** name, quantity, unit (kg, g, lb, oz, liters, ml, units, dozen, bunch, can, bag — selectable per item), category, notes, brand preference, checked/unchecked
- **Shopping items:** name, quantity, price, store, URL link, priority, notes, checked/unchecked
- **Packing items:** name, quantity, category (clothing, toiletries, electronics, documents), packed toggle
- **Custom list items:** name, quantity (optional), toggle type (checkbox, counter, done/undone), notes

#### Smart Features
- Frequently bought items — auto-suggest based on history
- Template lists (save a grocery list as a template for weekly shopping)
- Duplicate list
- Share list with others (view or edit access via link)
- Cross-off items as you shop (strikethrough mode)
- "Keep checked items" toggle — some lists you want to clear checked, others you want to keep as reference
- Sort by: category, alphabetically, custom order, recently added

---

### 7. ⏰ Clock, Alarms & Timers

A complete time management suite.

#### Alarm Clock
- Multiple alarms with individual on/off toggles
- Label each alarm
- Repeat on specific days of the week
- Alarm tone — system sounds, music, or custom audio file
- Vibration toggle + vibration pattern selection
- Volume override — alarm can bypass silent mode (toggle)
- Gradual volume increase (gentle wake)
- **Smart alarm** — wakes you within a 30-minute window at your lightest sleep phase (requires sleep tracking to be enabled)
- Snooze: enable/disable, snooze duration (1–30 min), max snooze count
- One-tap disable tomorrow's alarm
- Upcoming alarms widget

#### World Clock
- Add unlimited cities
- Shows current time, date, and UTC offset
- Visual indicator of day/night for each city
- Sort by time zone offset or custom order
- Highlight overlapping business hours between time zones (for meeting planning)
- Time zone converter — "what time is 3pm EST in Tokyo?"

#### Stopwatch
- Start, stop, lap, reset
- Lap times list with delta time (time since last lap)
- Average lap time calculation
- Save and name stopwatch sessions
- Background operation — continues running when app is closed

#### Timer
- Set hours, minutes, seconds
- Multiple simultaneous timers with individual labels
- Preset timers (quick add: 5 min, 10 min, 25 min Pomodoro, 45 min, 1 hour)
- Timer tone — custom per timer
- Repeat timer automatically (loop toggle)
- Background operation with notification countdown

#### Pomodoro / Focus Mode
- Default 25 min work / 5 min break / 15 min long break cycles
- Fully customizable durations
- Auto-start next session toggle
- Session counter — see how many Pomodoros completed today
- Link a task to a focus session — tracks time spent per task
- Focus stats: total focus hours per day, week, month
- Do Not Disturb integration during focus sessions

---

### 8. 😴 Sleep Tracker

- Log bedtime and wake time manually or automatically (motion detection)
- Sleep goal setting (e.g. 8 hours per night)
- Sleep quality rating (1–5 stars on wake)
- Sleep notes (dreams, how you feel)
- Weekly sleep chart — average hours per night
- Sleep debt tracker — cumulative hours short of goal
- Integrates with smart alarm for light-sleep wake
- Optional: connect to Apple Health / Google Fit for automatic sleep data import

---

### 9. 💧 Health & Wellness Trackers

#### Water Intake
- Daily water goal (ml or oz)
- Quick-add buttons (cup = 250ml, bottle = 500ml, custom)
- Log custom amounts with custom container sizes saved
- Daily progress bar + percentage
- Reminder to drink water every X hours
- Weekly average chart

#### Mood Tracker
- Log mood: 😄 Great / 🙂 Good / 😐 Okay / 😔 Low / 😢 Awful
- Add notes + tags to mood entries (weather, sleep, exercise, social)
- View mood heatmap calendar
- Mood trends chart — rolling 30-day average
- Correlations: "you're happier on days you exercise"

#### Weight & Body Measurements
- Log weight in kg or lbs (toggle)
- Log additional measurements: body fat %, waist, chest, hips, arms, legs (cm or inches — toggle)
- Goal weight setting
- Progress chart with trend line
- BMI calculator (optional)
- Import from Apple Health / Google Fit

#### Custom Health Trackers
- Create any health metric to track (blood pressure, blood sugar, medication, etc.)
- Define unit and measurement type
- Set goals and reminder schedule

---

### 10. 💰 Budget & Expense Tracker

- Log expenses with: amount, category, date, notes, payment method
- Income logging
- Monthly budget per category (groceries, transport, entertainment, etc.)
- Spending vs. budget progress bars
- Monthly summary: total spent, total income, net
- Recurring expense tracking (subscriptions, rent, bills)
- Weekly/monthly expense charts
- Currency selection (globally supported)
- Export to CSV

---

### 11. 📊 Daily Dashboard & Morning Briefing

#### Dashboard Widgets (customizable layout)
- Today's date, day of week, week number
- Weather (current + today's forecast) — location-based
- Today's tasks — count + list
- Habit ring — visual completion % for today's habits
- Upcoming events (next 3 from calendar)
- Active reminders count
- Water intake progress
- Mood log prompt (if not yet logged today)
- Focus time logged today
- Upcoming birthdays (next 7 days)
- Random motivational quote (optional, toggleable)
- Current Pomodoro / focus session status

#### Morning Briefing
- Daily weather summary
- Tasks due today
- Habits to complete today
- Events and meetings today
- Missed reminders from overnight
- Habit streak status (at risk streaks flagged)

#### Evening Review (optional)
- Habits completed today
- Tasks completed vs. planned
- Mood and water logged?
- Prompt to plan tomorrow

---

### 12. 🔍 Global Search

- Search tasks, notes, habits, reminders, events, lists, expenses
- Filter by type, date range, tag, list, priority
- Recent searches
- Search as you type with instant results

---

### 13. 🎨 Customization & Personalization

- **Themes:** Light, Dark, Auto (follows system), AMOLED Black
- **Accent colors:** 12+ color options
- **App icon variants:** light, dark, colorful options
- **Font size:** Small, Medium, Large, Extra Large
- **Dashboard layout:** drag-and-drop widget arrangement
- **Home screen widgets** (iOS 14+ / Android): Today tasks, habit rings, water intake, next reminder, focus timer
- **Tab bar customization** — choose which 5 sections appear in bottom nav
- **Notification preferences** per category

---

### 14. 🔐 Privacy & Security

- Biometric lock (Face ID, Touch ID, fingerprint)
- PIN code fallback
- Lock specific notes or lists
- **All data stored locally by default** — no account required to use the app
- Optional cloud backup (iCloud / Google Drive) — encrypted
- No ads, no data selling, no tracking

---

### 15. 🔄 Sync & Backup

- Local storage — works fully offline, always
- Optional account for cross-device sync
- iCloud sync (iOS) / Google Drive sync (Android)
- Manual export: full data backup as JSON
- Import backup to restore everything
- Sync with: Google Calendar, Apple Calendar, Apple Health, Google Fit

---

### 16. 📲 Widgets & Shortcuts

#### Home Screen Widgets
- Today's tasks (small, medium, large)
- Habit completion rings
- Water intake tracker
- Focus timer (start/stop from widget)
- Next reminder
- Upcoming event

#### Quick Actions (long press app icon)
- Add task
- Start focus session
- Log water
- New note
- Add reminder

#### Lock Screen Widgets (iOS 16+ / Android 13+)
- Habit completion count
- Next reminder
- Focus timer status

---

## 🎁 Wishlist Integration Roadmap

> **[Wishlist](https://github.com/ayehya2/wishlist)** is currently a standalone app. In a future release it will be fully absorbed into Life Helper as a native feature — not a bolt-on, but a deeply integrated part of the ecosystem.

### What the integration will look like

The Wishlist feature will live inside Life Helper as a dedicated section, sitting naturally alongside Lists, Budget, and Reminders. Here's exactly how it will connect:

| Wishlist Feature | How it integrates into Life Helper |
|---|---|
| Save items by URL | Becomes a "Wishlist" list type alongside Grocery, Shopping, Packing |
| Price tracking | Price drop alerts become just another Smart Reminder type |
| Price history chart | Lives in the item detail view, same chart style as Budget |
| Target price alerts | Uses Life Helper's existing notification infrastructure |
| Shareable wishlists | Uses Life Helper's existing list sharing system |
| Gift reservation | Friends can claim items on your shared list — unique to Wishlist lists |
| Budget tracking | Wishlist items feed into the Budget & Expense tracker |

### Account & Data Migration

Since Wishlist and Life Helper are two separate projects today, a seamless migration path will be provided when integration ships:

- **Single sign-on** — one Life Helper account covers both apps. No separate Wishlist login needed once integrated
- **One-tap import** — if you already have a Wishlist account, log in with the same credentials in Life Helper and all your data transfers automatically
- **Sync toggle** — choose whether your Wishlist data syncs to Life Helper's cloud or stays local-only
- **No data loss** — all saved items, price history, and alerts carry over fully
- **Standalone app remains available** — the Wishlist app will continue to work independently; integration is opt-in

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Framework | React Native with Expo |
| Language | TypeScript |
| Navigation | Expo Router (file-based) |
| State Management | Zustand |
| Local Storage | MMKV (fast key-value) + SQLite (structured data) |
| UI Library | NativeWind (Tailwind CSS) + custom components |
| Animations | React Native Reanimated 3 |
| Notifications | Expo Notifications |
| Background Tasks | Expo Background Fetch + Task Manager |
| Calendar Sync | react-native-calendar-sync |
| Health Integration | react-native-health (iOS) + Health Connect (Android) |
| Charts | Victory Native / Gifted Charts |
| Icons | Lucide React Native + Expo Icons |
| Biometrics | Expo Local Authentication |
| Location | Expo Location |
| Cloud Backup | Expo FileSystem + iCloud / Google Drive APIs |

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- npm or yarn
- Expo CLI

### Installation

1. Clone the repository
```bash
git clone https://github.com/ayehya2/life-helper.git
cd life-helper
```

2. Install dependencies
```bash
npm install
```

3. Start the app
```bash
npx expo start
```

4. Run on device
   - Download **Expo Go** on iOS or Android
   - Scan the QR code in the terminal

---

## 📅 Roadmap

| Phase | Description | Status |
|---|---|---|
| Phase 1 | Project Setup & README | ✅ Current |
| Phase 2 | Core Navigation, Dashboard Layout & Theme System | 🔜 |
| Phase 3 | Habit Tracker (all measurement types + heatmap) | 🔜 |
| Phase 4 | Tasks & To-Do Lists | 🔜 |
| Phase 5 | Reminders (time-based + location-based) | 🔜 |
| Phase 6 | Calendar (views + Google/Apple sync) | 🔜 |
| Phase 7 | Notes (all types + rich text) | 🔜 |
| Phase 8 | Lists (grocery, shopping, packing, custom) | 🔜 |
| Phase 9 | Clock, Alarms, Timers & Pomodoro | 🔜 |
| Phase 10 | Health Trackers (water, mood, weight, sleep) | 🔜 |
| Phase 11 | Budget & Expense Tracker | 🔜 |
| Phase 12 | Dashboard, Widgets & Quick Actions | 🔜 |
| Phase 13 | Cloud Sync, Backup & Privacy | 🔜 |
| Phase 14 | Polish, Animations, Accessibility & Launch | 🔜 |
| **Future** | **[Wishlist](https://github.com/ayehya2/wishlist) integration** — price tracking, gift reservation, single sign-on migration | 💡 |

---

Built with ❤️ for a better life.

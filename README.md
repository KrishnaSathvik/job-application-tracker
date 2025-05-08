# 📝 Job Application Tracker

A simple yet powerful job application tracker built using HTML, Bootstrap, JavaScript, and IndexedDB (via Dexie.js). The app helps users organize and manage their job applications efficiently with status tracking, notes, filters, charts, and more — all within the browser, no login required.

🔗 [Live App](https://krishnasathvik.github.io/job-application-tracker)  
📁 [GitHub Repository](https://github.com/KrishnaSathvik/job-application-tracker)

---

## ✨ Features

- Add, edit, and delete job applications
- Track status: Applied, Interviewing, Offered, Rejected, etc.
- Save additional info like resume link, contact person, deadline
- Filter by application status
- Visual charts for quick insights (Chart.js)
- Goal-setting and milestone modals
- Fully offline & data persists using IndexedDB (Dexie.js)

---

## 🛠️ Tech Stack

- **Frontend:** HTML, Tailwind CSS (previously Bootstrap), JavaScript
- **Database:** IndexedDB using [Dexie.js](https://dexie.org/)
- **Visualization:** [Chart.js](https://www.chartjs.org/)
- **UI/UX Add-ons:** Modals for goal setting, editing, recovery, milestones

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/KrishnaSathvik/job-application-tracker.git
cd job-application-tracker
```

### 2. Open in Browser

No installation needed. Simply open the `index.html` file in your browser.

```bash
open index.html  # For macOS
# or
start index.html # For Windows
```

---

## 🧱 Project Structure

```
job-application-tracker/
├── index.html
├── css/
│   └── tailwind.css
├── js/
│   ├── app.js              # Main logic for CRUD & filters
│   ├── chart.js            # Chart rendering
│   └── db.js               # Dexie.js DB config
├── assets/
│   └── icons, images...
└── README.md
```

---

## 📈 Future Enhancements

- Notification alerts for deadlines
- Sync with Google Sheets or Firebase
- Dark mode toggle
- Progressive Web App (PWA) support

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

### Steps:

1. Fork the repo
2. Create a feature branch
3. Commit your changes
4. Push to your fork
5. Open a pull request

---

## 📄 License

[MIT License](LICENSE)

---

## 👤 Author

**Krishna Sathvik**  
📧 [Connect on LinkedIn](https://www.linkedin.com/in/krishnasathvik)  
📸 [Instagram - TravelsWithKrishna](https://www.instagram.com/travelswithkrishna)

---

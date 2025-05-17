
# 🕸️ Hack The Haze – Fullstack Image Scraper Starter

Welcome to the official starter repository for **Hack The Haze – Theme 2**  
🌐 *Fullstack Web App to Scrape Images from URLs*

Hosted by [brainfogdev](https://github.com/brainfogdev)

---

## 📌 Problem Statement

> Create a fullstack web application that accepts one or multiple URLs from users, scrapes those web pages, and returns all the image links found.

---

## ✅ Requirements

### 🎯 Frontend (React)

- Input field to enter one or multiple URLs (comma-separated or multiline)
- Display all image results in a responsive grid or layout
- Handle:
  - Loading state
  - Error state
  - Empty/no images
- Clean, simple UX

### 🛠️ Backend (Python or Node.js)

- Accept URLs from the frontend
- Scrape each web page
- Return image links as JSON
- Handle:
  - Invalid or unreachable URLs
  - Duplicate image filtering (optional)

### 📊 Optional Features

- URL validation and normalization
- Image caching
- History storage using SQLite/PostgreSQL
- Pagination or lazy-loading
- User authentication

---

## 🧰 Preferred Stack

- **Frontend**: React.js (JavaScript or TypeScript)
- **Backend**: 
  - Python (Flask or FastAPI) **or**  
  - Node.js (Express)
- **Optional DB**: SQLite / PostgreSQL
- **Optional Deployments**:
  - Frontend: Vercel / Netlify
  - Backend: Render / Railway

---

## 📁 Suggested Folder Structure

```

hackthehaze-fullstack-image-scraper/
├── client/              # Frontend (React.js)
│   ├── src/
│   └── public/
├── server/              # Backend (Node.js or Python)
│   ├── routes/
│   └── utils/
├── README.md
└── THOUGHTS.md

````

---

## 🏁 Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/brainfogdev/hackthehaze-fullstack-image-scraper.git
cd hackthehaze-fullstack-image-scraper
````

---

### 2. Setup Frontend

```bash
cd client
npm install
npm start
```

---

### 3. Setup Backend (Choose One)

#### ▶️ Node.js (Express)

```bash
cd server
npm install
npm run dev
```

#### 🐍 Python (Flask/FastAPI)

```bash
cd server
pip install -r requirements.txt
uvicorn main:app --reload
```

---

## 📝 Submission Guidelines

Ready to launch your scraper? Follow these steps to submit your project:

---

### 1️⃣ **Fork This Repo**

> Click the **Fork** button to create your copy. Then clone and start building.

---

### 2️⃣ **Build Your Solution**

Finish the frontend + backend. Make it robust, clean, and beautiful.

---

### 3️⃣ **Include the Following Files**

📄 `README.md`

* Project overview
* Tech stack
* Setup instructions
* Screenshots or demo GIFs (recommended!)

🧠 `THOUGHTS.md`

* Your approach & logic
* Challenges and solutions
* Improvements you'd add with more time

---

### 4️⃣ (Optional) Deploy Your Project

* Deploy frontend (Vercel/Netlify)
* Deploy backend (Render/Railway)
* Paste the live links in your README

---

### 5️⃣ **Submit on Unstop**

Submit the following on the [Unstop Hackathon Portal](https://unstop.com):

* 🔗 GitHub repository URL
* 🔗 Live deployed links (if available)

---

## 💡 Tips to Win

* Handle messy, real-world inputs cleanly
* Scrape efficiently and responsibly
* Design a beautiful frontend
* Validate URLs and give great feedback to users
* Impress us with extras like caching or DB history!

---

## 🤝 Need Help?

Stuck? Reach out to the organizing team or open an [Issue](https://github.com/brainfogdev/hackthehaze-fullstack-image-scraper/issues).

---

## 🏆 Build Smart. Scrape Clean. Stand Out.

This isn't just another CRUD app — it's your chance to build a **useful, fullstack utility with real-world impact.**
Impress the judges and **hack the haze**! 🕸️⚡🖼️



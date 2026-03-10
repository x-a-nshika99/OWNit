 <div align="center">
 

# 🚀 OwnIt — Proof-Based Accountability System

**Tracking is common. Enforcement is not.**

*Transform personal goals into structured commitments — with proof, streaks, and AI-powered reflection.*

<br/>

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)

<br/>

> 🏆 Built for **HackShodh 2026** — A platform that replaces motivation with measurable execution.

</div>

---

## 📌 Overview

**OwnIt** transforms personal goals into structured commitments backed by real proof.

Most productivity tools track *intentions*. OwnIt enforces *execution*.

Instead of relying on reminders or motivation, the platform requires users to:
- 📸 **Submit daily proof of work**
- 🔥 **Maintain active streaks**
- 🧠 **Reflect on missed actions** — with AI-driven analysis

This makes progress measurable and inconsistency impossible to ignore.

---

## ✨ Key Features

### 🔒 Locked Goal System
Users can set **only one active goal at a time**, ensuring focused execution with zero distractions.

### 📸 Daily Proof Submission
Every day, users must submit verifiable proof of effort:
| Proof Type | Examples |
|---|---|
| 📷 Screenshots | App screenshots, progress photos |
| 📁 Files | Documents, designs, reports |
| 💻 Project Outputs | Builds, exports, deliverables |
| 🐙 GitHub Commits | Code pushed to repository |

### 🔥 Streak-Based Consistency
- Each successful submission **increases the streak**
- A missed day **resets the streak** + triggers mandatory reflection
- Visual streak indicators keep accountability front and center

### 🧠 Reflection Mechanism
When a day is missed, users must submit a reflection explaining why. This promotes:
- Self-awareness over self-deception
- Pattern recognition in behavior
- Intentional accountability

### 🤖 AI Reflection Analysis
Powered by OpenAI, the AI reads reflections and identifies:
- **Ownership level** — Are they taking responsibility?
- **Excuse patterns** — Repeated avoidance signals
- **Commitment signals** — Language that shows genuine intent

### 📊 Risk Score Indicator
A data-driven **risk score** predicts the likelihood of future streak breaks based on:
- Reflection quality
- Submission consistency
- Historical behavior patterns

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React.js, Tailwind CSS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **Authentication** | Firebase Authentication |
| **Storage** | Cloudinary |
| **AI Integration** | OpenAI API |

---

## ⚙️ System Flow

```
User
 │
 ▼
Frontend Interface  (React + Tailwind)
 │
 ▼
Backend API         (Node.js + Express)
 │
 ▼
Authentication      (Firebase Auth)
 │
 ▼
Proof Upload        (Cloudinary Storage)
 │
 ▼
Streak Calculation  (Custom Logic)
 │
 ▼
AI Reflection Analysis  (OpenAI API)
 │
 ▼
Risk Score Generation
 │
 ▼
Dashboard Visualization
```

---

## 📂 Project Structure

```
ownit/
│
├── client/                  # React frontend
│   ├── components/          # Reusable UI components
│   ├── pages/               # Route-level pages
│   └── services/            # API call handlers
│
├── server/                  # Node.js backend
│   ├── routes/              # API route definitions
│   ├── controllers/         # Business logic
│   ├── models/              # MongoDB schemas
│   └── services/            # AI & external integrations
│
├── utils/                   # Streak & risk score logic
├── docs/                    # Architecture documentation
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js `v18+`
- MongoDB (local or Atlas)
- Firebase project credentials
- Cloudinary account
- OpenAI API key

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/ownit.git
cd ownit

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
```

### Environment Variables

Create a `.env` file in `/server`:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
FIREBASE_API_KEY=your_firebase_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
OPENAI_API_KEY=your_openai_key
```

### Run the App

```bash
# Start backend
cd server
npm run dev

# Start frontend (in a new terminal)
cd client
npm start
```

---

## 🎥 Demo

> 🎬 Screenshots and demo video will be added after deployment.

---

## 🌍 Why OwnIt Matters

| Traditional Tools | OwnIt |
|---|---|
| Track intentions | Enforces execution |
| Motivation-dependent | Proof-dependent |
| Easy to ignore | Accountability is mandatory |
| No consequence for failure | Streak reset + reflection required |

By combining **proof verification**, **streak tracking**, **reflection analysis**, and **AI-powered behavioral insights**, OwnIt promotes consistent effort and long-term behavioral change.

---

## 🔮 Future Roadmap

- [ ] Advanced behavioral analytics dashboard
- [ ] AI streak-break prediction engine
- [ ] Adaptive accountability groups
- [ ] Mobile application (iOS + Android)
- [ ] Public proof feed for social accountability

---

## 📚 References

- [Habit Tracking — James Clear](https://jamesclear.com/habit-tracker)
- [Behavioral Change Support Systems — Wikipedia](https://en.wikipedia.org/wiki/Behavioral_change_support_system)
- [Persuasive Technology — Wikipedia](https://en.wikipedia.org/wiki/Persuasive_technology)
- [Digital Behavior Change Research — NCBI](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11161714/)

---

<div align="center">

**Built with 💜 at HackShodh 2026**

*If this project resonates with you, drop a ⭐ on the repo!*

</div>

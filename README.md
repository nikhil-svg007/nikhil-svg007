<div align="center">
  <img src="https://raw.githubusercontent.com/nikhil-svg007/assets/main/nikhil-banner.svg" width="100%" alt="Nikhil Banner" />
</div>

<p align="center">
  <a href="https://linkedin.com/in/YOUR-LINKEDIN">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:getnikhil96616@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://github.com/nikhil-svg007">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://leetcode.com/u/I_nikhil/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" />
  </a>
  &nbsp;
  <a href="https://codeforces.com/profile/getnikhil96616">
    <img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=flat-square&logo=codeforces&logoColor=white" />
  </a>
</p>

---

## About

I'm a full-stack engineer specializing in the **MERN stack**, with a strong focus on **system design**, **real-time architecture**, and **security**. I approach every project by thinking through scalability, data flow, and failure modes before writing a single line of code.

Recent work includes a **real-time banking dashboard with a fraud detection engine**, a **production-style crypto paper-trading simulator** with live Binance price feeds, and an **AI-powered developer collaboration platform** — all built with production-grade architecture in mind.

**Currently open to full-time roles and internships.**

---

## Projects

### [VaultGuard](https://github.com/nikhil-svg007/vaultguard) — Real-Time Banking Dashboard
> Full-stack banking application with a built-in fraud detection engine and real-time transaction monitoring.

- Designed a fraud detection engine flagging transactions by large amounts, high velocity, unusual hours, and round-figure patterns
- Built a live transaction and fraud-alert feed with Socket.io; admin controls for account freeze, dispute, and rollback
- Separate customer and admin/analyst portals with role-based access control
- JWT authentication, bcrypt password hashing, and Redis-powered rate limiting (100 req/min)

`React` `Redux Toolkit` `Tailwind CSS` `Node.js` `Express` `MongoDB` `Redis` `Socket.io` `JWT`

---

### [Crypto Trading Simulator](https://github.com/nikhil-svg007/crypto-trading-simulator) — Real-Time Paper Trading Platform
> Production-style MERN crypto paper-trading simulator streaming live Binance prices, with atomic trade execution and FIFO P&L.

- Streams live prices for 7+ trading pairs from the Binance WebSocket API into an in-memory, O(1) price registry
- Atomic BUY/SELL execution using MongoDB multi-document transactions and conditional atomic updates to prevent overspending/overselling under concurrent requests
- FIFO-based realized P&L via a dedicated position-lot model, with Decimal128/decimal.js precision handling
- Redis-cached, trade-invalidated leaderboard and JWT auth with refresh-token rotation via HttpOnly cookies

`React` `Vite` `Socket.io Client` `Node.js` `Express` `MongoDB` `Redis` `JWT` `Binance WebSocket API` `decimal.js`

---

### [Workloom](https://github.com/nikhil-svg007/workloom) — AI-Powered Developer Collaboration Platform
> A single workspace unifying project management, bug tracking, real-time chat, file sharing, and an AI assistant for dev teams.

- Project, task, and bug tracking with role-based and ownership-based access control (Admin/Member) enforced at the API layer
- Real-time team chat and live activity updates via Socket.io
- Integrated Google Gemini API for code explanation, bug detection, API/schema generation, and README creation, with per-user rate limiting
- Secure file uploads via Multer, backed by JWT-authenticated protected routes

`React` `Tailwind CSS` `Node.js` `Express` `MongoDB` `Socket.io` `JWT` `Multer` `Gemini API`

---

## Tech Stack

| Layer | Technologies |
|---|---|
| **Frontend** | React, Vite, Redux Toolkit, Tailwind CSS, Recharts |
| **Backend** | Node.js, Express.js, Socket.io |
| **Database / Cache** | MongoDB, MySQL, Redis |
| **Auth & Security** | JWT, bcrypt |
| **Tools** | Git, NPM, Docker, Postman |

---

## Competitive Programming

| Platform | Handle | Rating |
|---|---|---|
| LeetCode | [I_nikhil](https://leetcode.com/u/I_nikhil/) | 1500+ |
| Codeforces | [getnikhil96616](https://codeforces.com/profile/getnikhil96616) | 1100 — Pupil |

Solved 300+ DSA problems across Arrays, Trees, Graphs, Dynamic Programming, and System Design fundamentals.

---

<div align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%" />
</div>

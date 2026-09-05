# Hi, I'm Mudit Gola👋

IT undergrad at **Delhi Technological University (DTU)**, graduating 2027.
I build full-stack web apps (MERN + Next.js) and grind DSA for SDE interviews.

- 🔭 Building real-time and AI-powered web apps — see the projects below
- 🌱 Currently sharpening **C++ DSA** and full-stack fundamentals
- 🧩 **400+ LeetCode** solved · **1650+** contest rating (top ~24% globally)
- 💬 Ask me about **MERN, Next.js, WebSockets, or REST API design**
- 📫 Reach me — [LinkedIn](https://leetcode.com/u/Muditgola15/) · [Email](mailto:muditgola1@gmail.com)

## 🛠️ Tech Stack

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## 🚀 Projects

### [CoinTickR](https://github.com/Muditgolaa/CoinTickR) — Real-Time Crypto Analytics Dashboard
`Next.js` · `TypeScript` · `React` · `WebSockets` · `REST APIs`
- Integrated CoinGecko's REST API with a Binance WebSocket feed for sub-second price/trade streaming, rendering live candlestick (OHLC) charts that update with no page reloads.
- Designed a dual-source architecture decoupling REST and WebSocket layers behind a single hook, delivering live streaming on free API tiers instead of a paid plan.
- Server-side data fetching via Next.js App Router + Server Actions to keep API access off the client; shipped a global Cmd/Ctrl+K command palette with debounced live search.

### [Spanda](https://github.com/Muditgolaa/Spanda) — Multi-Device Synchronized Audio
`Next.js` · `TypeScript` · `Node.js` · `Socket.IO` · `Web Audio API` · `Zod`
- Devices in a 6-digit room play in **~10 ms sync** via NTP-style clock sync over WebSockets (40 samples, worst-half outlier rejection) with sample-accurate Web Audio scheduling.
- Built a stateless Socket.IO relay (in-memory rooms, no DB) with a Zod discriminated-union message protocol validated on every inbound frame; all playback logic runs client-side.
- Engineered spatial audio (source orbiting a 2D room, per-client gain maps at ~30 fps) plus a real-time FFT visualizer and direct-to-Cloudinary uploads.

### [Serverless E-Commerce Analytics Pipeline](https://github.com/Muditgolaa/Serverless-E-Commerce-Analytics-Pipeline) — Data Engineering
`Python` · `AWS Glue` · `S3` · `PySpark` · `SQL` · `Power BI`
- Built a serverless ETL pipeline on AWS Glue and S3, transforming raw e-commerce data with PySpark and SQL.
- Surfaced the cleaned dataset in Power BI dashboards for analytics and reporting.

### [NipunAI](https://github.com/Muditgolaa/NipunAI) — AI Interview Coach
`React` · `Node.js` · `Express` · `MongoDB` · `JWT` · `Groq LLM` · `OAuth`
- Full-stack MERN app that turns a job description into 8 AI-generated questions and scores each timed answer **0–100** with feedback via the Groq LLM.
- Designed a REST API (12+ endpoints) and a 4-collection MongoDB schema, with an aggregation pipeline powering the analytics dashboard.
- Implemented JWT + bcrypt auth and Google OAuth from scratch; middleware scopes every query to the logged-in user, with rate-limited AI routes.
## and more...

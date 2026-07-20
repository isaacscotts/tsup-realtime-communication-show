# Real-Time Communication Ecosystem (Web & Mobile)

A full-featured, cross-platform real-time messaging and communication platform inspired by modern applications like WhatsApp and Discord. 

This ecosystem features both a **React Web Application** and a **React Native Mobile Application (CLI)** powered by a unified TypeScript backend, focusing on scalable real-time systems, native media streams, and consistent cross-platform state management.

---

## 🌐 Live Deployments & Demo

- **Web App Demo:** 👉 https://isaac-tsups-ts.vercel.app/
- **Android APK (Mobile Build):** 👉https://drive.google.com/file/d/1W0CuMIpY9ga5HOkpSUq7CdR6sFr1E1dK/view?usp=drivesdk

> ⚡ **Render Free Tier Note:** The backend server is hosted on Render's free tier. If the link takes 50–60 seconds to respond initially, the server is just waking up from a spinning-down period (cold start). Once awake, real-time communications operate with normal, low-latency performance.

---

## 🔥 Features

### 🔐 Authentication & Onboarding
- Cross-platform user authentication and route protection (Clerk)
- User registration via webhooks
- Onboarding flow with editable profiles and avatar selection

### 💬 Messaging & Real-Time Communication
- Cross-platform real-time messaging using WebSockets (Socket.IO)
- Chat history persistence and status tracking (Sent / Delivered / Read)
- Typing and voice recording indicators
- Real-time presence updates (Online / Offline / Last Seen)
- Context menu interactions

### 📸 Media & Audio
- Image sharing and file uploads handled via Multer
- Voice message recording with dynamic waveform visualization
- Audio processing using Web Audio API (AudioContext + AnalyserNode) on web
- Native camera capture and device video stream integration

### 📞 Calls & Streaming
- Peer-to-peer audio and video calling between web and mobile clients
- Real-time signaling using WebSockets
- Low-latency media streaming using WebRTC

---

## 🧠 Tech Stack

### Client Applications
- **Web:** React, TypeScript, Tailwind CSS
- **Mobile:** React Native (CLI), TypeScript, Native Modules

### Backend Infrastructure
- **Server:** Node.js, Express, TypeScript
- **Database & ORM:** PostgreSQL, Prisma
- **Real-Time & Media:** Socket.IO, WebRTC, Web Audio API

---

## 🏗️ Technical Architecture Highlights

- **Cross-Platform State:** Structured the data layers so both the React web client and React Native mobile client receive identical real-time event payloads via Socket.IO.
- **Media Pipeline:** Implemented audio capturing and rendering via the browser's `AudioContext` on web, mirrored with native audio recording permissions and hardware streams on mobile.
- **P2P Streaming:** Utilized WebRTC for full mesh signaling to handle audio/video tracks between distinct device types with minimal latency.

---

## 🔒 Source Code

The source code repositories for both the Web and React Native applications are kept private.

However, I’m happy to:
- Walk through the cross-platform architecture
- Explain implementation details
- Demonstrate specific features via a live code review call

---

## 🤝 Open to Opportunities
I’m open to collaborations, contract roles, or freelance work related to Full-Stack Web Development, React Native (CLI), and real-time network systems.

## 📫 Contact
- **Email:** isaacscottsk@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/kayima-isaac-70a8a03a3/

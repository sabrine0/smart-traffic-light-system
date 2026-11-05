# 🚦 Smart Traffic Light System (STLS)

A connected, **adaptive traffic-management platform** — from AI-assisted signal timing to
operator & police dashboards, a live simulation and a real hardware controller.

## 🧩 Monorepo Structure
| Folder | Stack | Role |
|--------|-------|------|
| `backend/` | **NestJS**, TypeORM, JWT, WebSockets (Socket.IO) | REST + realtime API, auth, signal logic |
| `frontend/` | **Next.js**, React, Google Maps, Three.js, 3D force-graph | Operator & police dashboards, live map, simulation |
| `mobile/` | React Native / Expo | On-the-go monitoring |
| `desktop/` | Desktop client | Control-room app |
| `controller-runtime/` | Hardware runtime | Drives the physical signal controller (Arduino) |
| `tools/` | pptxgenjs, Puppeteer | Reporting / deck generation |
| `docs/` | Markdown | Hardware integration spec & guides |

## ✨ Features
- 🧠 **Adaptive signal timing** based on live traffic conditions
- 🗺️ Interactive **map dashboards** (Google Maps) for operators and police
- 🔌 **Realtime** updates via WebSockets
- 🕹️ Traffic **simulation** and 3D visualization
- 🔧 **Hardware prototype** integration (Arduino-based controller)
- 🔐 JWT authentication and role-based access

## 🛠️ Tech Stack
`NestJS` · `Next.js` · `React` · `TypeORM` · `Socket.IO` · `Google Maps API` · `Three.js` · `Arduino`

## 🚀 Getting Started
Each package has its own README and scripts. Typical flow:
```bash
# backend
cd backend && npm install && npm run start:dev
# frontend
cd frontend && npm install && npm run dev
```

## 🔭 Future Work
- Reinforcement-learning signal optimization
- City-scale multi-intersection coordination

---
*Author: [Sabrine Essaket](https://github.com/sabrine0) · AI & Software Systems*

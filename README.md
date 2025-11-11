# FuelEU Maritime — Full-Stack Compliance Module

This project is a simplified version of the **FuelEU Maritime Regulation (EU 2023/1805)** compliance system.  
It models ship routes, greenhouse gas (GHG) intensities, and compliance balance (CB) management — including **Banking** and **Pooling** features.  
The goal was to design a clean, testable full-stack solution following a **Hexagonal Architecture**, while also experimenting with AI-assisted development.

---

## 🧠 Overview

The platform has two main parts:

- **Frontend:** React + TypeScript + TailwindCSS (dashboard interface)
- **Backend:** Node.js + TypeScript (Express API)
- **Architecture:** Ports & Adapters (Hexagonal)
- **Database:** In-memory for demo; PostgreSQL adapter stub included

The app allows users to:

- View and filter ship routes
- Compare GHG intensities against baseline values
- Calculate and bank compliance balances
- Form compliant pools between ships

_This project demonstrates a clean architectural approach, practical AI-assisted coding, and working end-to-end functionality with a modern TypeScript stack._

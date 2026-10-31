# 🏠 RoomieSplit — Real-Time Flatmate Expense & Chore Sync

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

> **Stop arguing over unpaid Wi-Fi bills and unwashed dishes.** RoomieSplit is a real-time, zero-setup web app that automates shared apartment expenses, simplifies circular debts, and gamifies daily flat chores.

---

## ⚡ The Problem vs. Our Solution

* **The Problem:** Living with flatmates often leads to messy WhatsApp money trails, circular IOUs (*"A owes B, B owes C"*), and forgotten household chores.
* **The Solution:** **RoomieSplit** links roommates via a unique **Room ID** (`RM-XXXX`). Anyone who signs in with the code joins the flat automatically—syncing bills, simplified settlements, and chore streaks across every device in real time.

---

## 🚀 Key Features

* **🔑 Frictionless Room ID Onboarding:** Enter your name and a shared `RM-XXXX` code on the welcome screen to automatically join the flat roster across devices.
* **💸 Smart Debt Simplification:** Condenses messy circular debts into the minimum number of transfers using a greedy net-balance algorithm.
* **📲 1-Click WhatsApp Settlement Receipt:** Generates a clean, formatted payment summary ready to paste into the flat WhatsApp group.
* **🧹 Gamified Chore Rota (+ Karma Points):** Assign **One-Time** or **Repeating** tasks (*Daily, Weekly, Alternate Days*). Completing chores on time awards **+15 Karma** and builds a live reliability leaderboard.
* **📊 Live Spending Analytics:** Interactive Chart.js doughnut breakdown across *Rent, Groceries, Utilities, Wi-Fi,* and *Night Out*.
* **🧪 1-Click Judge Demo Mode:** Populates realistic student apartment data instantly for live evaluation without manual typing.

---

## 🧠 How Debt Simplification Works

Instead of everyone paying everyone else back and forth, RoomieSplit calculates each flatmate's **Net Balance**:

$$\text{Net Balance} = \text{Total Paid} - \text{Equal Share}$$

If **Alex** owes **Rohan ₹500**, and **Rohan** owes **Priya ₹500**, RoomieSplit eliminates the middleman and outputs a single transfer: **Alex → Priya (₹500)**.

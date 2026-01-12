# Esports Tournament Logistics Planner 🎮🏆

## 📌 Project Overview
Designed an operational runbook for a Tier-1 LAN Tournament (e.g., BGMI/Valorant Series). This project manages the logistics for **16 Professional Teams (80+ Athletes)** including travel, accommodation, and compliance checks.

## 📊 Operational Scope
* **Travel Coordination:** Tracking flight arrivals (IndiGo/Air India) and arranging airport pickups for 50+ travelers.
* **Hospitality:** Managing rooming lists (Twin Sharing for players, Single for Managers) at partner hotels (Radisson/Novotel).
* **Risk Management:** Monitoring critical flags in the dataset:
    * 🚩 **Visa Expiry:** Detected for Player 'Ash' (Team Orangutan).
    * 🚩 **Flight Cancellations:** Identified for Team Numen (AI-810).
    * 🚩 **Tech Failures:** PC Setup failed for Player 'Troye' (Entity Gaming).

## 🛠 Tools Used
* **Data Management:** CSV dataset simulating real-time event tracking.
* **Crisis Protocols:** Conditional logic to highlight delayed flights or failed compliances immediately.

## 🚀 Business Relevance
Demonstrates the ability to handle high-pressure event logistics, applicable to roles in **Esports Operations, Event Management, and Supply Chain**.

## 📅 Event Timeline (Logistics Plan)
```mermaid
gantt
    title Tournament Day 1 Operations
    dateFormat  HH:mm
    axisFormat %H:%M
    section Arrivals
    Team Soul Arrival       :done,    10:00, 11:00
    Enigma Gaming Arrival   :active,  11:30, 12:30
    section Hotel Ops
    Check-in & Rooming      :         11:00, 13:00
    Lunch Buffer            :         13:00, 14:00
    section Tech Checks
    Network Setup           :crit,    09:00, 12:00
    Player PC Setup         :         14:00, 16:00

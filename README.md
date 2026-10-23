# 🛡️ Raqeeb (رقيب) | Hajj Hackathon Finalist

> **A Digital Operational Intelligence Layer for Holy Sites Maintenance & Safety**  
> 🏆 **Top 4 Finalist** at the Umm Al-Qura Hajj Hackathon.

---

## 📌 Project Overview
During the Hajj season, multiple entities operate across the Holy Sites (Makkah, Mina, Arafat, Muzdalifah) with fragmented systems and isolated data. **Raqeeb** acts as a smart operational intelligence layer built *on top* of existing systems without replacing them[cite: 5, 10]. It bridges maintenance and safety data spatially and temporally to prevent conflicts, avoid delays, and provide a unified oversight dashboard for higher authorities.

---

## 🎯 The Problem & Impact
- **Fragmentation:** Over 400 government and private entities operate independently with separate databases and schedules.
- **Operational Conflicts:** Lack of a unified mechanism to detect overlapping maintenance works (e.g., road excavations and electrical cable repairs occurring in the same place and time).
- **Historical Context:** Disjointed operations historically led to severe delays, safety risks, and operational inefficiencies.

---

## 💡 The Solution (How Raqeeb Works)
Raqeeb integrates data from diverse sources and processes it through a unified pipeline:
1. **Data Integration Layer:** Gathers maintenance and safety logs via **APIs**, **Webhooks**, and secure **SFTP File Transfers** (Hybrid integration strategy).
2. **Spatial & Temporal Correlation:** Maps work orders by geographic location and schedule to instantly flag spatial, temporal, or combined conflicts.
3. **Predictive Analytics:** Analyzes historical patterns to forecast potential delays and root causes.
4. **Unified Oversight Dashboard:** Provides decision-makers with real-time analytics, interactive maps, key performance indicators (KPIs), and automated alerts.

---

## 🔄 Integration Strategy (Hybrid Approach)
* **APIs & Webhooks:** For advanced entities, ensuring real-time and secure data synchronization with read-only permissions.
* **File Sharing (SFTP / CSV / Excel):** A secure, periodic fallback solution designed for legacy systems to lower the barrier of entry.

---

## 📂 Repository Contents
- `presentation/` - Official Pitch Deck & Presentation PDF (`__ابتكار بنيان (رقيب)_.pdf`).
- `documentation/` - Comprehensive Project Memo & Technical Breakdown (`__مذكره رقيب _.pdf`).

---

## 👥 Team
Developed by Team **Bonyan**:
* **Aseel Zainy**
* **Hala Al-Jawii**
* **Asal Kalntan** 
*(Umm Al-Qura University - Custodian of the Two Holy Mosques Institute for Hajj and Umrah Research)*

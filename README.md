# 🎪 Queuechella - Discrete Event Simulation & Operations Optimization 🎸

Welcome to the Queuechella Simulation Project! This repository showcases a comprehensive, end-to-end Discrete Event Simulation (DES) process for modeling and optimizing the daily operations of a massive two-day music festival.

The project covers the entire simulation lifecycle: from raw data analysis and distribution fitting to Object-Oriented implementation, event-driven logic, and statistical optimization under real-world budget constraints.

### 🚀 Project Overview

The goal of this project was to design a highly detailed simulation of the "Queuechella" music festival to identify bottlenecks and improve overall visitor satisfaction. By tracking the complete visitor journey—including entry gates, distinct music stages, food stalls, and peripheral attractions—we tested various operational upgrades to find the most cost-effective solutions within a **1,000,000 ₪ budget**.

### 🛠️ Tools & Technologies Used

* **Environment:** Google Colab / Jupyter Notebook 
* **Programming Language:** Python 🐍
* **Architecture:** Object-Oriented Programming (OOP) & Top-Down Design
* **Statistical Analysis:** NumPy & SciPy (Distribution fitting, MLE, random sampling)
* **Data Handling & Visualization:** Pandas & Matplotlib
* **Methodology:** Discrete Event Simulation (DES)

---

### 📈 The End-to-End Process (Step-by-Step)

#### Phase 1: Data Analysis & Distribution Fitting 📊
* Analyzed historical festival data to find the best-fit distributions for service times and arrival rates.
* Implemented custom random number generators and sampling algorithms (e.g., Box-Muller for Normal distribution, Inverse Transform, and **Acceptance-Rejection** for complex DJ Stage duration formulas).

#### Phase 2: Object-Oriented Conceptual Design 🏗️
* Mapped the entire festival into a robust class architecture.
* **Entities:** Modeled different visitor types with unique behaviors, patience thresholds, and preferences (Singles, Couples, and Friend Groups).
* **Facilities:** Created modular classes for the Main Stage, Indie Stage, DJ Stage, Photo Stations, Merch Tents, Body Art, and Food Courts.

#### Phase 3: Event-Driven Simulation Logic ⏳
* Built a dynamic Future Event List (FEL) to manage time and schedule events chronologically.
* Implemented complex real-world logic: queue abandonment limits (e.g., leaving a line after 15-20 minutes), group splitting/waiting, and dynamic facility capacities.
* **Satisfaction Scoring:** Developed a dynamic rating mechanism that updates continuously based on wait times, show experiences, and music genre preferences.

#### Phase 4: Optimization & Alternative Testing 💰
* Configured the baseline "As-Is" scenario to extract current KPIs (Wait times, bottleneck identification, average satisfaction).
* Simulated multiple operational upgrades under a **1,000,000 ₪ budget**, including:
  * 🍔 *Better Kitchen Staff* (Reducing bad meal probabilities).
  * 🛡️ *Security Expansion* (Increasing stage capacities by 30%).
  * 🎫 *Automated Entry Gates* (Slashing initial entrance wait times).
  * 🎸 *Premium Mainstream Bands* (Boosting satisfaction and merch sales).

#### Phase 5: Statistical Analysis & Conclusions 📉
* Calculated the required number of simulation runs to achieve a **0.1 relative precision**.
* Performed rigorous statistical comparisons between the baseline and the proposed alternatives at a **90% confidence level**.
* Delivered actionable, data-backed recommendations to maximize the festival's ROI and operational efficiency.

---

### 📂 Repository Structure

* `/Code:` The complete Python simulation notebook (Colab format), fully documented in English.
* `/Data:` Raw Excel files containing historical festival samples (`samples_for_simulation.xlsx`).
* `/Docs:` Detailed simulation reports including flowcharts, distribution fitting mathematical proofs, and event graphs.
* `/Presentation:` Final executive summary slides outlining the statistical comparison and recommended budget allocation.

---
*This project was completed as part of the "Simulation" B.Sc. course in the Industrial Engineering & Management Department at Ben-Gurion University of the Negev.*

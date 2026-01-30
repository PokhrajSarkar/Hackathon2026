# Project Name: [RescueLink]
**Problem Statement ID:** CS05TS  
**Team Name:** [Kittens Can Code]  
**College Name:** [St Aloysius (Deemed to be University)-AIMIT]

## 🌐 Live Demo
**[Click here to view the Live Emergency Portal](https://pokhrajsarkar.github.io/Hackathon2026/)**

---

## ## Problem Statement
Road accident victims often face life-threatening delays ("The Golden Hour") due to slow notification systems and the difficulty of communicating precise GPS locations to emergency responders during high-stress situations.

## ## Proposed Solution
**RescueLink** is a lightweight, one-tap web portal that bypasses traditional call centers. It allows bystanders or victims to send instant, location-verified alerts directly to EMS providers with zero friction.

## ## Key Features
* **One-Tap SOS:** Uses the Browser Geolocation API to lock GPS coordinates instantly.
* **Two-Stage Emergency Flow:** Separates location locking from data entry to ensure coordinates are captured even if the user is interrupted.
* **Contextual Dispatch:** Collects User Name and Emergency Type (Road Accident, Medical, Fire) to better inform First Responders.
* **Live UI State Management:** Seamlessly transitions between SOS, Data Entry, and Success states without refreshing the page.
* **Responder Dashboard (New):** A dedicated view for EMS personnel to receive incoming alerts and view coordinates in real-time.

## ## Technical Complexity & Stack
* **Frontend:** HTML5 & Tailwind CSS (for rapid, responsive UI).
* **Logic:** Vanilla JavaScript (Geolocation API).
* **Data Flow:** Cross-page communication using `localStorage` to simulate real-time database updates.
* **Version Control & Hosting:** GitHub Web Workflow & GitHub Pages.

## ## Usability & Impact
* **Target Users:** Accident victims, bystanders, and EMS dispatchers.
* **Impact:** By automating location sharing and context gathering, we aim to reduce emergency response times by 30-50%, directly saving lives.

## ## Setup Instructions
1. Visit the live link provided above on any smartphone or modern web browser.
2. Grant "Location Access" when prompted to allow the SOS system to function.
3. Fill in the emergency details and click "Confirm & Dispatch".
4. To view the responder side, visit: `https://pokhrajsarkar.github.io/Hackathon2026/dashboard.html`.

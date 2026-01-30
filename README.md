# Project Name: RescueLink
**Problem Statement ID:** CS05TS  
**Team Name:** Kittens Can Code  
**College Name:** St Aloysius (Deemed to be University)-AIMIT

## ## Problem Statement
Road accident victims often face life-threatening delays due to slow notification systems and the difficulty of communicating precise GPS locations to emergency responders during high-stress situations. This gap in the "Golden Hour" significantly reduces survival rates.

## ## Proposed Solution
RescueLink is a lightweight, one-tap web portal designed for instant emergency reporting. It bypasses traditional call centers to send location-verified alerts directly to an EMS Dispatch Dashboard, allowing for immediate mobilization of medical help with zero friction.

## ## Innovation & Creativity
Unlike native apps that require pre-installation, RescueLink is a zero-install web solution. It utilizes the browser's native Geolocation API to ensure 100% accuracy in victim location without requiring the user to speak or know their surroundings. It features a two-stage logic that locks location first, then gathers context.

## ## Technical Complexity & Stack
* **Frontend:** HTML5, Tailwind CSS (Responsive UI)
* **Logic:** Vanilla JavaScript (ES6+)
* **APIs:** HTML5 Geolocation API
* **Data Flow:** Cross-page communication via `localStorage` for simulated real-time updates.
* **Version Control:** GitHub
* **Deployment:** GitHub Pages

## ## Usability & Impact
* **Users:** Accident victims, bystanders, and EMS dispatchers.
* **Interaction:** Users interact via a high-contrast SOS button; responders monitor a live dashboard feed.
* **Impact:** Aims to reduce emergency response times by 30-50% by automating the data transfer process.

## ## Setup Instructions
1. Clone the repository or access the live link.
2. Open `index.html` in any modern web browser to act as the Victim.
3. In a separate tab (same browser), open `dashboard.html` to act as the Dispatcher.
4. Grant location permissions when prompted to enable GPS tracking.

## ## Presentation / Demo Link
* **Live Deployment:** [https://pokhrajsarkar.github.io/Hackathon2026/](https://pokhrajsarkar.github.io/Hackathon2026/)
* **Responder View:** [https://pokhrajsarkar.github.io/Hackathon2026/dashboard.html](https://pokhrajsarkar.github.io/Hackathon2026/dashboard.html)

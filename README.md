# Project Name: RescueLink
**Problem Statement ID:** CS05TS  
**Team Name:** Kittens Can Code  
**College Name:** St Aloysius (Deemed to be University)-AIMIT

## Problem Statement
Traditional emergency reporting relies on voice calls, which are prone to human error, panic, and difficulty in communicating precise GPS locations. This delay often results in missing the "Golden Hour," significantly reducing the survival chances of road accident victims.

## Proposed Solution
RescueLink is a high-speed web-based emergency bridge. It allows victims or bystanders to broadcast their exact GPS coordinates and incident type (Road Accident, Fire, or Medical) to a centralized Dispatch Dashboard with a single tap, ensuring responders have precise data before they even leave the station.

## Innovation & Creativity
* **Zero-Install Access:** No app store download required; works via link or QR code for immediate use in high-stress situations.
* **Asynchronous GPS Locking:** Captures location in the background while the user provides context, ensuring data is ready the moment they hit dispatch.
* **Instant Dashboard Sync:** Uses a low-latency data bridge to alert responders in real-time without manual page refreshes.

## Technical Complexity & Stack
* **Frontend UI:** Tailwind CSS for a high-visibility, "Emergency-Response" styled interface.
* **Core Logic:** Vanilla JavaScript (ES6) for broad device compatibility.
* **APIs:** HTML5 Geolocation API for high-precision coordinate tracking.
* **Data Bridge:** LocalStorage-based state management for real-time inter-tab communication.

## Usability & Impact
* **User-Centric Design:** Large, high-contrast buttons for users in shock or low-light conditions.
* **Impact:** Provides a 1-click solution for reporting, potentially reducing emergency arrival times by 30-50% in urban and rural environments.

## Setup Instructions
1. Open the **Victim Portal** (`index.html`) on a mobile device or browser.
2. Grant Location Permissions when prompted.
3. Tap the **SOS** button to initialize.
4. Fill in the Reporter Name and Accident Category.
5. Hit **Dispatch Responders**.
6. Monitor the **Dispatch Command Center** (`dashboard.html`) to see the live alert and GPS link.

## Presentation / Demo Link
* **GitHub Repository:** https://github.com/PokhrajSarkar/Hackathon2026/
* **Live Deployment:** https://pokhrajsarkar.github.io/Hackathon2026/

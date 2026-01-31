***Project Name***: RescueLink


***Problem Statement ID*** : CS05TS


***Team Name*** : Kittens Can Code


***College Name*** : St Aloysius (Deemed to be University)-AIMIT


***Problem Statement***

Traditional emergency reporting relies on voice calls, which are prone to human error, panic, and difficulty in communicating precise GPS locations. This delay often results in missing the "Golden Hour," significantly reducing the survival chances of road accident victims.


***Proposed Solution***

RescueLink is a high-speed web-based emergency bridge. It allows victims or bystanders to broadcast their exact GPS coordinates and incident type (Road Accident, Fire, or Medical) to a centralized Dispatch Dashboard with a single tap. By utilizing a real-time reactive data stream, it ensures responders have precise data before they even leave the station.


***Innovation & Creativity***

Zero-Install Access: No app store download required; works via link or QR code for immediate use in high-stress situations.

Real-Time WebSocket Sync: Leverages Google Firebase Firestore to push alerts to the dashboard in under 200ms, eliminating the need for manual page refreshes.

Tactical Command UI: A "Glassmorphism" styled interface with a pulsing notification system, optimized for low-light command center environments.

Atomic Resolution Protocol: A one-tap "Mark Resolved" feature that instantly synchronizes the database and clears the global dashboard stream.


***Technical Complexity & Stack***

Frontend UI: Tailwind CSS for a high-visibility, "Emergency-Response" styled interface with custom CSS animations.

Core Logic: Vanilla JavaScript (ES6+) utilizing Asynchronous functions and Event Listeners.

Backend / Database: Google Firebase Firestore (NoSQL) for real-time state management and data persistence.

APIs: HTML5 Geolocation API for high-precision coordinate tracking and Google Maps API for responder intercept routing.


***Usability & Impact***

User-Centric Design: Large, high-contrast buttons and minimal input fields designed for users in shock or low-light conditions.

Impact: Provides a 1-click solution for reporting, potentially reducing emergency arrival times by 30-50% in urban and rural environments by eliminating information decay.


***Setup Instructions***

Open the Victim Portal (index.html) on a mobile device or browser.
Grant Location Permissions when prompted.
Tap the SOS button to initialize the capture.
Fill in the Reporter Name and Incident Category.
Hit Dispatch Responders.
Monitor the Dispatch Command Center (dashboard.html) to view the live pulsing alert, track GPS coordinates, and mark the issue as resolved.


***Presentation / Demo Link***

GitHub Repository: https://github.com/PokhrajSarkar/Hackathon2026/

Live Deployment: https://pokhrajsarkar.github.io/Hackathon2026/

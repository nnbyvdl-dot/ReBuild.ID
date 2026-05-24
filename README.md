# ReBuild.ID
A smart city web application for citizen reporting, real-time map tracking, and urban insight visualization.
ReBuild.ID

Features
1. City Pulse
Real-time feed of citizen reports
Like, comment, and interaction system
Media upload (image/video support)
Dynamic post updates

2. Realtime Map
Interactive map using Leaflet.js
Location-based incident tracking
Marker visualization for city events

3. Citizen Report
Upload reports with image/video
Add description and user identity
Real-time feed integration

4. Insight Dashboard
Trend analysis visualization
Risk prediction indicators
Urban activity monitoring

5. Citizen Pulse
Community voting system
Public opinion tracking
Real-time sentiment display

6. Authentication System
Login & Register pages
Guest mode access (limited features)
LocalStorage-based session system
Profile avatar auto-generated from username
Logout functionality

7. Tech Stack
HTML5
CSS3 (Responsive + Glass UI Design)
JavaScript (Vanilla JS)
Leaflet.js (Interactive Maps)
Font Awesome (Icons)
Google Fonts (Poppins)

Project Structure
ReBuild.ID/
│
├── index.html          # Main platform (City Pulse, Insight, etc.)
├── login.html          # Login page
├── register.html       # Register page
├── style.css           # Main styling
├── script.js           # Main JavaScript (if separated)
│
├── images/             # Assets (images)
├── video/              # Background videos
└── README.md

How It Works
1. User opens login or register page
2. Credentials are saved using localStorage
3. User is redirected to main platform (index.html)
4. System checks login status:
    - Logged in → show profile avatar + username
    - Guest → limited access mode
5. User can:
    - Submit reports
    - Interact with posts
    - View insights and maps

Authentication Logic
1. userRole stored in localStorage
2. username stored in localStorage
3. Avatar generated from first letter of username
4. Logout clears session and resets UI

Guest Mode
1. Guest users can:
    - View posts
    - Explore maps
    - View insights

2. But cannot:
    - Submit reports
    - Interact with full system features

UI Concept
1. Dark modern city-themed UI
2. Glassmorphism design (blur + transparency)
3. Responsive layout (mobile-friendly)
4. Card-based content system
5. Smooth animations and transitions

Future Improvements
1. Backend integration (database system)
2. Real-time API for reports
3. Firebase authentication
4. Admin dashboard
5. Notification system
6. AI-based report classification

Developer
1. Frontend Developer: Nabilla Ayu Nevanda & Frisnanda Zulfyanti
2. UI/UX Concept: Smart City Interface
3. Project Type: Academic / Prototype Web App

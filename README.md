📋 Project Description: RoadRescue SL
🚀 Project Overview
RoadRescue SL is a responsive mobile-first web application prototype engineered to provide immediate, location-based roadside assistance to stranded motorists. Developed as a Semester 1 project, the application tackles the real-world problem of vehicular breakdowns by instantly mapping nearby service hubs, calculating critical metrics (distance, ETA), and providing an immediate emergency panic mechanism.

The prototype focuses heavily on regional localization, with data sets and routing behaviors pre-optimized for the Colombo and Kadawatha thoroughfares in Sri Lanka.

🛑 The Problem Statement
Vehicle breakdowns (engine failures, flat tyres, dead batteries) on busy Sri Lankan roads like the Colombo-Kandy Road or Galle Road cause severe commuter stress, traffic congestion, and safety hazards. Drivers frequently struggle to find reliable, open mechanical assistance nearby because they lack immediate information regarding:

The exact physical distance to the nearest operational garage.

The specific service capabilities available at those hubs (e.g., towing vs. electrical repair).

A swift, unified way to broadcast their precise location coordinates in an urgent crisis.

💡 The Solution
RoadRescue SL bridges this information gap through an intuitive, lightweight Single Page Application (SPA) layout that mimics a native mobile application. The platform provides three core functionalities:

Live Geospatial Tracking: Integrating Leaflet.js and OpenStreetMap, the app bypasses static layouts to actively track the user’s real device GPS coordinates, displaying their stranded vehicle dynamically on a digital map layer.

Dynamic Service Discovery: Users can browse a live-updating directory of nearby garages. Clicking a service provider dynamically binds their profile data—such as custom service tags, star ratings, operational status, and real-time distance metrics—to the screen view.

Instant SOS Panic Protocol: For high-stress situations, a prominent "SOS" trigger instantly shifts the app into an emergency broadcast mode, simulating a live coordinates transmission over wireless frequencies to surrounding mobile breakdown vans.

🛠️ Technical Architecture & Stack
Designed for rapid deployment, cross-device execution, and an optimized user experience with zero heavy installation requirements:

Frontend Design: Semantic HTML5 layouts wrapped in high-fidelity CSS3 custom phone configurations.

Interactivity Engine: Vanilla JavaScript (ES6+) managing asynchronous UI state transitions and view routing.

Mapping Framework: Leaflet.js open-source map engine binding live device navigator.geolocation telemetry variables.

Asset Integration: Tabler Icons vector web-fonts framework for clean, professional visual indicators.

🎯 Target Audience & Impact
Stranded Motorists: Everyday drivers needing fast, transparent, and immediate roadside recovery solutions.

Local Garage Mechanics & Small Businesses: Providing regional vendors with a direct, digital channel to receive service inquiries and emergency rescue dispatch requests.

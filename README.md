# ALA-2-ADF

🌍 ALA-2 – Premium Country Explorer
🎥 Project Video
Google Drive Link:
👉 [Add your video link here]

🌎 ALA-2 – Flutter REST API Application

ALA-2 is a premium Flutter mobile application that fetches and displays country information using public REST APIs.

The app demonstrates:

Real-world REST API integration
JSON parsing into Dart objects
Hero animations
Glassmorphism UI
Live timezone-based clock
Wikipedia history integration
Search and filtering
Favorites system
Dark and Light theme switching
Modern UI animations

📌 Abstract:-
In today’s globalized world, access to country-related information such as population, region, time, and historical background is essential for students and professionals.
ALA-2 provides a centralized mobile platform to explore country data using public REST APIs, with a premium animated user interface and live timezone-based clock system.

❓ Problem Statement:-

Users often need reliable country information but must visit multiple websites to find:
Population data
Region classification
Local country time
Historical background

This application solves the problem by aggregating country information from public REST APIs and presenting it in a structured, animated, and user-friendly mobile interface.

🎯 Objectives:-

Integrate multiple REST APIs in Flutter
Parse JSON response into structured Dart data
Display country data using GridView
Implement search functionality
Implement region filter
Implement favorites system
Calculate live country time using timezone offset
Apply modern UI animation techniques
Build a clean, scalable single-file architecture

🛠 Tech Stack:-

Flutter (Latest Stable)

Dart

HTTP Package

REST Countries API

Wikipedia REST API

Hero Animation

Timer (Live Clock)

BackdropFilter (Glassmorphism)

🏗 Architecture
Simple Flutter Architecture:

UI (Screens)
↓
HTTP Service
↓
REST API
Single-file implementation inside main.dart.

🌐 APIs Used
1️⃣ REST Countries API

Used for:
Country name
Flag
Population
Region
Timezone
API:https://restcountries.com/v3.1/all
2️⃣ Wikipedia REST API

Used for:
Country historical summary
API:https://en.wikipedia.org/api/rest_v1/page/summary/{country}

✨ Features

🚀 Splash Screen
Animated fade-in
Gold gradient background

🏠 Home Screen
Gold premium gradient UI
Glassmorphism blur cards
Grid layout
Country flag
Country name
Population display
Search functionality
Region filter dropdown
Favorites (heart icon)
Pull-to-refresh button
Bottom navigation (Home & Favorites)
Dark / Light theme toggle
Smooth Hero animation

📄 Detail Screen

Custom curved page transition
Hero animation for flag
Live country time (updates every second)
Country date display
Timezone-based calculation
Wikipedia history integration
Animated typing effect for history
Premium colorful gradient background

🧠 Live Country Time Logic

The application:
Extracts timezone (example: UTC+05:30)
Calculates offset

Uses:
DateTime.now().toUtc().add(Duration(hours: offset))
Updates every second using Timer.periodic

📂 Project Structure
lib/
 └── main.dart

pubspec.yaml
README.md

▶️ How to Run the Project

Clone repository:

git clone <your-repository-link>
Navigate into project:
cd ala-2
Install dependencies:
flutter pub get
Run the application
flutter run

🎨 UI Highlights

Luxury gold gradient theme
Glass blur design
Premium serif typography
Smooth curved transitions
Animated clock UI
Typing animation effect
Dark & Light mode

🎓 Learning Outcomes

This project demonstrates:
REST API integration in Flutter
JSON parsing
State management
UI animations
Hero animations
Custom page transitions
Timezone calculations
Multi-API integration
Professional UI design

OUTPUT :-
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/c163c7ae-2e2d-4d6a-9f69-1d80f38bb871" />
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/e1617846-0f37-46c0-8614-57bd13086ba9" />
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/9750bb41-b221-4cd1-bed9-1b71b4b1a54f" />
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/3ac1ccb7-6d5d-4647-b336-b1ab5273aceb" />
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/647101dd-445d-40be-aca1-5a14b9de2a45" />
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/bfa27a4a-3bad-4b77-8585-783528e876a6" />
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/bb4b9b63-f9a1-480b-933c-88a7c7205c22" />








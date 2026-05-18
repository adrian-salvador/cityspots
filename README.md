# City Spots

City Spots is an Android application built for the ECE 452 (Software Design and Architecture Course) Group Project. 
This Android application aims to provide a mobile experience for discovering, saving, and organizing “city spots” (e.g., places you want to visit or favorite locations), with cloud-backed persistence to support shared and consistent data.

### [Link to (YouTube Video) Demo](https://youtu.be/Czk8sb6vbe4?si=V1NSuKB_XKSEctzW)

---

## Tech Stack

- **Kotlin** — Android application development  
- **Android SDK** — Native Android platform  
- **Gradle** — Build and dependency management  
- **Firebase Realtime Database** — Cloud-hosted database for storing and syncing city spot data  

---

## Project Structure

High-level layout of the repository:

- `app/` — Main Android application module  
- `gradle/` & `gradlew` — Gradle wrapper and configuration  
- `test_images/` — Images used for testing and validation  
- `timelog.md` — Project time log  

---

## Core Functionality (High-Level)

- Create and manage city spots within the app  
- Persist city spot data using **Firebase Realtime Database**  
- Synchronize data across sessions via a cloud backend  
- Designed with an emphasis on software architecture and maintainability  

---

## Getting Started

### Prerequisites
- Android Studio (latest stable recommended)
- Android SDK (installed via Android Studio)
- JDK (bundled with Android Studio)

### Running the App
1. Clone the repository:
   ```bash
   git clone https://github.com/adrian-salvador/cityspots.git
   cd cityspots

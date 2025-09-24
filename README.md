# Flightscry: Android Flight Itinerary App Using Skyscanner Backpack UI

**Flightscry** is an **Android mobile application** built as a **proof of concept (PoC)** for Skyscanner.  
This project demonstrates a **flight itinerary UI** using **Backpack**, Skyscanner’s custom UI library.

---

## 🛠 Project Overview

- **Purpose:** Showcase a user’s flight itinerary on mobile using reusable UI components from **Backpack**.
- **Scope:** Single-screen UI for flight itinerary display.
- **UI Features:**
  - Flight information card
  - Departure & arrival airport codes and times
  - Passenger name display
  - “Done” button (Backpack button component)
- **Example Flight Data Displayed:**
  - Passenger: John Doe
  - Flight Number: AI203
  - Departure: BLR — 08:45
  - Arrival: DEL — 11:30

---

## 📂 Project Structure
Flightscry/
├── app/
│ ├── src/
│ │ └── main/
│ │ ├── java/com/flightscry/MainActivity.kt
│ │ ├── res/
│ │ │ ├── layout/activity_main.xml
│ │ │ ├── values/colors.xml
│ │ │ └── values/styles.xml
│ │ └── AndroidManifest.xml
│ └── build.gradle.kts
├── .gitignore
├── build.gradle.kts
├── settings.gradle.kts
└── README.md
---

## ⚙️ Technologies Used

- **Language:** Kotlin  
- **Minimum SDK:** 33 (Android Tiramisu)  
- **Compile SDK:** 33  
- **UI Library:** [Backpack](https://backpack.github.io/) (Skyscanner)  
- **Layouts:** ConstraintLayout + LinearLayout + Backpack components (Cards, Text, Buttons)

---

## 🎨 Key UI Components

- **BpkCardView:** Container for flight info  
- **BpkText:** Display flight number, departure, arrival, and passenger  
- **BpkButton:** Interactive "Done" button  

The UI is **fully responsive** and demonstrates how Backpack components can be used to quickly prototype mobile app screens.

---

## 🚀 How to Run

1. Download or clone the repository:  
```bash
git clone https://github.com/Karthikgs3/Flightscry-SkyScanner.git
```
👤 Author

- Karthik G Sharma
- Skyscanner Forage Internship Project



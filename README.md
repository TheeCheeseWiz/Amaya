# 🚨 Amaya — Mobile Emergency Signaling & GPS Tracking System

A mobile emergency signaling and GPS mapping application built using **Sketchware** (generating native Java and XML), integrated with **Firebase Authentication**, **Google Maps API**, and **Cloudflare**.

> **Note:** This repository serves as a project case study and architectural walkthrough highlighting the app's authentication flow, GPS coordinate/map interface, and emergency signaling workflow.

---

## 🎯 Problem Statement
During emergencies, accessing your account, fetching GPS coordinates, checking map location, and reaching contacts or authorities quickly requires a direct mobile workflow. **Amaya** provides a straightforward mobile interface combining user authentication, coordinate/location retrieval, map visualization, and emergency call/report actions.

---

## ⚙️ Core Functionality & Workflow

1. **Authentication & Quick Authorities Access:**
   - Supports email/password sign-in, new account registration, and password recovery via **Firebase Authentication**, alongside direct **911** quick access on the login screen.
2. **Coordinate Retrieval & Emergency Calling:**
   - Fetches and displays latitude and longitude coordinates (`GET LOCATION`), shows live location lookup status, and provides quick calling options for a friend/family contact or **911** authorities.
3. **GPS Mapping & Report Trigger:**
   - Displays a **Google Maps** view with a location-enablement prompt (*"Don't forget to turn your location on! it may take a while"*) and a **REPORT** button.
4. **Cloud & Native Mobile Layer:**
   - Built with **Sketchware** (native Java and XML layouts) and supported by **Cloudflare** and cloud services.

---

## 🛠️ Tech Stack
- **Mobile Development:** Sketchware (Native Java & XML)
- **Maps & Location:** Google Maps API, Device GPS
- **Auth & Cloud:** Firebase Authentication, Cloudflare

---

## 📸 System Walkthrough

### 1. Authentication & Quick Emergency Access
Provides email and password login, registration and password-reset flows, and an immediate **911** authorities button.
<img width="392" height="800" alt="assets-01-login-and-emergency-access" src="https://github.com/user-attachments/assets/8e768e3b-6208-4d8a-af34-23568f149d05" />

### 2. Live Map View & Report Trigger
Displays the Google Maps interface with a reminder to enable device location and a **REPORT** button at the top right.
<img width="389" height="800" alt="assets-02-gps-map-and-report-trigger" src="https://github.com/user-attachments/assets/3848a3a2-4a2a-4958-b4a2-6014df054cf4" />

### 3. Location Coordinates & Emergency Calling
Displays latitude and longitude values with a **GET LOCATION** trigger, status readout, contact call input, and **911** authorities button.
<img width="390" height="800" alt="assets-03-gps-coordinates-and-calling" src="https://github.com/user-attachments/assets/9a20e495-be8d-429a-b522-fcd575f573d3" />

---

## 📌 Project Context
Developed as a mobile application and technopreneurship project, demonstrating practical integration of geolocation, Google Maps, authentication, and native Android UI/logic generated through Sketchware.

# 🚆 Transit Mate

Transit Mate is an Android app that provides real-time UK train information using the National Rail Open Data API. Built with modern Android tools like Jetpack Compose, it offers a fast, clean, and reliable way to check departures, arrivals, and plan journeys across the UK rail network.

---

## 📱 App Overview

| Departures Tab | From-To Planner |
|----------------|-----------------|
| <img src="https://github.com/Gomida05/Gomida05.github.io/blob/main/Projects/TransitMate/screenshots/Home.png?raw=true"/> | <img src="https://github.com/Gomida05/Gomida05.github.io/blob/main/Projects/TransitMate/screenshots/Route.png?raw=true"/> |

---

## ✨ Features

### 🚉 Live Train Information
- **Live Departures & Arrivals** – Real-time data for UK stations  
- **Station Board** – View services with platform, delays, and status  
- **Service Details** – Expand any train to see full calling patterns  

### 🔁 Route Planner
- Search direct services between two stations  
- Swap stations instantly  
- Fast results with smart caching (no unnecessary reloads)  

### 🔍 Smart Search
- Fast station search with debounce + caching  
- Reuse previous searches instantly  
- Clean inline search UI  

### 🎫 Ticket Information
- **Ticket Types** – Browse and search ticket categories  
- **Restrictions** – View detailed fare restrictions  
- Data cached locally for faster access  

### ⚡ Performance Improvements
- In-memory + file caching for faster load times  
- Reduced unnecessary API calls  
- Smooth navigation with no reload flicker  
- Faster startup and improved responsiveness  

### 🎨 UI & UX
- Built fully with **Jetpack Compose**  
- Clean Material Design interface  
- Smooth animations and expandable components  

---

## 🛠️ Tech Stack

- **Language:** Kotlin  
- **UI:** Jetpack Compose  
- **Architecture:** ViewModel + StateFlow  
- **APIs:** National Rail Open Data & Huxley2  
- **Networking:** OkHttp  
- **Data Handling:** XML parsing (XmlPullParser)  
- **Caching:** Memory + local file caching  

---

## 🧩 Future Improvements

- [ ] Favorites / Bookmarked stations  
- [ ] Notifications for delays or cancellations  
- [ ] Offline support for key data  
- [ ] Improved accessibility (screen reader support)  

---

## 📦 Play Store Status

It's now available to test in Google Play Store  
👉 https://play.google.com/store/apps/details?id=com.das.transitMate  

---

## 📄 License

This project is licensed under the Apache License 2.0 – see the [LICENSE](https://github.com/Gomida05/TransitMate/blob/main/LICENSE) file for details.

---

## ❤️ Notes

Built to make UK train travel faster, simpler, and more reliable—especially for everyday commuters.

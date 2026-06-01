# Transit Mate: Advanced UK Rail Intelligence

Transit Mate is a high-performance Android application designed to provide comprehensive, real-time intelligence for the United Kingdom's railway network. Built with a focus on data integrity, reliability, and minimalist design, it serves as a sophisticated companion for both daily commuters and long-distance travelers.

The application leverages direct feeds from National Rail (Darwin) and a custom-built infrastructure to deliver precise timing, platform information, and service disruptions across more than 2,500 stations.

---

## Visual Interface

| Home Page | Live Departure Board | Ticket Discovery | 
| :---: | :---: | :---: |
| <img src="https://play-lh.googleusercontent.com/ac99XXXQVRoyK7uvSa-ECaM_QEjVUUqOqOqakC9ckDCAD294eh3UMF_i6WzgNt9X_T9dolfCcusNshOe2hQfiA=w1052-h592-rw" width="200"/> | <img src="https://play-lh.googleusercontent.com/CiqG4NGXvy14IVCQHXEla4GNkWs1wSWClePx9ds7W77b5gNQnhGaNEblBjFlakeo5hHkFiPG-eC-m5xszjSu=w1052-h592-rw" width="200"/> | <img src="https://play-lh.googleusercontent.com/V2PJ96JAsgn6YXDizYdZML_1KpvNTxeXVzCtLPGg8iz5T_QQGU6CjZlqvgqm3AO0J9KEQzoViGX7ctKcDcSs2TU=w1052-h592-rw" width="200"/>


---

## Key Capabilities

### Real-Time Station Intelligence
*   **Live Boards:** High-frequency data streams provide up-to-the-minute departure and arrival information.
*   **Platform Tracking:** Stay informed with precise platform assignments and real-time updates on changes.
*   **Calling Patterns:** View full service schedules including every intermediate stop and timing.

### Journey Planning and Timetables
*   **A-to-B Planner:** A robust engine for planning direct routes between any two stations in the UK.
*   **National Timetable:** Instant access to the complete schedule for the entire network, supporting historical and future service lookups.

### Regulatory and Ticketing Information
*   **Ticket Encyclopedia:** Clear explanations of advance, off-peak, and anytime ticket categories.
*   **Restriction Intelligence:** Direct access to detailed validity rules and easement conditions to ensure compliance with official terms.

### Smart Reminder Engine
*   **Minute-Perfect Alerts:** Local notification system with a modern grid layout and persistent scheduling.
*   **Exact Alarms:** Utilizes Android's `AlarmManager` and `BroadcastReceiver` to ensure alerts trigger precisely at the scheduled time, even in low-power modes.

---

## Technical Specifications

Transit Mate is developed using the modern Android "Gold Standard":

*   **Language:** 100% Pure Kotlin.
*   **Backend:** Custom Ktor service integrated with Supabase for high-performance data handling.
*   **UI Framework:** Jetpack Compose (Declarative UI) with Material 3.
*   **Architecture:** Clean Architecture with Repository pattern and Hilt Dependency Injection.
*   **Persistence:** Room for journey data and DataStore for user preferences.
*   **Security:** Firebase App Check and Google Play Integrity API for robust application protection.
*   **Networking:** Ktor Client with Kotlinx Serialization for efficient data exchange.

---

## Implementation Details

### Theme and Design
The application features a minimalist monochrome design language. The primary palette is restricted to pure Black and White, utilizing subtle surface elevations and outlines to create hierarchy without visual clutter. Functional colors are reserved strictly for critical status information to maximize readability.

### Privacy and Stability
Transit Mate prioritizes user privacy. While utilizing Firebase for essential crash reporting and performance monitoring to ensure application stability, no personal journey data is collected or tracked externally. All user reminders and planned journeys are stored securely and locally on the device.

---

## Availability

Transit Mate is available for download on the [Google Play Store](https://play.google.com/store/apps/details?id=com.das.transitMate).

---
*Developed with precision for the United Kingdom rail commuter.*

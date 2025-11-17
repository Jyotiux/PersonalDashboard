

# Mini Dashboard — Location-Based Weather, Time, and Notes

## **Project Overview**

The **Mini Dashboard** is a lightweight, web-based application that provides users with **real-time information** in a single interface. The dashboard integrates three key components:

1. **Live Clock** – Displays the current local time, updated every second.
2. **Weather** – Shows real-time weather information (temperature and wind speed) based on the user’s current geographic location.
3. **Notes** – Allows users to create, store, and delete personal notes using the browser's `localStorage` as a local persistence layer.

The project demonstrates **basic web development, API integration, and client-side data persistence** without requiring any server-side backend.

---

## **Technologies Used**

* **HTML5** – Structure of the dashboard.
* **CSS3** – Responsive and visually appealing layout using grid and card design.
* **JavaScript (ES6)** – Dynamic behavior:

  * Live clock using `setInterval`.
  * Weather API integration with **Open-Meteo**.
  * Notes management using **localStorage**.
* **Open-Meteo API** – Provides real-time weather data based on latitude and longitude.

---

## **Features**

1. **Dynamic Time Display**

   * Updates every second.
   * Uses the browser’s local time zone.

2. **Location-Based Weather**

   * Uses the **Geolocation API** to obtain the user's latitude and longitude.
   * Fetches real-time temperature and wind speed from the Open-Meteo API.
   * Displays results directly on the dashboard.

3. **Local Notes System**

   * Users can add, view, and delete notes.
   * Data persists across sessions using `localStorage`.
   * Click on a note to delete it.

4. **Responsive Design**

   * Grid layout adjusts to screen width.
   * Cards have subtle shadows and padding for clean aesthetics.

---

## **Setup Instructions**

1. Clone the repository or download the source code.
2. Open the `dashboard.html` file in any modern web browser (Chrome, Firefox, Edge).
3. Allow **location access** to enable dynamic weather updates.
4. Use the **Notes section** to add and manage personal notes.

**No additional setup or server required.**

---

## **Future Enhancements**

* Add **dynamic city selection** for weather information.
* Include additional API modules, such as **news headlines**, **cryptocurrency prices**, or **stock data**.
* Enable **editable and searchable notes** for enhanced user experience.
* Improve UI/UX with advanced styling or a mobile-first design.

---

## **Learning Outcomes**

This project demonstrates:

* Integrating **third-party APIs** in client-side applications.
* Using **Geolocation API** for location-aware functionality.
* Implementing **data persistence** in the browser via `localStorage`.
* Designing a **responsive and user-friendly interface** using HTML, CSS, and JavaScript.
* Building a fully **frontend-based application** without a backend server.

---

## **Screenshots**

<img width="1889" height="912" alt="image" src="https://github.com/user-attachments/assets/8cdee772-6ac7-439a-9134-f85b0e4b181e" />




---

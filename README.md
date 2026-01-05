# 🌦️ Weather Web App

A clean and responsive weather dashboard built with **HTML, CSS, and JavaScript**. This app allows users to search for weather conditions by City, Country, or Area name, providing real-time updates and a weekly forecast using the **Visual Crossing API**.

![Project Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## ✨ Features

* **Global Search:** Get weather data by searching for any City, Country, or Area name.
* **Current Weather:** Displays today's temperature, humidity, wind speed, and conditions.
* **Weekly Forecast:** Shows the weather outlook for the next 7 days.
* **Responsive Design:** Looks good on both desktop monitors and mobile phones.
* **Error Handling:** Alerts the user if a city is not found or if the input is empty.

## 🛠️ Tech Stack

* **Structure:** HTML5
* **Styling:** CSS3 (Flexbox/Grid)
* **Logic:** Vanilla JavaScript (ES6+)
* **Data Source:** [Visual Crossing Weather API](https://www.visualcrossing.com/)

## 🚀 How to Run Locally

Since this project uses only HTML, CSS, and JS, you don't need to install complex dependencies.

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/your-username/weather-app.git](https://github.com/your-username/weather-app.git)
    ```

2.  **Navigate to the project folder**
    ```bash
    cd weather-app
    ```

3.  **Add your API Key**
    * Open the `script.js` file (or wherever your fetch logic is).
    * Locate the `apiKey` variable and paste your Visual Crossing key:
        ```javascript
        const apiKey = "YOUR_VISUAL_CROSSING_KEY_HERE";
        ```

4.  **Launch the App**
    * **Option A (Recommended):** If you use VS Code, install the "Live Server" extension, right-click `index.html`, and choose **"Open with Live Server"**.
    * **Option B:** Simply double-click `index.html` to open it in your browser.

## ⚠️ API Note

This app uses the **Visual Crossing Free Tier**.
* **Limit:** 1000 records per day.
* If the app stops showing data, please check if the daily limit has been reached.

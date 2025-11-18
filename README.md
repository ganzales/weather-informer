
## Description
This project converts an unused smartphone into a dedicated weather informer display. It uses a single self-contained HTML/JavaScript file to fetch weather data (via the Yandex API) and display time, date, temperature, and additional weather indicators in full-screen mode. The setup requires minimal hardware changes — just a phone, constant power, and a browser. Full russian description [here](https://mysku.club/blog/diy/105101.html).

![pic_1](https://github.com/user-attachments/assets/9856e338-c1ca-4e2c-86cc-a2ec845acaca)

## Features

- Real-time display of accurate clock (hours:minutes:seconds) and date with day of week. 

- Current weather conditions including temperature, cloudiness, wind speed and direction, humidity, and pressure with intuitive visual indicators. 

- Forecast summary for upcoming periods (morning, day, evening, night) with essential metrics. 

- Visual representation of day length and current time of day (sunrise/sunset, moon phase). 

- Optimised for portrait orientation on smartphones; designed for continuous 24/7 display. 

- Single-file solution (≈80 kB) with embedded config, engine, styles and graphics — no server required for simple usage.

## Requirements

- Smartphone with working browser. 

- Internet connection (WiFi or mobile data) to fetch weather updates. 

- Yandex Smart Home API access (free tier sufficient) and valid API key.

- Latitude and longitude of your physical location. 

- Continuous power supply to keep screen on permanently; screen sleep must be disabled. 

- Browser capable of loading local HTML files and running JavaScript; portrait orientation recommended. 

## Installation & Usage

### 1. Acquire device:
Use any functional smartphone with a browser (WiFi or network connectivity).  
Ensure it's permanently powered (via USB charger or mains supply).

### 2. Enable “screen always on”:
On Android: go to Settings → About phone → tap Build number 5 times → Developer options → enable “Stay awake” (screen never turns off while charging).
Alternative: install a “keep screen on” app.

### 3. Obtain Yandex Smart Home API key:
Go to Yandex Smart Home API page, authenticate, then Connect → copy API key.

### 4. Get geolocation coordinates:
Use Google Maps (or any map tool) to locate your address, obtain latitude & longitude.

### 5. Download single-file informer:
Download the HTML file (~80 kB) from the provided repository link.

### 6. Configure file:
Open informer.html in a text editor. Locate config section and replace:
- <code>api</code> value with your Yandex key
- <code>lat</code> and <code>lon</code> with your coordinates  
Save changes.

### 7. Deploy to phone:
Copy informer.html to the phone’s storage (e.g., Downloads folder).  
Open with a browser (Chrome/Yandex Browser/Samsung Internet).  
If required, use URL format:

<code>file:///storage/emulated/0/Download/informer.html</code>

or similar.

### 8. Launch and go full-screen:
Tap to open. Then enter full-screen mode and disable browser UI.  
Ensure device is permanently powered and placed in a fixed location.

### 9. Optional integration:
Mount the phone on a wall or near entrance. Optionally integrate camera stream or home-automation status masked behind the informer.

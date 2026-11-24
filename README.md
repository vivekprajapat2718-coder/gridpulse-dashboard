# GridPulse Dashboard

GridPulse is an ESP32-based prototype for monitoring a four-way intersection. Ultrasonic sensors detect vehicles, ThingSpeak carries the telemetry, and a browser dashboard displays the traffic signal status.

## How it works

1. Ultrasonic sensors detect vehicles on the intersection approaches.
2. The ESP32 handles signal control and sends telemetry to ThingSpeak.
3. The web dashboard reads ThingSpeak data and displays the intersection status.

**Data flow:** Ultrasonic sensors → ESP32 → ThingSpeak → web dashboard

## Open the dashboard

- For the hosted version, open the [GitHub Pages deployment](https://github.com/vivekprajapat2718-coder/gridpulse-dashboard/deployments/github-pages) and choose **View deployment**.
- To run locally, clone or download this repository and open `index.html` in a browser. The live view needs an internet connection and an available ThingSpeak feed.

## Repository scope

`index.html` contains the dashboard. The ESP32 firmware and wiring files are part of the hardware setup and are outside this repository.

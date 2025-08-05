Yechi's Digital Clock
Overview
Yechi's Digital Clock is a simple, responsive HTML, CSS, and JavaScript project that displays the current time and date in real‑time.
It updates every second and adapts to different screen sizes for better viewing on mobile and desktop devices.

Features
Live Time Update – Displays hours, minutes, and seconds in real time.
Current Date – Shows the day of the week, month, day, and year.
Responsive Design – Uses media queries to adjust font size and layout for various screen widths (from large monitors to very small displays).
Simple UI – Minimal, clean interface with a centered layout.
Custom Styling – Purple background, light text, and a styled clock box with shadows.

Technologies Used
HTML5 – Structure and semantic layout.
CSS3 – Styling, responsive media queries, and layout adjustments.
JavaScript (Vanilla) – Handles real‑time clock updates and date formatting.

File Structure
bash
Copy
Edit

How It Works
The HTML sets up a clock container with:
A heading
The clock display (00:00:00)
The date display (Monday 24th July 2025)
The JavaScript function yechisClock():
Gets the current time using new Date()
Formats hours, minutes, and seconds with leading zeros using .padStart(2, '0')
Gets a formatted date string using .toLocaleDateString()
Updates the clock and date in the DOM
setInterval() calls yechisClock() every 1000ms (1 second) to keep it updated.
CSS styles the clock and ensures it remains readable on all devices via media queries.

How to Run
Download or copy the code into a file named index.html.
Open the file in any modern web browser.
The clock will start running automatically.

Notes
The project does not require an internet connection.

All code is contained in one file for simplicity, but CSS and JavaScript can be separated for larger projects.

Date format is in US English, but can be changed by modifying the toLocaleDateString() options.

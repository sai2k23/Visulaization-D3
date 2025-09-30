📈 D3 Visualization – Temperature & Humidity Dashboard
An interactive data visualization dashboard built with D3.js v7 to display detailed time-series data for environmental conditions and heating system status.

This project was developed as part of an assignment and finalized on 30-09-2025.

🚀 Key Features and Enhancements
Feature Area	Description	Status
Multi-time Views	Switch between Hour, Day (full range reset), Week, Month, and Year overviews.	✅
Date Navigation	Quickly jump to any specific day (00:00 to 24:00 view) using the dedicated date input field.	📅
Dual Interaction Mode	Toggle the Pan (↔) button to switch mouse controls between: Tooltip Inspection (Default) and Chart Panning/Dragging.	↔️
Clean Visuals	Persistent heater triangles and working dots have been removed from the chart to reduce clutter and focus solely on the main data lines.	✨
Iconic Legend	The legend uses relevant icons and color-coding for better visual identification (e.g., 🏠, 💧, 🔥).	🖼️
Interactive Tooltip	Displays exact, time-snapped values for all datasets on hover, including the iconic status of the heater (e.g., 🔥 ON / 💧 OFF).	✅
Performance	Line-drawing animation runs only once on the initial page load, making all subsequent view changes instant and smooth.	⚡
Export	Download the chart as a vector image (SVG).	⬇️
🛠️ Project Structure and Setup
Project Files
Visulaization-D3/
│── index.html  # Main D3 chart implementation (Run this file)
│── data.json   # Sample input dataset
└── README.md   # Project documentation (this file)
Setup Instructions
Clone the repository.

Run Locally: You must serve the file using a local web server (like the VS Code Live Server extension or python -m http.server) because modern browsers restrict direct file access for the external Open-Meteo API data.

📊 Data Visualization Legend
The data sources and their corresponding icons in the sidebar:

Data Key	Icon	Line/Marker	Color
Room Temp	🏠	Line	Steelblue
Set Temp	🎯	Line	Orange
Outside Temp	☁️	Line	Purple
Humidity	💧	Line	Light Green
Heater State Change	🔥	(Tooltip Status Only)	N/A
Override Active	⚠️	Diamond Marker	Orange
Working + Heating	⚙️	(Tooltip Status Only)	Black
⚙️ Technical Details
Technology Stack: D3.js v7, JavaScript, HTML, CSS

Data Source: Local data.json and external Open-Meteo Weather Archive API.

Assignment Completion: 30-09-2025

Contributor
K Sai Krishna (Developer)
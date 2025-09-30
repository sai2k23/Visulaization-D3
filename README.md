# D3 Visualization – Temperature & Humidity Dashboard

An interactive data visualization built with **D3.js v7** to display temperature, humidity, and system state changes (heater, override, working hours).  
This project was developed as part of an assignment and finalized on **30-09-2025**.

---

## 🚀 Features
- **Multi-time views:** Switch between Hour, Day, Week, Month, and Year.
- **Smooth line animation:** Data lines are drawn with animation (first load only).
- **Custom legend with icons:** Toggle datasets (humidity, room temp, set temp, outside, heater, override, working).
- **Interactive markers:**  
  - 🔺 Heater ON/OFF markers (green = ON, red = OFF)  
  - 🔶 Override markers  
  - ⚫ Working + Heating dots
- **Tooltip with focus line:** Displays exact values on hover.
- **Zoom & Pan:** Explore the chart in detail with adaptive axis ticks.
- **Brush selection:** Highlight and zoom into specific ranges.
- **Date navigation:**  
  - Click an x-axis date → jump into Hour view for that day.  
  - Or pick a date directly via the date input field.
- **Export:** Download chart as SVG.

---

## 📂 Project Structure
Visulaization-D3/
│── index.html # Main D3 chart implementation
│── data.json # Sample input dataset
│── README.md # Project documentation


---

## ⚙️ Setup & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/sai2k23/Visulaization-D3.git
   Open index.html (or d3.html) in your browser using Live Server (VSCode extension) or any static server.

Make sure data.json is in the same folder as the HTML file.

Interact with the chart using the toolbar, legend, and date picker.

📊 Data

Source: data.json (custom dataset).

Fields:

timestamp

room_temp

set_temp

humidity

heating

override

working_hours

🛠️ Built With

D3.js v7
 – Data-Driven Documents

JavaScript, HTML, CSS

✨ Contributors

K Sai Krishna (Developer)

📅 Assignment Completion

Started: 22-09-2025

Completed: 30-09-2025
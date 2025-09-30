# Visualization-D3

An interactive **D3.js line chart** for exploring **Temperature & Humidity data** with support for multiple time views, drilldown navigation, zooming, tooltips, and animated rendering.  

---

## 📌 Features

- **Multiple time resolutions**:  
  Switch between **Day / Hour / Week / Month / Year** views.  
- **Drilldown navigation**:  
  - Click on a **Day tick** → navigates to **Hours** of that day.  
  - Click on an **Hour tick** → navigates to **Minutes** of that hour.  
- **Zoom-aware x-axis**:  
  Zoom in/out and the axis automatically adapts:
  - High zoom → seconds,
  - Medium zoom → minutes,
  - Default → hours/days.  
- **Animated drawing**:  
  Four line series animate smoothly **together** on first load. Markers (heater state changes, overrides, working activity) appear **only after lines finish drawing**.  
- **Rich tooltip**:  
  Shows values (Room Temp, Set Temp, Outside Temp, Humidity) with contextual info like heater status 🔥 and working activity ⚙️.  
- **Legend toggles**:  
  Show/hide datasets interactively. Icons are used instead of color squares for readability.  
- **Date picker**:  
  Jump directly to a specific date → auto-switches to hourly view for that day.  
- **Zoom & pan controls**:  
  Buttons to zoom in/out/reset, or use mouse zoom/pan with cursor feedback.  
- **Export**:  
  Download the chart as an SVG file.  

---

## 🎯 Why These Features?

- **Drilldown (Day → Hour → Minute)**: Enables both high-level trends and micro-level inspection without needing a calendar widget.  
- **Minute-level view**: Helpful for analyzing fine-grained events (like quick heater toggles).  
- **Zoom-aware axes**: Keeps axis readable across different scales.  
- **Synchronized animation**: Lines first, markers second — avoids clutter and makes event markers more visible.  
- **Legend icons**: More intuitive (💧 humidity, 🏠 room temp, 🔥 heater, etc.).  
- **Date picker**: Quick direct access to specific days.  

---

## ⚙️ Tech Stack

- **[D3.js v7](https://d3js.org/)** → charting & interactions  
- **HTML + CSS + JavaScript** → structure & styling  
- **Open-Meteo API** → outside temperature data  
- **Local JSON (`data.json`)** → room, set temp, humidity, heater, override, working_hours logs  

---

## 🗂️ Project Structure

Visualization-D3/
│
├── d3.html # Main D3 chart implementation
├── data.json # Local dataset (temperature, humidity, heater logs)
├── README.md # Documentation


---

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/sai2k23/Visualization-D3.git
   cd Visualization-D3
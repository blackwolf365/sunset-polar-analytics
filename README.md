# 🌅 solis-dual-chart

An interactive, zero-dependency web tool for visualizing annual sunset cycles through synchronized polar and linear astronomical charts.

## ✨ Features

* **Synchronized Dual Views**: Toggle between Radial (Polar) and Linear (Classic) charts, or inspect both simultaneously with real-time state synchronization.
* **Interactive Control Wheel**: Seamlessly navigate through the 365-day calendar year using a custom tactile dial, direct canvas dragging, or offset sliders.
* **NOAA Solar Algorithm**: Real-time astronomical sunset computation based on configurable Latitude and Longitude inputs.
* **Daylight Saving Time (DST) Switch**: On-the-fly toggle between fixed standard time (UTC+2) and dynamic Daylight Saving Time adjustments (UTC+3).
* **Daylight Change Acceleration**: Visual overlay highlighting periods of maximum sunset time shift across equinoxes and solstices.
* **Zero External Dependencies**: Lightweight HTML5 Canvas and Vanilla JavaScript implementation packed in a single file.

## 🛠️ How It Works

1. **Radial Mapping**: Maps the 365-day year onto a 360° circular axis, rendering earlier sunsets closer to the center and later sunsets toward the outer perimeter.
2. **Linear Curve**: Plots sunset time across the year with custom X-axis shifting to align and center desired months.
3. **State Sync**: Dragging the radial handle or spinning the dial updates dates, angles, seasonal themes, and markers instantly across all rendered views.

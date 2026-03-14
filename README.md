<div align="center">

# 🌌 PyClimaExplorer

<a href="https://sustainifya-tsrzceateuyvw8w3gymriu.streamlit.app/">
  <img src="https://img.shields.io/badge/🚀%20DEPLOYED%20WEB%20APP-ACCESS%20HERE-00FFFF?style=for-the-badge&logo=streamlit&logoColor=white" alt="Live Demo" height="50">
</a>

<br>

<a href="https://youtu.be/ajrCQpAJ00Q?si=3PUJZOPHV0YR4ask">
  <img src="https://img.shields.io/badge/📺%20DEMO%20VIDEO%20LINK-WATCH%20ON%20YOUTUBE-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Video Demo" height="40">
</a>

<p><strong>Scientific Intelligence Platform for Rapid Climate Data Visualization</strong></p>

<h3>Team: Next Gen Developers</h3>
<p><b>Team Lead:</b> Aryan Mishra | <b>Member:</b> Aditya Kumar Singh</p>

</div>

---

## 🌟 Project Overview

**PyClimaExplorer** is a premium, highly interactive web application designed for researchers, scientists, policy makers, and the general public to explore complex climate datasets (CESM, ERA5, CMIP6). It acts as your command intelligence center for planetary climate telemetry.

Developed for the **TECHNEX '26 Hackathon**.

## 📸 Platform Highlights

### 1. The Command Center Dashboard
Get immediate insights with dynamic Multi-dimensional charts utilizing the NASA MERRA-2 dataset.
<p align="center">
  <img src="assets/dashboard_main.png" width="800" alt="Main Dashboard" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.5);"/>
</p>

### 2. Spatio-Temporal Intelligence
Animated time-lapse controls to visualize climatic shifts step-by-step. Access Zonal Profiles, Meridional Stacks, and Distribution statistics dynamically. 
<p align="center">
  <img src="assets/analysis_view.png" width="800" alt="Spatio Temporal Map" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.5);"/>
</p>

### 3. The 3D Topographical Globe
Witness planetary metrics rendered as a 3D intelligent map, exploring anomaly maps interactively.
<p align="center">
  <img src="assets/globe_render.png" width="800" alt="3D Topographical Globe" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.5);"/>
</p>

### 4. High-Resolution Anomaly Diagnostics
Detailed analysis of intensity cells and global mean trends across the temporal axis.
<p align="center">
  <img src="assets/3d_intensity.png" width="800" alt="Intensity Analysis" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.5);"/>
</p>

---

## 🚀 Key Features

*   **Scientific Command Center**: 9 dynamic ECharts providing multi-dimensional insights.
*   **NetCDF File Port**: Upload and analyze your own `.nc` files directly.
*   **Geospatial Intelligence Map**: Plotly-powered interactive 2D maps and 3D topographical globes.
*   **AI Command Analysis**: Integrated ML modules for predictive projections.
*   **Orbital Data Acquisition**: Direct integration with ECMWF ERA5 via Copernicus CDS API.

---

## ⚙️ Installation & Local Setup
### 1. Prerequisites
Ensure you have Python 3.9+ installed and a virtual environment tool like `venv` or `conda`.
### 2. Quick Start
```bash
# Clone the repository
git clone <repository-url>
cd Py-Climax
# Setup environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
# Install dependencies
pip install -r requirements.txt
# Run the platform
streamlit run app.py

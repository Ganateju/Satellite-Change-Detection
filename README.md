# 🛰️ Sat-Scan Terminal v3.0

### Geospatial Intelligence Platform | Temporal Earth Observation & Change Analysis

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://satilite-image-detection.streamlit.app/)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/AI-PyTorch-EE4C2C?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![Google Earth Engine](https://img.shields.io/badge/Data-Google_Earth_Engine-4285F4?logo=google&logoColor=white)](https://earthengine.google.com/)
[![License](https://img.shields.io/badge/License-MIT-00FF41.svg)](https://opensource.org/licenses/MIT)

---

<img width="2752" height="1536" alt="SatScan" src="https://github.com/user-attachments/assets/93797dda-1598-42e4-a65e-32169cf40c18" />

---

> 🚀 **Live Demo**
>
> https://satilite-image-detection.streamlit.app/

---

# 📌 Overview

Sat-Scan Terminal is a geospatial intelligence platform designed to detect, analyze and classify temporal surface changes using Sentinel-2 imagery.

Originally developed for **Smart India Hackathon (SIH)**, Sat-Scan evolved into a complete engineering rebuild emphasizing:

- Temporal Synchronization
- Robust Feature Comparison
- Noise Resistant Classification
- Interpretable Spatial Analysis
- Large Scale Geospatial Processing

---

# Status

| Metric | Value |
|--------|-------|
| Current State | Functional MVP |
| Deployment | Streamlit Application Released |
| Validation | Real-world Satellite Evaluation |
| Version | v3.0 |
| Status | Active |

---

# 🌟 Core Innovation

Sat-Scan derives understanding from four complementary layers.

| Layer | Objective |
|-------|-----------|
| Temporal Alignment | Synchronize T1 and T2 observations |
| Feature Similarity | Siamese embeddings instead of pixel differencing |
| Probabilistic Interpretation | Dynamic World priors suppress environmental noise |
| Spatial Reasoning | Contour extraction enables interpretable outputs |

Together these components create a robust pipeline capable of operating under real-world geospatial conditions.

---

# 📜 Engineering Journey

Initial prototypes suffered from:

- Coordinate desynchronization
- Seasonal false positives
- Region instability
- Poor spatial interpretation

Rather than applying incremental fixes, the architecture was redesigned from first principles.

Sat-Scan v3.0 represents:

- Root-cause debugging
- Architectural redesign
- Robustness over convenience
- Interpretability over complexity

---

# 🛰️ Sat-Scan Pipeline

| Stage | Purpose |
|-------|---------|
| Sentinel-2 Acquisition | Retrieve temporal imagery |
| AOI Selection | Define analysis region |
| Temporal Alignment | Synchronize observations |
| Feature Extraction | Siamese ResNet embeddings |
| Distance Analysis | Compute change similarity |
| Clustering | Identify candidate regions |
| Contour Extraction | Generate interpretable boundaries |
| Dynamic World Classification | Region labeling |
| Probabilistic Filtering | Noise suppression |
| Visualization | Interactive DualMap rendering |
| Reporting | Change statistics |

---

# 🛠️ Technology Stack

| Domain | Stack |
|--------|-------|
| Deep Learning | PyTorch • Siamese Networks • ResNet-18 |
| Remote Sensing | Sentinel-2 • Google Earth Engine |
| Image Processing | Scikit-Image |
| Geospatial Processing | Rasterio • Affine Transform |
| Visualization | Streamlit • Folium • DualMap |
| Classification | Dynamic World Probability Bands |
| Spatial Analysis | Thresholding • Contours • Clustering |

---

# 📡 Classification Logic

```python
IF Cluster_Area > Threshold:

    IF DynamicWorld_Mode == Built:
        LABEL = "HUMAN-MADE"

    ELSE:
        LABEL = "NATURAL"
```

---

# 📊 System Outputs

✔ Contour-based Region Detection

✔ Reduced Seasonal False Positives

✔ Human-interpretable Classification

✔ Temporal Synchronization

✔ Surface Change Statistics

✔ Interactive Visualization

---

# 📈 Improvements Over Initial Version

| Component | Initial Prototype | Sat-Scan v3.0 |
|-----------|------------------|---------------|
| Alignment | Drift Issues | Fully Synchronized |
| Noise Handling | High False Positives | Majority Rule Filtering |
| Detection | Bounding Boxes | Contours |
| Stability | Experimental | Consistent |
| Visualization | Static | Interactive |
| Classification | Pixel-based | Probabilistic |

---

# 🚀 Local Setup

```bash
git clone https://github.com/Ganateju/Satilite-Image-Detection.git

cd Satilite-Image-Detection

pip install -r requirements.txt
```

Create:

```text
.env
```

```text
GEE_PROJECT_ID=your-google-project-id
```

Run:

```bash
streamlit run frontend/app.py
```

---

# Engineering Domains

- Geospatial Intelligence
- Remote Sensing
- Computer Vision
- Deep Learning
- Spatial Analytics
- Earth Observation
- Data Visualization
- Systems Engineering

---

# 🧩 Developer Note

> Failure is acceptable.
>
> Not understanding failure is not.

Sat-Scan was rebuilt through architectural analysis and systematic debugging rather than incremental patching.

---

Built by Ganateju

*"Perception under uncertainty."*

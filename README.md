# Loughborough Town GeoAI Pedestrian Flow Dynamics

An interactive 2D WebGL visualization demonstrating predicted pedestrian footfall intensity and dynamic motion trajectories across Loughborough Town, UK.
* **Direct Link:** [Launch Live 3D Pedestrian Dynamics Map](https://mohamedshamroukh.github.io/Loughborough-pedestrian-flow/)
---
### 🌐 Embed Interactive 3D Map in Web Articles / Journals

<iframe 
  src="[https://mohamedshamroukh.github.io/Loughborough-pedestrian-flow/](https://mohamedshamroukh.github.io/Loughborough-pedestrian-flow/)" 
  width="100%" 
  height="600px" 
  style="border: 1px solid #2a2a38; border-radius: 8px; box-shadow: 0 4px 16px rgba(0,0,0,0.5);" 
  allow="fullscreen"
  loading="lazy">
</iframe>

### Dataset & Model Architecture
This visualization is powered by GeoAI pedestrian flow predictions generated across a densified 10-meter road network grid in Loughborough Town.

* **Model Architecture:** LightGBM Regression with Leave-One-Out Cross-Validation (LOOCV)
* **Predictive Accuracy:** $R^2 = 0.89$, Mean Absolute Error ($\text{MAE} = 400$)
* **Sampling Resolution:** Densified road network grid at 10-meter intervals
* **Funding:** UK Government’s Towns Fund as part of the Loughborough Town Deal Project

---
### Contact & Authors
Mohamed Shamroukh | Loughborough University | m.shamroukh@lboro.ac.uk | LinkedIn

Dr. Asya Natapov | Loughborough University

Dr. Taimaz Larimian | Loughborough University
### Citation
If you use this dataset or visualization in your academic work, please cite:

```bibtex
@dataset{Shamroukh2026Pedestrian,
  author    = {Mohamed Shamroukh and Asya Natapov and Taimaz Larimian},
  title     = {Pedestrian flow predictions dataset for Loughborough Town, UK},
  publisher = {Loughborough University},
  year      = {2026},
  doi       = {10.17028/rd.lboro.33122717.v1},
  url       = {[https://doi.org/10.17028/rd.lboro.33122717](https://doi.org/10.17028/rd.lboro.33122717)}
} 

Shamroukh, Mohamed; Natapov, Asya; Larimian, Taimaz (2026). Pedestrian flow predictions dataset for Loughborough Town, UK. Loughborough University. Dataset. https://doi.org/10.17028/rd.lboro.33122717.v1

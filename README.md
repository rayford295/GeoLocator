# 🔐 GeoLocator: A Location-Integrated Large Multimodal Model (LMM) for Inferring Geo-Privacy

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Published in Applied Sciences](https://img.shields.io/badge/Journal-Applied%20Sciences-green)
![DOI](https://img.shields.io/badge/DOI-10.3390%2Fapp14167091-blue)

> This repository contains the code, models, and experiments from the paper:  
> **"GeoLocator: A Location-Integrated Large Multimodal Model (LMM) for Inferring Geo-Privacy"**  
> Published in *Applied Sciences*, 2024.  
> 📄 [Read the full paper](https://doi.org/10.3390/app14167091)

---

## 🧠 Overview

With the growing use of large multimodal models (LMMs) like GPT-4, the potential for **geo-privacy breaches** through online image sharing has drastically increased. This project presents **GeoLocator**, a GPT-4-based multimodal model capable of **inferring precise geographic information from images and social media content**.

🛰️ **Goal**: Assess the risks of LMMs in revealing sensitive geographic information  
🔎 **Approach**: Image + text → inferred location  
🛡️ **Outcome**: Raise awareness and support ethical GeoAI practices

---

## 🤖 Interactive Demo: GeoLocator Custom GPT

To facilitate interactive exploration and qualitative analysis, we provide a publicly accessible Custom GPT implementation of GeoLocator:

🔗 GeoLocator (Custom GPT)
https://chatgpt.com/g/g-qxqvMb6YJ-geolocator

This interactive version allows users to:

Upload images and assess potential geo-privacy leakage

Perform image-based location inference using multimodal reasoning

Explore how visual cues (architecture, signage, vegetation, terrain) contribute to geographic disclosure

The Custom GPT serves as a human-in-the-loop extension of the GeoLocator framework, complementing the quantitative experiments reported in the paper.

Usage Notice:
This tool is intended for research, educational, and ethical analysis purposes only.
Any use in publications, benchmarks, or derivative systems should properly cite the original paper and repository.


---

## 📌 Key Contributions

- ✅ Designed **GeoLocator**, an LMM integrated with location inference capabilities  
- ✅ Evaluated the model using a dataset of geotagged images and text from public sources  
- ✅ Demonstrated how GPT-4-like models can **infer locations with high accuracy**  
- ✅ Highlighted ethical challenges and privacy risks in **Open-Source Intelligence (OSINT)** contexts

---

## 🗺️ Interactive StoryMap

We created an interactive ArcGIS StoryMap to provide a narrative walkthrough of our methodology, results, and geospatial visualizations:

🔗 [View StoryMap](https://storymaps.arcgis.com/stories/a34ffb2aacf74afdb3881b77be65064a/)

---

## 📂 Project Resources

You can access all supplementary materials, data, code, and figures used in the project via our public Google Drive folder:

🔗 [Google Drive Folder](https://drive.google.com/drive/folders/1UtLnIxYT3iB7crGtuaz7iM1CCB0mgxyA?usp=drive_link)

---

## 📁 Repository Structure

```bash
├── index.html               # Demo landing page
├── styles.css               # Web styling
├── .github/
│   └── workflows/           # GitHub Actions automation
│       ├── auto-assign.yml
│       └── proof-html.yml
└── README.md                # Project overview (you are here)

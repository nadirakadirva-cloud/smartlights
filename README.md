# 🚦 Smart Traffic Control Using YOLOv8 and LLM-Assisted Decision Making

## Overview

This project presents an **intelligent traffic control system** that integrates **computer vision** and **AI-based decision logic** to support adaptive traffic light management.
Using **YOLOv8** for vehicle detection and classification, the system counts vehicles approaching an intersection and prepares the ground for **dynamic traffic signal control**, potentially enhanced with **Large Language Models (LLMs)** for high-level decision-making.

The project is designed as a **research-oriented prototype** and can be extended toward real-world smart city traffic management systems.

---

## Key Features

* 🚗 **Vehicle Detection & Counting**

  * YOLOv8-based detection of vehicles in traffic scenes
  * Front-facing vehicle recognition for lane-level analysis

* 🔄 **Binary Vehicle Direction Classification**

  * Training a classifier to distinguish front/back vehicle orientations
  * Supports more accurate traffic flow estimation

* 🧠 **AI-Ready Traffic Decision Framework**

  * Architecture prepared for integration with LLMs
  * Enables rule-based or language-model-driven traffic light strategies

* 📊 **Data Preprocessing & Model Training**

  * Image preprocessing pipeline
  * Supervised training workflow for traffic-related vision tasks

---

## Project Structure

```text
Smart_traffic_control_Yolo_LLM.ipynb
README.md
```

The entire pipeline is implemented inside a single Jupyter Notebook for clarity and reproducibility.

---

## Methodology

1. **Data Preparation**

   * Input images/videos of road traffic
   * Preprocessing for YOLOv8 compatibility

2. **Vehicle Detection**

   * YOLOv8 model detects cars in each frame
   * Bounding boxes and confidence scores extracted

3. **Direction Classification**

   * Binary classifier trained to identify vehicle orientation
   * Used to estimate incoming vs outgoing traffic flow

4. **Traffic Control Logic (Conceptual)**

   * Vehicle counts and directions can be passed to:

     * Rule-based systems, or
     * LLM-based controllers for adaptive signal timing

---

## Technologies Used

* **Python**
* **YOLOv8 (Ultralytics)**
* **OpenCV**
* **PyTorch**
* **Jupyter Notebook**
* *(Optional extension)* Large Language Models (LLMs)

---

## Installation

```bash
pip install ultralytics opencv-python torch torchvision
```

Ensure you have Python 3.8+ and a GPU-enabled environment for faster training.

---

## Usage

1. Open the notebook:

```bash
jupyter notebook Smart_traffic_control_Yolo_LLM.ipynb
```

2. Run cells sequentially to:

   * Preprocess data
   * Train the vehicle orientation classifier
   * Perform vehicle detection and counting

3. Modify or extend decision logic for traffic signal control as needed.

---

## Applications

* Smart city traffic systems
* Adaptive traffic light control
* Urban mobility analytics
* AI-driven transportation research
* Academic and student projects in AI & Computer Vision

---

## Future Work

* 🚦 Real-time traffic light control simulation
* 🧠 Full LLM integration for adaptive policy generation
* 📹 Video-stream-based inference
* 🌐 Multi-intersection coordination
* 📈 Performance benchmarking with real traffic datasets

---

## Disclaimer

This project is a **research and educational prototype**.
It is not intended for direct deployment in safety-critical traffic environments without extensive validation and regulatory approval.

---

## Author

**Nadiram Kadyrova**
10th grade student
---

If you would like, I can also:

* Rewrite this README for **IEEE / conference repositories**
* Add **badges (Python, YOLO, License, etc.)**
* Create a **diagram or architecture figure**
* Tailor it for **GitHub Stars / portfolio visibility**

Just tell me your goal.

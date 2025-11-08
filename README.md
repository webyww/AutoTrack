# 🚗 AutoTrack: Training-Free and Interpretable 3D Multi-Object Tracking

<div align="center">

[![Paper](https://img.shields.io/badge/Paper-Under_Review-blue)]()
[![YouTube Demo](https://img.shields.io/badge/🎬_Demo-YouTube-red)](https://youtu.be/RgQ2RkXjt44)
[![NuScenes Leaderboard](https://img.shields.io/badge/NuScenes-Leaderboard-green)](https://eval.ai/web/challenges/challenge-page/476/leaderboard/1321)
[![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)]()
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)]()
[![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Windows-lightblue)]()

---

### 🔹 *AutoTrack on KITTI Dataset*
<img src="https://github.com/webyww/AutoTrack/blob/main/doc/AutoTrack.gif" width="1000" alt="AutoTrack Demo">

</div>

---

## 🧩 Overview

**AutoTrack** is a training-free and fully interpretable **3D Multi-Object Tracking (MOT)** framework for autonomous driving.  
It introduces an **Observation-Driven Motion Model (ODM)** and an **Adaptive Thresholding Mechanism**,  
achieving state-of-the-art performance on **nuScenes** and **KITTI** without any task-specific training.

---

## 📊 Comparison Overview

<div align="center">
<img src="https://github.com/webyww/AutoTrack/blob/main/doc/lb.png" width="900" alt="Leaderboard Comparison">
  
🔗 [View on NuScenes Leaderboard](https://eval.ai/web/challenges/challenge-page/476/leaderboard/1321)  
🎬 [Watch Demo on YouTube](https://youtu.be/RgQ2RkXjt44)
</div>

---

## 🏆 Main Results

### **nuScenes Test Set**
| Method | Detector | AMOTA | MOTA | IDS | Model | Log |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| **AutoTrack** | FocalFormer-F | **77.9** | **66.5** | 178 | [Google Drive](https://drive.google.com/file/d/1mMJwioLTqLOcuGHiuQ8d5FPaHqhRZQQA/view?usp=sharing) | — |

---

### **nuScenes Val Set**
| Method | Detector | AMOTA | MOTA | IDS | Model | Log |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| **AutoTrack** | FocalFormer-F | **79.3** | **69.6** | 136 | [Google Drive](https://drive.google.com/file/d/1mMJwioLTqLOcuGHiuQ8d5FPaHqhRZQQA/view?usp=sharing) | — |

---

### **KITTI Test Set**
| Method | Detector | HOTA | MOTA | IDS | Model | Log |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| **AutoTrack** | CenterPoint | **81.05** | **89.87** | 36 | [Google Drive](https://drive.google.com/file/d/1mMJwioLTqLOcuGHiuQ8d5FPaHqhRZQQA/view?usp=sharing) | — |

---

### **KITTI Val Set**
| Method | Detector | HOTA | MOTA | IDS | Model | Log |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| **AutoTrack** | CenterPoint | **81.05** | **89.87** | 36 | [Google Drive](https://drive.google.com/file/d/1mMJwioLTqLOcuGHiuQ8d5FPaHqhRZQQA/view?usp=sharing) | — |

---

## 📦 Installation

```bash
git clone https://github.com/webyww/AutoTrack.git
cd AutoTrack
pip install -r requirements.txt

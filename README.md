# 🚗 AutoTrack: An auto threshold and accurate 3D Multi-Object
Tracking Framework for Autonomous Driving

<div align="center">

[![Paper]()]()
[![YouTube Demo](https://img.shields.io/badge/🎬_Demo-YouTube-red)](https://youtu.be/dkpyJnh1BSQ)
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

**AutoTrack** Multi-object tracking (MOT) in autonomous driving
remains challenging due to motion prediction errors, observation
noise, and reliance on manually tuned matching thresholds. In
this paper, we propose AutoTrack, an efficient, training-free,
and fully interpretable 3D MOT framework with an adaptive
thresholding mechanism. Specifically, we design an Observation-
Driven motion Model(ODM) that leverages fully observable
variables to improve state prediction accuracy. A Dynamic Noise
Adjustment(DNA) strategy is incorporated to adaptively update
the process and observation noise covariances in real time,
enhancing filtering robustness under dynamic uncertainty. To
address similarity metric imbalance during data association, we
introduce a novel Gaussian Affinity(GA) cost that unifies transla-
tional and rotational discrepancies in a probabilistic space, yield-
ing more discriminative and consistent associations. Moreover, an
Auto Thresholding algorithm automatically determines matching
boundaries across diverse driving scenarios, eliminating heuristic
tuning. Extensive experiments on the nuScenes and KITTI bench-
marks demonstrate that AutoTrack achieves superior perfor-
mance, attaining 77.9% AMOTA with only 178 identity switches
on the nuScenes test set, significantly surpassing existing state-
of-the-art methods. The implementation and evaluation results
are publicly available at: https://github.com/webyww/AutoTrack.

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
| Method | Detector | AMOTA | MOTA | IDS | Result | Log |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| **AutoTrack** | FocalFormer-F | **77.9** | **66.5** | 178 | [Google Drive](https://drive.google.com/file/d/1mMJwioLTqLOcuGHiuQ8d5FPaHqhRZQQA/view?usp=sharing) | — |

---

### **nuScenes Val Set**
| Method | Detector | AMOTA | MOTA | IDS | Result | Log |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| **AutoTrack** | FocalFormer-F | **79.3** | **69.6** | 136 | [Google Drive](https://drive.google.com/file/d/1mMJwioLTqLOcuGHiuQ8d5FPaHqhRZQQA/view?usp=sharing) | — |

---

### **KITTI Test Set**
| Method | Detector | HOTA | MOTA | IDS | Result | Log |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| **AutoTrack** | CenterPoint | **81.05** | **89.87** | 36 | [Google Drive](https://drive.google.com/file/d/1mMJwioLTqLOcuGHiuQ8d5FPaHqhRZQQA/view?usp=sharing) | — |

---

### **KITTI Val Set**
| Method | Detector | HOTA | MOTA | IDS | Result | Log |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| **AutoTrack** | CenterPoint | **81.05** | **89.87** | 36 | [Google Drive](https://drive.google.com/file/d/1mMJwioLTqLOcuGHiuQ8d5FPaHqhRZQQA/view?usp=sharing) | — |

---

## 📦 Installation

```bash
git clone https://github.com/webyww/AutoTrack.git
cd AutoTrack
pip install -r requirements.txt
```
---

## 🙏 Acknowledgement

This project would not have been possible without the following outstanding open-source works:

- **[MCTrack](https://github.com/lixiaoyu2000/FastPoly)**
  
- **[Fast-poly](https://github.com/lixiaoyu2000/FastPoly)** 
    
- **[Poly-mot](https://github.com/lixiaoyu2000/Poly-MOT)** 
    
- **[FF3D](https://github.com/lixiaoyu2000/FastPoly)**
  
- **[CenterPoint](https://github.com/tianweiy/CenterPoint)** 
    
- **[3D-Detection-Tracking-Viewer](https://github.com/hailanyi/3D-Detection-Tracking-Viewer)**

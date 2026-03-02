# SPART-ITSC-2026

# SPART: Spatial-Partitioning and Adaptive Real-time Temporal Algorithm

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Paper: ITSC 2026 (Under Review)](https://img.shields.io/badge/Paper-ITSC_2026_(Under_Review)-green.svg)]()

> **Note:** This repository has been anonymized for double-blind peer review at IEEE ITSC 2026. 

SPART is an efficient computational framework designed to extract virtual LiDAR-like perception data directly from real-world traffic trajectory datasets (such as the INTERACTION dataset). It bridges the gap between raw traffic data and perception-stack testing by emulating exact geometric sensor observations without the prohibitive computational overhead of full physics-based graphical simulators like CARLA or Gazebo. The use of real-world data aids in testing over realisitic LiDAR-like pointclouds instead of simulated artificial environments, encouraging better safety validation of navigation planning and control architectures.

## 🛠️ Installation & Requirements

SPART is built to run on standard hardware without requiring a heavy GPU cluster.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/anonymous-repo/SPART.git](https://github.com/anonymous-repo/SPART.git)
   cd SPART
   
2. **Install dependencies:**
It is recommended to use a virtual environment.
```bash
  pip install numpy pandas matplotlib scipy numba imageio

3. **Dataset Preparation**
This framework is configured to process the INTERACTION Dataset (https://interaction-dataset.com/)

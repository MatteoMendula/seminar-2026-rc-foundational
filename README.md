# Reservoir Computing in the Wild: From Energy-Efficient Digital Twins to Foundational Dynamical Substrates

![Status](https://img.shields.io/badge/Status-Upcoming-blue) ![Date](https://img.shields.io/badge/Date-Feb%2011%2C%202026-orange) ![Speaker](https://img.shields.io/badge/Speaker-Dr.%20Matteo%20Mendula-green)

### 📅 **Event Details**
- **Date:** Wednesday, February 18, 2026
- **Time:** 10:00h CET
- **Location:** CTTC Auditorium B4/B6 (Barcelona, Spain) & Online
- **Registration:** [Link to Registration/Teams Meeting]

---

## 🔍 Overview

**Can efficient architectures such as Reservoir Computing (RC) compete with energy-intensive Deep Learning architectures in real-world scenarios?**

The remarkable success of attention-based models (Transformers) has set a high bar for AI performance, but often at an unsustainable energy cost. This seminar traces the evolution of Reservoir Computing from a lightweight tool for edge deployment to a robust **Foundational Model** capable of learning universal physical dynamics.

We will explore three key evolutionary phases of this technology:

### 1. The Optimization Phase: Breaking the Training Bottleneck
We address the historical difficulty of tuning RC hyperparameters. By introducing an **adaptive ε-Greedy search strategy**, we demonstrate:
* **70% reduction** in offline optimization time.
* **88% reduction** in energy consumption.
* Seamless online adaptation using Recursive Least Squares (RLS) with minimal memory overhead.

### 2. The Application Phase: Hierarchical Digital Twins
Moving to industrial applications, we apply RC to **Hierarchical Digital Twin (DT)** ecosystems. Using a novel "Fidelity" metric that balances accuracy, maintainability, and deployability, our **RC-DT engine** achieves:
* **39% higher accuracy** than LSTM baselines on anomaly detection tasks.
* **Order-of-magnitude lower energy consumption**.
* Superior adaptability for maintenance in Cyber-Physical Systems.

### 3. The Future: RC as a "Universal Dynamical Substrate"
*Current Work & Novel Contribution*

We challenge the traditional view of the Reservoir as a "random feature generator." Instead, we reframe it as a **Dynamical Substrate**—a recurrent medium structurally tuned to the "Edge of Chaos" via **Lyapunov Rejection Sampling**.

By treating the Reservoir as a Foundational Model for physics, we achieve:
* **Zero-Shot Transfer:** Successfully identifying operational regimes (e.g., Idle vs. Burst) on unseen hardware with **76% accuracy**.
* **Few-Shot Calibration:** Using just 1,000 samples to collapse forecasting error (RMSE) by **92%**, effectively "calibrating" the universal substrate to a new environment.

---

## 👨‍🏫 Speaker Biography

**Dr. Matteo Mendula** is a researcher at the **Sustainable Artificial Intelligence Research Unit** at the [Centre Tecnològic de Telecomunicacions de Catalunya (CTTC)](https://www.cttc.es/).

His research focuses on bridging the gap between the computational efficiency of Reservoir Computing (RC) and the performance demands of state-of-the-art Deep Learning. He specializes in the optimization of offline-online training cycles and the application of lightweight AI in Hierarchical Digital Twin ecosystems. His recent work explores the use of Lyapunov-guided reservoirs as foundational models for extracting universal dynamical laws in resource-constrained environments.

---

## 📚 Associated Resources & Code

To ensure reproducibility, the code and datasets discussed in this seminar are available in the following repositories:

* **DARE-ML:** [`dare-ml`]([https://gitlab.cttc.es/supercom/afp-dt-fgcs](https://gitlab.cttc.es/supercom/dare-ml-eesp-2025))
* **ε-Greedy Optimization:** [`ijcnn-2025-epsilongreedy-rc`](https://gitlab.cttc.es/supercom/ijcnn-2025-epsilongreedy-rc)
* **Adaptive Fidelity Profiling (DTs):** [`afp-dt-fgcs`](https://gitlab.cttc.es/supercom/afp-dt-fgcs)

---

## 📝 Citation
If you find these concepts useful for your research, please consider citing our recent works:

> M. Mendula, C. Leonelli, M. Miozzo, P. Dini, *"DARE-ML: Democratized Accessible Resource Environment for Machine Learning in the SUPERCOM Platform."*, ISC High Performance 2025 International Workshops, Hamburg, Germany, 2025.

> M. Mendula, M. Miozzo, P. Dini, *"Reservoir Computing in Real-World Environments: Optimizing the Cost of Offline and Online Training,"* IJCNN, Rome, Italy, 2025.

> M. Mendula, M. Miozzo, P. Bellavista, P. Dini, *"Reservoir computing for enhanced fidelity in hierarchical digital twin ecosystems,"* Future Generation Computer Systems, 2026.




---
*Organized by CTTC - Sustainable Artificial Intelligence Research Unit*

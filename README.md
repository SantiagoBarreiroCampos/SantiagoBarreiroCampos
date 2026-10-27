<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SantiagoBarreiroCampos/SantiagoBarreiroCampos/main/assets/banner.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SantiagoBarreiroCampos/SantiagoBarreiroCampos/main/assets/banner-light.svg">
  <img alt="Santiago Barreiro Campos — Software Engineer" src="https://raw.githubusercontent.com/SantiagoBarreiroCampos/SantiagoBarreiroCampos/main/assets/banner.svg" width="100%">
</picture>

</div>

Software Engineer at **Santander Digital Services**, Madrid. Graduated from **Universidad Europea de Madrid**.

My day job lives in Santander's private enterprise GitHub. This account is where I park ideas. Something catches my attention — usually a question I cannot settle by reading about it — and I build the smallest thing that answers it, measure whether it actually worked, and stop there. *How far can a network be compressed before it stops working. Can a ballot be verifiable without anyone holding the voter's identity. What does coordination actually buy a fleet of vehicles. Why should a passing test fail because a `div` moved.*

So: no tutorials, no clones, nothing half-finished left as a placeholder. Small projects, one idea each. They all run, and every number below comes out of the code rather than out of a claim.

---

## Latest ideas

<sub>Most recent first. Each one is a single question, taken far enough to get an answer.</sub>

<table>
<tr>
<td width="50%" valign="top">

### [autonomous-fleet-simulation](https://github.com/SantiagoBarreiroCampos/autonomous-fleet-simulation)

<sub>`Python` · `Pygame` · MIT</sub>

**What is vehicle-to-vehicle communication actually worth, in numbers?**

Three fleets — fully autonomous, mixed, fully manual — driven through the same roundabout side by side, with a live dashboard on speed, energy, flow and congestion.

Energy is modelled properly: rolling resistance, aerodynamic drag, and the real cost of accelerating. That is what makes the result legible — stop-and-go traffic is expensive, and coordination is what removes it.

Press `S` mid-run to inject a sudden stop and watch which fleet recovers first.

</td>
<td width="50%" valign="top">

### [BitNet b1.58](https://github.com/SantiagoBarreiroCampos/BitNet)

<sub>`Python` · `PyTorch` · `NumPy` · MIT</sub>

**How much of a neural network is actually load-bearing?**

Every weight quantized to `-1`, `0` or `+1` — 1.58 bits — with absmean scaling and a Straight-Through Estimator to keep gradients flowing through a step that has no derivative.

| | |
|---|---|
| Compression | **18.7×** · 1,052 KB → 56.5 KB |
| Accuracy | **97.14%** vs 97.66% FP32 |
| CPU inference | **1.49× faster** |
| Sparsity | 36.9% of weights land on zero |

A GPT-style transformer reached **19.0×** on 811,008 parameters and still generated coherent text at 26–62 tokens/s on CPU.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [blockchain-voting](https://github.com/SantiagoBarreiroCampos/blockchain-voting)

<sub>`Python` · `cryptography` · `p2pnetwork` · `tkinter`</sub>

**Can a vote be provably yours without anyone storing who you are?**

Voter identity is **SHA-256 over a secret salt** — the real ID is never stored or transmitted. Each ballot carries an **RSA-2048** signature, so a vote is verifiable without being attributable.

| | |
|---|---|
| Consensus | Proof of Work, difficulty 2 |
| Block | Mined every 2 votes |
| Network | Mesh, automatic peer discovery |
| Resync | 30 s, longest valid chain |

Double voting is checked against the chain *and* the mempool. Nodes reconnect on their own.

</td>
<td width="50%" valign="top">

### [Self-Healing Automation](https://github.com/SantiagoBarreiroCampos/Automation-project-with-Self-Healing-algorithm)

<sub>`Python` · `Selenium` · `Machine Learning`</sub>

**Why should a passing test fail because the markup moved?**

A Machine Learning model relocates broken element locators at runtime, matching on surrounding structure instead of a brittle path, so the suite survives a redesign rather than going red on it.

The interesting part is not the automation. It is treating locator drift as a prediction problem rather than a maintenance chore.

</td>
</tr>
</table>

<div align="center">

<sub>Every figure above is measured, and reproducible from the experiments in those four repositories.</sub>

</div>

---

## Where the habit started

University work, still up because it is the same reflex with less range.

**[IA_prediccion_precio_BTC](https://github.com/SantiagoBarreiroCampos/IA_prediccion_precio_BTC)** <sub>`Jupyter` `pandas` `scikit-learn`</sub> — Bitcoin price modelling from historical market data, feature engineering and model comparison worked end to end.

**[InteligenciaArtificial](https://github.com/SantiagoBarreiroCampos/InteligenciaArtificial)** <sub>`Jupyter`</sub> — the AI coursework the notebooks above grew out of.

**[ProyectoDeComputacion1](https://github.com/SantiagoBarreiroCampos/ProyectoDeComputacion1)** <sub>`Python`</sub> — early university computing project.

**[Eventell.ProyIng](https://github.com/SantiagoBarreiroCampos/Eventell.ProyIng)** <sub>`Java`</sub> — first-year engineering project, and my first real codebase.

---

## What I reach for

Ordered by how much of it is visible in the repositories above, rather than by how it reads on a CV.

| | |
|---|---|
| **Daily — and here in the code**<br><sub>quantization, training loops, P2P nodes, simulation, test automation</sub> | ![Python](https://img.shields.io/badge/Python-30363D?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-30363D?style=flat-square&logo=pytorch&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-30363D?style=flat-square&logo=numpy&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-30363D?style=flat-square&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-30363D?style=flat-square&logo=scikitlearn&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-30363D?style=flat-square&logo=jupyter&logoColor=white) ![Selenium](https://img.shields.io/badge/Selenium-30363D?style=flat-square&logo=selenium&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-30363D?style=flat-square&logo=pytest&logoColor=white) ![Git](https://img.shields.io/badge/Git-30363D?style=flat-square&logo=git&logoColor=white) |
| **Comfortable — used in production**<br><sub>day job at Santander, so none of it is visible here</sub> | ![FastAPI](https://img.shields.io/badge/FastAPI-30363D?style=flat-square&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-30363D?style=flat-square&logo=flask&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-30363D?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-30363D?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-30363D?style=flat-square&logo=mongodb&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-30363D?style=flat-square&logo=docker&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-30363D?style=flat-square&logo=typescript&logoColor=white) ![Angular](https://img.shields.io/badge/Angular-30363D?style=flat-square&logo=angular&logoColor=white) ![Laravel](https://img.shields.io/badge/Laravel-30363D?style=flat-square&logo=laravel&logoColor=white) |
| **Read and write it when the problem asks**<br><sub>university, and whatever comes up</sub> | ![Java](https://img.shields.io/badge/Java-30363D?style=flat-square&logo=openjdk&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-30363D?style=flat-square&logo=cplusplus&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-30363D?style=flat-square&logo=tensorflow&logoColor=white) |

<sub>**Languages:** Spanish (native) · English (professional) · French (basic professional) · Italian (basic)</sub>

---

<div align="center">

**Next up:** extreme quantization past ternary — what stays reliable once a model gets that small.

<sub>New ideas land here as they come. If one of them overlaps with something you are working on, I am happy to talk about it.</sub>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-30363D?style=for-the-badge)](https://www.linkedin.com/in/santiago-barreiro-campos-b69054231/)
[![Email](https://img.shields.io/badge/Email-30363D?style=for-the-badge&logo=gmail&logoColor=EC7000)](mailto:santiago.barreirocampos@gmail.com)

</div>

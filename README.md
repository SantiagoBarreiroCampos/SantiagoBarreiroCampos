<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SantiagoBarreiroCampos/SantiagoBarreiroCampos/main/assets/banner.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SantiagoBarreiroCampos/SantiagoBarreiroCampos/main/assets/banner-light.svg">
  <img alt="Santiago Barreiro Campos — Computer Engineer" src="https://raw.githubusercontent.com/SantiagoBarreiroCampos/SantiagoBarreiroCampos/main/assets/banner.svg" width="100%">
</picture>

</div>

## Now

Computer Engineer at **Santander Digital Services**, in Madrid. Graduated from **Universidad Europea de Madrid**.

Most of what I build sits where **machine learning** meets **systems that have to keep running**: neural networks compressed to the point where they barely have weights left, decentralized consensus, and automation that repairs itself instead of breaking.

Right now I am working through **ternary quantization** — networks whose every weight is `-1`, `0` or `+1`. The numbers are below.

## Selected work

<table>
<tr>
<td width="50%" valign="top">

**[BitNet b1.58](https://github.com/SantiagoBarreiroCampos/BitNet)**

Ternary neural networks — 1.58 bits per weight, so every weight is `-1`, `0` or `+1`.

**18.7× compression** (1,052 KB → 56.5 KB) at **97.14%** accuracy against **97.66%** for the FP32 baseline, and **1.49× faster** CPU inference. A GPT-style transformer reached 19.0× on 811,008 parameters, 36.9% of them naturally zero.

<sub>Python · PyTorch · NumPy</sub>

</td>
<td width="50%" valign="top">

**[blockchain-voting](https://github.com/SantiagoBarreiroCampos/blockchain-voting)**

Decentralized proposal voting over a P2P mesh network, with a graphical client.

**RSA-2048** signatures per ballot and **SHA-256 with a secret salt** for voter identity — the real ID is never stored or transmitted. Mesh nodes reconnect automatically and resynchronize on a fixed interval.

<sub>Python · Cryptography · P2P</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Self-Healing Automation](https://github.com/SantiagoBarreiroCampos/Automation-project-with-Self-Healing-algorithm)**

Automation that recovers on its own when the UI underneath it moves.

A Machine Learning algorithm relocates broken element locators at runtime, so a suite survives markup changes instead of failing on them.

<sub>Python · Selenium · Machine Learning</sub>

</td>
<td width="50%" valign="top">

**[BTC Price Prediction](https://github.com/SantiagoBarreiroCampos/IA_prediccion_precio_BTC)**

Predictive modelling of Bitcoin price from historical market data.

Feature engineering and model comparison worked through end to end in notebooks.

<sub>Jupyter · pandas · scikit-learn</sub>

</td>
</tr>
</table>

## By the numbers

<div align="center">

![BitNet compression](https://img.shields.io/badge/BitNet%20compression-18.7x-EC7000?style=for-the-badge&labelColor=30363D)
![Accuracy retained](https://img.shields.io/badge/Accuracy%20retained-97.14%25-EC7000?style=for-the-badge&labelColor=30363D)
![CPU inference](https://img.shields.io/badge/CPU%20inference-1.49x%20faster-EC7000?style=for-the-badge&labelColor=30363D)
![Ternary weights](https://img.shields.io/badge/Per%20weight-1.58%20bits-EC7000?style=for-the-badge&labelColor=30363D)
![Ballot signatures](https://img.shields.io/badge/Ballot%20signatures-RSA--2048-EC7000?style=for-the-badge&labelColor=30363D)

<sub>Measured, not estimated &mdash; reproducible from the experiments in the repositories above.</sub>

</div>

## Toolbox

| | |
|---|---|
| **Machine learning** | ![Python](https://img.shields.io/badge/Python-30363D?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-30363D?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-30363D?style=flat-square&logo=tensorflow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-30363D?style=flat-square&logo=scikitlearn&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-30363D?style=flat-square&logo=numpy&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-30363D?style=flat-square&logo=pandas&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-30363D?style=flat-square&logo=jupyter&logoColor=white) |
| **Distributed systems** | ![Blockchain](https://img.shields.io/badge/Blockchain-30363D?style=flat-square&logo=blockchaindotcom&logoColor=white) ![P2P](https://img.shields.io/badge/P2P-30363D?style=flat-square&logo=webrtc&logoColor=white) |
| **Backend & data** | ![FastAPI](https://img.shields.io/badge/FastAPI-30363D?style=flat-square&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-30363D?style=flat-square&logo=flask&logoColor=white) ![Laravel](https://img.shields.io/badge/Laravel-30363D?style=flat-square&logo=laravel&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-30363D?style=flat-square&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-30363D?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-30363D?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-30363D?style=flat-square&logo=mongodb&logoColor=white) |
| **Web** | ![Angular](https://img.shields.io/badge/Angular-30363D?style=flat-square&logo=angular&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-30363D?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-30363D?style=flat-square&logo=javascript&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-30363D?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-30363D?style=flat-square&logo=css&logoColor=white) |
| **Automation & testing** | ![Selenium](https://img.shields.io/badge/Selenium-30363D?style=flat-square&logo=selenium&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-30363D?style=flat-square&logo=pytest&logoColor=white) |
| **Also work in** | ![Java](https://img.shields.io/badge/Java-30363D?style=flat-square&logo=openjdk&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-30363D?style=flat-square&logo=cplusplus&logoColor=white) |
| **Day to day** | ![Docker](https://img.shields.io/badge/Docker-30363D?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-30363D?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-30363D?style=flat-square&logo=github&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-30363D?style=flat-square) ![PyCharm](https://img.shields.io/badge/PyCharm-30363D?style=flat-square&logo=pycharm&logoColor=white) |

## Beyond code

![Spanish](https://img.shields.io/badge/Spanish-Native-30363D?style=flat-square&labelColor=EC7000)
![English](https://img.shields.io/badge/English-Professional-30363D?style=flat-square&labelColor=EC7000)
![French](https://img.shields.io/badge/French-Basic%20professional-30363D?style=flat-square&labelColor=EC7000)
![Italian](https://img.shields.io/badge/Italian-Basic-30363D?style=flat-square&labelColor=EC7000)

## Reach me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-30363D?style=for-the-badge)](https://www.linkedin.com/in/santiago-barreiro-campos-b69054231/)
[![Email](https://img.shields.io/badge/Email-30363D?style=for-the-badge&logo=gmail&logoColor=EC7000)](mailto:santiago.barreirocampos@gmail.com)

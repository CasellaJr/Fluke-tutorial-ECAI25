# Fluke-tutorial-ECAI25
*A hands-on tutorial using the [fluke](https://github.com/makgyver/fluke) federated-learning framework for the ECAI 2025 tutorial session*

## 🎯 Overview  
This repository contains the material for the tutorial held at ECAI 2025 (European Conference on Artificial Intelligence) introducing the fluke federated-learning utility framework. It provides a step-by-step set of Jupyter notebooks that illustrate how to use fluke for custom algorithms, defenses (e.g., Krum), and adversarial/malicious scenarios in federated learning.

## 📂 Structure  
- `1_fluke_custom_alg.ipynb` : Demonstrates how to extend fluke with a new custom algorithm.  
- `2_fluke_krum.ipynb` : Shows how to implement and evaluate a robust aggregation technique (e.g., Ť Krum) within fluke.  
- `3_fluke_malicious.ipynb` : Explores setting up a malicious client scenario and evaluating its impact on federated training.  
- `README.md` : This file.  

## 🛠 Prerequisites  
Before running the notebooks, please ensure you have:  
- Python 3.10+ (or a compatible version)  
- The `fluke` framework installed (e.g., `pip install fluke-fl` or install from source)  
- Typical ML/federated-learning dependencies: PyTorch or TensorFlow (depending on your setup), NumPy, and Jupyter Notebook/JupyterLab.

## 🚀 Getting Started  
1. Clone this repository:  
    ```
    git clone https://github.com/CasellaJr/Fluke-tutorial-ECAI25.git
    cd Fluke-tutorial-ECAI25
    ```
2. Create a virtual env:
    ```
    python3 -m venv venv
    source venv/bin/activate   
    ```

## 📘 Tutorial Flow

1. **Custom Algorithm**  
   Learn how Fluke’s modular architecture allows you to define and integrate your own federated learning algorithms.  
   You’ll understand how to subclass key components and register them in the training pipeline.

2. **Robust Aggregation (Krum)**  
   Implement the *Krum* defense technique to make the server’s aggregation process robust against adversarial or faulty clients.  
   This section demonstrates how to plug in existing defenses or design new ones.

3. **Malicious Clients Simulation**  
   Simulate and analyze the impact of malicious participants in a federated learning setting.  
   You’ll explore attack strategies, evaluate robustness, and visualize performance under adversarial conditions.

Throughout the tutorial, you’ll gain hands-on experience with:
- Federated communication (clients ↔ server)
- Model aggregation and evaluation
- Attack and defense mechanisms in FL systems

---

## ✅ Target Audience

This tutorial is designed for:

- 🎓 **Students** attending ECAI 2025 who want a practical introduction to federated learning.  
- 🧑‍🔬 **Researchers** interested in experimenting with and extending federated learning algorithms.  
- 💻 **Developers** seeking to quickly prototype and test FL workflows using an open, modular framework.  
- 🧠 **Practitioners** aiming to understand the robustness, security, and scalability aspects of federated learning.

No prior experience with Fluke is required — a basic understanding of machine learning and Python is enough to get started!


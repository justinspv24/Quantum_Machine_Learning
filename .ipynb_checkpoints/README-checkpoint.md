# ⚛️ Quantum Machine Learning (QML) Journey

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Framework](https://img.shields.io/badge/Framework-PennyLane%20%7C%20PyTorch-orange)
![Status](https://img.shields.io/badge/Status-Active%20Development-green)

## 📖 About
This repository documents my transition from Classical ML to **Quantum Machine Learning**. 

The goal of this project is to implement algorithms ranging from fundamental quantum logic to state-of-the-art Hybrid Quantum-Classical Networks. It serves as a living portfolio of my understanding of how to map classical ML intuition (optimization, kernels, gradients) onto Quantum Processing Units (QPUs).

**Primary Tech Stack:**
* **PennyLane** (Differentiable quantum programming)
* **PyTorch** (Hybrid integration)
* **Qiskit** (Circuit visualization/backend)

---

## 🛠️ Environment Setup

To replicate the code in this repository, follow these steps to set up the environment.

### 1. Clone the repository
```bash
git clone [https://github.com/YOUR_USERNAME/quantum-ml-journey.git](https://github.com/YOUR_USERNAME/quantum-ml-journey.git)
cd quantum-ml-journey
```

### 2. Create the Conda Environment

I use a dedicated environment to avoid conflicts between classical ML libraries and Quantum SDKs.
```bash
conda create -n qml python=3.10
conda activate qml
```

### 3. Install Dependencies
```bash
 pip install pennylane qiskit qiskit-aer matplotlib notebook torch torchvision
```


## 🗺️ Repository Structure & Roadmap

The repository is organized by complexity, moving from basic qubit manipulation to advanced variational algorithms.

### 📂 `01_Quantum_Foundations`
*Focus: The physics of information.*
* **Basics:** Qubits, Superposition, and Entanglement.
* **Gates:** Unitary operations and the Bloch Sphere.
* **Protocols:** Teleportation and Superdense Coding.

### 📂 `02_Hybrid_Algorithms` (Variational Circuits)
*Focus: "Gradient Descent" on a Quantum Computer.*
* **Qubit Rotation:** Training a circuit to rotate a qubit using classical optimizers.
* **VQE:** Variational Quantum Eigensolver (Finding ground states).
* **QAOA:** Quantum Approximate Optimization Algorithm.

### 📂 `03_Quantum_Kernels`
*Focus: Mapping data to high-dimensional Hilbert spaces.*
* **Kernel Estimation:** Calculating Gram matrices using quantum circuits.
* **QSVM:** Quantum Support Vector Machines for classification.

### 📂 `04_Advanced_QNNs`
*Focus: Deep Learning architectures in the quantum realm.*
* **Data Re-uploading:** Single-qubit classifiers.
* **QCNN:** Quantum Convolutional Neural Networks.
* **QGAN:** Quantum Generative Adversarial Networks.

### 📂 `05_Projects`
* **Capstone:** Transfer Learning with Hybrid ResNet-Quantum Networks.

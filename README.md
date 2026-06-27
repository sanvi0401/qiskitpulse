# Qiskit Pulse Experiments

A collection of experiments and implementations using **Qiskit Pulse**, demonstrating pulse-level quantum programming, waveform design, and quantum hardware control.

## 📌 Overview

Unlike the standard quantum circuit model, **Qiskit Pulse** provides low-level access to quantum hardware by allowing users to directly control microwave pulses applied to qubits. This repository contains notebooks and code examples exploring pulse programming concepts using IBM's Qiskit framework. Qiskit Pulse enables fine-grained control over pulse timing, amplitude, phase, and frequency for advanced calibration and quantum control experiments. :contentReference[oaicite:0]{index=0}

## ✨ Features

- Pulse-level quantum programming
- Custom pulse waveform generation
- Pulse schedule construction
- Drive and measurement channel operations
- Quantum gate calibration experiments
- Visualization of pulse schedules
- Interactive Jupyter notebooks

## 🛠️ Technologies Used

- Python 3.x
- Qiskit
- Qiskit Pulse
- NumPy
- Matplotlib
- Jupyter Notebook

## 📂 Repository Structure

```
qiskitpulse/
│
├── notebooks/          # Pulse programming notebooks
├── images/             # Figures and visualizations
├── requirements.txt    # Python dependencies
└── README.md
```

> The actual structure may vary depending on the notebooks included in this repository.

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/sanvi0401/qiskitpulse.git
cd qiskitpulse
```

### Create a virtual environment (optional)

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install qiskit numpy matplotlib jupyter
```

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the desired notebook and execute the cells sequentially.

## 📖 Topics Covered

- Pulse Builder API
- Pulse Schedules
- Gaussian Pulses
- Constant Pulses
- Delay Instructions
- Pulse Channels
- Timing and Synchronization
- Measurement Operations
- Pulse Visualization
- Quantum Hardware Control

## 📷 Sample Concepts

- Pulse waveform generation
- Drive channels
- Measurement channels
- Schedule alignment
- Pulse timing
- Calibration techniques

## 🎯 Learning Objectives

This repository is intended for learners interested in:

- Quantum Computing
- Pulse-Level Quantum Programming
- Quantum Hardware Calibration
- Quantum Control
- IBM Quantum Platform
- Advanced Qiskit Programming

## ⚠️ Note

Qiskit Pulse has been deprecated in newer versions of Qiskit and removed in Qiskit 2.x following IBM Quantum's transition away from public pulse-level hardware access. These examples are therefore most useful with compatible Qiskit 1.x releases or for educational purposes. :contentReference[oaicite:1]{index=1}

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

## 📚 References

- IBM Quantum Documentation
- Qiskit Documentation
- Qiskit Pulse Research Paper

## 📄 License

This project is licensed under the MIT License.

---

### Author

**Sanvi Devnani**

- GitHub: https://github.com/sanvi0401
- LinkedIn:https://www.linkedin.com/in/sanvi-devnani-6032ba288/

---

⭐ If you found this repository useful, consider giving it a star!

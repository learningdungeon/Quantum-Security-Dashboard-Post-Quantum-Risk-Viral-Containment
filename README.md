# Quantum-Security-Dashboard-Post-Quantum-Risk-Viral-Containment
An interactive Python dashboard modeling the post-quantum vulnerability of AES-128 encryption and simulating a Quantum QAOA-based strategy for real-time viral data containment in a security breach scenario.

# 🛡️ Quantum Security Dashboard: Post-Quantum Risk & Viral Containment (QPoland Hackathon 2025)

## Project Overview

This project is an interactive **Quantum Security Dashboard** developed during the **QPoland Hackathon 2025 (Open Track)**. It addresses a dual challenge in post-quantum security: the vulnerability of classical cryptography (specifically AES-128) to quantum attacks (Shor's and Grover's algorithms) and the need for optimized **real-time containment** of leaked sensitive data in a viral social media environment.

The solution utilizes **Qiskit** (simulated) for modeling the quantum components, combining data visualization and interactive widgets to provide an executive-level risk assessment.

## Key Features

* **AES-128 Quantum Vulnerability:** Benchmarks five different quantum circuit implementations of the AES-128 cipher, comparing resource costs (**Qubits**, **T-depth**, **TofD-W Cost**) and resulting **Effective Security (bits)** under a quantum threat.
* **Integrated Risk Assessment:** Dynamically calculates a combined risk score based on both cryptographic vulnerability and the viral spread scenario (e.g., 'Encrypted Video Leak').
* **Quantum Containment Strategy (QAOA Model):** Simulates the effectiveness of using the **Quantum Approximate Optimization Algorithm (QAOA)** to identify and block high-influence nodes for superior viral containment compared to baseline methods.
* **Interactive Controls:** Uses `ipywidgets` to allow users to select different scenarios, compare AES implementations, and adjust risk thresholds.
* **Dynamic Recommendations:** Provides real-time security recommendations (Critical, High, Medium, Low) based on the current dashboard risk score.

## Technical Details

The dashboard is built using a Python class (`QuantumSecurityDashboard`) within a Jupyter Notebook environment.

| Component | Description | Relevance to Quantum Cryptography |
| :--- | :--- | :--- |
| **AES Benchmarking Data** | Hardcoded data from academic research on the quantum cost of breaking AES-128. | Demonstrates the practical **resource requirements** for a quantum attack on classical cryptosystems. |
| **Viral Containment Plot** | Compares `No Intervention`, `Random Blocking`, and `Quantum QAOA` spread curves. | Models a real-world application of **Quantum Machine Learning/Optimization** for mitigating a security breach outcome. |
| **Qiskit/Quantum Elements** | The QAOA model is conceptualized; plots and metrics are based on theoretical advantages demonstrated in quantum optimization literature. | Shows a clear path toward using **Quantum Computing** for **security incident response**. |

## How to Run

1.  Clone this repository.
2.  Ensure you have the required Python libraries installed: `pandas`, `numpy`, `matplotlib`, `ipywidgets`, and `IPython.display`.
3.  Open the file `AES_Setup (2).ipynb` in a Jupyter environment.
4.  Run all cells to display the interactive dashboard controls and output.

---
*Created as part of the QPoland Hackathon 2025, Open Track: Quantum Cryptography Focus.*
*Project by QuantumCrazy Team/ **Noor** (Qiskit Advocate)| Friend of OQI.CERN*

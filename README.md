# Quantum Random Number Generator (QRNG)
**Participant:** Murshed SK

---

## 1. Project Overview

This project is a **Quantum Random Number Generator (QRNG)** built for qiskit fall fest 2025 - IEEE Chicago edition hackathon. It's a Minimum Viable Project (MVP) that fulfills the core requirements of the "Open-Ended Project" brief.

Using Qiskit, the program runs a 3-qubit circuit on a simulator. It uses Hadamard gates to create an equal superposition of all 8 possible states ($|000\rangle$ to $|111\rangle$). The project delivers two outputs: (1) a single, truly random number by running the circuit once, and (2) a histogram from 1024 runs to prove that all 8 outcomes are "equally likely".

---

## 2. Results and Outputs

The project successfully produces two key outputs as defined in the brief:

### Output 1: The Single Random Number
The first part of the script runs the circuit for a **single shot** to produce one truly random number. This fulfills the primary "generator" requirement.

<img width="439" height="82" alt="image" src="https://github.com/user-attachments/assets/a7b4dd76-d1ab-424e-8cae-64586ba7dff8" />

### Output 2: The "Proof of Quantum-ness"
The second part runs the circuit for **1024 shots** to demonstrate the "true quantum nature" of the circuit. The resulting histogram (shown below) clearly displays the "$n$ equal buckets of measurement results," proving that all 8 outcomes were (roughly) equally likely to be measured.

<img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/a6f4d921-4719-4603-8866-6d5532dda71a" />

---

## 3. Challenges Faced and Solutions

Here are the challenges encountered during the project and how they were resolved.

* **Challenge:**
    * The full project, including the "Deeper questions" about noise mitigation, was not feasible.
    * **Solution:** I aggressively scoped the project down to an MVP. I focused *only* on the "Getting Started" and "Tips" sections, delivering the core generator and its proof. In the future, I'll look at those advanced questions.

* **Challenge: Local Environment and Installation**
    * Setting up a local Conda environment and installing Qiskit can be time-consuming and prone to `PATH` or launcher errors.
    * **Solution:** I bypassed all local setup issues by using **Google Colab**. This allowed me to have a working Qiskit environment in under a minute by simply running `!pip install qiskit-aer` in a notebook cell.

---

## 4. Participant Information

* **Full Name:** Murshed SK
* **Email:** murshedsk135@gmail.com

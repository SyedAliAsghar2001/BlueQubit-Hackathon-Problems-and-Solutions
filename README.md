# 🚀 BlueQubit Hackathon  

Welcome to my repository for the **BlueQubit Quantum Hackathon**!  

This repo contains the official **QASM problem circuits** released during the hackathon, along with my own **worked-out solutions**. The event challenged participants to tackle *Peaked Circuit* problems — specially designed quantum circuits where one hidden bitstring dominates the probability distribution.  

My goal here is to document both the **problem statements** and my **approach to solving them**, so others can learn and build upon these solutions.  

---

## 🎯 Hackathon Overview  
- **Event**: BlueQubit Quantum Hackathon  
- **Duration**: 24 hours  
- **Challenge**: Identify the *peak bitstring* hidden in each quantum circuit.  
- **Tools**: Participants were encouraged to use BlueQubit’s simulators and hardware, but any quantum framework (Qiskit, PennyLane, etc.) was fair game.  

---

## 🔍 Peaked Circuits Challenge  
Each `.qasm` file sets up a quantum state with a **non-uniform distribution**. Among all possible bitstrings, one appears with significantly higher probability.  

👉 The mission: **Find the peak bitstring!**  

For example:  
- Suppose the measured distribution strongly favors **0110**.  
- The circuit is designed such that this bitstring stands out with much higher probability compared to all others.  

This repository includes both the **original circuits** and my **verified solutions** for each.  

---

## 📚 About Peaked Circuits  
“Peaked circuits” were introduced by **Scott Aaronson** as a way to demonstrate *verifiable quantum advantage*. Unlike fully random circuits, they are:  
- **Hard to simulate classically** (Google estimated supercomputers would take ~10²⁵ years).  
- **Easy to verify on a quantum device** — simply measure and check if the peak bitstring emerges!  

These problems are designed to test both **creativity** and **technical skill** in working with quantum simulators and hardware.  

---

## 🏆 My Contributions  
- Implemented solutions using simulation tools.  
- Verified peak bitstrings against theoretical expectations.  
- Documented results for each challenge.  

This repo can serve as a reference for others looking to understand how to approach **Peaked Circuit problems** in practice.  

---

✨ If you’re preparing for similar hackathons, I recommend brushing up on:  
- Basic quantum circuit design (Qiskit / PennyLane tutorials)  
- Measurement distributions and state preparation  
- Efficient simulation techniques for larger qubit counts  

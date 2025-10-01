
# Qiskit 1-qubit


This repository contains a **simple quantum program** using Qiskit to introduce students to **quantum circuits, gates, and measurement**.

## Program Explanation

- **QuantumCircuit(1, 1)**: Creates 1 qubit and 1 classical bit.
- **qc.h(0)**: Applies Hadamard gate to put the qubit in superposition.
- **qc.measure(0, 0)**: Measures the qubit and stores the result in the classical bit.
- **Aer.get_backend('qasm_simulator')**: Runs the circuit on a classical simulator.
- **shots=10**: Executes the circuit 10 times and records the results.
- **counts**: Shows how many times each outcome (`0` or `1`) occurred.

---

## Tasks for Students

1. **Change the number of shots** to 100 and observe the result.  
2. **Add a second qubit**, apply Hadamard gates to both qubits, measure, and print the result.  
3. **Replace the Hadamard gate with an X gate** and observe how the measurement changes.  

---

## Instructions

1. **Fork this repository** on GitHub.  
2. **Clone** your forked repository:
   ```bash
   git clone hhttps://github.com/arunpandianj/Qiskit_1-qubit
   ```
3. Navigate to the directory:
   ```bash
   cd Qiskit_1-qubit
   ```
4. **Install Qiskit** (if not already installed):

5. **Run the program**:

6. Complete the **tasks** in your forked repo and **push changes** back.  

---

**Tip:** Experiment with different gates, qubits, and shots to see how quantum measurement behaves.

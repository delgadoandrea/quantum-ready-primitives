# quantum-ready-primitives

This repository contains the scripts to simulate a 1D Ising model on PennyLane while tracking metrics such as number of qubits, gates and circuit depth. The code will initialize the qubits, perform a time evolution using Trotter decomposition, and measure observables. Since we can't inder the time complexity in terms of execution time with PennyLane, we infer it from gate counts and circuit depth.

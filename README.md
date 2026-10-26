# Pharos Dry Run Executor Agent

An intelligent pre-transaction simulation agent developed in **Java** for the Pharos Agent Arena designed to simulate transaction outcomes and gas costs before sending them to the live market[cite: 10].

## 📋 Requirements Met

1. **Non-Broadcasting Simulation (Req. 01):** Utilizes gas estimation and local calls to simulate transactions safely without broadcasting them[cite: 10].
2. **Success/Reversion Prediction (Req. 02):** Accurately forecasts success or reversion, providing exact reversion reasons and gas cost estimates[cite: 10].
3. **State Comparison (Req. 03):** Displays expected state changes (balances before and after execution)[cite: 10].
4. **Automatic Guard Block (Req. 04):** Automatically halts and blocks execution if the dry-run simulation fails[cite: 10].

## 🚀 How to Run

1. Certifique-se de ter o **Java JDK** instalado.
2. Compile o ficheiro:
   ```bash
   javac DryRunExecutor.java

# Quantum Computing 101

[![License](https://img.shields.io/github/license/ayltai/quantum-computing-101.svg?style=flat)](https://github.com/ayltai/quantum-computing-101/blob/master/LICENSE)

Welcome to the Quantum Computing 101 workshop!

In this repository, you can find a collection of Jupyter notebooks that show the basics of quantum computing using [Qiskit](https://www.qiskit.org). Feel free to learn from this repository, to ask [questions](https://github.com/ayltai/quantum-computing-101/issues), or to [contribute](https://github.com/ayltai/quantum-computing-101/pulls).

## Contents

### [Hello, Quantum World!](https://github.com/ayltai/quantum-computing-101/blob/master/1-hello-quantum-world.ipynb)
Learn how to write your first quantum program.

### [Hello, Quantum Gates!](https://github.com/ayltai/quantum-computing-101/blob/master/2-hello-quantum-gates.ipynb)
Have fun with your first quantum gates.

### [Quantum random number generator](https://github.com/ayltai/quantum-computing-101/blob/master/3-quantum-random-number-generator.ipynb)
Learn how to use qubits to generate true random numbers.

### [Superdense coding](https://github.com/ayltai/quantum-computing-101/blob/master/4-superdense-coding.ipynb)
Send 2 bits of information using 1 qubit only.

### [Quantum teleportation](https://github.com/ayltai/quantum-computing-101/blob/master/5-quantum-teleportation.ipynb)
Learn how to teleport information securely.

## Quick start

### macOS
1. Install Python 3:
   ```sh
   brew install python3
   ```
2. Install Virtualenv:
   ```sh
   brew install virtualenv
   ```
3. Create a virtual environment to run Python 3 code:
   ```sh
   venv .venv
   source .venv/bin/activate
   ```
4. Clone this project:
   ```sh
   git clone https://github.com/ayltai/quantum-computing-101.git
   cd quantum-computing-101
   ```
5. Get your IBM-Q token as described [here](https://qiskit.org/documentation/install.html).
6. Export your IBM-Q token as an environment variable:
   ```sh
   export IBMQ_TOKEN=1234...5678
   ```
7. Run a Jupyter notebook:
   ```sh
   jupyter nbconvert --to=html --ExecutePreprocessor.enabled=True 1-hello-quantum-world.ipynb
   ```
8. Examine the HTML output, `1-hello-quantum-world.html`.

## License
[MIT](https://github.com/ayltai/quantum-computing-101/blob/master/LICENSE)

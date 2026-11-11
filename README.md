# Quantum Computing Projects

Two games built for quantum computing coursework at the University of Technology Sydney. Both run as
Jupyter notebooks.

## Quantum Penalty Shootout (individual)

`quantum_penalty_shootout.ipynb`

A two-player football penalty game in which the goalkeeper's dive is decided by a quantum circuit.

- Six-qubit OpenQASM 2.0 circuit whose measured bit patterns map to five dive directions.
- Runs the circuit on a remote Quokka quantum server over HTTP, with endpoint selection and a random-bit
  fallback when the server is unavailable.
- Interactive interface built with ipywidgets, with live score, turn and attempt tracking.

## Qubit Quest (group project, team of seven)

`qubit_quest.ipynb`

A quantum maze game. Players move through a dungeon and open quantum walls by editing circuits and moving
gates between a toolbelt and the circuit, using superposition, entanglement and measurement to reach the
goal. Team members are credited in the notebook.

## Tools

Python, OpenQASM 2.0, ipywidgets, Jupyter.

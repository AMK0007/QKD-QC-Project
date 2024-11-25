# QKD-simulation
Quantum Key Distribution simulation project for CS4048 Quantum Computing

Includes a survey and simulation of the BB84, B92, and E91 protocols for quantum key distribution, as well as solutions to selected exercises from Nielsen \& Chuang's _Quantum Computation and Quantum Information_.

## Installation
```bash
pip install -r requirements.txt
```

## Example Usage
```python
import qkdalgo.simulations as sim
sim.runBB84(<keylen>)
```

## Modules used:
NumPy - www.numpy.org

PyCrypto - https://www.dlitz.net/software/pycrypto

Quantum Information Toolkit (QIT) - qit.sourceforge.net

Nose - https://pypi.python.org/pypi/nose/1.3.7
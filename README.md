
# Physics Simulations

This is a set of small projects created for the purpose of learning. Here, I tried to utilize my physics knowledge in order to create the various simulations below to familiarize myself with Python as well as create a visual aid for some concepts in physics. 

## Solar System Simulation

A Python simulation of planetary orbits using Newtonian gravity, visualized with Matplotlib.

## Physics Implementation

```python
def compute_force(p1, p2):
    r_vec = p1["pos"] - p2["pos"]
    r_mag = np.linalg.norm(r_vec)
    force_mag = G * p1["mass"] * p2["mass"] / (r_mag**2 + 1e-4)  # Softening term
    return -force_mag * (r_vec / r_mag)
```
![Solar System](SolarSystemAnimation.gif)


## Lorentz Transformation Simulation

![lorentz transform](LorentzAnimation.gif)


# Physics Simulations

A collection of computational physics projects combining Python programming with fundamental physics concepts. These simulations serve as both learning tools and visual demonstrations of physical principles.

## Solar System Simulation
A numerical N-body simulation modeling planetary dynamics under Newtonian gravitation.

This Python implementation uses:

- **Physics**: Newton's law of universal gravitation (F = GMm/r²)
- **Numerics**: Euler integration with softening parameter (ε = 1e-4)
- **Visualization**: Matplotlib for 2D rendering with trail effects
- **Features**:
  - Customizable initial conditions
  - Circular/elliptical orbit presets
  - Energy conservation monitoring

![Solar System](SolarSystemAnimation.gif)

## Lorentz Transformation Simulation
A visualization of special relativistic effects that occur at relativistic velocities. The β parameter quantifies the object's speed as a fraction of light speed, with space-time distortion becoming significant as β → 1. Note that the object isn't shown above, only the space that becomes distorted. 

![lorentz transform](LorentzAnimation.gif)

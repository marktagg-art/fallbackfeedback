# fall back feedback 01: murmur

Generative artwork exploring the intersection of chaos theory and collective behavior. Triangular "birds" ride invisible currents shaped by the Lorenz strange attractor.

**[View the artwork →](https://yourusername.github.io/fall-back-01/)**

---

## About

The attractor's equations govern the flow. Discrete triangular forms bank and turn through space, accumulating across layers and cycles.

Strange attractors + murmurations share structural properties:
- **Emergent complexity** from simple local rules
- **Sensitive dependence** on initial conditions
- **Scale-free correlations** across the entire system
- **Attractor states** the system tends toward but never exactly repeats

In both, global beauty emerges from local simplicity.

## Lorenz system  

The system models convection using Euler integration with these equations:

```
dx/dt = σ(y - x)
dy/dt = x(ρ - z) - y
dz/dt = xy - βz
```

Where σ = 10, β = 8/3, and ρ drifts between configurable start/end values across layers.

---

## Triptych

Each variation shares the same seed (27) but explores different parameters:

I. RGB primaries on dark brown, 3 cycles 
II. Diluted red+white+blue on light gray, 6 cycles
III. Purple+orange+gray on spring green, 6 cycles

---

## Composer

For creating variations. Adjustable parameters:

- **Flock**: Layer count, cycles, streams per layer, flight duration
- **Birds**: Element size, size variation, spacing, organic drift
- **Flow**: ρ (rho) start/end values that shape the attractor
- **Composition**: Scale, offset, rotation
- **Colors**: Background and three element colors with independent opacities

---

## Scripting

Built with [p5.js](https://p5js.org/). This project runs client-side in the browser, no server required.

---

## Files

```
index.html     Triptych 
composer.html  Interactive tool for creating custom variations
README.md      This file
```

---

## License

MIT license. Explore, adjust, create.

---

*fall back feedback 01: murmur*  
*December 2025*

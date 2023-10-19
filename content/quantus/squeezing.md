---
title: Quantum Squeezing
date: 2023-10-19
---

# Heisenberg's Uncertainty Principle
The **uncertainty principle** states that there exists a limit to the precision of which certain pairs of physical properties can be simultaneously known.
The more accurately one property is measured, the less accurately the other property is known.
Such paired properties, like position and momentum, are known as **canonically conjugate variables**.
Provided the uncertainties of two paired variables, represented by $\Delta x$ and $\Delta p$, the mathematical inequality representing the uncertainty principle is as follows.
$$
\Delta x\Delta p \geq \frac{\hbar}{2}
$$
The uncertainties in a pair of conjugate variables are always greater than or equal to half the reduced Planck's constant. Hence, the more precisely we can measure one variable, the less precisely we can measure the other variable.
## Existence as a fundamental property
This principle exists as a **fundamental property of quantum systems**, and is a consequence of the wave-particle duality of subatomic particles.

---
# Quantum squeezing
Following from Heisenberg's uncertainty principle, quantum squeezing is a technique used to enhance the precision of one variable in a quantum system, at the expense of the increased noise of its conjugate variable.
Quantum squeezing has been used for the construction of atomic clocks — electronic oscillations of atoms (such as caesium) provides a constant phase irrespective of external conditions, unlike regular wristwatches which may be subject to time alteration due to gravitational time dilation as described by Einstein's theory of general relativity.
It is also used in interferometry setups, such as the Laser Interferometer Gravitational-wave Observatory (LIGO), allowing the sensing of gravitational waves originated by the collision of two black holes about 1.3 billion light years away.
## Optical fibers
In **light-based quantum communications**, quantum squeezing can be used to reduce the noise associated with optical signal detection, improving sensitivity of measurements. This is used in [quantum key distribution](https://en.wikipedia.org/wiki/Quantum_key_distribution), where the accurate measurement of the quantum states of light is crucial for secure communication of cryptographic keys.
The process of quantum squeezing in optical fibers makes use of [nonlinear optical effects](https://en.wikipedia.org/wiki/Nonlinear_optics), such as **four-wave mixing (FWM)** or **parametric down-conversion**. 
In such processes, intense pump light beams are sent through a nonlinear optical medium (e.g. an optical fiber) and undergoes interactions with said medium to generate **squeezed light**.
- In FWM, interactions between three light wave frequencies in a nonlinear optical medium can give rise to a **fourth frequency**, resulting in **energy conservation**. 
	- This is extremely beneficial in optical phase conjugation and parametric amplification, but can also have adverse effects due to the loss of coherence and phase mismatching.
- In parametric down-conversion, a pump photon can interact in the fiber to produce a pair of **entangled signal and idler photons**, which can be used to create squeezed coherent states of light.
### Limitations
The amount of squeezing in quantum communication is primarily limited by optical losses due to degradation in quantum signals caused by scattering or absorption as travelling distance increases.
**Phase fluctuations** may also disrupt delicate quantum states of photons, resulting in problems in quantum key distribution and other information theory protocols that rely on precise phase matching.
In some crystalline optical fibers, **imperfections in the crystal lattice** can introduce noise that degrades the quantum properties of squeezed light.
The phenomenon of **birefringence** of anisotropic materials could also result in polarisation mode mixing, affecting the overall quality of the quantum squeezing of light.
### Computational models of atom-photon interactions
For designing a computational model of resonant atom-photon interactions within quantum-based optical fibers, one must take into account for atom-field coupling, detuning, along with the physical properties of the fiber. This can be represented by the Hamlitonian operator, alongside appropriate representations of the quantum states.
Use a quantum computing framework like Qiskit to solve the time-dependent Schrodinger equation using the circumstances and initial conditions of the quantum system, including the atom's initial state and the input state of the optical fiber.





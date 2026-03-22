# ⚛️ Quantum Field Theory

## 📄 Main Proof Document
Solutions to Srednicki's Part 1 covering all the core concepts of QFT with Scalar Fields. 

---

## 📚 Topics Learnt and Notes on Them

### 1.) Elementary QFT
$$\mathcal{L} = -\frac{1}{2}\partial^\mu \phi \partial_\mu \phi - \frac{1}{2}m^2\phi^2 + \frac{1}{6}g\phi^3$$

Walked through how we can take a Lagrangian for the $\phi^3$ theory and take out the path integral for it. We can expand the path integral into a dual Taylor series to get the path integral as a graphical representation of the series depicting a transition probability. Physically, this path integral can be visualized as summing over different configurations where a field can be. An important notion learnt from this section is how the number of particles is not a conserved quantity for a theory of quantum mechanics and special relativity. 

### 2.) Perturbation Theory
$$\Pi(k^2) = \frac{1}{2}g^2 \int \frac{d^d \ell}{(2\pi)^d} \frac{1}{[\ell^2 + m^2][(\ell+k)^2 + m^2]}$$

Learnt how loop corrections worked and how we can use dimensional regularization by adding the dimensional parameter to regulate the divergences of the integral (leading into renormalization). It's called perturbation theory because we can add more loop-corrections to the scattering amplitude to make it more "Quantum", so we are perturbing in terms of quantum effects. These calculations are quite fun. 

### 3.) Scattering
$$\langle f | i \rangle = i^n \int d^4x_1 \dots d^4x_n e^{i(k_1 x_1 + \dots)} (-\partial^2 + m^2) \dots \langle 0 | T\{\phi(x_1) \dots \phi(x_n)\} | 0 \rangle$$

Learnt LSZ reduction formula, it ties very much to elementary QFT because you are calculating a correlation function. Learnt how we can take the $\langle 0 | T\{\phi(x_1)\phi(x_2)\phi(x_3)\phi(x_4)\} | 0 \rangle$ type correlations into decay rates and scattering cross-sections that can be measured in experiment. Learnt about unstable particles and resonances. 

### 4.) Renormalization and EFT
$$\mathcal{L} = -\frac{1}{2}Z_\phi \partial^\mu \phi \partial_\mu \phi - \frac{1}{2}Z_m m^2\phi^2 - \frac{1}{24}Z_g g\phi^4$$

Learnt about the $\overline{\text{MS}}$ renormalization scheme. Walked through EFT and how it is just filtering out all the high energy physics/short distance physics by adding a lattice and integrating out all higher degrees of freedom through operators. Learnt about the renormalization group approach and how we can calculate beta functions to relate parameters in the Lagrangian. I really enjoy the RG and EFT conceptually because they are such a cool way of eliminating the divergences at high energies. 

### 5.) Symmetries
$$j^\mu = \frac{\partial \mathcal{L}}{\partial(\partial_\mu \phi)} \delta \phi$$

Learnt about discrete and continuous symmetries like parity, time-conjugation, etc. Learnt about Noether's theorem and how Lie groups work to generate these symmetries on a field.

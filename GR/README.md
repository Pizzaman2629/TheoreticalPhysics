# 🌌 General Relativity

## 📄 Main Proof Document
Studied all the differential geometry needed to learn General Relativity: Manifolds, Tensors, Curvature, etc. and used that to derive Einstein's Equations using the Einstein-Hilbert action. Used Penrose diagrams to analyze the causal structure of different spaces like Minkowski, de Sitter and Anti de Sitter. 

---

## 📚 Topics Learnt and Notes on Them

### 1.) Manifolds


These are basically just spaces you can twist around and exploit to define curvature, etc. Basically, I learnt how the generalization of a locally flat space can be thought of as a manifold. Also learnt the topology necessary to identify Manifolds suitable for describing spacetime, such as Hausdorff topologies. Learnt about maps between topological spaces such as homeomorphisms. 

### 2.) Vectors and Tensors
$$ds^2 = g_{\mu\nu} dx^\mu dx^\nu$$

Redefined Vectors to be based on points in locally flat space to allow them to be used with Manifolds. Learnt about the dual space in GR and how it's defined using the derivative operator to map a vector back into $\mathbb{R}$. Learnt about the metric for a topological space and how it can be thought of as a tool to measure distances and angles. Learnt about tensors as independent geometric identities that are maps from multiple vector and covector spaces to $\mathbb{R}$.

### 3.) Curvature and the Covariant Derivative
$$\nabla_\mu V^\nu = \partial_\mu V^\nu + \Gamma^\nu_{\mu\lambda} V^\lambda$$



Learnt about how curvature of a manifold is described with the Riemann tensor and the Ricci tensor which can be thought of as encoding the parallel transport properties of a vector field w.r.t another vector field. Learnt about parallel transport which is equivalent to the total derivative in fluid mechanics where you can use Christoffel symbols to move a vector along a curved spacetime.

### 4.) Einstein's Field Equations
$$S = \int \left( \frac{R}{16\pi G} + \mathcal{L}_M \right) \sqrt{-g} \, d^4x$$
$$R_{\mu\nu} - \frac{1}{2}R g_{\mu\nu} = 8\pi G T_{\mu\nu}$$

Used the Einstein-Hilbert action to derive Einstein's field equations. These equations show how the spacetime bends to accommodate certain symmetries and conditions. When adding the matter part with the energy momentum tensor, we can see how spacetime bends according to matter distributions. Learnt how to solve this equation under a static, spherically symmetric condition called the Schwarzschild Solution. 

### 5.) Causal Structure
Learnt how to use Penrose Diagrams and Hypersurfaces to describe Minkowski, de Sitter and Anti de Sitter spaces' behaviour at boundaries. 

| Minkowski Space | de Sitter Space |
| :--- | :--- |
| <img width="450" alt="Penrose Minkowski" src="https://github.com/user-attachments/assets/f7bda597-5b7a-49fd-80e0-381a145b47de" /> | <img width="450" alt="Penrose de Sitter" src="https://github.com/user-attachments/assets/9fa93356-1733-49bb-926e-9859131fe36f" /> |
| Penrose Diagram for Minkowski Space, Taken from Tong's Notes. | Penrose Diagram for de Sitter Space, Taken from Tong's Notes. |

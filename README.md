# Spacetime Theory

### *Empathy with the Universe*

by *Norbert Nopper*

- **[Quaternion-Hypersphere Theory](#quaternion-hypersphere-theory-of-spacetime-)**
- [What is Time?](WhatIsTime.md)
- [Faster Than Light](FasterThanLight.md)
- [Outlook](Outlook.md)
- [Summary](Summary.md)

## Quaternion-Hypersphere Theory of Spacetime 🌌

### *Spacetime is energy*

![Expansion of the Hypersphere S³](hypersphere_expansion.png)

## Definition of a Quaternion

A quaternion is defined as:

$$q = w + p\mathbf{i} + r\mathbf{j} + s\mathbf{k}$$

where $w, p, r, s \in \mathbb{R}$ and the basis elements satisfy:

$$\mathbf{i}^2 = \mathbf{j}^2 = \mathbf{k}^2 = \mathbf{i}\mathbf{j}\mathbf{k} = -1$$

## Theory

A spacetime event is represented as a quaternion:

$$q = ct + x\mathbf{i} + y\mathbf{j} + z\mathbf{k}$$

where the components map as $w \equiv ct$, $p \equiv x$, $r \equiv y$, $s \equiv z$. Here $t$ is time, $c$ is the speed of light, and $x, y, z$ are the spatial coordinates of the Cartesian coordinate system. Scaling time by $c$ ensures all four components share the same unit of length [m].

Any point $q$ lies on a **hypersphere S³** of radius $R$, satisfying:

$$|q| = \sqrt{c^2t^2 + x^2 + y^2 + z^2} = R$$

This places time and space on equal footing with a Euclidean signature $(+,+,+,+)$. Note that this differs from the Minkowski signature $(-,+,+,+)$ of standard Special Relativity; in this framework, concepts such as Lorentz invariance and causal structure require separate treatment. In particular, causal ordering emerges from the foliation of spacetime by hyperspheres of increasing radius $R$ (see [Foundations](#foundations)), rather than from the metric signature itself.

The constraint $|q| = R$ reduces the four quaternion components to three independent degrees of freedom: a point on $S^3_R$ is specified by three hyperspherical angles $(\chi, \theta, \phi)$, with $ct = R\cos\chi$ and $r = R\sin\chi$. The component $ct$ is therefore a *position* coordinate on the current hypersphere — a "temporal angle" — and must be distinguished from the cosmic epoch $\tau$ introduced below.

All components $ct, x, y, z$ are expressions of the same underlying energetic reality — spacetime **is** energy. The quaternion norm $|q| = R$ is the Schwarzschild radius of the total mass $m$ of the universe, directly proportional to the mass-energy:

$$E = \frac{c^4}{2G} R$$

where $G$ is the gravitational constant.

## Expansion of the Universe

When energy materializes into massive particles (e.g. pair production), the total mass $m$ increases and the radius $R$ of the hypersphere grows — the universe expands. Thus $R$ is not a constant but a function of the total mass formed:

$$R = \frac{2Gm}{c^2}$$

Here $E$ and $R$ track the **mass-energy** component only. At the singularity, no mass has yet formed ($m = 0$, $R = 0$), while energy exists in non-mass form (e.g. radiation). As radiation converts to mass, $m$ grows, $R$ grows, and total energy (mass-energy + radiation) is conserved throughout.

| State | Description | Hypersphere |
|-------|-------------|-------------|
| Singularity | No mass formed ($m = 0$) | $R = 0$ |
| Big Bang | Energy → mass begins | $R$ starts growing |
| Present | Ongoing conversion | $R$ is large |
| Future | Conversion approaches completion | $R \to R_{\max} = \frac{2GE_{\text{total}}}{c^4}$ |

Cosmic expansion is driven by the conversion $E = mc^2$, not by a cosmological constant.

## Foundations

To make the preceding picture a well-defined dynamical framework rather than a single static hypersphere, the theory rests on the following structural commitments.

### Foliation of spacetime

Spacetime is a four-dimensional manifold foliated by three-spheres of increasing radius:

$$\mathcal{M} = \bigcup_{R \in [0,\, R_{\max}]} S^3_R$$

An **event** is a pair $(R, q)$ with $q \in S^3_R$. The quaternion $q = ct + x\mathbf{i} + y\mathbf{j} + z\mathbf{k}$ with $|q| = R$ parameterizes one leaf of the foliation; different leaves correspond to different epochs of the universe.

### Epoch versus coordinate time

Two distinct notions of "time" appear in the theory and must not be conflated:

- $ct$ — a **position coordinate** on the current hypersphere, i.e. one of the four quaternion components, constrained by $|q| = R$. It is a geometric label, not a clock reading.
- $\tau$ — the **cosmic epoch**, a monotonic parameter indexing the foliation. It is the clock reading that orders events causally.

To first approximation $\tau := R/c$, so that $R$ and $\tau$ grow together.

### Dynamical law for $R(\tau)$

Expansion is specified by a monotone growth law. The simplest choice consistent with a finite maximum is:

$$\frac{dR}{d\tau} = c \cdot f(R), \qquad f(R) = 1 - \frac{R}{R_{\max}}$$

which gives $R(\tau) = R_{\max}\bigl(1 - e^{-c\tau / R_{\max}}\bigr)$. The associated mass-formation rate follows from $R = 2Gm/c^2$:

$$\frac{dm}{d\tau} = \frac{c^2}{2G} \frac{dR}{d\tau}$$

Total energy $E_{\text{tot}} = mc^2 + E_{\text{rad}}$ is conserved; radiation energy decreases as mass energy increases. Any monotone $f \geq 0$ with $f(R_{\max}) = 0$ is admissible; the specific form above is an illustrative minimal choice.

### Causal order

Events are ordered by epoch:

$$(R_A, q_A) \prec (R_B, q_B) \iff R_A < R_B$$

Events sharing the same $R$ (i.e. lying on the same leaf $S^3_R$) are causally unrelated. Causality is thus a property of the foliation, not of the metric signature. Because $R$ is required to grow monotonically, the ordering is a total order on epochs and a well-defined partial order on events.

### Two roles of $c$

The constant $c$ plays two conceptually distinct roles:

- $c_{\text{geom}}$ — a **unit conversion factor** in $ct$, with units m/s, which puts the temporal and spatial components of $q$ on the same footing. It imposes no kinematic speed limit.
- $c_{\text{light}}$ — the **propagation speed of light** on $S^3_R$, an empirical quantity to be derived from the dynamics of massless fields in this geometry.

In standard physics these are identified; in this framework they are equal numerically but conceptually separate. Statements about "faster-than-light" motion (see [Faster Than Light](FasterThanLight.md)) refer to $c_{\text{light}}$ and assert that nothing in the S³ geometry enforces $v \leq c_{\text{light}}$ as a universal bound.

## Novelty

Each ingredient of this theory has precedent in the literature:

- **Quaternions for spacetime** — explored since Hamilton, with contributions by Silberstein and others
- **S³ hypersphere cosmology** — proposed in various forms by Suntola, Carroll, and Ramírez
- **Schwarzschild radius as cosmic scale** — central to black hole cosmology models
- **Euclidean signature $(+,+,+,+)$** — used in quantum gravity via Wick rotation (Hartle–Hawking)
- **Expansion without a cosmological constant** — pursued by several alternative cosmologies

What is novel is the **specific synthesis**: a single quaternion $q = ct + x\mathbf{i} + y\mathbf{j} + z\mathbf{k}$ with Euclidean norm constraining all events to S³, whose radius $R$ is identified as the Schwarzschild radius of the total mass of the universe via $E = \frac{c^4}{2G} R$, with cosmic expansion driven entirely by energy-to-mass conversion.

## Observable Implications

Several features distinguish this framework from standard ΛCDM cosmology:

- **No cosmological constant** — Expansion is driven by energy-to-mass conversion rather than dark energy. The predicted expansion history differs from ΛCDM, particularly at late times when conversion slows and $R$ asymptotically approaches $R_{\max}$.
- **Euclidean signature** — The $(+,+,+,+)$ metric predicts no fundamental distinction between timelike and spacelike intervals. Any observed Lorentz-invariant phenomena must emerge as effective behavior, potentially testable through high-precision interferometry or cosmological observations at extreme scales.
- **Finite maximum radius** — The universe has a definite upper bound $R_{\max} = \frac{2GE_{\text{total}}}{c^4}$, implying a closed spatial geometry. This could leave imprints in the cosmic microwave background (CMB) as suppressed large-angle correlations or matched-circle signatures.
- **Schwarzschild radius coincidence** — The observable universe's radius should track the Schwarzschild radius of its total mass content. This relationship can be checked against current cosmological data for the observable mass-energy density and Hubble radius.

## References

- [Cartesian coordinate system](https://en.wikipedia.org/wiki/Cartesian_coordinate_system)
- [Cosmic microwave background](https://en.wikipedia.org/wiki/Cosmic_microwave_background)
- [Cosmological constant](https://en.wikipedia.org/wiki/Cosmological_constant)
- [Gravitational constant](https://en.wikipedia.org/wiki/Gravitational_constant)
- [Lambda-CDM model](https://en.wikipedia.org/wiki/Lambda-CDM_model)
- [Mass–energy equivalence](https://en.wikipedia.org/wiki/Mass%E2%80%93energy_equivalence)
- [N-sphere](https://en.wikipedia.org/wiki/N-sphere)
- [Pair production](https://en.wikipedia.org/wiki/Pair_production)
- [Quaternion](https://en.wikipedia.org/wiki/Quaternion)
- [Schwarzschild radius](https://en.wikipedia.org/wiki/Schwarzschild_radius)
- [Spacetime](https://en.wikipedia.org/wiki/Spacetime)
- [Special relativity](https://en.wikipedia.org/wiki/Special_relativity)
- [Time](https://en.wikipedia.org/wiki/Time)
- [Wick rotation](https://en.wikipedia.org/wiki/Wick_rotation)

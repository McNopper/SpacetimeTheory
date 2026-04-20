# Spacetime Theory

### *Empathy with the Universe*

by *Norbert Nopper*

- **[Quaternion-Hypersphere Theory](#quaternion-hypersphere-theory-of-spacetime)**
- [What is Time?](WhatIsTime.md)
- [Faster Than Light](FasterThanLight.md)
- [Outlook](Outlook.md)
- [Summary](Summary.md)

## Quaternion-Hypersphere Theory of Spacetime

### *Spacetime is energy*

## Definition of a Quaternion

A quaternion is defined as:

$$q = w + p\mathbf{i} + r\mathbf{j} + s\mathbf{k}$$

where $w, p, r, s \in \mathbb{R}$ and the basis elements satisfy:

$$\mathbf{i}^2 = \mathbf{j}^2 = \mathbf{k}^2 = \mathbf{i}\mathbf{j}\mathbf{k} = -1$$

## Theory

A spatial point in the universe is represented as a quaternion:

$$q = \xi + x\mathbf{i} + y\mathbf{j} + z\mathbf{k}$$

where the components map as $w \equiv \xi$, $p \equiv x$, $r \equiv y$, $s \equiv z$. Here $x, y, z$ are the spatial coordinates of the Cartesian coordinate system and $\xi$ is a fourth embedding coordinate, all in units of length [m]. Time is treated separately (see [Foundations](#foundations)).

Any point $q$ lies on a **hypersphere $S^3$** of radius $R$, satisfying:

$$|q| = \sqrt{\xi^2 + x^2 + y^2 + z^2} = R$$

The spatial universe is therefore a closed three-sphere $S^3_R$ of positive curvature — the $k = +1$ case of Friedmann–Lemaître–Robertson–Walker cosmology, embedded here in a four-dimensional Euclidean auxiliary space via the quaternion. The full spacetime is Lorentzian: time $\tau$ is a separate coordinate, and the spacetime metric has signature $(-,+,+,+)$, so Special and General Relativity are recovered in full. See [Foundations](#foundations) for the complete structure.

The constraint $|q| = R$ reduces the four quaternion components to three independent spatial degrees of freedom: a point on $S^3_R$ is specified by three hyperspherical angles $(\chi, \theta, \phi)$, with $\xi = R\cos\chi$ and $r = R\sin\chi$, where $r = \sqrt{x^2 + y^2 + z^2}$.

The quaternion norm $|q| = R$ is the Schwarzschild radius of the total mass $m$ of the universe, directly proportional to the mass-energy:

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

Spacetime is a four-dimensional Lorentzian manifold foliated by spatial three-spheres of increasing radius:

$$\mathcal{M} = \mathbb{R}_\tau \times S^3_{R(\tau)}, \qquad R: \tau \mapsto R(\tau) \in [0,\, R_{\max}]$$

An **event** is a pair $(\tau, q)$ with $\tau \in \mathbb{R}$ the cosmic time and $q \in S^3_{R(\tau)}$ the spatial position, represented as a quaternion $|q| = R(\tau)$ in the four-dimensional Euclidean embedding space.

### Metric and signature

The spacetime metric is Lorentzian with signature $(-,+,+,+)$:

$$ds^2 = -c^2\, d\tau^2 + ds^2_{S^3_R}$$

where $ds^2_{S^3_R}$ is the round metric on the spatial three-sphere of radius $R$. In hyperspherical coordinates $(\chi, \theta, \phi)$:

$$ds^2 = -c^2 d\tau^2 + R^2\bigl[\,d\chi^2 + \sin^2\chi\,(d\theta^2 + \sin^2\theta\, d\phi^2)\,\bigr]$$

This is exactly the **closed ($k = +1$) Friedmann–Lemaître–Robertson–Walker** metric, with the extra identifications $R(\tau) = 2Gm(\tau)/c^2$ and the growth law below. Special and General Relativity are recovered in full within this geometry: Lorentz invariance holds locally on any sufficiently small patch, time dilation and length contraction follow from the Minkowski tangent-space structure, and light cones exist at every event.

### Comoving map

Points on different slices are identified by their hyperspherical angles. A **comoving observer** at fixed angular coordinates $(\chi_0, \theta_0, \phi_0)$ traces the worldline

$$q_{\text{comoving}}(\tau) = R(\tau) \cdot \hat{q}_0, \qquad \hat{q}_0 = (\cos\chi_0,\, \sin\chi_0\sin\theta_0\cos\phi_0,\, \sin\chi_0\sin\theta_0\sin\phi_0,\, \sin\chi_0\cos\theta_0)$$

This is the FLRW comoving map: angular coordinates are conserved, and physical arc length between two comoving observers is $R(\tau)\,\Delta\chi$, which grows with $R$. Cosmic expansion is this scaling of arc lengths, not a local velocity of matter.

### Dynamical law for $R(\tau)$

The growth law is derived from a first-order kinetic assumption: the rate of energy-to-mass conversion is proportional to the un-converted energy remaining. Writing $m_{\max} := E_{\text{tot}}/c^2$ for the asymptotic mass,

$$\frac{dm}{d\tau} = k\,(m_{\max} - m)$$

for some rate constant $k > 0$. The only rate constant available from the theory's own content is $k = c/R_{\max}$ (the inverse light-crossing time of the asymptotic universe). Using $R = 2Gm/c^2$ and $R_{\max} = 2Gm_{\max}/c^2$:

$$\frac{dR}{d\tau} = c\left(1 - \frac{R}{R_{\max}}\right)$$

This is the growth law. It has a unique solution with $R(0) = 0$:

$$R(\tau) = R_{\max}\left(1 - e^{-c\tau / R_{\max}}\right)$$

Total energy is conserved: $E_{\text{tot}} = mc^2 + E_{\text{rad}}$, with $E_{\text{rad}}(\tau) = E_{\text{tot}}\,e^{-c\tau/R_{\max}}$ decaying exponentially into mass. This $R(\tau)$ plays the role of the FLRW scale factor (up to the identification $a(\tau) \propto R(\tau)$) and replaces the usual Friedmann equation: expansion is driven by the conversion kinetics, not by a cosmological constant.

### Hubble parameter

The Hubble parameter is defined from the comoving map as the logarithmic rate of change of the scale $R$:

$$H(\tau) = \frac{1}{R}\frac{dR}{d\tau} = \frac{c}{R_{\max}} \cdot \frac{e^{-c\tau/R_{\max}}}{1 - e^{-c\tau/R_{\max}}} = \frac{c}{R}\left(1 - \frac{R}{R_{\max}}\right)$$

In the early universe ($R \ll R_{\max}$), $H \approx c/R$ — a large Hubble rate. Asymptotically ($R \to R_{\max}$), $H \to 0$: expansion freezes without a cosmological constant. Comparison with observational $H(z)$ is the primary empirical test (see [Outlook](Outlook.md)).

### Light, proper time, and causal structure

Because the metric is Lorentzian, all standard relativistic results hold:

- **Light propagation.** Photons follow null geodesics: $ds^2 = 0$, i.e. $c\, d\tau = ds_{S^3_R}$ along the trajectory. The speed of light on any sufficiently small patch of $S^3_R$ is $c$.
- **Proper time.** Along a worldline $(\tau, q(\tau))$, proper time is $d\tau_{\text{proper}}^2 = d\tau^2 - ds_{S^3_R}^2/c^2$. For a particle moving at spatial arc speed $v = ds_{S^3}/d\tau$, this gives $d\tau_{\text{proper}} = d\tau \sqrt{1 - v^2/c^2}$ — the standard Lorentz factor $\gamma$. Time dilation is reproduced exactly.
- **Light cones and local causality.** At each event the tangent space is Minkowski, so light cones separate causal from acausal pairs of nearby events in the usual way. No particle with nonzero rest mass can reach $v = c$ without infinite energy.
- **Global causal order.** Because the spatial slices are compact and $\tau$ is globally defined, the foliation provides a global time function. Causal order between non-infinitesimally-separated events combines the local light-cone structure with the $\tau$ ordering of slices.

### The speed of light is a limit

Within this framework, the speed of light $c$ is a true kinematic limit: no massive particle can reach or exceed it, exactly as in Special Relativity. Faster-than-light travel is **not** a feature of the theory. An earlier attempt to frame $c$ as merely a unit-conversion factor required a Euclidean bulk signature that contradicts observed time dilation; the Lorentzian signature adopted here restores agreement with experiment at the cost of abandoning that possibility. See [Faster Than Light](FasterThanLight.md) for the historical context of this choice.

## Novelty

Each ingredient of this theory has precedent in the literature:

- **Quaternions as a description of spatial geometry** — unit quaternions naturally parameterize the 3-sphere $S^3$; explored since Hamilton.
- **Closed $k=+1$ FLRW cosmology** — standard General Relativity solution with positively curved spatial slices.
- **Schwarzschild radius as cosmic scale** — central to "universe as a black hole" models (Pathria, Good, and others).
- **Expansion without a cosmological constant** — pursued by several alternative cosmologies.

What is novel is the **specific synthesis**: a closed FLRW universe in which the spatial scale $R(\tau)$ is identified with the Schwarzschild radius of the total mass of the universe, $R = 2Gm/c^2$, and cosmic expansion is driven entirely by energy-to-mass conversion via the first-order kinetic law $dR/d\tau = c(1 - R/R_{\max})$. This replaces the Friedmann equation with a single conversion-rate equation and eliminates dark energy.

## Observable Implications

Several features distinguish this framework from standard ΛCDM cosmology:

- **No cosmological constant** — Expansion is driven by energy-to-mass conversion rather than dark energy. The predicted expansion history $R(\tau) = R_{\max}(1 - e^{-c\tau/R_{\max}})$ differs from ΛCDM, particularly at late times when $R$ asymptotically approaches $R_{\max}$ and $H \to 0$ rather than approaching a de Sitter attractor.
- **Finite maximum radius** — The universe has a definite upper bound $R_{\max} = \frac{2GE_{\text{total}}}{c^4}$, implying a closed spatial geometry ($\Omega_k < 0$). This could leave imprints in the cosmic microwave background (CMB) as suppressed large-angle correlations or matched-circle signatures.
- **Schwarzschild radius coincidence** — The observable universe's radius should track the Schwarzschild radius of its total mass content. This relationship can be checked against current cosmological data for the observable mass-energy density and Hubble radius.
- **Single free parameter** — Unlike ΛCDM's two density parameters ($\Omega_m$, $\Omega_\Lambda$), the expansion history is fixed by the single parameter $R_{\max}$ (equivalently $E_{\text{tot}}$), making the theory highly falsifiable.

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

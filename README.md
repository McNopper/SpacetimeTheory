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

The curvature radius $R(\tau)$ of the spatial $S^3$ is not a constant: it evolves according to the standard Friedmann equation applied to the closed FLRW metric (see [Foundations](#foundations)). At every cosmic time, the theory imposes the Schwarzschild-radius consistency relation between $R$ and the total mass-energy content,

$$R(\tau) = \frac{2G m(\tau)}{c^2},$$

where $m(\tau)$ is the total mass-energy within the spatial slice, expressed in mass units. In near-critical FLRW this relation is satisfied automatically up to factors of order unity; it does not supply an independent dynamical equation for $R$.

| State | Description | Hypersphere |
|-------|-------------|-------------|
| Singularity | No matter yet | $R = 0$ |
| Big Bang | Matter and radiation era begins | $R$ starts growing |
| Present | Matter + $\Lambda$-dominated FLRW expansion | $R$ close to the Hubble radius |
| Future | Late-time de Sitter attractor | $R$ grows without bound |

Cosmic expansion is governed by the standard Friedmann equation on the closed $S^3$ spatial geometry (matter, radiation, and cosmological constant); see [Foundations](#foundations).

## Foundations

To make the preceding picture a well-defined dynamical framework rather than a single static hypersphere, the theory rests on the following structural commitments.

### Foliation of spacetime

Spacetime is a four-dimensional Lorentzian manifold foliated by spatial three-spheres of increasing radius:

$$\mathcal{M} = \mathbb{R}_\tau \times S^3_{R(\tau)}, \qquad R: \tau \mapsto R(\tau) \ge 0$$

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

The dynamics of $R(\tau)$ is the standard **Friedmann equation** obtained from the Einstein field equations applied to the closed FLRW metric above. With matter density $\rho_m$, radiation density $\rho_r$, and a cosmological constant $\Lambda$,

$$\left(\frac{1}{R}\frac{dR}{d\tau}\right)^{\!2} = \frac{8\pi G}{3}\bigl(\rho_m + \rho_r\bigr) - \frac{c^2}{R^2} + \frac{\Lambda c^2}{3}.$$

In terms of present-day density parameters $\Omega_m, \Omega_r, \Omega_k \le 0, \Omega_\Lambda$ (with $\Omega_m + \Omega_r + \Omega_k + \Omega_\Lambda = 1$ and $\Omega_k = -c^2/(H_0^2 R_0^2)$), the Hubble parameter as a function of redshift $z = R_0/R - 1$ is

$$H(z)^2 = H_0^2\bigl[\,\Omega_m(1+z)^3 + \Omega_r(1+z)^4 + \Omega_k(1+z)^2 + \Omega_\Lambda\,\bigr].$$

This is **closed ΛCDM**: the geometric core of the theory (the $S^3$ spatial slices parameterized by unit quaternions) is retained, while the cosmological dynamics is supplied by the Einstein field equations applied to that geometry.

> **Historical note.** An earlier version of this write-up proposed the first-order "conversion-kinetic" law $dR/d\tau = c(1 - R/R_{\max})$, derived by dimensional analysis from the assumption that energy converts into mass at a rate proportional to the un-converted energy remaining. That law is not a solution of the Einstein equations and predicts a monotonically decelerating expansion, $q(z) = x_0/(1+z-x_0) > 0$. A direct fit to 1580 Pantheon+SH0ES Type Ia supernovae yields $\Delta\chi^2 \approx +237$ versus flat $\Lambda$CDM, rejecting the kinetic law at roughly 15$\sigma$. It is retained here only for historical reference and has been replaced by the Friedmann equation above.

### Why still "quaternion-hypersphere"?

Under this replacement, the distinctive claims of the theory are:

1. **Closed spatial topology $S^3$**, naturally parameterized by unit quaternions. The closed ($k=+1$) FLRW branch is a *choice* within standard GR; most modern fits (Pantheon+ alone, Planck + BAO) are consistent with $\Omega_k$ small but not manifestly zero, and the theory predicts $\Omega_k < 0$ strictly.
2. **Schwarzschild-radius identification** $R(\tau) = 2Gm(\tau)/c^2$ as a consistency condition between the total mass-energy content and the curvature radius. This is a numerological coincidence in any near-critical FLRW model; whether it has independent dynamical content is an open question.
3. **Arrow of time from monotonic expansion.** Cosmic time $\tau$ is distinguished by the monotonic growth of $R(\tau)$ (Friedmann solutions with $\Lambda > 0$ and $\Omega_m < 1$ are monotonic to the future).
4. **A definition of time tied to the existence of matter.** Local clocks are physical systems built from matter; in the pre-matter limit there is nothing to register a duration, and cosmic $\tau$ becomes operationally void. This is a philosophical stance, not an additional dynamical equation.

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
- **Closed $k=+1$ FLRW cosmology** — a standard solution of the Einstein field equations with positively curved spatial slices.
- **Schwarzschild radius as cosmic scale** — central to "universe as a black hole" models (Pathria, Good, and others).

What this write-up contributes is a **specific synthesis and an operational stance on time**: the closed ($k=+1$) FLRW branch of GR is adopted as the global geometry; the spatial slices are explicitly parameterized as unit-quaternion 3-spheres; the curvature radius is identified with the Schwarzschild radius $R(\tau) = 2Gm(\tau)/c^2$ of the total mass-energy content; and cosmic time $\tau$ is defined operationally as the parameter labelling these spatial slices, requiring matter for its physical realization. The cosmological dynamics itself is standard $\Lambda$CDM on the closed $S^3$, after the original "conversion-kinetic" law was found to be empirically excluded (see the historical note in [Foundations](#foundations)).

## Observable Implications

The theory, in its corrected form, is a closed-$\Lambda$CDM model. Distinguishing predictions from flat $\Lambda$CDM are therefore restricted to curvature-sensitive observables:

- **Strictly closed spatial geometry ($\Omega_k < 0$)** — the theory predicts $k = +1$, not $k = 0$. The most stringent current bound, from Planck 2018 + BAO, is $\Omega_k = 0.001 \pm 0.002$, consistent with $\Omega_k = 0$ and with a small negative $\Omega_k$. A future measurement establishing $\Omega_k < 0$ at high significance would support the theory; a measurement establishing $\Omega_k > 0$ would falsify it.
- **Schwarzschild-radius consistency** — the identification $R(\tau) = 2Gm(\tau)/c^2$ couples the total mass-energy content to the curvature radius today. In near-critical FLRW this relation is automatically satisfied to within factors of order unity and therefore does not by itself constitute an independent test; it acquires predictive content only if combined with an independent dynamical derivation, which is not provided here.
- **Matched-circle / large-angle CMB signatures** — a finite closed universe with $R_0$ below the particle horizon could imprint matched circles or suppressed low-$\ell$ power in the CMB. Existing searches constrain the antipode to be beyond the last-scattering surface; consistency with Planck therefore requires $|\Omega_k| \lesssim \text{few} \times 10^{-3}$.
- **Supernova Hubble diagram** — with closed-FLRW $\Lambda$CDM dynamics, the theory fits Pantheon+SH0ES at the same level as flat $\Lambda$CDM (see [Outlook](Outlook.md)). This is a constraint satisfied, not a distinctive prediction.

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

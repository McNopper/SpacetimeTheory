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

## Abstract

This note is a **conceptual synthesis**, not a new dynamical theory. It assembles four ingredients — (i) a quaternionic parameterization of the spatial three-sphere $S^3$, (ii) the closed $k=+1$ branch of Friedmann–Lemaître–Robertson–Walker (FLRW) cosmology, (iii) the Schwarzschild-radius identification $R \sim 2Gm/c^2$ relating the curvature radius to the total mass-energy content (an order-unity coincidence in any near-critical FLRW cosmology), and (iv) a relational stance in which cosmic time is defined operationally through matter-built clocks — into a single self-consistent picture. Each ingredient has independent precedent (quaternions on $S^3$: Hamilton; closed FLRW: Friedmann, Lemaître; Schwarzschild-scale cosmology: Pathria, Good, Stuckey, Popławski, Melia; relational time: Mach, Barbour, Rovelli). The combination is offered as a pedagogical and philosophical reframing of standard closed-$\Lambda$CDM, not as a source of new empirical predictions.

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

The quaternion norm $|q| = R$ is identified, to within order-unity factors in near-critical FLRW, with the Schwarzschild radius of the total mass $m$ of the universe, so that

$$E \sim \frac{c^4}{2G} R$$

relates the mass-energy content to the curvature radius (with $G$ the gravitational constant). This is an approximate consistency relation inherited from the near-critical-density regime; it is not imposed here as an exact dynamical law.

## Expansion of the Universe

The curvature radius $R(\tau)$ of the spatial $S^3$ is not a constant: it evolves according to the standard Friedmann equation applied to the closed FLRW metric (see [Foundations](#foundations)). In a near-critical FLRW cosmology the curvature radius and the Schwarzschild radius of the total mass-energy content agree to within factors of order unity,

$$R(\tau) \sim \frac{2G m(\tau)}{c^2},$$

where $m(\tau)$ is the total mass-energy within the spatial slice, expressed in mass units. This is an approximate consistency relation rather than an independent dynamical equation for $R$; it is satisfied automatically whenever the matter density is close to critical.

| State | Description | Hypersphere |
|-------|-------------|-------------|
| Initial singularity | Diverging density, zero volume | $R = 0$ |
| Early universe | Radiation- then matter-dominated FLRW expansion | $R$ grows |
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

This is exactly the **closed ($k = +1$) Friedmann–Lemaître–Robertson–Walker** metric, supplemented by the order-unity consistency relation $R(\tau) \sim 2Gm(\tau)/c^2$ and the growth law below. Special and General Relativity are recovered in full within this geometry: Lorentz invariance holds locally on any sufficiently small patch, time dilation and length contraction follow from the Minkowski tangent-space structure, and light cones exist at every event.

### Comoving map

Points on different slices are identified by their hyperspherical angles. A **comoving observer** at fixed angular coordinates $(\chi_0, \theta_0, \phi_0)$ traces the worldline

$$q_{\text{comoving}}(\tau) = R(\tau) \cdot \hat{q}_0, \qquad \hat{q}_0 = (\cos\chi_0,\, \sin\chi_0\sin\theta_0\cos\phi_0,\, \sin\chi_0\sin\theta_0\sin\phi_0,\, \sin\chi_0\cos\theta_0)$$

This is the FLRW comoving map: angular coordinates are conserved, and physical arc length between two comoving observers is $R(\tau)\,\Delta\chi$, which grows with $R$. Cosmic expansion is this scaling of arc lengths, not a local velocity of matter.

### Dynamical law for $R(\tau)$

The dynamics of $R(\tau)$ is the standard **Friedmann equation** obtained from the Einstein field equations applied to the closed FLRW metric above. With matter density $\rho_m$, radiation density $\rho_r$, and a cosmological constant $\Lambda$,

$$\left(\frac{1}{R}\frac{dR}{d\tau}\right)^{\!2} = \frac{8\pi G}{3}\bigl(\rho_m + \rho_r\bigr) - \frac{c^2}{R^2} + \frac{\Lambda c^2}{3}.$$

In terms of present-day density parameters $\Omega_m, \Omega_r, \Omega_k, \Omega_\Lambda$ satisfying $\Omega_m + \Omega_r + \Omega_k + \Omega_\Lambda = 1$, with $\Omega_k = -kc^2/(H_0^2 R_0^2)$, the Hubble parameter as a function of redshift $z = R_0/R - 1$ is

$$H(z)^2 = H_0^2\bigl[\,\Omega_m(1+z)^3 + \Omega_r(1+z)^4 + \Omega_k(1+z)^2 + \Omega_\Lambda\,\bigr].$$

The synthesis adopts the closed branch $k=+1$ (i.e. $\Omega_k < 0$) as a modeling choice.

This is **closed ΛCDM**:the geometric core of the synthesis (the $S^3$ spatial slices parameterized by unit quaternions) is retained, while the cosmological dynamics is supplied by the Einstein field equations applied to that geometry.

### Why still "quaternion-hypersphere"?

The distinctive features of this synthesis are:

1. **Closed spatial topology $S^3$**, naturally parameterized by unit quaternions. The closed ($k=+1$) FLRW branch is a *choice* within standard GR; current Planck + BAO data ($\Omega_k = 0.0007 \pm 0.0019$) are consistent with flat or slightly-closed geometry. The synthesis adopts $\Omega_k < 0$ ($k=+1$ closed) as a modeling choice, not a derived prediction.
2. **Schwarzschild-radius identification** $R(\tau) \sim 2Gm(\tau)/c^2$ as a suggestive numerical coincidence between the total mass-energy content and the curvature radius, holding to within factors of order unity in any near-critical FLRW cosmology. It is not claimed here to be an exact dynamical law; whether it can be promoted to one is an open question.
3. **Arrow of time from monotonic expansion.** Cosmic time $\tau$ is distinguished by the monotonic growth of $R(\tau)$ (Friedmann solutions with $\Lambda > 0$ and $\Omega_m < 1$ are monotonic to the future).
4. **A definition of time tied to the existence of matter.** Local clocks are physical systems built from matter; in the pre-matter limit there is nothing to register a duration, and cosmic $\tau$ becomes operationally void. This is a philosophical stance, not an additional dynamical equation.

### Light, proper time, and causal structure

Because the metric is Lorentzian, all standard relativistic results hold:

- **Light propagation.** Photons follow null geodesics: $ds^2 = 0$, i.e. $c\, d\tau = ds_{S^3_R}$ along the trajectory. The speed of light on any sufficiently small patch of $S^3_R$ is $c$.
- **Proper time.** Along a worldline $(\tau, q(\tau))$, proper time is $d\tau_{\text{proper}}^2 = d\tau^2 - ds_{S^3_R}^2/c^2$. For a particle moving at spatial arc speed $v = ds_{S^3}/d\tau$, this gives $d\tau_{\text{proper}} = d\tau \sqrt{1 - v^2/c^2}$ — the standard Lorentz factor $\gamma$. Time dilation is reproduced exactly.
- **Light cones and local causality.** At each event the tangent space is Minkowski, so light cones separate causal from acausal pairs of nearby events in the usual way. No particle with nonzero rest mass can reach $v = c$ without infinite energy.
- **Global causal order.** Because the spatial slices are compact and $\tau$ is globally defined, the foliation provides a global time function. Causal order between non-infinitesimally-separated events combines the local light-cone structure with the $\tau$ ordering of slices.

### The speed of light is a limit

Within this framework, the speed of light $c$ is a true kinematic limit: no massive particle can reach or exceed it, exactly as in Special Relativity. Faster-than-light travel is **not** a feature of the theory. See [Faster Than Light](FasterThanLight.md) for why the Lorentzian structure forces this conclusion.

## Novelty

This write-up is **a synthesis**, not a new physical theory. Each ingredient has independent precedent in the literature:

- **Quaternions as a description of spatial geometry.** Unit quaternions naturally parameterize the 3-sphere $S^3$ via $|q|^2 = R^2$; this goes back to Hamilton (1843) and is standard in geometry, robotics, and rotation theory. In this write-up the quaternion multiplicative structure is *not* used as a dynamical object — it enters only as a coordinate choice equivalent to ordinary hyperspherical coordinates $(\chi,\theta,\phi)$ on $S^3$.
- **Closed ($k=+1$) FLRW cosmology.** A standard solution of the Einstein field equations with positively curved spatial slices (Friedmann 1922; Lemaître 1927). The closed branch has remained on the menu of cosmological models throughout; Planck 2018 + BAO currently constrain $\Omega_k = 0.0007 \pm 0.0019$, consistent with either flat or slightly closed.
- **Schwarzschild radius as cosmic scale** ("universe as a black hole"). First proposed by Pathria (*Nature* 240, 298, 1972) and Good (1972); developed subsequently by Stuckey (*Am. J. Phys.* 62, 788, 1994), Popławski (in the torsion/Einstein–Cartan context, 2010–), and Melia's $R_h = ct$ program. The identification $R \sim 2Gm_{\text{tot}}/c^2$ is a near-critical-FLRW coincidence, because $\rho_{\text{crit}} = 3H_0^2/8\pi G$ gives $2Gm/c^2 \sim c/H_0$ up to order-unity factors.
- **Relational time / time emerging with matter.** Mach's principle; the Leibniz–Clarke correspondence; and, closer to present-day physics, Barbour (*The End of Time*, 1999) and Rovelli's relational / thermal-time programme (e.g. *Forget time*, 2009). The "no clocks without matter" stance in this write-up is a particular reading of that broader tradition, not an independent discovery.

What this write-up *contributes* is the **specific combination**: the four ingredients above are assembled into a single, explicitly-written-out, internally-consistent picture, with the Lorentzian-signature closed-FLRW metric as the common scaffolding, quaternion norms as the spatial parameterization, the Schwarzschild radius identification as a consistency relation, and the relational stance supplying the operational meaning of cosmic time $\tau$. No new dynamical equation is proposed; no prediction distinct from standard closed-$\Lambda$CDM is derived. The value of the synthesis, if any, is pedagogical and foundational, not empirical.

## Observable Status

The theory is empirically **closed-$\Lambda$CDM** and therefore shares all of its successes and tensions. It is neither predicted to agree with the data any better nor worse than that baseline. Relevant empirical checkpoints, framed as consistency conditions rather than distinctive predictions:

- **Spatial curvature sign.** The write-up privileges $k=+1$; current Planck + BAO data give $\Omega_k = 0.0007 \pm 0.0019$, consistent with zero at $\sim 10^{-3}$ precision. A future definitive detection of $\Omega_k > 0$ would refute the $k=+1$ choice; a definitive detection of $\Omega_k < 0$ would align with it. The closed branch is at present a *choice within* standard GR, not a distinctive prediction.
- **Schwarzschild-radius consistency.** $R_0 \sim 2Gm_{\text{tot}}/c^2$ is satisfied automatically in any near-critical FLRW cosmology to within factors of order unity. It does not currently function as an independent empirical test; promoting it to a dynamical constraint would require additional theoretical work not carried out here.
- **Supernova Hubble diagram.** Fitting the closed-$\Lambda$CDM predictions of this framework to 1580 Pantheon+SH0ES Type Ia supernovae yields $\chi^2 = 681.3$, indistinguishable from flat $\Lambda$CDM at this data set's precision (see [Outlook](Outlook.md)). Consistency achieved, nothing predicted.
- **CMB topology.** A closed universe with antipode within the last-scattering sphere would leave matched-circle signatures; null results from WMAP/Planck searches imply the antipode lies beyond the observable horizon, consistent with $|\Omega_k|$ small (including zero).

## References

### Scientific literature

- Barbour, J. (1999). *The End of Time: The Next Revolution in Physics*. Oxford University Press.
- Friedmann, A. (1922). "Über die Krümmung des Raumes". *Zeitschrift für Physik* 10, 377.
- Good, I. J. (1972). "Chinese universes". *Physics Today* 25(7), 15.
- Hamilton, W. R. (1844). "On quaternions". *Philosophical Magazine* 25(3), 489.
- Lemaître, G. (1927). "Un univers homogène de masse constante et de rayon croissant…". *Annales de la Société Scientifique de Bruxelles* A47, 49.
- Melia, F. (2007). "The cosmic horizon". *Mon. Not. R. Astron. Soc.* 382, 1917.
- Pathria, R. K. (1972). "The universe as a black hole". *Nature* 240, 298.
- Planck Collaboration (2020). "Planck 2018 results. VI. Cosmological parameters". *Astronomy & Astrophysics* 641, A6.
- Popławski, N. (2010). "Cosmology with torsion: an alternative to cosmic inflation". *Physics Letters B* 694, 181.
- Rovelli, C. (2011). "Forget time". *Foundations of Physics* 41, 1475.
- Scolnic, D. et al. (2022). "The Pantheon+ analysis: the full data set and light-curve release". *Astrophys. J.* 938, 113.
- Stuckey, W. M. (1994). "The observable universe inside a black hole". *American Journal of Physics* 62, 788.

### Background references

- [Cartesian coordinate system](https://en.wikipedia.org/wiki/Cartesian_coordinate_system)
- [Cosmic microwave background](https://en.wikipedia.org/wiki/Cosmic_microwave_background)
- [Cosmological constant](https://en.wikipedia.org/wiki/Cosmological_constant)
- [Gravitational constant](https://en.wikipedia.org/wiki/Gravitational_constant)
- [Lambda-CDM model](https://en.wikipedia.org/wiki/Lambda-CDM_model)
- [Mass–energy equivalence](https://en.wikipedia.org/wiki/Mass%E2%80%93energy_equivalence)
- [N-sphere](https://en.wikipedia.org/wiki/N-sphere)
- [Quaternion](https://en.wikipedia.org/wiki/Quaternion)
- [Schwarzschild radius](https://en.wikipedia.org/wiki/Schwarzschild_radius)
- [Spacetime](https://en.wikipedia.org/wiki/Spacetime)
- [Special relativity](https://en.wikipedia.org/wiki/Special_relativity)
- [Time](https://en.wikipedia.org/wiki/Time)

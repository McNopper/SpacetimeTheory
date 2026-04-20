# Spacetime Theory

### *Empathy with the Universe*

by *Norbert Nopper*

- [Quaternion-Hypersphere Theory](README.md)
- **[What is Time?](#what-is-time)**
- [Faster Than Light](FasterThanLight.md)
- [Outlook](Outlook.md)
- [Summary](Summary.md)

## What is Time?

### *Time is the foliation parameter*

In this framework, time is the **cosmic parameter** $\tau$ that indexes the foliation of spacetime:

$$\mathcal{M} = \mathbb{R}_\tau \times S^3_{R(\tau)}$$

Each slice $S^3_{R(\tau)}$ is a closed three-sphere of radius $R(\tau)$. Time is not a coordinate on the sphere — it labels *which* sphere we are on. As $\tau$ grows, the radius $R(\tau)$ grows, and the universe expands.

## Premise

A spatial point in the universe is represented as a quaternion $q = \xi + x\mathbf{i} + y\mathbf{j} + z\mathbf{k}$ lying on the spatial three-sphere $S^3_R$:

$$|q| = \sqrt{\xi^2 + x^2 + y^2 + z^2} = R$$

The four components are all spatial: $\xi$ is a fourth embedding coordinate in the auxiliary four-dimensional Euclidean space used to realize $S^3_R$. The full spacetime metric is Lorentzian,

$$ds^2 = -c^2\, d\tau^2 + ds^2_{S^3_R}$$

so Special and General Relativity hold in full. See [Foundations](README.md#foundations).

## Two kinds of time

It is useful to distinguish three quantities that have historically been lumped together as "time":

- $\tau$ — **cosmic time**, the foliation parameter, the clock reading of a comoving observer (one at rest on a fixed angular position $(\chi_0,\theta_0,\phi_0)$ on the sphere).
- $\tau_{\text{proper}}$ — **proper time** along an arbitrary worldline, given by $d\tau_{\text{proper}}^2 = d\tau^2 - ds_{S^3_R}^2/c^2$. Moving observers accumulate $\tau_{\text{proper}} < \tau$ — the standard Lorentz time dilation.
- $\xi$ — the fourth **spatial** embedding coordinate of $q$, with $\xi = R\cos\chi$. This is *not* time. It is a geometric label on the spatial sphere.

## The spatial constraint

The quaternion norm constraint $|q| = R$ is a **spatial** statement: it fixes $q$ on the three-sphere. Decomposing into the embedding coordinate $\xi$ and the Cartesian spatial distance $r = \sqrt{x^2 + y^2 + z^2}$:

$$\xi^2 + r^2 = R^2$$

This is the Pythagorean relation on the 4D embedding space, not a time–space trade-off. Both $\xi$ and $r$ are spatial lengths; they together locate a point on $S^3_R$ but they do not constrain how much time has passed.

Since $R = \frac{2Gm}{c^2}$, the spatial scale grows as mass forms:

$$\xi^2 + r^2 = \left(\frac{2Gm}{c^2}\right)^2$$

More mass means a larger spatial sphere — and more room.

## Degrees of Freedom

The quaternion constraint $|q| = R$ reduces the four components $(\xi, x, y, z)$ to three independent spatial degrees of freedom. A point on $S^3_R$ is specified by three hyperspherical angles $(\chi, \theta, \phi)$ with

$$\xi = R\cos\chi, \qquad r = R\sin\chi$$

All three angles are spatial. The cosmic time $\tau$ is the fourth, independent, Lorentzian coordinate of spacetime.

## Proper time along a worldline

For an observer moving with spatial velocity $\vec{v}$ on $S^3_R$ (arc speed $v = |ds_{S^3}/d\tau|$), proper time satisfies

$$\frac{d\tau_{\text{proper}}}{d\tau} = \sqrt{1 - \frac{v^2}{c^2}}$$

This is the ordinary Lorentz factor. At $v \to c$ the factor vanishes — time dilation is infinite, the classical light-speed barrier. Time is thus not observer-relative in the S³ sense of an earlier version of this theory; it is observer-relative in the standard Special-Relativistic sense.

## Why time emerges with matter

At $\tau = 0$ no mass has formed, so $R(0) = 0$: the spatial universe is a point, and there is no room for anything to happen. As $\tau$ advances the universe expands according to the Friedmann equation, the radius $R(\tau)$ grows, space opens up, and cosmic time $\tau$ accumulates. In this sense time *emerges* together with a nontrivial spatial universe: the existence of a meaningful temporal axis presupposes matter — physical clocks are built from matter — and a nontrivial spatial universe for those clocks to reside in.

This is a **relational** rather than an absolute conception of time, and it stands in a well-known tradition:

- **Mach's principle** and the **Leibniz–Clarke correspondence** (1715–16) argue that duration, like position, is meaningful only relative to physical contents.
- **Barbour** (*The End of Time*, 1999) pushes this to its limit: on his view there is no fundamental time parameter at all, only correlations between configurations of matter.
- **Rovelli**'s relational and thermal-time programme (e.g. *Forget time*, 2009) reconstructs the "flow of time" as a thermodynamic property of the local observer rather than a background feature of spacetime.

The stance adopted here is more conservative than either Barbour's or Rovelli's: the cosmic foliation parameter $\tau$ is retained as a mathematical label, but its *operational* meaning requires matter-built clocks. In the pre-matter limit ($R \to 0$) there is no physical realization of a clock and therefore no operationally defined duration; cosmic $\tau$ becomes mathematically well-defined but operationally void. The philosophical content is the operational coupling of time to matter; the dynamical content is standard FLRW cosmology.

## References

### Scientific and philosophical literature

- Barbour, J. (1999). *The End of Time: The Next Revolution in Physics*. Oxford University Press.
- Leibniz, G. W. & Clarke, S. (1715–16). *The Leibniz–Clarke Correspondence*.
- Mach, E. (1883). *Die Mechanik in ihrer Entwicklung*.
- Rovelli, C. (2011). "Forget time". *Foundations of Physics* 41, 1475.

### Background references

- [Friedmann–Lemaître–Robertson–Walker metric](https://en.wikipedia.org/wiki/Friedmann%E2%80%93Lema%C3%AEtre%E2%80%93Robertson%E2%80%93Walker_metric)
- [Gravitational constant](https://en.wikipedia.org/wiki/Gravitational_constant)
- [Lorentz factor](https://en.wikipedia.org/wiki/Lorentz_factor)
- [N-sphere](https://en.wikipedia.org/wiki/N-sphere)
- [Proper time](https://en.wikipedia.org/wiki/Proper_time)
- [Quaternion](https://en.wikipedia.org/wiki/Quaternion)
- [Schwarzschild radius](https://en.wikipedia.org/wiki/Schwarzschild_radius)
- [Speed of light](https://en.wikipedia.org/wiki/Speed_of_light)
- [Time](https://en.wikipedia.org/wiki/Time)

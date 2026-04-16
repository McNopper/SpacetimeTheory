# Faster Than Light 🚀💫

### *beyond light speed is possible*

by *Norbert Nopper*

## The Light Speed Barrier in Special Relativity

In Einstein's Special Relativity, the Minkowski signature $(-,+,+,+)$ produces the Lorentz factor:

$$\gamma = \frac{1}{\sqrt{1 - \dfrac{v^2}{c^2}}}$$

where

- $v$ is the velocity of the object
- $c$ is the speed of light
- $\gamma$ is the Lorentz factor

As $v \to c$, the Lorentz factor $\gamma \to \infty$. The relativistic energy of a massive object is:

$$E = \gamma mc^2$$

where $m$ is the mass of the object. This means accelerating a massive object to the speed of light requires infinite energy — an absolute barrier.

## No Lorentz Factor on S³

In the Quaternion-Hypersphere Theory, the Euclidean signature $(+,+,+,+)$ replaces the Minkowski signature. The fundamental constraint is:

$$(ct)^2 + r^2 = R^2$$

where $r = \sqrt{x^2 + y^2 + z^2}$ is the spatial distance and $R$ is the radius of the hypersphere S³.

The minus sign in $(1 - v^2/c^2)$ that produces the Lorentz factor originates from the Minkowski signature. With a Euclidean signature, this term does not arise. There is no $\gamma$, no divergence at $v = c$, and no infinite energy barrier.

## Dynamics

On S³, the natural paths of free motion are **geodesics** — great circles on the hypersphere. The geometry of a sphere imposes no maximum angular velocity: a particle can traverse a great circle at any speed. No new speed limit emerges from the curvature of S³ itself.

This contrasts with Minkowski spacetime, where the metric signature forces timelike geodesics to remain within light cones. On S³ with Euclidean signature, all directions are equivalent — there is no geometric distinction between "slow" and "fast" paths.

## Energy

In Special Relativity, the energy of a massive object is:

$$E = \gamma m_p c^2 = \frac{m_p c^2}{\sqrt{1 - \dfrac{v^2}{c^2}}}$$

where $m_p$ is the mass of the object. This diverges as $v \to c$ — the infinite energy barrier. To derive the corresponding result on S³, we begin from first principles.

### Lagrangian on S³

A particle of mass $m_p$ moves on S³ of radius $R$. In hyperspherical coordinates $(\chi, \theta, \phi)$, the spacetime coordinates are:

$$ct = R\cos\chi, \qquad r = R\sin\chi$$

where $r$ decomposes further via $\theta$ and $\phi$. The induced metric on S³ is:

$$ds^2 = R^2 \left[ d\chi^2 + \sin^2\chi \left( d\theta^2 + \sin^2\theta \, d\phi^2 \right) \right]$$

The Lagrangian for a free particle on this manifold is:

$$\mathcal{L} = \frac{1}{2} m_p \, g_{ab} \, \dot{q}^a \dot{q}^b = \frac{1}{2} m_p R^2 \left[ \dot{\chi}^2 + \sin^2\chi \left( \dot{\theta}^2 + \sin^2\theta \, \dot{\phi}^2 \right) \right]$$

where dots denote derivatives with respect to an affine parameter $\lambda$.

### Equations of Motion

The Euler-Lagrange equation for $\chi$ (with $\dot{\theta} = \dot{\phi} = 0$ for motion along a single great circle) gives:

$$\ddot{\chi} = 0 \quad \Longrightarrow \quad \chi(\lambda) = \chi_0 + \omega\lambda$$

Free particles trace great circles at constant angular velocity $\omega$ — the geodesics of S³.

### Kinetic Energy

The kinetic energy follows directly:

$$E_{\text{kin}} = \frac{1}{2} m_p R^2 \omega^2 = \frac{1}{2} m_p v_{S^3}^2$$

where $v_{S^3} = R\omega$ is the arc velocity on S³. This is the Newtonian form:

- Quadratic growth with speed — no divergence at any velocity
- No Lorentz factor $\gamma$ appears
- The conjugate momentum $p_\chi = m_p R^2 \omega$ is linear in $\omega$

For the general case (motion in all three angular directions), the energy is:

$$E_{\text{kin}} = \frac{1}{2} m_p R^2 \left[ \dot{\chi}^2 + \sin^2\chi \left( \dot{\theta}^2 + \sin^2\theta \, \dot{\phi}^2 \right) \right]$$

which remains quadratic in the angular velocities.

### Why No Lorentz Factor

In Special Relativity, the Lorentz factor arises from two features of the Minkowski metric:

1. The minus sign in $ds^2 = -c^2 dt^2 + dr^2$
2. The four-velocity normalization $g_{\mu\nu} u^\mu u^\nu = -c^2$

Together, these produce $\gamma = 1/\sqrt{1 - v^2/c^2}$ and the energy divergence at $v = c$.

On S³ with Euclidean signature $(+,+,+,+)$:

1. The metric has all positive terms: $ds^2 = R^2 d\chi^2 + \ldots$
2. The quantity $g_{ab} u^a u^b = v_{S^3}^2$ is determined by initial conditions, not fixed by a constraint

Neither ingredient of the Lorentz factor exists. The energy is $\frac{1}{2} m_p v_{S^3}^2$ for all speeds, with no barrier at $v_{S^3} = c$ or anywhere else.

## Causality

In Special Relativity, light cones separate cause from effect. Faster-than-light signals could reach events outside the light cone, potentially violating causal order.

On S³, causality does not depend on a speed limit. Instead, it emerges from the monotonic growth of $R$:

- Every event belongs to an epoch defined by $R$
- $R$ only grows as energy converts to mass
- An event at $R_1$ is strictly before an event at $R_2 > R_1$
- Returning to a smaller $R$ would require mass to convert back to energy, which is cosmologically suppressed

Causal order is preserved by the **direction of the universe's expansion**, not by a local speed limit. A particle can move at any speed on S³ at a given $R$, but it cannot travel backward to an earlier epoch.

This has a further implication: if $R$ were to shrink (as in a cyclic scenario), causal ordering would break down — events could no longer be strictly ordered by epoch. Since causality is empirically observed, the monotonic growth of $R$ is not merely an assumption but a requirement of the theory. This favors the stable scenario described in the parent theory, where the universe remains at $R_{\max}$ once all energy has converted to mass.

## Summary

What the theory permits:

- Moving faster than light through space at a given epoch
- Arriving at distant locations in less time than light would

What the theory does not permit:

- Traveling backward in time — this would require $R$ to shrink
- Causal paradoxes — epochs are strictly ordered by $R$

Faster-than-light travel on S³ is a question of propulsion, not of fundamental physics. The destination is the future, never the past.

## References

- [Quaternion-Hypersphere Theory of Spacetime](README.md)
- [What is Time?](WhatIsTime.md)
- [Lorentz factor](https://en.wikipedia.org/wiki/Lorentz_factor)
- [Faster-than-light](https://en.wikipedia.org/wiki/Faster-than-light)

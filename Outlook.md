# Spacetime Theory

### *Empathy with the Universe*

by *Norbert Nopper*

- [Quaternion-Hypersphere Theory](README.md)
- [What is Time?](WhatIsTime.md)
- [Faster Than Light](FasterThanLight.md)
- **[Outlook](#outlook)**
- [Summary](Summary.md)

## Outlook

### *Where the theory goes from here*

The Quaternion-Hypersphere Theory of Spacetime is a self-contained geometric framework: a Lorentzian foliation $\mathcal{M} = \mathbb{R}_\tau \times S^3_{R(\tau)}$ with closed ($k=+1$) FLRW metric $ds^2 = -c^2\, d\tau^2 + ds^2_{S^3_R}$, spatial slices parameterized by unit quaternions, $R$ identified with the Schwarzschild radius of the total mass of the universe, and expansion dynamics governed by the standard Friedmann equation applied to this geometry (see [Foundations](README.md#foundations)).

Because the signature is Lorentzian, Special and General Relativity are built in — Lorentz invariance, time dilation, light cones, and the $c$-limit are not open questions. Because the cosmological dynamics is standard $\Lambda$CDM on a closed $S^3$, the expansion history fits Type Ia supernovae at the same level as flat $\Lambda$CDM. What remains open is **empirical**: whether the theory's distinctive claims — strictly closed spatial geometry ($\Omega_k < 0$), the Schwarzschild-radius consistency $R(\tau) = 2Gm(\tau)/c^2$, and observable consequences of finite closed topology — are borne out by data.

## Spatial Curvature: $\Omega_k < 0$?

The theory predicts $k = +1$ strictly. Current constraints:

- Planck 2018 temperature + polarization alone: $\Omega_k = -0.044^{+0.018}_{-0.015}$ (mild preference for closed, driven by the lensing amplitude).
- Planck 2018 + BAO: $\Omega_k = 0.0007 \pm 0.0019$ (consistent with flat).

A future CMB + large-scale-structure measurement that resolves this tension in favour of $\Omega_k < 0$ at high significance would support the theory; one that establishes $\Omega_k > 0$ would falsify it.

## Supernova Hubble Diagram

A direct fit of the closed-FLRW $\Lambda$CDM predictions of this theory to 1580 Pantheon+SH0ES Type Ia supernovae (with diagonal errors) yields

| Model | Free parameters | $\chi^2$ | $\chi^2/\mathrm{dof}$ | Best fit |
|---|---|---|---|---|
| flat $\Lambda$CDM (reference) | $H_0, \Omega_m$ | 681.3 | 0.432 | $H_0 = 73.0$, $\Omega_m = 0.349$ |
| QH-Friedmann, closed | $H_0, \Omega_m, \Omega_k$ | 681.3 | 0.432 | $H_0 = 73.0$, $\Omega_m = 0.349$, $\Omega_k \to 0$ |

Pantheon+ alone does not distinguish between flat and slightly-closed FLRW; this is a consistency check satisfied, not an independent test. The discriminating power on $\Omega_k$ comes from the CMB and BAO.

> **Historical note.** An earlier version of the theory proposed a first-order conversion-kinetic law $dR/d\tau = c(1 - R/R_{\max})$ in place of the Friedmann equation. The same Pantheon+ fit yields $\chi^2 = 918.1$, a $\Delta\chi^2 \approx +237$ excess over flat $\Lambda$CDM (roughly $15\sigma$). That law is therefore empirically excluded and has been replaced by the Friedmann equation above.

## CMB Signatures of Finite Geometry

A closed $S^3$ geometry with finite $R_0$ has observable consequences in the cosmic microwave background:

- **Suppressed large-angle correlations** — a finite universe suppresses the lowest multipoles of the CMB power spectrum. The observed anomalously low quadrupole ($\ell = 2$) is intriguing but not currently statistically compelling.
- **Matched circles** — in a closed topology with an antipode within the last-scattering surface, the CMB sky would contain pairs of circles with matching temperature patterns. Searches have been carried out and null; they imply the antipode must lie beyond the last-scattering surface, i.e. $|\Omega_k| \lesssim \text{few} \times 10^{-3}$.
- **Curvature** — the spatial-curvature parameter $\Omega_k$ should be strictly negative. Current Planck + BAO bounds are consistent with zero, setting a lower bound on $R_0$.

## Schwarzschild-Radius Consistency

The theory identifies $R_0$ with the Schwarzschild radius of the total mass-energy:

$$R_0 = \frac{2G m_{\text{tot}}}{c^2}.$$

This relation is automatically satisfied to within order-unity factors in any near-critical FLRW cosmology (where the density is close to critical, $\rho_{\text{crit}} = 3H_0^2/8\pi G$, and the curvature radius is close to the Hubble radius $c/H_0$). A sharper test requires:

- careful accounting of total mass-energy (baryonic + dark matter + radiation equivalent + the contribution from $\Lambda$);
- clarifying whether $R_0$ is to be identified with the curvature radius inferred from $\Omega_k$, the Hubble radius, or the particle horizon;
- a derivation that promotes the relation from a coincidence to a dynamical consequence.

## Gravitational Phenomena

Local gravity is standard General Relativity on the $S^3_R$ background. Solar-system, binary-pulsar, LIGO/Virgo, and Event Horizon Telescope tests apply unchanged; no deviation is predicted at any currently accessible precision. Confirming that embedding the Schwarzschild / Kerr solutions into the cosmological $S^3_R$ background introduces no detectable corrections is a minor consistency task.

## Summary of Empirical Tests

| Area | Predicted quantity | Observational comparison |
|------|-------------------|-------------------------|
| Spatial curvature | $\Omega_k < 0$ strictly | Planck + BAO |
| Expansion history | Closed-FLRW $\Lambda$CDM $H(z)$ | SN Ia (Pantheon+), BAO |
| CMB topology | Matched circles, low-$\ell$ suppression | Planck |
| Schwarzschild consistency | $R_0 = 2Gm_{\text{tot}}/c^2$ | Inferred $m_{\text{tot}}$, $\Omega_k$ |
| Local gravity | Standard GR on $S^3_R$ | Solar-system, LIGO/Virgo, EHT, pulsar timing |

## References

- [Baryon acoustic oscillations](https://en.wikipedia.org/wiki/Baryon_acoustic_oscillations)
- [Cosmic microwave background](https://en.wikipedia.org/wiki/Cosmic_microwave_background)
- [Event Horizon Telescope](https://en.wikipedia.org/wiki/Event_Horizon_Telescope)
- [Friedmann equations](https://en.wikipedia.org/wiki/Friedmann_equations)
- [General relativity](https://en.wikipedia.org/wiki/General_relativity)
- [Gravitational wave](https://en.wikipedia.org/wiki/Gravitational_wave)
- [Hubble's law](https://en.wikipedia.org/wiki/Hubble%27s_law)
- [Kerr metric](https://en.wikipedia.org/wiki/Kerr_metric)
- [Lambda-CDM model](https://en.wikipedia.org/wiki/Lambda-CDM_model)
- [LIGO](https://en.wikipedia.org/wiki/LIGO)
- [Pound–Rebka experiment](https://en.wikipedia.org/wiki/Pound%E2%80%93Rebka_experiment)
- [Schwarzschild metric](https://en.wikipedia.org/wiki/Schwarzschild_metric)
- [Shapiro time delay](https://en.wikipedia.org/wiki/Shapiro_time_delay)
- [Type Ia supernova](https://en.wikipedia.org/wiki/Type_Ia_supernova)

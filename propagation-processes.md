---
title: "How UHECRs propagate to Earth"
description: The physics of UHECR propagation — GZK photopion production, pair production, photodisintegration of nuclei, magnetic deflections in the cosmic web, and cosmogenic neutrinos and photons.
permalink: /propagation/processes/
---

# Propagation: from source to Earth

Between acceleration and detection, a UHECR crosses tens to hundreds of megaparsecs of intergalactic space. That space is not empty: it is filled with the **cosmic microwave background** (CMB, 411 photons/cm³ at T = 2.7 K), the **extragalactic background light** (EBL, the accumulated infrared–optical starlight), and **magnetic fields** organized along the cosmic web. Propagation reshapes the spectrum, the composition, and the arrival directions of everything we detect.

*See the [2D animation](/propagation/) or [3D visualization](/propagation-3d/) of these processes.*

## Energy losses of protons

- **Photopion production (the GZK effect).** Above E ≈ 5×10¹⁹ eV, a CMB photon seen in the proton's rest frame exceeds the pion production threshold: p + γ → Δ⁺ → p π⁰ or n π⁺. Each interaction removes ~20% of the proton's energy, and the loss length drops to ~20 Mpc. Predicted independently by Greisen and by Zatsepin & Kuzmin in 1966, this process guarantees a flux suppression — a proton observed at 10²⁰ eV must come from within the **GZK horizon** of roughly 100–200 Mpc, no matter how powerful more distant sources are.
- **Bethe–Heitler pair production.** Above ~10¹⁸ eV, p + γ_CMB → p + e⁺e⁻ removes ~0.1% of the energy per interaction; its loss length is ~Gpc. This gentler drain shapes the spectrum around the *ankle* and is one interpretation of the *dip* region.
- **Adiabatic losses.** All particles lose energy ∝ (1+z) to cosmological expansion — relevant for distant sources.

## Photodisintegration of nuclei

Nuclei do not photoproduce pions as easily; instead they are **photodisintegrated**. When a CMB or EBL photon reaches ε′ ≈ 10–30 MeV in the nucleus rest frame, it excites the **giant dipole resonance**, and the nucleus evaporates one or more nucleons: A + γ → (A−1) + n, (A−2) + 2n, … The Lorentz factor — energy per nucleon — is roughly conserved, so fragments continue with E/A ≈ const. Iron survives about as far as protons of the same energy, while intermediate-mass nuclei are fragile: propagation naturally reshuffles an injected composition. Combined fits of the Auger spectrum and X<sub>max</sub> data prefer sources injecting intermediate-mass nuclei (N, Si) with hard spectra and a rigidity-dependent maximum energy — an imprint of exactly these processes.

## Magnetic deflections

Charged particles do not travel straight:

- **Extragalactic fields** are ≲ 1 nG in voids and 10–100 nG in filaments and clusters; their strength and filling factor are among the least-known quantities in astrophysics.
- **The Galactic magnetic field** (a few µG, coherent over kpc scales) adds a final, direction-dependent deflection of a few degrees at the highest rigidities.

The deflection scales with **rigidity** R = E/Z:

> δθ ≈ few° × Z × (E / 10²⁰ eV)⁻¹

so a 10²⁰ eV proton points back to within a few degrees of its source, while an iron nucleus of the same energy (Z = 26) is scattered across tens of degrees. Deflections also cause **time delays** of 10³–10⁵ years relative to light — which is why a transient source ([TDE](/sources/tdes/) or [GRB](/sources/grbs/)) is long dark by the time its particles arrive.

## Cosmogenic messengers

The same interactions that drain UHECR energy create secondaries: π⁺ decay yields **cosmogenic neutrinos** (EeV scale), and π⁰ decay feeds **electromagnetic cascades** down to the GeV–TeV gamma-ray band. Neither is deflected, so both point back to their production sites. The still-undetected cosmogenic neutrino flux is a key target for [GRAND, IceCube-Gen2 and POEMMA](/experiments/): its level encodes the UHECR composition, source evolution, and the proton fraction at the highest energies.

## Related

- [What are UHECRs?](/what-are-uhecrs/) — the energy spectrum shaped by these losses
- [Candidate sources](/sources/blazars/) — what the horizon allows
- [Open questions](/open-questions/) — GZK cutoff vs. source exhaustion

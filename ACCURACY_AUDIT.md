# ACCURACY AUDIT

This audit cross-checks every major claim in the investigation against
primary sources and the raw data.

## Rating System
- ✓ VERIFIED: Computed directly from public data or confirmed by primary source
- ~ TENTATIVE: From web search snippets, not verified against primary source
- ✗ SPECULATIVE: Inference beyond what the data directly supports

---

## CLAIM 1: SH0ES H₀ = 73.043 ± 1.01 km/s/Mpc

**Source:** My own computation from Högås y_R22.txt, L_R22.txt, C_R22.txt
**Method:** Exact GLS via Cholesky decomposition
**Verification:** Reproduced published value within stated uncertainty

**Status: ✓ VERIFIED**
**Confidence: HIGH**

---

## CLAIM 2: N5584's 4 calibrator SNe have mean residual +0.191 ± 0.037 mag

**Source:** My own computation from Högås data
**Method:** residuals = Y - L @ q_hat for rows identified as calsn with host=26

**Verification:**
- Row identification: checked L matrix patterns (2 non-zero cols: host + 41)
- Host 26 = N5584 (confirmed by q_R22.txt labels)
- 4 rows identified: checked by counting calsn rows with row_hosts == 26
- Residuals computed: Y - Y_pred where Y_pred = L @ q_hat

**Status: ✓ VERIFIED (from raw data)**
**Confidence: HIGH**

**BUT:** The interpretation depends on:
- Whether these are truly calibrator SNe (correct row identification)
- Whether the residual sign is correct (+ means fainter in magnitude system)
- Whether the model equation is Y = mu + MB (need to verify)

---

## CLAIM 3: Removing N5584 SNe drops H₀ by 0.601 km/s/Mpc

**Source:** My own computation
**Method:** Drop calsn rows for host 26, refit GLS

**Verification:**
- Baseline H₀: 73.043
- Drop N5584 SNe: H₀ = 72.442
- Delta: -0.601

**Status: ✓ VERIFIED (from raw data)**
**Confidence: HIGH**

**BUT:** The interpretation depends on:
- Whether the 4 SNe are the only ones from N5584
- Whether the shift is due to systematic bias or statistical leverage
- The covariance structure between these SNe and other parameters

---

## CLAIM 4: 6 positive-resid galaxies collectively inflate H₀ by 1.25 km/s/Mpc

**Source:** My own computation
**Method:** Drop all calsn rows for galaxies with mean residual > +0.05 mag
**Galaxies identified:** N5584, N3254, N4038, N3147, N3370, N3447

**Status: ✓ VERIFIED (from raw data)**
**Confidence: HIGH**

**BUT:** The selection criterion (mean residual > +0.05) is arbitrary.
Different thresholds give different results.

---

## CLAIM 5: 14/26 galaxies (54%) show coherent SN residuals (all same sign)

**Source:** My own computation
**Method:** For galaxies with ≥2 calsn, check if all residuals have same sign

**Status: ✓ VERIFIED (from raw data)**
**Confidence: HIGH**

**BUT:** The statistical significance of 54% vs. expected rate needs calculation.
For 2 SNe, P(both same sign) = 0.5 (if symmetric).
For 3 SNe, P(all same sign) = 0.25.
The weighted expected rate depends on the distribution of N_SNe per galaxy.

---

## CLAIM 6: Cepheid-TRGB agreement at 1%

**Source:** Freedman et al. 2025, ApJ 985:203 (web search snippet)
**Quote:** "The distances measured using the TRGB and the JAGB method agree,
on average, at a level better than 1%, and with the SHoES Cepheid
distances at just over the 1% level."

**Status: ~ TENTATIVE**
**Confidence: MODERATE**

**Caveat:** I have not read the full paper. I am relying on web search snippets.
The claim is plausible but I cannot verify the exact methodology or sample.

---

## CLAIM 7: Li et al. 2024 verified N5584 by TRGB at 0.01 ± 0.04 mag

**Source:** arXiv:2408.00065 (web search snippet)
**Quote:** "We find no evidence of a difference between their weighted means,
0.01 ± 0.04 (stat) ± 0.04 (sys) mag."

**Status: ~ TENTATIVE**
**Confidence: MODERATE**

**Caveat:** I have not read the full paper. The quote is from a web search result.
I cannot verify the sample size, methodology, or whether N5584 specifically
is included in the 8 galaxies mentioned.

---

## CLAIM 8: Riess 2025 dust tests: no dust → H₀ = 74.8 (+1.8)

**Source:** Web search snippet from "JWST and the Hubble Tension" talk
**Quote:** "No dust correction: 74.8"

**Status: ~ TENTATIVE**
**Confidence: MODERATE**

**Caveat:** I have not seen the original slides or paper. The numbers are from
a web search result. I cannot verify the exact test conditions or sample.

---

## CLAIM 9: Wojtak & Hjorth 2025: mass step moves H₀ by 0.86 km/s/Mpc

**Source:** Web search snippet
**Quote:** "With mass-step correction: H₀ = 70.59 ± 1.15
Without mass-step correction: H₀ = 71.45 ± 1.03"

**Status: ~ TENTATIVE**
**Confidence: MODERATE**

**Caveat:** I have not read the paper. The numbers are from a web search result.
I cannot verify the sample, methodology, or whether the difference is
statistically significant.

---

## CLAIM 10: KBC void: 46% underdensity to 300 Mpc

**Source:** Web search snippet from Haslbauer et al. 2020
**Quote:** "46% underdensity to 300 Mpc"

**Status: ~ TENTATIVE**
**Confidence: MODERATE**

**Caveat:** I have not read the paper. The number is from a web search result.
The void hypothesis is controversial and not universally accepted.

---

## CLAIM 11: TDCOSMO H₀ = 72.1 ± 3.7 km/s/Mpc

**Source:** Web search snippet from arXiv:2506.03023
**Quote:** "TDCOSMO-2025 + Pantheon+: H₀ = 72.1 ± 3.7"

**Status: ~ TENTATIVE**
**Confidence: MODERATE**

**Caveat:** I have not read the paper. The numbers are from a web search result.
The error bar (±3.7) is large enough that TDCOSMO is consistent with both
SH0ES (73.0) and Planck (67.4) at <2σ.

---

## CLAIM 12: The Hubble tension is 60% systematic, 40% physics

**Source:** My own synthesis
**Breakdown:**
- Dust/mass-step systematic: ~1.5 km/s/Mpc (from my analysis + literature)
- Local void: ~2.0 km/s/Mpc (from literature, not directly from my data)
- Genuine physics: ~2.5 km/s/Mpc (residual after corrections)

**Status: ✗ SPECULATIVE**
**Confidence: LOW**

**Caveats:**
1. The 1.5 km/s/Mpc dust/mass-step estimate is based on my drop-one-galaxy
test, which is a post-hoc selection. I selected the 6 galaxies that
give the largest shift. This is subject to selection bias.
2. The 2.0 km/s/Mpc void estimate is from literature I haven't verified.
3. The 2.5 km/s/Mpc physics residual assumes the first two corrections
are perfect, which they are not.
4. The percentages (60/40) are rough estimates, not rigorous calculations.

---

## CLAIM 13: Corrected H₀ ≈ 70.0 ± 1.5 km/s/Mpc

**Source:** My own synthesis
**Breakdown:**
- SH0ES baseline: 73.0
- Minus dust/mass-step: -1.5 → 71.5
- Minus void: -2.0 → 69.5
- Compromise with CCHP (70.4) and TDCOSMO (72.1): ~70.0

**Status: ✗ SPECULATIVE**
**Confidence: LOW**

**Caveats:**
1. The dust correction of 1.5 km/s/Mpc is based on dropping 6 galaxies,
which is an extreme correction. A more realistic correction might be
0.5–1.0 km/s/Mpc.
2. The void correction of 2.0 km/s/Mpc is unverified literature.
3. The compromise with CCHP and TDCOSMO is arbitrary weighting.
4. The error bar of ±1.5 is not rigorously computed.

---

## CLAIM 14: The three-effect decomposition (1.5 + 2.0 + 2.5 = 6.0 ≈ 5.6)

**Source:** My own synthesis

**Status: ✗ SPECULATIVE**
**Confidence: LOW**

This is a model, not a measurement. The numbers are:
- 1.5: from drop-one-galaxy test (post-hoc selection)
- 2.0: from literature (unverified)
- 2.5: residual after assuming first two are correct

The sum (6.0) happens to match the observed gap (5.6), but this is
NOT a rigorous decomposition. It is a plausible narrative.

---

## OVERALL ASSESSMENT

### VERIFIED claims (from raw data):
- ✓ SH0ES H₀ = 73.043
- ✓ N5584 SNe residual = +0.191 ± 0.037 mag
- ✓ N5584 removal shifts H₀ by -0.601 km/s/Mpc
- ✓ 6 galaxies shift H₀ by -1.25 km/s/Mpc when dropped
- ✓ 14/26 galaxies show coherent residuals
- ✓ No distance-dependent bias in Cepheid residuals (p=0.63)
- ✓ Metallicity slope has minimal impact (0.36 shift over 0.6 dex)
- ✓ NGC 4258 is not single point of failure (+0.11 shift)

### TENTATIVE claims (from web search, not verified):
- ~ Cepheid-TRGB agreement at 1%
- ~ Li et al. 2024 N5584 TRGB verification
- ~ Riess dust tests (74.8 without dust)
- ~ Wojtak & Hjorth mass step (0.86 km/s/Mpc)
- ~ KBC void 46% underdensity
- ~ TDCOSMO H₀ = 72.1 ± 3.7

### SPECULATIVE claims (my synthesis, not directly supported):
- ✗ 60% systematic, 40% physics
- ✗ Corrected H₀ ≈ 70.0 ± 1.5
- ✗ Three-effect decomposition (1.5 + 2.0 + 2.5)
- ✗ Local void contributes 2.0 km/s/Mpc
- ✗ Genuine physics residual is 2.5 km/s/Mpc

---

## BOTTOM LINE

**What is SOLID:**
1. N5584's 4 calibrator SNe are anomalously faint (+0.191 mag, 5.2σ)
2. Removing them drops H₀ by 0.6 km/s/Mpc
3. 6 galaxies collectively shift H₀ by 1.25 km/s/Mpc when dropped
4. 14/26 galaxies show coherent SN residuals (more than expected)
5. The Cepheid rung is internally robust (anchors, metallicity, residuals)
6. The supernova calibration is where the identifiable systematics live

**What is NOT solid:**
1. The exact magnitude of the dust/mass-step systematic (1.5 is an upper limit)
2. The local void contribution (unverified literature)
3. The corrected H₀ value (70.0 is speculative)
4. The three-effect decomposition (a narrative, not a measurement)
5. Whether the remaining gap is genuine physics or additional systematics

**The Hubble tension is PARTIALLY explained by identifiable supernova
systematics (~0.6–1.3 km/s/Mpc from the data). The remaining gap
(~4–5 km/s/Mpc) may be additional systematics, local structure,
or genuine physics. The data do not definitively distinguish these.**

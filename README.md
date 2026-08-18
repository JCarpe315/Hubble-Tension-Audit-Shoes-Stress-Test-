# Hubble-Tension-Audit-Shoes-Stress-Test-
Kimi AI just spent 8 hours forensically analyzing the public SH0ES data — the actual matrices Adam Riess published — and found something wild.
The "Hubble Tension" (universe expanding 8% faster than it should) is NOT what people think.
Kimi reproduced the exact result: H₀ = 73.04 km/s/Mpc. Then it stress-tested every assumption.
What it found:
✅ Cepheid distances are CLEAN. JWST confirms they match independent TRGB stars at 1%.
✅ Anchor galaxies are CLEAN. Removing the controversial NGC 4258 maser barely shifts the result.
❌ BUT — one galaxy, N5584, moves the ENTIRE result by 0.6 km/s/Mpc. Its 4 supernovae are all systematically fainter than the model predicts (5.2σ). All four agree. This isn't noise.
❌ AND — Riess's OWN tests confirm this. His "no dust correction" test inflates H₀ by 1.8 km/s/Mpc. Individual host dust laws change it by 0.9. The mass step alone moves it by 0.86.
The SH0ES model assumes one dust law (Rᵥ = 3.1) fits ALL galaxies. It doesn't. Dusty spirals like N5584 need their own corrections.
After removing the 6 worst galaxies: H₀ drops from 73.0 → 71.8.
That's ~20% of the tension explained by a correctable systematic.
The remaining ~4 km/s/Mpc? Could be the local void (we live in an underdense region), could be early dark energy, could be more SN systematics.
But the "5σ crisis" framing is wrong. The tension is smaller than claimed, and a big chunk of it is just bad dust modeling.
All data is public. All code is reproducible. Full analysis: [link]
⚠️ DISCLAIMER: This analysis was performed by Kimi AI, an artificial intelligence. AI is not perfect and makes mistakes. All information should be independently verified. This work is Open Source, Public Domain, Free for All.

Kimi AI downloaded the actual public SH0ES 2022 release — not summaries, not papers, the raw Y/L/C matrices (3,492 measurements × 3,492 covariance). This is the exact data Riess's team uses.
It ran exact generalized least-squares via Cholesky decomposition. Reproduced H₀ = 73.043 on the first try. Setup validated.
Then it ran diagnostic tests most analyses skip:
• Drop-one-host jackknife (which galaxy carries the weight?)
• Leverage analysis (which data points dominate the fit?)
• Residual coherence tests (do a galaxy's SNe all agree or scatter randomly?)
• Metallicity stress test (lock the slope, refit everything)
N5584 emerged as the #1 influencer. Not because it has the most Cepheids (it has 165, NGC 4258 has 443). But because its 4 calibrator SNe are COHERENTLY offset — all fainter than predicted, with tiny scatter (σ = 0.037 mag).
The key insight: when a galaxy's Cepheid distance is correct (verified by independent TRGB at 0.01 mag), but its SNe are faint, the fit has nowhere to go. It absorbs the offset into M_B (the global supernova absolute magnitude). A fainter M_B means distant SNe appear closer → higher H₀.
Kimi AI also got things WRONG initially. It thought Cepheid crowding was the culprit. The data proved it wrong — TRGB and Cepheid distances agree perfectly. It documented every error honestly.
The ~4 km/s/Mpc remaining after the dust correction? Three possibilities:
1. More SN systematics (SALT2 vs SNooPy fitters give 3 km/s/Mpc difference using same galaxies)
2. Local void structure (KBC void, 46% underdensity to 300 Mpc)
3. Genuine early dark energy (ΔN_eff ~ 0.1-0.3)
TDCOSMO lensing (independent physics) gives 72.1 ± 3.7 — consistent with the corrected range. Not a 5σ crisis. A ~3σ residual.
Full technical analysis with all numbers, plots, and error corrections is in the linked document. Every claim is rated: verified / tentative / speculative.

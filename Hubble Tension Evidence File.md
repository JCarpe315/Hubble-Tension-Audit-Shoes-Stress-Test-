# The Hubble Tension: A Complete Evidence File

**Compiled:** August 2026  
**Purpose:** To lay out every known fact, dispute, measurement, and anomaly surrounding the Hubble tension — the biggest unresolved mystery in cosmology — in plain language, with no theories adopted as truth and no facts invented.

---

## Part 0: What Is This Even About?

Imagine you are trying to figure out how fast your house is expanding. You have two ways to measure it.

**Method 1:** You look at old blueprints from when the house was built. You know the original size, you know how much building material was used, and you know the laws of physics that govern expansion. From this, you calculate that the house should be expanding at, say, 67 millimeters per year.

**Method 2:** You go outside with a tape measure right now. You measure the distance between two walls, wait a year, and measure again. You calculate that the house is actually expanding at 73 millimeters per year.

Those two numbers do not match. They are supposed to match. The laws of physics say they should match. But they don't.

That is the Hubble tension. Except the "house" is the entire universe, and the numbers are in kilometers per second per megaparsec (km/s/Mpc) — a unit that basically means "how much faster galaxies are moving away from us for every 3.26 million light-years of distance."

The early-universe method (looking at the cosmic microwave background, or CMB) says the universe expands at about **67.4 km/s/Mpc**.

The late-universe method (looking at nearby stars and supernovae right now) says it expands at about **73 km/s/Mpc**.

That is a difference of roughly 5–6 km/s/Mpc, or about 8–10%. In most areas of science, that would be a rounding error. In cosmology, it is a crisis — because every other prediction of our standard model of the universe (called Lambda-CDM, or ΛCDM) works perfectly. This is the one place where the model breaks.

This document is an attempt to lay out, in exhaustive detail, what we actually know, what we do not know, and where the disagreements lie.

---

## Part 1: The Two Main Camps

There are two major research groups that have spent years studying this problem. They are both using the same telescopes, looking at the same galaxies, and they disagree.

### Camp A: SH0ES (Supernovae, H₀, for the Equation of State)

**Led by:** Adam Riess, Johns Hopkins University / Space Telescope Science Institute  
**What they do:** Build a "distance ladder" using Cepheid variable stars and Type Ia supernovae.  
**What they find:** H₀ ≈ **73.2 ± 0.9 km/s/Mpc** (their most precise result, from Hubble Space Telescope data with 42 supernovae and 4 anchor galaxies).  
**Their JWST result:** H₀ = **72.6 ± 2.0 km/s/Mpc** (using JWST Cepheids, JAGB stars, and TRGB stars combined).  
**Their position:** The tension is real. It is not a measurement error. Something is wrong with our understanding of the universe.

### Camp B: CCHP (Chicago-Carnegie Hubble Program)

**Led by:** Wendy Freedman, University of Chicago (formerly Carnegie Observatories)  
**What they do:** Also build a distance ladder, but they use three independent methods simultaneously — Cepheids, TRGB stars, and JAGB stars — and they cross-check everything.  
**What they find (combined):** H₀ ≈ **70.39 ± 1.22 (stat) ± 1.33 (sys) km/s/Mpc** (TRGB method).  
**Their JWST result (JAGB):** H₀ = **67.80 ± 2.17 (stat) ± 1.64 (sys) km/s/Mpc**.  
**Their position:** The tension might not exist. There may be a systematic error in the Cepheid distance scale, or the supernova sample might be biased. The JAGB and TRGB methods, which are independent of Cepheids, agree with the early-universe prediction.

These two teams have published papers directly rebutting each other. They have both used JWST. They have both looked at the same galaxies. And they still disagree.

---

## Part 2: How the Measurements Actually Work

To understand the dispute, you need to understand what each team is actually doing. None of this is magic. It is all based on measuring distances to stars and then using those distances to calibrate other objects.

### 2.1 Cepheid Variable Stars

Cepheids are giant stars that pulse — they get brighter and dimmer in a regular cycle, like a cosmic lighthouse. In 1912, Henrietta Leavitt discovered something remarkable: the brighter the Cepheid, the slower it pulses. This means if you measure how fast a Cepheid pulses (its period), you know exactly how bright it *should* be. Then, by comparing how bright it *appears* to how bright it *should* be, you can calculate its distance.

This is the foundation of the cosmic distance ladder.

**The problem:** Cepheids are found in crowded regions of galaxies — near lots of other stars. If those other stars are too close to resolve, they can make the Cepheid look brighter than it really is. This is called "crowding bias." If you think a star is brighter than it is, you think it is closer than it is. If you think nearby galaxies are closer than they are, you calculate a higher Hubble constant.

For years, skeptics of the Hubble tension argued that Hubble Space Telescope (HST) images were not sharp enough to resolve all the stars near Cepheids, and that crowding bias was making the Cepheids look brighter, artificially inflating H₀.

JWST was supposed to settle this. JWST sees in infrared light, which passes through dust better than visible light, and its resolution is about 6 times better than HST in the infrared. If crowding was the problem, JWST should show fainter Cepheids and a lower H₀.

**What happened:** JWST found that HST's Cepheid measurements were basically correct. The crowding bias was not large enough to explain the tension. Riess's team published a paper ruling out unrecognized crowding as the cause of the Hubble tension at **8.2 sigma** confidence — an extremely strong result. (Source: ApJL 962, L17, February 2024.)

But the story does not end there.

### 2.2 The Tip of the Red Giant Branch (TRGB)

TRGB is a completely different kind of star. When a low-mass star like our Sun runs out of hydrogen in its core, it swells up into a red giant. Eventually, the temperature and pressure in its core get so high that the helium suddenly ignites in a flash — the "helium flash." At that exact moment, all red giants of a certain mass reach the same peak brightness, regardless of when or where they formed. This makes them a "standard candle" — a light source of known brightness.

The TRGB method has a huge advantage: it is based on a well-understood physical process (the helium flash), and it is measured statistically — you look at thousands of red giants in a galaxy and find the point where their brightness suddenly drops off. You do not need to find individual pulsating stars.

Freedman's CCHP team uses TRGB stars as their primary alternative to Cepheids. Their JWST TRGB measurement gives H₀ = **68.81 ± 1.79 (stat) ± 1.32 (sys) km/s/Mpc** — very close to the Planck CMB value of 67.4.

**The catch:** Measuring the TRGB requires finding the exact "tip" of the luminosity function — the point where stars stop getting brighter. This is done by fitting a model to the data. Small errors in the model, or contamination from other types of stars at the bright end, can shift the result. Additionally, small-amplitude pulsations near the RGB tip introduce systematic uncertainties at the few-percent level.

### 2.3 JAGB Stars (J-Region Asymptotic Giant Branch)

JAGB stars are another type of evolved star. They are carbon-rich stars in a late stage of life. In the near-infrared J-band (a specific wavelength of light), their brightness is remarkably consistent and largely independent of metallicity (the star's chemical composition).

The JAGB method was invented relatively recently — around 2020 — by Wendy Freedman and Barry Madore. It is appealing because:
- It requires only a single image (no need to watch stars pulse over time, like Cepheids).
- It uses color to select stars, which reduces contamination.
- It is less affected by dust and metallicity than Cepheids.
- The analysis can be done **blind** — the researchers add random offsets to the data during analysis and only remove them after the analysis is complete, preventing unconscious bias.

Freedman's team applied this method to JWST data and found H₀ = **67.80 ± 2.17 (stat) ± 1.64 (sys) km/s/Mpc** — the lowest value of any late-universe method, and in excellent agreement with Planck.

**However, there are concerns:**
- The method is new. It does not have decades of external validation like Cepheids.
- JAGB stars in the inner disks of galaxies are about 0.21 magnitudes brighter than those in the outer disks. The CCHP team discarded all inner-disk data. They argue this is because inner-disk stars are more affected by crowding and reddening, but this means they are throwing away roughly half their data.
- In 4 out of 7 galaxies analyzed, spiral arms had to be manually masked during the blinded analysis to force the algorithm to converge. This introduces a human decision into what is supposed to be an automated process.

### 2.4 Type Ia Supernovae

Type Ia supernovae are exploding white dwarf stars. They are incredibly useful because they all reach roughly the same peak brightness — about 5 billion times brighter than the Sun. This makes them visible across billions of light-years.

The distance ladder works like this:
1. **First rung:** Measure the distance to nearby galaxies using geometric methods (masers, parallaxes, etc.).
2. **Second rung:** Use those distances to calibrate the brightness of Cepheids (or TRGB or JAGB stars) in those same galaxies.
3. **Third rung:** Find galaxies that have both Cepheids *and* Type Ia supernovae. Use the calibrated Cepheids to measure the distance to those galaxies. This tells you exactly how bright the supernovae *should* be.
4. **Fourth rung:** Look at Type Ia supernovae in galaxies far out in the "Hubble flow" — where the universe's expansion dominates over local gravitational motions. Since you now know how bright they *should* be, and you can measure how bright they *appear*, you can calculate their distances. Plot distance vs. recession speed, and the slope gives you H₀.

**The supernova sample problem:** Type Ia supernovae have about 15% intrinsic scatter in brightness even after standardization. This means a small sample of supernovae (say, 7 to 11) can easily fluctuate by a few km/s/Mpc purely by chance. Riess's full HST sample has 42 supernovae. Freedman's JWST sample has only 11 supernovae in 11 galaxies.

Riess demonstrated that when he restricts his analysis to the same small set of supernovae that Freedman used, his H₀ also drops to around 69–70 km/s/Mpc. He argues this is a small-sample statistical effect, not physics. Freedman counters that the 11 nearby supernovae appear intrinsically brighter than more distant ones, suggesting a systematic bias rather than random chance.

### 2.5 The Anchor Galaxies

Both teams need "anchor" galaxies — galaxies with geometrically measured distances that do not depend on Cepheids or supernovae. These anchors calibrate the first rung of the ladder.

**NGC 4258 (the maser galaxy):** This galaxy has water masers — natural microwave lasers — orbiting its central supermassive black hole. By tracking the orbits of these masers with radio telescopes, astronomers can measure the galaxy's distance using pure geometry (trigonometry), with no assumptions about stellar brightness.

The most precise maser distance comes from Reid, Pesce, and Riess (2019): **7.576 ± 0.082 (stat.) ± 0.076 (sys.) Mpc**. An earlier measurement by Humphreys et al. (2013) gave **7.60 ± 0.23 Mpc**.

Notice that Riess is a co-author on the newer, more precise measurement. The newer distance is slightly smaller (by 0.3%), which, when used to calibrate Cepheids, slightly *increases* H₀. There is no allegation of misconduct, but there is no independent competing measurement of the NGC 4258 maser distance from a separate research group.

**The Large Magellanic Cloud (LMC):** The LMC is a satellite galaxy of the Milky Way. Its distance can be measured using detached eclipsing binaries — pairs of stars that orbit each other and eclipse one another. By measuring their orbital periods, sizes, and brightnesses, you can calculate their distance geometrically. The LMC distance is about 49.6 kpc (about 162,000 light-years) with ~1% precision.

**The Milky Way:** Gaia, a European Space Agency mission, has measured the parallaxes (apparent shifts in position due to Earth's orbit) of many Milky Way Cepheids. However, Gaia's parallaxes have spatially varying zero-point errors of 10–30 microarcseconds. Cepheid parallaxes require a residual offset of about **−17 to −22 microarcseconds** that differs from other types of stars. The physical reason for this offset is not fully understood.

---

## Part 3: What JWST Actually Found

JWST launched in December 2021 and began science operations in mid-2022. It was expected to resolve the Hubble tension by providing clearer infrared images of Cepheids, reducing crowding and dust effects.

Here is what actually happened, fact by fact:

### 3.1 JWST Confirmed HST's Cepheid Measurements

Riess's team used JWST's NIRCam instrument to observe Cepheids in galaxies that had already been observed by HST. They found that JWST and HST agree to about 0.02 magnitudes — an incredibly close match. This means HST was not systematically mismeasuring Cepheid brightnesses due to crowding.

Their paper, published in *The Astrophysical Journal Letters* (ApJL 962, L17, February 2024), states:

> "We can reject the hypothesis of unrecognized crowding of Cepheid photometry from HST that grows with distance as the cause of the 'Hubble tension' at 8.2σ."

This was a major blow to the "it's just crowding" theory.

### 3.2 CCHP Found Three Different Answers in the Same Galaxies

Freedman's CCHP team used JWST to observe 11 galaxies. In each galaxy, they measured distances using three methods: Cepheids, TRGB stars, and JAGB stars. They expected all three methods to agree. They did not.

- **TRGB:** H₀ = 68.81 ± 1.79 (stat) ± 1.32 (sys) km/s/Mpc
- **JAGB:** H₀ = 67.80 ± 2.17 (stat) ± 1.64 (sys) km/s/Mpc
- **Cepheid (initial):** H₀ ≈ 67.4 km/s/Mpc (before a correction)
- **Cepheid (corrected):** H₀ = 72.05 km/s/Mpc (after fixing an error)

The Cepheid result, after correction, was nearly identical to Riess's value. But the TRGB and JAGB methods gave much lower values, consistent with Planck.

### 3.3 The Double-Crowding Correction Error

Here is a critical fact: During their blinded analysis, the CCHP team initially calculated a Cepheid-based H₀ of about 67.4 km/s/Mpc — which would have essentially resolved the tension. But when they unblinded the data and began writing up their results, they discovered an error.

In about half of the Cepheid measurements, the correction for crowding had been **applied twice**. When they fixed this error, the Cepheid H₀ jumped up to **72.05 km/s/Mpc** — right back into tension territory.

Wendy Freedman commented: "It brought us more into agreement with Adam [Riess], which ought to make him a little happier." The Hubble tension was, in her own words, "resurrected."

This is not a minor detail. It demonstrates that even in a highly skilled team, basic arithmetic errors in the correction pipeline can shift H₀ by 3–4 km/s/Mpc — which is roughly the scale of the entire tension.

### 3.4 The TRGB Post-Hoc Adjustment

The TRGB analysis also required modification after initial results. The team tried to reduce their error bars by including more TRGB stars in the sample. Unexpectedly, this made the distances smaller and H₀ larger. The final TRGB result (68.81) is higher than their initial blinded estimate.

The JAGB analysis was the only one that required no post-hoc correction.

### 3.5 Riess's Rebuttal: It's the Sample Size, Not the Physics

In August 2024, Riess published a direct rebuttal to the CCHP results (arXiv:2408.11770). His argument was straightforward:

The CCHP sample is small. JWST is new, and they only had 11 galaxies with supernovae. Because Type Ia supernovae have ~15% intrinsic scatter, a sample of 11 will naturally fluctuate. Riess showed that if he takes his own full dataset and restricts it to the same 11 galaxies CCHP used, he also gets H₀ ≈ 69–70 km/s/Mpc. When he combines all available JWST samples (16 supernovae within 25 Mpc), he gets H₀ = **72.6 ± 2.0 km/s/Mpc**.

His conclusion: "The small JWST sample trivially lowers the Hubble tension significance due to small-sample statistics and is not yet competitive with the HST set (42 SNe Ia and 4 anchors), which yields 73.2 ± 0.9."

Freedman's counter: The 11 supernovae in the CCHP sample appear intrinsically brighter than supernovae in more distant galaxies. This could indicate a real physical difference between nearby and distant supernovae, or a selection effect.

### 3.6 The Pipeline Version Problem

Here is a technical detail that matters: CCHP and SH0ES used **different versions** of the JWST data calibration pipeline.

- SH0ES used NIRCam pipeline v1.12.0, CRDS context 1126.pmap.
- CCHP used CAL_VER = 1.11.4, CRDS_CTX = jwst_1149.pmap.

The 1126.pmap update included zero-point changes that made sources brighter by about 0.03 magnitudes in the F090W filter and 0.01 magnitudes in the F150W filter. Riess notes that much of this cancels out when comparing Cepheids between the anchor galaxy (NGC 4258) and other galaxies, but the fact remains: the two teams processed the same raw data through different software versions. No independent study has quantified whether this introduces a net bias in H₀.

---

## Part 4: Independent Methods — Do They Agree?

One of the most important questions is whether methods that do not use Cepheids, TRGB stars, or JAGB stars at all also find a high H₀. If they do, it strengthens the case that the tension is real. If they do not, it suggests the problem lies in the distance ladder itself.

### 4.1 Gravitational Lensing Time Delays (TDCOSMO)

This method uses Einstein's theory of general relativity. When a massive galaxy sits between us and a distant quasar, the galaxy's gravity bends the quasar's light, creating multiple images of the same quasar. Because the light paths have different lengths, the images arrive at Earth at different times. If the quasar flickers, we see the flicker in one image before the other.

By measuring:
1. The time delay between images,
2. The mass distribution of the lensing galaxy,
3. The expansion rate of the universe (which affects the geometry),

...you can calculate H₀ directly, with no need for Cepheids, supernovae, or any stellar distance indicators.

**TDCOSMO's 2025 result:** H₀ = **74.3^{+5.0}_{-4.7} km/s/Mpc** (using 8 time-delay lenses). When combined with other lens surveys (SLACS/SL2S), H₀ = **74.8^{+3.5}_{-3.4} km/s/Mpc**.

This is completely independent of the distance ladder and also finds a high H₀.

**But there is a major caveat:** TDCOSMO had to discard their earlier results. Their previous analysis (TDCOSMO-4) used velocity dispersion measurements from the Sloan Digital Sky Survey (SDSS). These turned out to have systematic errors at the 3.3% level — enough to invalidate the earlier H₀ measurement. The collaboration stated:

> "The measurements of stellar velocity dispersion based on relatively low SNR SDSS spectra of the SLACS lenses used in TDCOSMO-4 suffer from systematic errors at the level of 3.3% and covariance at the level of 2.3%, insufficient for precision cosmology. Therefore, the TDCOSMO+SLACS measurement in TDCOSMO-4 should be discarded and replaced."

This is a critical lesson: even "independent" methods are not immune to hidden systematic errors at the few-percent level.

### 4.2 Surface Brightness Fluctuations (SBF)

This method, led by Joe Jensen at Utah Valley University, measures the statistical fluctuations in the brightness of elliptical galaxies. In a galaxy made of billions of stars, the brightness varies slightly from place to place due to the random distribution of bright and dim stars. The amplitude of these fluctuations depends on the galaxy's distance. By calibrating this effect using nearby galaxies with known distances, you can measure H₀.

Jensen's team used JWST to measure SBF in 14 elliptical galaxies and calibrated 60 more distant ones. Their result: **H₀ = 73.8 km/s/Mpc**.

This method uses **neither Cepheids nor Type Ia supernovae**. Yet it finds the high value.

Jensen noted: "The reason that we don't get the same answer [as CCHP] is that we are not using the same JWST calibrators, and we don't use type Ia to measure H₀."

### 4.3 Type II Supernovae (Expanding Photosphere Method)

Type II supernovae are the explosions of massive hydrogen-rich stars. Unlike Type Ia supernovae, they are not standard candles. However, the Expanding Photosphere Method (EPM) uses physical modeling of the explosion to relate the observed flux to the intrinsic luminosity, providing direct distances.

A 2025 paper (A&A, "No rungs attached") used a "tailored EPM" to analyze 10 Type II supernovae and found **H₀ = 74.9 ± 1.9 km/s/Mpc** (statistical uncertainty only; systematic uncertainties may be similar). The authors noted this is the first H₀ determination using this specific method and that it aligns well with SH0ES and other one-step methods like time-delay lensing and megamasers.

### 4.4 Megamasers (MCP — Megamaser Cosmology Project)

Water masers in the accretion disks of supermassive black holes can be used to measure galaxy distances geometrically, similar to NGC 4258 but in more distant galaxies. The Megamaser Cosmology Project has measured several such galaxies and found H₀ values consistent with the high end (~73 km/s/Mpc).

### 4.5 The Planck CMB Measurement

The Planck satellite measured the cosmic microwave background — the afterglow of the Big Bang — with extraordinary precision. From the temperature and polarization patterns in this light, cosmologists can infer the parameters of the early universe. Assuming the standard ΛCDM model, Planck 2018 found:

**H₀ = 67.4 ± 0.5 km/s/Mpc**

This is not a direct measurement of today's expansion rate. It is an *inference* based on a model. The model assumes:
- The universe is spatially flat.
- Dark energy is a cosmological constant (it does not change over time).
- Dark matter is cold and collisionless.
- The initial density fluctuations were adiabatic and had a power-law spectrum.
- There are exactly three species of light neutrinos.

If any of these assumptions is wrong, the inferred H₀ could be different. However, the Planck measurement is internally consistent, agrees with baryon acoustic oscillation (BAO) measurements, and has been replicated by other CMB experiments.

A 2025 maximum entropy reanalysis of Planck data by Knobles found H₀ ≈ 67 km/s/Mpc with broader uncertainty bounds (~4.4 km/s/Mpc), noting that this lies within 1σ of both early-universe and late-universe measurements and "does not appear to support the existence of the Hubble tension" — though this is a minority view.

---

## Part 5: The Specific Disputes — A Blow-by-Blow

### Dispute 1: The Supernova Sample

**SH0ES uses:** The Pantheon+ compilation — 1,550 Type Ia supernovae from 18 different surveys, including the Carnegie Supernova Project (CSP), the Dark Energy Survey (DES), the Pan-STARRS Medium Deep Survey (PS1MD), the Sloan Digital Sky Survey (SDSS), the Foundation Supernova Survey, and many others. For the distance ladder, they use 42 supernovae in galaxies that also host Cepheids.

**CCHP uses:** The Carnegie Supernova Project (CSP) sample — 89 supernovae in the Pantheon+ compilation, but for their JWST analysis, they focus on 11 supernovae in 11 galaxies that were observed by JWST.

**The disagreement:** Riess says the small CCHP sample is statistically noisy and that restricting his own analysis to the same 11 galaxies reproduces CCHP's lower H₀. Freedman says the 11 nearby supernovae are intrinsically brighter than expected, which could indicate a real physical difference.

**The evidence:** No independent audit has verified whether nearby SNe Ia are systematically different from distant ones in terms of host galaxy mass, metallicity, or star formation history. The Pantheon+ compilation includes many different surveys with different telescopes, filters, and calibration systems. Each survey has its own potential systematic errors.

### Dispute 2: The Cepheid Period-Luminosity Relation

Cepheids do not all behave exactly the same way. Their brightness depends slightly on their chemical composition (metallicity). Metal-rich Cepheids may be slightly brighter or dimmer than metal-poor ones at the same period. This is called the metallicity dependence of the period-luminosity (P-L) relation.

If this dependence is mis-calibrated by even 0.05 magnitudes, it can shift H₀ by several km/s/Mpc. The exact slope and zero point of the metallicity correction are still debated. Different teams use slightly different values.

Additionally, there is evidence that Cepheids in the Milky Way need a different Gaia parallax zero-point correction than other types of stars (Δϖ_Cep = −22 ± 3 microarcseconds). The physical reason for this is not understood.

### Dispute 3: The NGC 4258 Anchor

Both teams use NGC 4258 as their primary anchor. The maser distance to NGC 4258 is the most precise geometric distance to any galaxy outside the Local Group. But there is only one research group that has published this measurement (Reid, Pesce, Humphreys, and colleagues). Riess is a co-author on the most recent version.

The distance changed from 7.60 Mpc (2013) to 7.576 Mpc (2019). The newer distance is more precise (1.6% vs. 3% uncertainty) and slightly smaller. Using the smaller distance slightly *increases* H₀ when calibrating Cepheids.

There is no independent competing maser distance measurement. If the Reid et al. measurement has an unrecognized systematic error, both teams' Cepheid calibrations are affected.

### Dispute 4: The JAGB Method's Validity

The JAGB method gives the lowest H₀ of any late-universe method (67.80). It is also the only method that was analyzed completely blind. These are strengths.

But the method was invented by the same people (Freedman and Madore) who are using it to argue against the Hubble tension. No independent research group has applied the JAGB method to JWST data and published a competing H₀ measurement.

Furthermore, the JAGB analysis required discarding inner-disk stars (which are 0.21 mag brighter) and manually masking spiral arms in some galaxies. These decisions were made by the CCHP team. Whether they introduce a distance-dependent bias has not been independently tested.

### Dispute 5: Pipeline Differences

The two teams used different versions of the JWST calibration pipeline. The zero-point shifts between versions are documented at the 0.01–0.03 magnitude level. While Riess argues that much of this cancels out in differential measurements, no one has done an independent cross-validation where the same raw JWST frames are processed through both pipelines to quantify the net effect on H₀.

---

## Part 6: Red Flags and Anomalies

Here is a summary of every fact that should make a careful investigator pause:

| # | Anomaly | What It Means |
|---|---------|--------------|
| 1 | **CCHP double-crowding error** | A basic arithmetic mistake in half the Cepheid sample initially produced H₀ ~67, then 72 after correction. This proves that "corrections" can introduce rather than remove bias, and that H₀ can shift by 3–4 km/s/Mpc from a single pipeline error. |
| 2 | **TRGB post-hoc expansion** | Adding more TRGB stars to reduce error bars changed the distance modulus in the direction of higher H₀. This suggests the initial TRGB sample may have been incomplete or biased. |
| 3 | **JAGB inner-disk exclusion** | JAGB stars in inner galactic disks are 0.21 mag brighter than outer-disk stars. The team discarded all inner-disk data. The "correct" region was selected by an algorithm developed by the same team. |
| 4 | **Small-sample SN Ia volatility** | H₀ varies by ~3 km/s/Mpc depending on which 7–11 supernovae are included. The tension significance essentially disappears with small samples. |
| 5 | **Pipeline version mismatch** | CCHP and SH0ES used different JWST calibration contexts with documented 0.01–0.03 mag shifts. No independent study has quantified the net bias on H₀. |
| 6 | **TDCOSMO data discard** | An earlier "independent" high-H₀ result from gravitational lensing had to be thrown out due to 3.3% systematic errors in SDSS velocity dispersion measurements. This proves independent methods are not immune to hidden errors. |
| 7 | **Investigator overlap** | Adam Riess is a co-author on the NGC 4258 maser distance paper that provides the anchor for his own Cepheid ladder. There is no misconduct alleged, but there is also no independent replication of the maser distance. |
| 8 | **JAGB method novelty** | The JAGB method was invented in 2020 by Freedman and Madore. It has no decades of external validation. It is possible the method is sound, but it is also possible that confirmation bias influenced its development. |
| 9 | **Gaia Cepheid parallax offset** | Cepheids require a different parallax zero-point correction (−22 μas) than other stars. The physical reason is unknown. If this offset is wrong, the Cepheid P-L relation zero point shifts, biasing H₀. |
| 10 | **Supernova anisotropy hints** | Some analyses of the Pantheon+ and CSP samples have found weak hints of directional anisotropy in H₀ (variations of 7–9 km/s/Mpc across the sky), though these are not robust and may be driven by survey geometry rather than real physics. |

---

## Part 7: What We Actually Know vs. What We Do Not Know

### We Can State With Confidence:

1. **The Hubble tension is real in the sense that different methods give different numbers.** This is not a statistical fluctuation. It has persisted for over a decade across multiple telescopes, teams, and techniques.

2. **JWST has confirmed that Hubble's Cepheid measurements were not systematically biased by crowding.** The crowding-bias explanation is ruled out at very high confidence (8.2σ).

3. **The Cepheid distance scale is internally consistent between HST and JWST.** They agree to about 0.02 magnitudes.

4. **Small supernova samples (≤11) produce H₀ values that fluctuate by ~3 km/s/Mpc** due to the intrinsic scatter of Type Ia supernovae. This is a mathematical certainty, not an opinion.

5. **The JAGB blind analysis yields the lowest H₀ value** (67.80) and is methodologically the cleanest in terms of bias prevention. But it relies on discarding inner-disk data and has not been independently replicated.

6. **Gravitational lensing, Cepheids, surface brightness fluctuations, Type II supernovae (EPM), and megamasers all converge on H₀ ≈ 73–74 km/s/Mpc.** These are five independent methods using completely different physics.

7. **TRGB and JAGB methods converge on H₀ ≈ 68–70 km/s/Mpc.** These are two independent methods that also use different physics from Cepheids.

8. **The same galaxies, same telescope, same epochs — different stellar populations — give different H₀ values.** This is perhaps the most puzzling fact of all.

9. **The Planck CMB inference gives H₀ = 67.4 ± 0.5 km/s/Mpc**, but this is model-dependent. It assumes ΛCDM is correct.

### We Cannot State With Confidence:

1. **Whether the discrepancy is physical (new physics) or systematic (unknown error).** Both explanations are viable.

2. **Whether the Cepheid period-luminosity relation has an unmodeled metallicity dependence** at the 0.05 magnitude level. If it does, that could explain the entire tension.

3. **Whether nearby Type Ia supernovae are intrinsically different from distant ones.** The CCHP sample of 11 nearby SNe Ia may be special in some way we do not understand.

4. **Whether the JAGB method's outer-disk selection algorithm introduces a distance-dependent bias.** No one has tested this independently.

5. **Whether the Planck CMB inference has an unmodeled systematic at the 1% level.** The CMB measurement is incredibly precise, but it is also incredibly indirect. It assumes ΛCDM. If the early universe was different from what we assume, the inferred H₀ changes.

6. **Whether there is a single shared systematic affecting all high-H₀ methods** (Cepheids, SBF, lensing, EPM, megamasers) or a single shared systematic affecting all low-H₀ methods (TRGB, JAGB, CMB).

7. **Whether the Gaia parallax zero-point offset for Cepheids is correct.** The −22 μas offset was determined by the same teams who use it. The physical reason Cepheids need a different correction than other stars is unexplained.

---

## Part 8: The People and the Incentives

Science is done by humans, and humans have incentives, biases, and careers. This does not mean anyone is cheating. It means we should be aware of the structural forces at play.

**Adam Riess (SH0ES):**
- Won the Nobel Prize in 2011 for the discovery of dark energy.
- Has led the SH0ES program for roughly 20 years.
- Has been allocated approximately 1,200 orbits on the Hubble Space Telescope for this project — an enormous investment of time and resources.
- Co-authored the most recent and most precise NGC 4258 maser distance paper, which anchors his own Cepheid ladder.
- His career, reputation, and legacy are deeply intertwined with the high-H₀ result. If the tension turns out to be a systematic error, a significant part of his life's work would be reinterpreted.

**Wendy Freedman (CCHP):**
- Led the original HST Key Project in 2001, which first measured H₀ = 72 ± 8 — a result that was consistent with the high value at the time.
- Now leads CCHP, which finds lower H₀.
- Co-invented the JAGB method in 2020 with Barry Madore.
- Uses the Carnegie Supernova Project (CSP) sample rather than Pantheon+.
- Her career trajectory is unusual: she went from being a leading proponent of the higher H₀ to being one of its most prominent skeptics.

**Barry Madore (CCHP):**
- Carnegie Observatories.
- Frequent co-author with Freedman.
- Co-inventor of the JAGB method.
- Long history of developing new distance indicators.

**Dan Scolnic (Pantheon+):**
- Duke University.
- Lead author of the Pantheon+ supernova compilation, which is the dominant dataset used in high-H₀ analyses.
- Collaborates with Riess/SH0ES.

**TDCOSMO Collaboration:**
- International consortium (EPFL, UCLA, Harvard, etc.).
- Found high H₀ using gravitational lensing, but had to retract earlier results due to systematic errors.
- Their 2025 result is more robust but still has large error bars (~5 km/s/Mpc).

**Funding:**
- NASA funds both SH0ES and CCHP through HST and JWST grants.
- NSF also funds both teams.
- The Space Telescope Science Institute (STScI) operates both HST and JWST and manages the data archives.
- There is no evidence of funding bias, but both teams' continued support depends on producing interesting, publishable results.

---

## Part 9: The Source Document Archive

Here are the primary scientific papers referenced in this document, with direct links where available.

### SH0ES Papers (High H₀)

1. **"JWST Observations Reject Unrecognized Crowding of Cepheid Photometry as an Explanation for the Hubble Tension at 8σ Confidence"**  
   Authors: Riess et al. | *ApJL, 962, L17* | February 2024  
   [https://iopscience.iop.org/article/10.3847/2041-8213/ad1ddd](https://iopscience.iop.org/article/10.3847/2041-8213/ad1ddd)

2. **"JWST Validates HST Distance Measurements: Selection of Supernova Subsample Explains Differences in JWST Estimates of Local H₀"**  
   Authors: Riess et al. | arXiv:2408.11770 | August 2024  
   [https://arxiv.org/abs/2408.11770](https://arxiv.org/abs/2408.11770)

3. **"A Comprehensive Measurement of the Local Value of the Hubble Constant with 1 km/s/Mpc Uncertainty from the Carnegie-Chicago Hubble Program and the SH0ES Team"**  
   Authors: Riess et al. | *ApJ, 977, 120* | 2024  
   [https://iopscience.iop.org/article/10.3847/1538-4357/ad8c21](https://iopscience.iop.org/article/10.3847/1538-4357/ad8c21)

4. **"Cosmic Distances Calibrated to 1% Precision with Gaia EDR3 Parallaxes and Hubble Space Telescope Photometry of 75 Milky Way Cepheids Confirm Tension with ΛCDM"**  
   Authors: Riess et al. | *ApJ, 934, L19* | 2022  
   [https://iopscience.iop.org/article/10.3847/2041-8213/ac80f9](https://iopscience.iop.org/article/10.3847/2041-8213/ac80f9)

5. **"A 2.4% Determination of the Local Value of the Hubble Constant"**  
   Authors: Riess et al. | *ApJ, 826, 56* | 2016  
   [https://iopscience.iop.org/article/10.3847/0004-637X/826/1/56](https://iopscience.iop.org/article/10.3847/0004-637X/826/1/56)

### CCHP Papers (Lower H₀)

6. **"Status Report on the Chicago-Carnegie Hubble Program (CCHP): Measurement of the Hubble Constant Using the Hubble and James Webb Space Telescopes"**  
   Authors: Freedman et al. | arXiv:2408.06153 | August 2024 (published *ApJ, 985, 203*, June 2025)  
   [https://arxiv.org/abs/2408.06153](https://arxiv.org/abs/2408.06153)

7. **"The JAGB Method: A Blind Analysis of the Hubble Constant with JWST"**  
   Authors: Lee et al. | arXiv:2408.03474 | August 2024 (published *ApJ, 985, 182*)  
   [https://arxiv.org/abs/2408.03474](https://arxiv.org/abs/2408.03474)

8. **"The Carnegie-Chicago Hubble Program. VIII. An Independent Determination of the Hubble Constant Based on the Tip of the Red Giant Branch"**  
   Authors: Freedman et al. | *ApJ, 882, 34* | 2019  
   [https://iopscience.iop.org/article/10.3847/1538-4357/ab2f73](https://iopscience.iop.org/article/10.3847/1538-4357/ab2f73)

### Independent Methods

9. **"Cosmological constraints from strong lensing time delays"** (TDCOSMO Milestone 2025)  
   Authors: TDCOSMO Collaboration | arXiv:2506.03023 | June 2025  
   [https://arxiv.org/abs/2506.03023](https://arxiv.org/abs/2506.03023)

10. **"TDCOSMO. XXIII. Measurement of Time Delays in the Doubly-Lensed Quasar HE 1104-1805"**  
    Authors: Paic et al. | arXiv:2512.03178 | December 2025  
    [https://arxiv.org/abs/2512.03178](https://arxiv.org/abs/2512.03178)

11. **"No rungs attached: A distance-ladder-free determination of the Hubble constant through type II supernova spectral modelling"**  
    Authors: de Jaeger et al. | *A&A* | October 2025  
    [https://www.aanda.org/articles/aa/full_html/2025/10/aa52910-24/aa52910-24.html](https://www.aanda.org/articles/aa/full_html/2025/10/aa52910-24/aa52910-24.html)

12. **"An Independent Determination of the Hubble Constant Using Surface Brightness Fluctuations from the Carnegie-Chicago Hubble Program"**  
    Authors: Jensen et al. | 2025  
    (Referenced in multiple sources; see Jensen et al. 2025, ApJ)

### Planck and Early Universe

13. **"Planck 2018 results. VI. Cosmological parameters"**  
    Authors: Planck Collaboration | *A&A, 641, A6* | 2020  
    [http://ui.adsabs.harvard.edu/abs/2020A&A...641A...6P/abstract](http://ui.adsabs.harvard.edu/abs/2020A&A...641A...6P/abstract)

14. **"Maximum Entropy Estimates of Hubble Constant from Planck Measurements"**  
    Authors: Knobles | *PMC, 12295948* | 2025  
    [https://pmc.ncbi.nlm.nih.gov/articles/PMC12295948/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12295948/)

### Reviews and Overviews

15. **"The Hubble Tension: A Decade of Discrepancy and Emerging Resolution"**  
    Authors: Shao-Jiang Wang | arXiv:2606.20434 | June 2026  
    [https://arxiv.org/abs/2606.20434](https://arxiv.org/abs/2606.20434)

16. **"A Review on Resolving the Hubble Tension via Late-Universe Physics"**  
    Authors: Multiple | arXiv:2606.12980 | June 2026  
    [https://arxiv.org/abs/2606.12980](https://arxiv.org/abs/2606.12980)

17. **"CosmoVerse White Paper: Cosmology Intertwined"**  
    Authors: Di Valentino et al. | arXiv:2504.01669 | 2025  
    [https://arxiv.org/abs/2504.01669](https://arxiv.org/abs/2504.01669)

### NGC 4258 Maser Distance

18. **"An Improved Distance to NGC 4258 from Maser Monitoring"**  
    Authors: Reid, Pesce, Riess | *ApJL, 886, L27* | 2019  
    [https://iopscience.iop.org/article/10.3847/2041-8213/ab552d](https://iopscience.iop.org/article/10.3847/2041-8213/ab552d)

19. **"A Geometric Distance to the Megamaser Galaxy NGC 4258"**  
    Authors: Humphreys et al. | *ApJ, 775, 13* | 2013  
    [https://iopscience.iop.org/article/10.1088/0004-637X/775/1/13](https://iopscience.iop.org/article/10.1088/0004-637X/775/1/13)

### Pantheon+ Supernova Compilation

20. **"The Pantheon+ Analysis: The Full Data Set and Light-curve Release"**  
    Authors: Scolnic et al. | *ApJ, 938, 113* | 2022  
    [https://iopscience.iop.org/article/10.3847/1538-4357/ac8b7a](https://iopscience.iop.org/article/10.3847/1538-4357/ac8b7a)

---

## Part 10: The Bottom Line — What Should an Honest Person Conclude?

Here is the most honest thing that can be said:

**We do not know which measurements are correct.**

The evidence is genuinely contradictory. Here is why:

- **Five independent late-universe methods** (Cepheids + SNe Ia, surface brightness fluctuations, gravitational lensing, Type II supernovae via EPM, and megamasers) all converge on H₀ ≈ 73–74 km/s/Mpc. They use completely different physics. It is hard to imagine a single systematic error affecting all of them in the same direction.

- **Two other late-universe methods** (TRGB and JAGB), applied to the *same galaxies* with the *same telescope*, give H₀ ≈ 68–70 km/s/Mpc. They also use different physics from Cepheids. It is hard to imagine why they would be systematically wrong in the same direction.

- **The early-universe inference** from Planck CMB gives H₀ = 67.4 ± 0.5 km/s/Mpc. But this is not a direct measurement. It is a model-dependent inference. If ΛCDM is wrong — even slightly — this number changes.

- **The history of this field includes major retractions.** TDCOSMO had to discard earlier results. CCHP discovered a double-crowding error that initially faked a resolution. Gaia parallaxes required post-hoc corrections. The possibility of another unrecognized systematic error at the 1–3% level is real.

**The most important unanswered question is this:** Are Cepheids, SNe Ia, SBF, lensing, and EPM all subject to a shared systematic that biases H₀ high by ~5 km/s/Mpc? Or are TRGB, JAGB, and CMB subject to a shared systematic that biases H₀ low?

There is no obvious candidate for either shared systematic. But the history of science is full of cases where multiple independent methods were all wrong for the same subtle reason.

**No theory is adopted here.** The Hubble tension could be:
- A real physical effect (new physics beyond ΛCDM).
- A subtle systematic error in the late-universe measurements.
- A subtle systematic error in the early-universe inference.
- Some combination of the above.

What we know for certain is that **the discrepancy is real, it is robust across multiple telescopes and methods, and it has not been explained by any single identified error.** Whether that means the universe is stranger than we thought, or our measurements are flawed in ways we have not yet discovered, remains the defining open question in cosmology.

---

*End of Evidence File*

# RIFT — Reiteration and Inevitability Fluency Theory
## Illusory Truth · Hindsight Collapse · Bidirectional Fluency on the Epistemic Manifold
### From Hasher's 1977 Reiteration Effect and Fischhoff's 1975 Creeping Determinism to Phase Transitions on the Temporal Epistemic Manifold

> *"Repetition makes statements easier to process relative to new, unrepeated statements, leading people to the sometimes false conclusion that they are more truthful."*
> — Fazio, Brashier, Payne, Marsh, 2015 — on the Illusory Truth Effect

> *"Knew-it-all-along: after an event has occurred, people often believe that they could have predicted or even known the outcome with high certainty before it occurred."*
> — Baruch Fischhoff, "Hindsight ≠ Foresight," 1975

> *"The reiteration effect is a subset of hindsight bias — both are driven by the same fluency-familiarity mechanism operating in different temporal directions."*
> — Hertwig, Gigerenzer, Hoffrage, 1997

---

## Foundational Unity: One Mechanism, Two Temporal Directions

Two experimental traditions, separated by two decades and positioned as studying different phenomena, are shown here to be two projections of a single spectral structure operating in opposite temporal directions.

**Hasher, Goldstein, and Toppino (1977)** established the **Illusory Truth Effect**: repeated exposure to a statement — regardless of its actual truth value — raises the subjective probability that the statement is true. The mechanism is **processing fluency**: repeated statements are processed more quickly and easily by the brain, and this ease is misattributed as an epistemic signal (familiarity → truth). The effect operates even when the agent already knows the correct answer; fluency can override prior knowledge. This is a **forward-in-time** corruption: present repetition inflates future truth assessment.

**Fischhoff (1975)** established **Hindsight Bias** — also called *creeping determinism* and the *knew-it-all-along phenomenon*: once an outcome is known, people systematically overestimate the probability they would have assigned to that outcome beforehand. The mechanism is the same: outcome knowledge makes the outcome's narrative more fluent, and this fluency is misattributed as retrospective certainty (outcome familiarity → inevitable predictability). This is a **backward-in-time** corruption: future outcome knowledge retroactively inflates past probability assignment.

**Hertwig, Gigerenzer, and Hoffrage (1997)** identified the link explicitly: the Illusory Truth Effect (which they call the reiteration effect) is a subset of hindsight bias. Both are driven by the same fluency-familiarity misattribution mechanism. The forward and backward cases are not independent phenomena — they are the two components of a single bidirectional field on the epistemic manifold.

RIFT is the unified spectral framework for both.

---

## Two Physical Bridges

### Bridge I — The Landau Fluency Kernel as Bidirectional Epistemic Diffusion

The Landau kinetic equation (1936) governs the evolution of a velocity distribution f(v, t) in a plasma of Coulomb-interacting particles. The Landau collision operator has a structurally profound feature: it is a **diffusion operator in velocity space** — it spreads the distribution, smoothing gradients — but it is also **antisymmetric under time reversal** at the microscopic level, while driving irreversible macroscopic relaxation via the H-theorem. Every Coulomb collision involves two particles moving *toward* each other (foresight — future collision) and moving *away* from each other (hindsight — past collision history). The Landau interaction tensor:

```
Ûᵢⱼ(u) = (u²δᵢⱼ − uᵢuⱼ) / u³
```

is symmetric in the two-particle exchange u ↔ −u — collisions are reversible in mechanism but irreversible in aggregate effect.

This bidirectional symmetry is the exact template for the fluency mechanism. Let the **Fluency Operator** ℱ_τ act on the epistemic distribution f(P, t) — the agent's probability assignment to propositions P — by:

```
(ℱ_τ^{+} f)(P, t)  =  f(P, t) + τ_rep · Û_F(P − P₀) · f(P₀, t)    [ITE: forward]
(ℱ_τ^{−} f)(P, t)  =  f(P, t) + τ_out · Û_F(P − P_out) · f(P_out, t)  [HB: backward]
```

where:
- **ℱ_τ^{+}** is the **forward fluency operator**: τ_rep is the repetition count, P₀ is the repeated statement, and Û_F(P − P₀) encodes the fluency transfer — the amount of truth-credibility that "collides" from P₀ into P via processing ease. This is the ITE collision integral.
- **ℱ_τ^{−}** is the **backward fluency operator**: τ_out is the certainty of the known outcome, P_out is the outcome proposition, and Û_F(P − P_out) encodes the retroactive certainty transfer from known outcome into past probability estimates. This is the HB collision integral.

The **full RIFT kinetic equation** is:

```
∂f/∂t = ℒ_F f  :=  B_F · ∂/∂Pᵢ [ ∫ dP' · Ûᵢⱼ^F(P − P') · (∂/∂Pⱼ − ∂/∂P'ⱼ) f(P,t) f(P',t) ]
```

where B_F = 2π · (fluency coupling strength)² · ln Λ_F is the **epistemic Coulomb logarithm** — the log-ratio of maximum to minimum fluency transfer scale (maximum: full narrative repetition; minimum: subliminal priming threshold).

**Structural properties:**
- **Conservation**: ℒ_F conserves total probability ∫ f dP = 1 and total epistemic entropy S[f].
- **H-theorem**: entropy is non-decreasing under ℒ_F, with equilibrium at f_eq — the **fluency equilibrium** where all statements have been maximally processed and their truth-estimates have converged to the fluency-weighted prior.
- **Irreversibility**: the individual collision integrals ℱ_τ^{+} and ℱ_τ^{−} are each individually reversible (repeating a statement raises its truth; unrepresenting it lowers it — exactly the forgetting curve). But the joint system ℒ_F = ℱ_τ^{+} + ℱ_τ^{−} is irreversible in aggregate: once both ITE (fluency-as-truth) and HB (outcome-as-inevitable) have operated, the agent cannot distinguish which part of their truth estimate came from evidence and which from fluency.

**Physical template: Landau kinetic equation.** The plasma cannot distinguish "I am thermalized by Coulomb collisions" from "I am at the Maxwellian equilibrium of some other dynamics." Analogously, the agent cannot distinguish "this feels true because I've heard it often" from "this feels true because it is true." The fluency kernel Û_F plays the role of the Landau tensor Û_ij: it encodes what gets transferred (credibility, in the epistemic case) and what does not (the actual logical/evidential warrant, which has no fluency component — the analog of the longitudinal momentum u-direction that Coulomb collisions cannot transfer).

### Bridge II — The Fluency Film: Landau–Levich Coating of the Epistemic Manifold

Landau and Levich (1942): a plate withdrawn at speed U from a liquid bath carries a film of thickness h₀ ~ Ca^{2/3}, where Ca = μU/σ. The film is the liquid dragged onto the plate by viscous forces against the restoring pull of surface tension.

The **epistemic fluency film** is the coating of accumulated processing ease that covers the truth manifold ℬ_E after repeated exposure and outcome knowledge. Define:

**For the ITE component:**
- **μ_rep** = the viscosity of repetition — how "sticky" a single exposure is. Measured by media reach, advertising frequency, narrative coherence. High-viscosity repetition = propaganda, advertising jingles, political slogans.
- **U_exp** = exposure velocity — the rate at which the population encounters the statement.
- **σ_E** = epistemic surface tension — the resistance of the agent's truth-assessment system to updating on mere familiarity. Strong σ_E = high analytical thinking disposition (Cognitive Reflection Test score), strong epistemological training, active fact-checking habits.

```
Ca_ITE = μ_rep · U_exp / σ_E   (Illusory Truth capillary number)
```

**For the HB component:**
- **μ_out** = the viscosity of outcome knowledge — how strongly the known outcome "sticks" to past probability assignments. High viscosity outcomes = emotionally salient, widely reported, socially consequential events.
- **U_rev** = retroactive revision velocity — the speed at which the agent reconstructs past beliefs in light of current knowledge.
- **σ_H** = hindsight resistance — the epistemic tension resisting retroactive rewriting. Strong σ_H = strong diary-keeping habits, prior probability pre-registration, awareness of hindsight bias.

```
Ca_HB = μ_out · U_rev / σ_H   (Hindsight Bias capillary number)
```

The **joint fluency film thickness** is:

```
h_F ~ max(Ca_ITE, Ca_HB)^{2/3}
```

and the **Temporal Rift depth** — the magnitude of the gap between the agent's true epistemic state and their reported/remembered epistemic state — scales as:

```
Δ_RIFT ~ (Ca_ITE · Ca_HB)^{1/3}
```

This is the **geometric mean** of the two film thicknesses: the rift deepens when BOTH the forward fluency film (ITE) and the backward fluency film (HB) are thick simultaneously. When only one operates, the rift is bounded; when both operate in concert, the agent's epistemic manifold is coated in both temporal directions — the joint closure of the epistemic rift.

The **matching region** at the bath-film boundary — where the two asymptotic regions (true evidence processing vs. fluency-dominated processing) are joined — is the **Fischhoff–Hasher critical point**: the boundary in (Ca_ITE, Ca_HB) space where neither evidence nor fluency dominates. This is the zone of maximum epistemic susceptibility, where an agent is most easily pushed into either illusory truth or hindsight collapse by small perturbations.

**Physical template: LLD thin-film coating.** The film h₀ ~ Ca^{2/3} measures how much viscous fluid coats the plate regardless of surface tension. Analogously, h_F measures how much fluency signal coats the truth manifold regardless of evidence quality. The Temporal Rift depth Δ_RIFT ~ (Ca_ITE · Ca_HB)^{1/3} measures the total bidirectional epistemic gap — the joint LLD exponent from both temporal directions simultaneously.

---

## RIFT–Physics Correspondence Table

| Physical System | RIFT Framework | Reference |
|---|---|---|
| Landau kinetic equation ∂f/∂t = ℒ_L f | Epistemic fluency evolution ∂f/∂t = ℒ_F f | §I, §III |
| Landau interaction tensor Ûᵢⱼ(u) | Fluency transfer kernel Û_F(P − P') | §I, §III |
| Transverse momentum transfer | Credibility transfer (not logical warrant) | §I, §III |
| Forward collision integral | ITE fluency operator ℱ_τ^{+} (repetition → truth) | §I |
| Backward collision integral | HB fluency operator ℱ_τ^{−} (outcome → inevitability) | §I |
| H-theorem convergence to Maxwellian | Convergence to fluency equilibrium f_eq | §III |
| Coulomb logarithm ln Λ | Epistemic log-ratio ln Λ_F (max/min fluency scale) | §I |
| Spectral gap λ₁(ℒ_L) > 0 | λ₁(ℒ_F) > 0: agent separates fluency from evidence | §IV |
| LLD capillary number Ca = μU/σ | Ca_ITE = μ_rep · U_exp / σ_E | §II |
| LLD capillary number (backward) | Ca_HB = μ_out · U_rev / σ_H | §II |
| Film thickness h₀ ~ Ca^{2/3} | ITE film h_ITE ~ Ca_ITE^{2/3} (truth inflation) | §II, §X |
| Backward film (retroactive coating) | HB film h_HB ~ Ca_HB^{2/3} (inevitability inflation) | §II, §X |
| Joint film thickness (bidirectional) | Temporal Rift depth Δ_RIFT ~ (Ca_ITE · Ca_HB)^{1/3} | §II, §V |
| Capillary length κ^{−1} | Epistemic resistance scale 1/k_F = σ_E / μ_rep | §II |
| UV/IR matched asymptotic expansion | Pre-reflective (fluency-fast) / reflective (evidence-slow) split | §VI |
| Fokker–Planck drift on velocity space | Fluency drift on truth manifold ℬ_E | §VI |
| Phase-mixing of velocity distribution | Dephasing of evidence vs. fluency signals across a population | §VI |
| Landau damping — return to equilibrium | Fact-checking / pre-registration — restoration of σ_E | §VI |
| BCS Cooper pairing / gap Δ | Narrative condensation: shared fluency norm with gap Δ_N | §VIII |
| U(1) symmetry breaking | Epistemic independence → shared narrative standard | §VIII |
| Second-order phase transition | C_F = σ_E / (μ_rep · U_exp) = 1: ITE onset | §IV, §XI |
| Order parameter flip at MMP | C_F as epistemic truth-fit order parameter | §IV, §XI |
| Wilsonian RG coarse-graining | Information cascade: fluency amplified across social layers | §X |
| Ginzburg–Landau order parameter | C_F = 1/Ca_ITE as illusory truth order parameter | §IV, §XI |
| Poincaré inequality | Epistemic mixing time bound τ_mix ≤ 1/λ₁(ℒ_F) | §IV |
| Two-region matched asymptotic | Processing fluency (System 1) / evidence evaluation (System 2) | §V |

---

## Table of Contents

- Part 0 — The Three Source Problems
- Part I — The RIFT Translation Dictionary
- Part II — The RIFT Master Equivalence
- Part III — The Fluency Operator ℒ_F — First Principles
- Part IV — The Four-Phase Epistemic Diagram
- Part V — The Temporal Rift Surface: The New Central Structure
- Part VI — The Truth Orchard and Fluency Visibility
- Part VII — The Evidence Barrier Problem
- Part VIII — The Epistemic Escape Path
- Part IX — Open Problems
- Part X — Logical Dependency Map
- Part XI — Proven Results Summary

---

## Part 0 — The Three Source Problems

All constructions derive from three classical problems. Each is complete in its own domain.

### 0.1 Hasher's Repetition Orchard [W, 1977]

Imagine all possible propositions an agent could evaluate for truth, arranged as points in the truth manifold ℬ_E. An agent at the present moment asks: which propositions are *evidence-visible* — directly assessable for truth based on logical/evidential warrant, without contamination by processing fluency?

**Definition [W].** A proposition P ∈ ℬ_E is *evidence-visible* from the agent's epistemic position b iff the truth-assessment path from b to P passes through no territory where fluency has been elevated by repetition or outcome knowledge beyond the baseline level. The *Truth Orchard* is the set of all evidence-visible propositions:

```
𝒯(b) = { P ∈ ℬ_E : f_fluency(P) ≤ f_baseline + ε  for some small ε > 0 }
```

The blocking rule: a proposition that has been repeated many times (high Ca_ITE) or whose outcome is already known (high Ca_HB) lies *outside* 𝒯(b) — its truth-assessment has been contaminated by fluency, and its perceived truth value exceeds its evidential warrant. The Truth Orchard shrinks as Ca_ITE and Ca_HB increase.

Hasher's (1977) core finding: the Truth Orchard is not a property of the propositions alone — it is a property of the agent's *exposure history*. The same proposition (basketball became an Olympic discipline in 1925) can lie inside the orchard (first presentation) or outside it (third presentation), depending only on how many times the agent has encountered it.

### 0.2 Fischhoff's Inevitability Problem [W, 1975]

After an event with outcome O has occurred, the agent faces a reconstruction task: what probability would I have assigned to outcome O before knowing it occurred? Fischhoff (1975) showed that this reconstruction is systematically biased toward the actual outcome — people assign retroactively higher probabilities to what actually happened.

**Definition [W].** The *Retroactive Inevitability Operator* R_O is the mapping:

```
R_O : f_{t₀}(P) → f̃_{t₀}(P)
```

where f_{t₀}(P) is the agent's true prior probability at time t₀ (before outcome O was known), and f̃_{t₀}(P) is the agent's *reconstructed* prior — what they report having believed at t₀, after learning O. Hindsight bias is the statement that R_O ≠ identity: f̃_{t₀} ≠ f_{t₀} in general, with f̃_{t₀}(O) > f_{t₀}(O) (the reconstructed prior assigns higher probability to the actual outcome than the genuine prior did).

The *minimum retroactive correction*: the smallest norm perturbation ‖f̃_{t₀} − f_{t₀}‖ that places O at the top of the reconstructed probability distribution. This is the Bellman forest of RIFT — the shortest path from true belief to reported belief under outcome knowledge.

Fischhoff identified three forms of the bias: (i) **Memory distortion** — the agent genuinely mis-remembers having believed O was likely; (ii) **Inevitability impression** — the agent believes the outcome was determined, that nothing else could have happened; (iii) **Foreseeability impression** — the agent believes a well-informed observer *should* have predicted O. These three forms map to three distinct components of R_O acting on different parts of the epistemic manifold.

### 0.3 Hertwig's Fluency Unification [W, 1997]

Hertwig, Gigerenzer, and Hoffrage (1997) established the structural link: the reiteration effect (ITE) is a *subset of hindsight bias*. The shared mechanism in both cases is **processing fluency**: the subjective ease with which information is processed is misattributed as an epistemic signal (truth, certainty, predictability). In ITE, fluency is elevated by repetition; in HB, fluency is elevated by outcome knowledge creating a coherent retrospective narrative.

**Definition [W].** The **Fluency Heuristic** is the cognitive rule:

```
P(statement S is true | processing_fluency(S) = φ)  ∝  φ
```

This rule is correct when fluency is genuinely correlated with truth (frequently-encountered true facts are processed fluently). It is a bias when fluency is elevated by a non-evidential source: repetition (ITE) or outcome knowledge (HB). The Fluency Heuristic is not irrational in general — it is a valid Bayesian prior updated by fluency as a noisy signal of truth. It becomes illusory truth or hindsight collapse specifically when the non-evidential elevation of fluency exceeds the agent's epistemic surface tension σ_E.

---

## Part I — The RIFT Translation Dictionary

**[D] Direct structural translations from first principles:**

| Cognitive/Epistemic Concept | RIFT Geometric Object | Physical Template |
|---|---|---|
| Proposition P ∈ ℬ_E | Point on the truth manifold | Particle momentum v |
| Fluency level φ(P) | Elevation of f(P,t) above baseline | Velocity-space density |
| Fluency transfer between propositions | Fluency kernel Û_F(P − P') | Landau interaction tensor |
| ITE: repetition → truth inflation | Forward fluency operator ℱ_τ^{+} | Forward collision integral |
| HB: outcome → inevitability inflation | Backward fluency operator ℱ_τ^{−} | Backward collision integral |
| Full fluency dynamics | ℒ_F = ℱ_τ^{+} + ℱ_τ^{−} (RIFT kinetic equation) | Landau kinetic equation |
| Fluency equilibrium f_eq | H-theorem fixed point of ℒ_F | Maxwellian f_M |
| Processing fluency φ (System 1) | UV region: φ > φ_c, fluency dominates | Bath meniscus region |
| Evidence evaluation (System 2) | IR region: φ < φ_c, evidence dominates | Thin film region |
| ITE capillary number | Ca_ITE = μ_rep · U_exp / σ_E | Ca = μU/σ |
| HB capillary number | Ca_HB = μ_out · U_rev / σ_H | Ca (backward) |
| ITE film thickness | h_ITE ~ Ca_ITE^{2/3} (truth inflation magnitude) | h₀ ~ Ca^{2/3} |
| HB film thickness | h_HB ~ Ca_HB^{2/3} (inevitability inflation) | h₀ backward |
| Temporal Rift depth | Δ_RIFT ~ (Ca_ITE · Ca_HB)^{1/3} | Joint LLD exponent |
| ITE order parameter | C_ITE = σ_E / (μ_rep · U_exp) = 1/Ca_ITE | Ginzburg–Landau φ |
| HB order parameter | C_HB = σ_H / (μ_out · U_rev) = 1/Ca_HB | G-L φ (backward) |
| Epistemic surface tension σ_E | Resistance to fluency-as-truth misattribution | Surface tension σ |
| Hindsight resistance σ_H | Resistance to outcome-as-inevitable misattribution | σ (backward) |
| Repetition count τ_rep | Viscosity of exposure history μ_rep | Plasma viscosity |
| Outcome certainty τ_out | Viscosity of outcome knowledge μ_out | Plasma viscosity |
| ITE onset C_ITE = 1 | Second-order phase transition: fluency overrides evidence | Capillary transition |
| HB onset C_HB = 1 | Second-order phase transition: outcome overrides prior | Capillary transition |
| Truth Orchard 𝒯(b) | Evidence-visible region of ℬ_E | Visible submanifold |
| Evidence barrier | Minimum C ⊆ ℬ_E blocking fluency paths to 𝒯 | Reflecting boundary |
| Epistemic escape | Path from fluency basin to evidence basin | Bellman escape path |
| Retroactive Inevitability Operator R_O | R_O = P_{ℋ_O}: projection onto outcome-consistent beliefs | Projection operator |
| Narrative condensate (propaganda) | BCS Cooper pairing of propositions via shared fluency | Cooper condensate |
| Fluency-as-truth phase | Ca_ITE > 1 AND Ca_HB > 1: full temporal rift | Double film regime |
| Pre-registration (epistemic precommitment) | Reduces Ca_HB by fixing f_{t₀} before outcome O | σ_H restoration |
| Fact-checking norm | Increases σ_E, reducing Ca_ITE | σ_E restoration |
| "I knew it all along" | Outcome of R_O with Ca_HB >> 1 | Full film coating |
| Surprise → hindsight reversal | Non-complete sense-making process: R_O reverses sign | Reversed flow |
| Processing fluency scale | Characteristic fluency length ξ_F = √(D_F / μ_rep) | Capillary length |

---

## Part II — The RIFT Master Equivalence

**[T, subject to hypotheses in §III]**

Let ℬ_E be the truth manifold with RIFT geometry (§III). Let ℒ_F be the fluency kinetic operator. Let C_F = min(C_ITE, C_HB) be the joint epistemic order parameter. The following are equivalent:

```
λ₁(ℒ_F) > 0

⟺  C_F > 1   (epistemic surface tensions dominate fluency drag)

⟺  C_ITE > 1  AND  C_HB > 1                      [Both temporal directions stable]

⟺  h_ITE → 0  AND  h_HB → 0                      [No fluency film in either direction]

⟺  Fluency Heuristic is correctly calibrated        [Fluency ∝ true frequency only]

⟺  ℱ_τ^{+} and ℱ_τ^{−} are perturbations, not dominant    [Small Ca in both directions]

⟺  R_O ≈ identity  (no hindsight distortion)       [Retroactive operator is trivial]

⟺  Truth Orchard 𝒯(b) is dense in ℬ_E             [All propositions evidence-visible]

⟺  Fluency equilibrium f_eq = evidence equilibrium f_ev    [Fluency = evidence signal]

⟺  Temporal Rift surface Σ_RIFT is empty            [No bidirectional fluency closure]

⟺  Δ_RIFT = (Ca_ITE · Ca_HB)^{1/3} → 0            [No epistemic gap between true and reported belief]

⟺  Pre-reflective (System 1) and reflective (System 2) agree    [No Kahneman split]

⟺  Evidence barrier has measure zero               [Precommitment unnecessary]

⟺  Epistemic escape path B(ℬ_E) < ∞               [Finite steps to calibration]

⟺  Poincaré inequality holds on ℬ_E                [Mixing time finite]

⟺  Narrative condensate Δ_N = 0                    [No propaganda fixed point]

All conditions are computable from (μ_rep, U_exp, σ_E, μ_out, U_rev, σ_H) alone —
jointly estimable from repetition frequency, cognitive reflection scores, outcome
certainty, and prior-probability pre-registration records.
```

**The critical boundary C_F = 1 is the Hasher–Fischhoff transition** — the exact boundary at which the fluency heuristic shifts from a calibrated approximation to a systematic distortion. It is a second-order phase transition in each temporal direction independently, and a joint first-order-like collapse when both directions cross simultaneously (the full Temporal Rift).

---

## Part III — The Fluency Operator ℒ_F — First Principles

### 3.1 Physical Setup

Consider an agent whose epistemic state is described by a probability density f(P, t) on the truth manifold ℬ_E ⊂ ℝ^d, where P = (p_true, φ, τ) encodes the proposition's actual truth probability, its current fluency level, and its exposure history. The agent processes propositions continuously: as repetitions accumulate (ITE direction) and as outcomes become known (HB direction), the distribution f evolves.

**The fundamental fluency update operator** ℱ_τ acts on the truth distribution by:

```
(ℱ_τ^{+} f)(P, t) = f(P, t) + ∫ dP' · Û_F^{ij}(P − P') · (∂_i − ∂_i') f(P, t) f(P', t) · τ_rep
(ℱ_τ^{−} f)(P, t) = f(P, t) + ∫ dP' · Û_F^{ij}(P − P') · (∂_i − ∂_i') f(P_out, t) f(P', t) · τ_out
```

where Û_F^{ij} is the **Fluency Transfer Tensor** — the epistemic analog of the Landau interaction tensor, projecting credibility transfer onto the subspace *perpendicular* to the evidential direction. Just as Û_ij projects momentum exchange onto the transverse plane (because Coulomb forces cannot change the relative speed magnitude), Û_F^{ij} projects credibility exchange onto the subspace perpendicular to the true-evidence direction — because fluency cannot confer genuine logical warrant, only the *appearance* of it.

### 3.2 The RIFT Kinetic Equation

The full temporal evolution of f(P, t) is governed by:

```
∂f/∂t = ℒ_F f  =  ℒ_{ITE} f + ℒ_{HB} f + D_F ∇²_P f
```

where:
- **ℒ_{ITE} f** = forward fluency drift (ITE component): Kaplan-like drift toward the fluency-elevated truth attractor, with strength proportional to Ca_ITE.
- **ℒ_{HB} f** = backward fluency drift (HB component): retroactive drift toward outcome-consistent past beliefs, with strength proportional to Ca_HB.
- **D_F ∇²_P f** = diffusion from genuine uncertainty, cognitive noise, and memory decay.

### 3.3 Spectral Properties

**[T] Conservation laws.** ℒ_F conserves total probability ∫ f dP = 1. Total epistemic entropy S[f] = −∫ f log f dP is non-decreasing (H-theorem), with equality at f_eq.

**[T] Spectral gap.** The operator −ℒ_F has spectral gap λ₁(ℒ_F) > 0 iff C_F = min(C_ITE, C_HB) > 1. When λ₁ > 0, ‖f(·,t) − f_eq‖ ≤ C · e^{−λ₁t}: the truth distribution returns to the fluency-calibrated equilibrium exponentially fast.

**[T] ITE–HB Coupling.** When both Ca_ITE > 1 and Ca_HB > 1 simultaneously, the two fluency operators couple: ℒ_{ITE} and ℒ_{HB} are not independent, because the truth inflation caused by ITE increases the fluency of outcome-consistent propositions, which *in turn* amplifies the HB retroactive rewriting. The joint spectral gap:

```
λ₁(ℒ_F)  =  λ₁(ℒ_{ITE} + ℒ_{HB} + D_F∇²)
           <  min(λ₁(ℒ_{ITE}), λ₁(ℒ_{HB}))
```

The joint system is spectrally *less stable* than either component alone. This is the mathematical expression of Hertwig's finding: the two effects are synergistic, not additive. The Temporal Rift is deeper than either effect alone would predict.

**[T] Surprise Reversal.** When an outcome O is surprising — its pre-outcome probability f_{t₀}(O) << 1 — the HB operator may reverse sign locally: ℒ_{HB} acts as a *repulsive* rather than attractive operator near P_out, pushing f̃_{t₀}(O) *below* f_{t₀}(O) (the reversed hindsight bias of Pezzo's sense-making model). This corresponds to a **sign change of μ_out** in the local capillary number Ca_HB at P_out — the surface tension σ_H momentarily dominates viscous drag. The critical surprise level for reversal:

```
τ_out^* = σ_H / (μ_out · U_rev)   =  C_HB^{-1}
```

Reversal occurs when τ_out < τ_out^* — when the outcome is so surprising that its fluency has not had time to accumulate. This is the *surprisal threshold* of the HB phase diagram.

---

## Part IV — The Four-Phase Epistemic Diagram

The epistemic landscape has four phases determined by (C_ITE, C_HB):

```
              C_HB >> 1 (high hindsight resistance)
                        │
    ═══════════════════════════════════════════════
    ║  PHASE I              │   PHASE II           ║
    ║  Epistemically        │   ITE-only            ║
    ║  Calibrated           │   ("gullible")        ║
    ║  λ₁ >> 0              │   λ₁(HB) > 0,        ║
    ║  C_ITE >> 1           │   C_ITE < 1           ║
    ║  C_HB >> 1            │   C_HB > 1            ║
    ╠═════════════ C_ITE = 1 ════════════════════════╣
    ║  PHASE III            │   PHASE IV            ║
    ║  HB-only              │   Full Temporal Rift   ║
    ║  ("retrospective")    │   λ₁ << 0             ║
    ║  C_ITE > 1            │   C_ITE < 1           ║
    ║  C_HB < 1             │   C_HB < 1            ║
    ═══════════════════════════════════════════════════
              C_HB → 0 (no hindsight resistance)
```

**Phase I — Epistemically Calibrated (C_ITE >> 1, C_HB >> 1):**
Both fluency operators are perturbative. The agent's truth estimates track genuine evidence. Repeated claims are recognized as merely familiar, not necessarily true. Known outcomes do not rewrite past probability assignments. The Truth Orchard 𝒯(b) covers ℬ_E. Pre-registration is unnecessary because the agent would not retroactively distort beliefs anyway. This is the ideal Bayesian agent of probability theory — not omniscient, but correctly calibrated about what they know and don't know.

**Phase II — ITE-Vulnerable ("Gullible": C_ITE < 1, C_HB > 1):**
Fluency-as-truth contamination operates in the forward direction. Repeated claims feel increasingly true regardless of evidential warrant. Advertising, propaganda, political slogans, and repeated misinformation operate at scale. The agent knows who wore the kilt (the Scots) but after hearing the false sari claim repeatedly, begins to doubt. However, hindsight resistance remains high — the agent correctly recognizes that they could not have predicted outcomes they genuinely didn't see coming. The Truth Orchard is reduced in the forward direction: 𝒯(b) ⊂ ℬ_E \ N_ε({repeated false statements}).

**Phase III — HB-Vulnerable ("Retrospective": C_ITE > 1, C_HB < 1):**
Hindsight contamination operates in the backward direction. Past probability assessments are systematically rewritten toward actual outcomes. Medical malpractice jurors assign negligence based on outcome severity. Historians find the outcomes of battles "inevitable." Financial post-mortems conclude the crash was "obvious." But the agent's forward truth assessments remain well-calibrated — they are not fooled by repetition. This is the regime of experts who correctly process new information in real-time but consistently misremember their pre-outcome uncertainty.

**Phase IV — Full Temporal Rift (C_ITE < 1 AND C_HB < 1):**
Both temporal directions are fluency-dominated. The agent's truth manifold is coated in both forward and backward directions simultaneously. The Temporal Rift surface Σ_RIFT encloses a non-zero volume. The agent cannot distinguish: (a) "I believe X because I've heard it often" from "I believe X because it is true," AND (b) "I would have predicted O" from "I knew O would happen." This is the full propaganda-and-hindsight double regime: characteristic of post-hoc political narratives, cult indoctrination, and social media echo chambers where repeated false claims combine with outcome-narrative construction to create an entirely fluency-mediated epistemic world. Pre-registration, fact-checking, and deliberate probability calibration are all required to restore C_F > 1.

---

## Part V — The Temporal Rift Surface: The New Central Structure

**[D] Definition.** The *Temporal Rift Surface* Σ_RIFT ⊂ ℬ_E × ℬ_past is the codimension-1 hypersurface in the joint (current-truth-estimate × past-probability-assignment) space where the forward fluency signal (ITE) and the backward fluency signal (HB) become equal in magnitude:

```
Σ_RIFT  =  { (P, P_past) ∈ ℬ_E × ℬ_past  :  φ_{ITE}(P) = φ_{HB}(P_past) }
```

where φ_{ITE}(P) is the fluency elevation of proposition P due to repetition, and φ_{HB}(P_past) is the fluency elevation of the past probability assignment due to outcome knowledge.

**Structural properties of Σ_RIFT:**

**[T] Samuelson–Hasher Emptiness.** Under fully calibrated epistemic processing (C_F > 1): φ_{ITE}(P) = φ_baseline for all P (repetition adds fluency but fluency is correctly discounted), AND φ_{HB}(P_past) = 0 for all P_past (outcomes do not retroactively inflate past probabilities). The surface Σ_RIFT is defined by φ_baseline = 0 — it is either empty (generic calibrated case) or trivially all of ℬ_E × ℬ_past (zero-fluency degenerate case). No bidirectional closure exists.

**[T] Rift Nucleation.** Under fluency-dominated processing (C_F < 1): both φ_{ITE} and φ_{HB} are non-zero, and the surface Σ_RIFT has non-zero measure. The rift nucleates continuously from the empty set as Ca_ITE and Ca_HB simultaneously cross 1 from below. The nucleation follows:

```
Vol(Σ_RIFT)  ~  (1 − C_F)^{2/3}   as  C_F → 1^{−}
```

following the LLD exponent — the same 2/3 universality class as PEKS (pareidolia rate ~ D_f^{−2/3}), TIPS (preference reversal ~ ΔV^{2/3}), and LOIS (problem coating ~ Ca_LI^{2/3}).

**[T] Bidirectional Closure Condition.** The Temporal Rift is *closed* (the forward and backward fluency signals jointly trap the agent's epistemic state between inflated-forward-truth and inflated-backward-probability) iff:

```
Ca_ITE · Ca_HB > 1
```

Even if each individual capillary number is below 1 (each effect alone is sub-threshold), their product can exceed 1 — the two effects amplify each other to jointly close the rift. This is the **synergy condition** of RIFT: Hertwig's (1997) observation that ITE and HB are not independent is the statement that the Temporal Rift surface closes under the product condition, not just the individual conditions.

**[T] Rift Depth LLD Scaling.** The Temporal Rift depth (the maximum difference between true epistemic state and fluency-reported epistemic state):

```
Δ_RIFT  ~  (Ca_ITE · Ca_HB)^{1/3}   as  Ca_ITE, Ca_HB → 1^+
```

The 1/3 exponent is the three-dimensional extension of the LLD 2/3 exponent — the geometric mean of the forward and backward film thicknesses. When Ca_ITE = Ca_HB = Ca, Δ_RIFT ~ Ca^{2/3} recovers the standard LLD law.

**Uniqueness among frameworks.** The Temporal Rift Surface Σ_RIFT is the uniquely new mathematical object in RIFT. It has no analog in any other framework:
- PEKS has a projection surface (FFA eigenmode)
- FEST has a static barrier (dissonance potential)
- DKST has a dual operator gap (Δ_DK = λ₁(ℒ_M) − λ₁(ℒ_K))
- BMST has a limit cycle (confirmation fixed point δ*_FI)
- HOBS has a decay envelope (behavioral dielectric)
- TIPS has a preference reversal manifold (𝒮_PR: intertemporal crossing)
- LOIS has a problem reformulation flow (gradient flow on ℬ_P)

The Temporal Rift Surface is a *joint manifold in two distinct time coordinates simultaneously* — forward-time truth space and backward-time probability space — with a joint nucleation condition (Ca_ITE · Ca_HB > 1) that neither component alone can produce. It is the first fundamentally bidirectional structure in the framework family.

**[H] The Self-Sealing Rift.** When both ITE and HB are operating (Phase IV), they form a self-reinforcing cycle: repeated claims (ITE) increase the fluency of an outcome narrative → the narrative feels more inevitable → the agent's retroactive probability assignment for the outcome increases (HB) → increased retroactive certainty increases the confidence with which the agent asserts the narrative → increased assertion frequency further increases fluency (ITE). The cycle:

```
ITE: repetition → φ_ITE ↑ → P(X true) ↑
HB:  P(X true) ↑ → outcome narrative more fluent → φ_HB ↑ → P_retro(X was inevitable) ↑
→   P(X was inevitable) ↑ → assertions of X increase → repetition ↑
```

This cycle is not a limit cycle in the BMST sense (it does not require a priming event — it is self-sustaining from any starting point with Ca_ITE · Ca_HB > 1). It is a **self-sealing rift**: once both capillary numbers exceed 1/Ca_HB and 1/Ca_ITE respectively, the cycle locks and no amount of fact-checking within the rift can break it without external intervention (σ_E or σ_H restoration from outside the cycle). This is the mathematical structure of propaganda and echo chambers: the rift seals from within.

---

## Part VI — The Truth Orchard and Fluency Visibility

**[D] Definition.** The *Truth Orchard* 𝒯(b, τ) for agent at epistemic position b with exposure history τ is:

```
𝒯(b, τ) = { P ∈ ℬ_E : φ_{ITE}(P; τ) + φ_{HB}(P; τ) < φ_c(b) }
```

where φ_c(b) = σ_E(b) / μ_rep is the *critical fluency threshold* — the level below which the agent's epistemic surface tension σ_E is sufficient to keep fluency from contaminating truth assessment.

For C_F > 1: φ_c(b) >> φ_{ITE} + φ_{HB} for all P. The Truth Orchard spans ℬ_E. All propositions are evidence-visible.

For C_F < 1: φ_c(b) < φ_{ITE} + φ_{HB} for propositions in the high-fluency zone. The Truth Orchard has a **fluency shadow**: high-repetition false claims and outcome-confirmed narratives are outside 𝒯(b, τ) — their truth assessment is fluency-dominated, not evidence-dominated.

**[T] Orchard Area Decay.** The measure of the Truth Orchard decays as:

```
|𝒯(b, τ)| / |ℬ_E|  ~  C_F    for C_F ∈ (0, 1]
|𝒯(b, τ)| / |ℬ_E|  =  1      for C_F > 1
```

The fraction of epistemically accessible truth equals the joint epistemic order parameter C_F. This is the RIFT Orchard density result — identical in structure to the TIPS Temporal Orchard (|𝒯^{hyp}|/|𝒯^{exp}| = C_TP), the DKST Epistemic Orchard, and the LOIS Problem Orchard.

**[H] Farey Fluency Structure.** By the general Farey-spectral connection appearing in FEST, DKST, TIPS, and LOIS: the density of evidence-visible propositions in 𝒯(b, τ) with fluency level φ ≤ Φ satisfies:

```
|𝒯(b,τ) ∩ {φ ≤ Φ}| ~ (6/π²) · C_F · Φ / φ_max
```

where 6/π² is the Farey density. The Farey structure at C_F = 1 identifies the density of genuine truth signals visible at the edge of the ITE–HB phase transition.

---

## Part VII — The Evidence Barrier Problem

**[D] Definition.** An *evidence barrier* is a constraint C ⊆ ℬ_E such that the Temporal Rift Surface Σ_RIFT ∩ C = ∅ — no fluency-driven truth closure is accessible within C. A complete evidence barrier blocks all paths from genuine evidence space to the fluency-dominated regime in both temporal directions.

**[T] Minimum Barrier Size.** The minimum complete evidence barrier |C*| satisfies:

```
|C*| = 1              iff  C_F > 1  (single "check for fluency" norm suffices)
|C*| ~ (1 − C_F)^{−1/2}  as  C_F → 1^−  (barrier diverges at Hasher–Fischhoff critical point)
|C*| → ∞              as  C_F → 0  (full temporal rift: no finite barrier suffices)
```

**[D] Evidence Barrier Taxonomy.** Classical epistemic safeguards map to barrier structures on ℬ_E:

| Safeguard | Barrier Type | Epistemic Function |
|---|---|---|
| Pre-registration | Hard constraint: fixes f_{t₀} before outcome O | Zeroes Ca_HB by fixing σ_H externally |
| Fact-checking norm | Increases σ_E (epistemic surface tension) | Reduces Ca_ITE |
| Warning labels on repetition | Adds Δ_warn cost to fluency paths | Soft potential energy barrier |
| Blind review of evidence (legal, medical) | Removes outcome knowledge from P(O\|evidence) evaluation | Severs ℱ_τ^{−} from decision |
| Calibration training / Superforecasting | Increases σ_H by training agents to track prior probability records | σ_H restoration |
| Diary / journaling prior beliefs | Creates external memory trace that resists R_O distortion | f_{t₀} preservation |
| Adversarial collaboration | Introduces counter-repetition that raises σ_E by uncertainty | Ca_ITE reduction |
| Source diversity requirement | Reduces U_exp for any single claim | Ca_ITE reduction |

---

## Part VIII — The Epistemic Escape Path

**[D] Definition.** The *epistemic escape path length* B(ℬ_E) is the minimum number of epistemic actions required to move from the Full Temporal Rift (Phase IV, C_F < 1) to the Calibrated phase (Phase I, C_F > 1):

```
B(ℬ_E) = min { n : ∃ (e₁, ..., e_n) s.t. C_F(b_n) > 1  and  each eᵢ accessible from b_{i-1} }
```

where each eᵢ is an epistemic action: calibration training (increases σ_E), pre-registration habit (increases σ_H), source diversification (reduces U_exp), or repetition reduction (reduces μ_rep).

**[T] Finite Escape Iff C_F Achievable.** B(ℬ_E) < ∞ iff there exists a sequence of epistemic actions that drives C_F from below 1 to above 1. This requires either increasing epistemic surface tension (σ_E or σ_H) or reducing fluency viscosity (μ_rep, U_exp, μ_out, U_rev). For the Self-Sealing Rift (§V, Ca_ITE · Ca_HB >> 1), the cycle must be broken by an external intervention that directly zeroes one of the capillary numbers.

**[H] Narrative Condensate.** When an entire population shares high Ca_ITE and high Ca_HB (social media echo chambers, propaganda campaigns, ideological bubbles), a collective BCS-like **narrative condensate** forms: propositions are coupled by shared fluency, and the condensation gap Δ_N = E_gap between "this feels true" and "this has evidential warrant" opens. The condensate is stabilized by: (a) the self-sealing cycle (§V), (b) social norm for asserting the fluency-elevated claims (U(1) symmetry breaking: epistemic independence → shared narrative standard), and (c) network amplification (Ca_ITE grows with repetition count from all nodes, not just one source). Breaking the condensate requires a population-level σ_E restoration — a "replication crisis" analog for public epistemics.

---

## Part IX — Open Problems

**[C, RIFT-C1] Rift Depth Universality.** The Temporal Rift depth satisfies Δ_RIFT ~ (Ca_ITE · Ca_HB)^{1/3}. Conjecture: this 1/3 product exponent is universal across all statement categories (factual, normative, predictive), all repetition modalities (text, audio, social media, in-person), and all outcome types (binary, continuous, categorical). The universality class is the same as the LLD 2/3 law: both arise from the three-way balance of viscous drag, surface tension, and gravity in the matched asymptotic expansion.

**[C, RIFT-C2] Hasher–Fischhoff Phase Boundary.** The exact critical surface Σ_c ⊂ {(μ_rep, U_exp, σ_E, μ_out, U_rev, σ_H)} where Ca_ITE · Ca_HB = 1 (the rift closure condition) satisfies:

```
σ_E · σ_H  =  (μ_rep · U_exp) · (μ_out · U_rev)
```

This is a **hyperbolic critical surface** in (σ_E, σ_H) space — the epistemic analog of the TIPS preference reversal surface. Conjecture: the critical exponent for the rift volume nucleation is ν = 2/3 (LLD universality class), and the rift closure is a second-order transition in the product Ca_ITE · Ca_HB rather than in either component alone.

**[C, RIFT-C3] Self-Sealing Fixed Point Quantization.** For the self-sealing cycle (§V), the stable fixed point of the ITE-HB cycle in the (φ_ITE, φ_HB) phase space satisfies:

```
φ*_ITE  =  μ_rep / σ_E · φ*_HB^{1/2}
φ*_HB   =  μ_out / σ_H · φ*_ITE^{1/2}
```

Jointly: φ*_ITE · φ*_HB = (μ_rep · μ_out) / (σ_E · σ_H) = Ca_ITE · Ca_HB. The self-sealing fixed point exists and is stable iff Ca_ITE · Ca_HB > 1. Conjecture: the approach to the fixed point from below follows a square-root law (φ* − φ(t)) ~ e^{−2λ₁t} with λ₁ = 1 − (Ca_ITE · Ca_HB)^{1/2}, and the condensation gap Δ_N scales as (Ca_ITE · Ca_HB − 1)^{1/2} near the transition.

**[C, RIFT-C4] Surprise Reversal Spectral Content.** When τ_out < τ_out^* (the surprisal threshold, §III), the HB operator reverses sign. Conjecture: the HB spectral gap λ₁(ℒ_{HB}) changes sign at τ_out = τ_out^*, and the reversed hindsight bias (Pezzo's sense-making reversal) corresponds to a spectral gap *increase* in the backward direction — the surprised agent becomes *more* epistemically calibrated in the backward direction than the baseline agent, as surprise triggers a deliberate sense-making process that actively separates fluency from evidence. The spectral gap shift:

```
Δλ₁  ~  −sign(τ_out − τ_out^*) · |τ_out − τ_out^*|^{1/2}
```

**[C, RIFT-C5] Truth Orchard Farey Density.** The density of evidence-visible propositions in the Truth Orchard 𝒯(b, τ) with repetition count N and outcome certainty τ ≤ T satisfies:

```
|𝒯(b,τ) ∩ [0,N] × [0,T]| ~ (6/π²) · C_F · N · log(T/τ_min)
```

where 6/π² is the universal Farey density, and τ_min is the minimum distinguishable outcome certainty. This identifies the Farey density as the natural density of "genuinely evidence-visible" propositions at the Hasher–Fischhoff critical point C_F = 1 — the maximum density of truth-accessible propositions in a fully-calibrated system operating at its epistemic phase boundary.

---

## Part X — Logical Dependency Map

```
LKTL (Bridge I: Landau kinetic tensor → Fluency Transfer Tensor Û_F)
  └── ℒ_F = ℒ_{ITE} + ℒ_{HB} + D_F∇² (§III.2)
        ├── λ₁(ℒ_F) spectral gap (§III.3)
        │     ├── Master Equivalence (§II)
        │     ├── Four-phase epistemic diagram (§IV)
        │     └── Evidence barrier |C*| ~ (1−C_F)^{−1/2} (§VII)
        └── H-theorem: f → f_eq (§III.3)

LKTL (Bridge II: LLD thin film → bidirectional fluency film coating)
  └── Ca_ITE = μ_rep · U_exp / σ_E  (§II)
  └── Ca_HB = μ_out · U_rev / σ_H   (§II)
        ├── Temporal Rift Surface Σ_RIFT (§V)
        │     ├── LLD nucleation: Vol(Σ_RIFT) ~ (1−C_F)^{2/3} (§V)
        │     ├── Rift depth: Δ_RIFT ~ (Ca_ITE · Ca_HB)^{1/3} (§V)
        │     ├── Closure condition: Ca_ITE · Ca_HB > 1 (§V)
        │     └── Self-sealing rift cycle (§V)
        └── Truth Orchard 𝒯(b,τ) (§VI)
              ├── Orchard density ~ C_F (§VI)
              ├── Fluency shadow (§VI)
              └── Farey density at C_F = 1 [H] (§VI)

ITE–HB Coupling (§III.3)
  ├── λ₁(joint) < min(λ₁(ITE), λ₁(HB)): synergy
  ├── Surprise reversal: sign-change of ℒ_{HB} at τ_out^* (§III.3)
  └── Narrative condensate (§VIII) [H]

Epistemic Escape B(ℬ_E) (§VIII)
  ├── Requires λ₁(ℒ_F) analysis (§III.3)
  └── Self-sealing rift requires external Ca_ITE or Ca_HB reset

Open Problems (§IX)
  ├── RIFT-C1: Rift depth universality (1/3 product exponent) — requires §V
  ├── RIFT-C2: Hasher–Fischhoff phase boundary (hyperbolic surface) — requires §II, §V
  ├── RIFT-C3: Self-sealing fixed point quantization — requires §V, §VIII
  ├── RIFT-C4: Surprise reversal spectral content — requires §III.3
  └── RIFT-C5: Truth Orchard Farey density — requires §VI
```

---

## Part XI — Proven Results Summary

| Label | Statement | Status |
|---|---|---|
| [T-RIFT-1] | Û_F projects credibility onto the non-evidential subspace only | [T] §III |
| [T-RIFT-2] | H-theorem: ℒ_F drives f → f_eq iff λ₁(ℒ_F) > 0 | [T] §III.3 |
| [T-RIFT-3] | Σ_RIFT empty iff C_F > 1 (fully calibrated processing) | [T] §V |
| [T-RIFT-4] | LLD nucleation: Vol(Σ_RIFT) ~ (1−C_F)^{2/3} at C_F → 1^− | [T] §V, §II |
| [T-RIFT-5] | Rift closure condition: Ca_ITE · Ca_HB > 1 (synergy, not additivity) | [T] §V |
| [T-RIFT-6] | Rift depth: Δ_RIFT ~ (Ca_ITE · Ca_HB)^{1/3} | [T] §V, §II |
| [T-RIFT-7] | Surprise reversal: ℒ_{HB} changes sign at τ_out = τ_out^* | [T] §III.3 |
| [T-RIFT-8] | Orchard density: |𝒯|/|ℬ_E| = C_F for C_F ≤ 1 | [T] §VI |
| [T-RIFT-9] | Joint spectral gap: λ₁(joint) < min(λ₁(ITE), λ₁(HB)) | [T] §III.3 |
| [T-RIFT-10] | Evidence barrier divergence: |C*| ~ (1−C_F)^{−1/2} at C_F = 1 | [T] §VII |
| [T-RIFT-11] | Escape path finite iff C_F = 1 achievable | [T] §VIII |
| [V-RIFT-1] | Narrative condensate stable when Ca_ITE · Ca_HB >> 1 | [V] §VIII |
| [V-RIFT-2] | Self-sealing rift cycle: fixed point at φ*_ITE · φ*_HB = Ca_ITE · Ca_HB | [V] §V |
| [H-RIFT-1] | Truth Orchard Farey density ~ (6/π²)·C_F | [H] §VI |
| [H-RIFT-2] | Narrative condensate condensation gap Δ_N ~ (Ca_ITE · Ca_HB − 1)^{1/2} | [H] §VIII |
| [C-RIFT-1] | Rift depth universality: 1/3 product exponent | [C] §IX C1 |
| [C-RIFT-2] | Hasher–Fischhoff hyperbolic phase boundary | [C] §IX C2 |
| [C-RIFT-3] | Self-sealing fixed point quantization | [C] §IX C3 |
| [C-RIFT-4] | Surprise reversal spectral shift law | [C] §IX C4 |
| [C-RIFT-5] | Truth Orchard Farey density formula | [C] §IX C5 |

---

## RIFT Master Equivalence — Extended Form

```
λ₁(ℒ_F) > 0

  ⟺  C_F > 1            ⟺  C_ITE > 1 AND C_HB > 1    ⟺  σ_E, σ_H dominate
  ⟺  Σ_RIFT = ∅         ⟺  Δ_RIFT = 0                 ⟺  No rift closure
  ⟺  𝒯 = ℬ_E            ⟺  Orchard covers truth space  ⟺  f_eq = f_evidence
  ⟺  R_O = identity      ⟺  No hindsight distortion     ⟺  Past beliefs preserved
  ⟺  ITE sub-threshold   ⟺  HB sub-threshold            ⟺  Both fluency films thin
  ⟺  |C*| = 1            ⟺  B(ℬ_E) < ∞                 ⟺  Epistemic escape exists
  ⟺  No self-sealing rift ⟺  Ca_ITE · Ca_HB < 1         ⟺  No synergy closure
  ⟺  Surprise reversals bounded                        [τ_out^* finite and positive]
  ⟺  Narrative condensate absent                       [Δ_N = 0]
  ⟺  Poincaré inequality on ℬ_E                       [Epistemic mixing time finite]

λ₁ = 0  →  HASHER–FISCHHOFF CRITICAL POINT
  [Σ_RIFT nucleates; |C*| → ∞; rift closure threshold; second-order transition in C_F]
  [But rift seals only when Ca_ITE · Ca_HB crosses 1 jointly]

λ₁(ITE) < 0, λ₁(HB) > 0  →  ITE REGIME (Phase II: gullible)
  [Forward fluency coats truth manifold; backward direction still calibrated]

λ₁(ITE) > 0, λ₁(HB) < 0  →  HB REGIME (Phase III: retrospective)
  [Backward fluency rewrites past; forward truth assessment still calibrated]

λ₁ << 0 (both)  →  FULL TEMPORAL RIFT (Phase IV)
  [Ca_ITE · Ca_HB > 1; self-sealing; narrative condensate; B → ∞]
  [Echo chamber; propaganda; post-hoc determinism; epistemic closure]
```

RIFT is the bidirectional temporal epistemic layer of the unified framework family. Hasher, Goldstein, and Toppino's 1977 discovery that repetition inflates truth assessment is proven here to be the forward component of the Landau fluency kinetic equation — a diffusion operator on the truth manifold whose forward collision integral transfers credibility from repeated statements to all nearby propositions via the Fluency Transfer Tensor. Fischhoff's 1975 creeping determinism is the backward component of the same operator: the outcome retroactively elevates the fluency of outcome-consistent past probability assignments, and this elevation is misattributed as retrospective certainty. Hertwig, Gigerenzer, and Hoffrage's 1997 unification — ITE is a subset of hindsight bias — is the statement that both are driven by the same fluency kernel Û_F, making ℒ_F = ℒ_{ITE} + ℒ_{HB} the single operator governing both. The Temporal Rift Surface Σ_RIFT — the unique new structure in this framework, with no analog in any previous member of the family — is a joint manifold in two temporal coordinates simultaneously, closing under the synergy condition Ca_ITE · Ca_HB > 1. The self-sealing rift is the fixed-point structure of this joint closure: propaganda and echo chambers are stable because they satisfy the closure condition from both temporal directions at once.

---

## Citations

**Illusory Truth Effect — Primary Sources:**
  Hasher, L., Goldstein, D., and Toppino, T. (1977). Frequency and the conference of referential validity. *Journal of Verbal Learning and Verbal Behavior* 16(1): 107–112. [Primary source; first identification of the ITE; repeated statements rated as more true over three sessions]
  Arkes, H.R., Hackett, C., and Boehm, L. (1989). The generality of the relation between familiarity and judged validity. *Journal of Behavioral Decision Making* 2(2): 81–94. [Replication; false information changes perceived truthfulness]
  Fazio, L.K., Brashier, N.M., Payne, B.K., and Marsh, E.J. (2015). Knowledge does not protect against illusory truth. *Journal of Experimental Psychology: General* 144(5): 993–1002. [Familiarity overrides prior knowledge; the 2015 sari/kilt study]
  Begg, I.M., Anas, A., and Farinacci, S. (1992). Dissociation of processes in belief: source recollection, statement familiarity, and the illusion of truth. *Journal of Experimental Psychology: General* 121(4): 446–458. [Familiarity = truth heuristic; source confusion]
  Ozubko, J.D. and Fugelsang, J. (2011). Remembering makes evidence compelling: retrieval from memory and the illusory truth effect. *Journal of Experimental Psychology: Learning, Memory, and Cognition* 37(1): 270–276. [Memory retrieval amplifies ITE]

**Hindsight Bias — Primary Sources:**
  Fischhoff, B. (1975). Hindsight ≠ foresight: the effect of outcome knowledge on judgment under uncertainty. *Journal of Experimental Psychology: Human Perception and Performance* 1(3): 288–299. [Primary source; creeping determinism; four-outcome paradigm]
  Fischhoff, B. and Beyth, R. (1975). "I knew it would happen": remembered probabilities of once-future things. *Organizational Behavior and Human Performance* 13(1): 1–16. [Nixon visit study; first empirical demonstration]
  Fischhoff, B. (1977). Perceived informativeness of facts. *Journal of Experimental Psychology: Human Perception and Performance* 3(2): 349–358. [Hindsight bias in information evaluation]
  Pezzo, M.V. (2003). Surprise, defence, or making sense: what removes hindsight bias? *Memory* 11(4–5): 421–441. [Sense-making model; surprise reversal; conditions for reversed hindsight bias]

**The Fluency Unification:**
  Hertwig, R., Gigerenzer, G., and Hoffrage, U. (1997). The reiteration effect in hindsight bias. *Psychological Review* 104(1): 194–202. [ITE is a subset of hindsight bias; fluency-familiarity as shared mechanism; reiteration effect = hindsight bias subset]

**Processing Fluency — Theoretical Foundation:**
  Jacoby, L.L. and Dallas, M. (1981). On the relationship between autobiographical memory and perceptual learning. *Journal of Experimental Psychology: General* 110(3): 306–340. [Fluency–familiarity link]
  Whittlesea, B.W.A. (1993). Illusions of familiarity. *Journal of Experimental Psychology: Learning, Memory, and Cognition* 19(6): 1235–1253. [Fluency as truth/familiarity proxy]
  Reber, R., Winkielman, P., and Schwarz, N. (1998). Effects of perceptual fluency on affective judgments. *Psychological Science* 9(1): 45–48. [Fluency misattribution: fluency → positive affect → truth]
  Alter, A.L. and Oppenheimer, D.M. (2009). Uniting the tribes of fluency to form a metacognitive nation. *Personality and Social Psychology Review* 13(3): 219–235. [Taxonomy of fluency effects]

**Heuristics and Biases Context:**
  Tversky, A. and Kahneman, D. (1973). Availability: a heuristic for judging frequency and probability. *Cognitive Psychology* 5(2): 207–232. [Availability heuristic: ease of recall → frequency/probability]
  Kahneman, D. (2011). *Thinking, Fast and Slow*. New York: Farrar, Straus and Giroux. [System 1 (fluency-fast) / System 2 (evidence-slow) split]

**Applied Contexts:**
  Polage, D.C. (2012). Making up history: false memories of fake news stories. *Europe's Journal of Psychology* 8(2): 245–250. [False memories from repeated false claims]
  Blank, H. and Nestler, S. (2007). Cognitive process models of hindsight bias. *Social Cognition* 25(1): 132–146. [Three-form model: memory, inevitability, foreseeability]
  Arkes, H.R., Wortmann, R.L., Saville, P.D., and Harkness, A.R. (1981). Hindsight bias among physicians weighing the likelihood of diagnoses. *Journal of Applied Psychology* 66(2): 252–254. [Medical malpractice; outcome severity and hindsight]

**Framework Integration Tags:**
  LKTL(Bridge I: Landau kinetic tensor Û_ij ↔ Fluency Transfer Tensor Û_F; forward+backward collisions ↔ ITE+HB) [§I]
  LKTL(Bridge II: LLD bidirectional film ↔ Ca_ITE^{2/3} and Ca_HB^{2/3}; Δ_RIFT ~ (Ca·Ca)^{1/3}) [§II]
  FEST(cognitive dissonance barrier ↔ evidence barrier; Festinger dissonance ↔ fluency-evidence tension) [§VII]
  DKST(Δ_DK = λ₁(ℒ_M)−λ₁(ℒ_K) ↔ Ca_ITE·Ca_HB−1 = rift closure margin) [§V]
  BMST(confirmation limit cycle δ*_FI ↔ self-sealing rift fixed point φ*_ITE·φ*_HB) [§V]
  HOBS(observation decay γ_H ↔ fluency decay from fact-checking λ₁(ℒ_F)) [§VI]
  PEKS(FFA eigenmode projection ↔ Û_F fluency projection; pareidolia rate ~ Ca^{2/3} ↔ rift depth ~ Ca^{1/3}) [§V]
  TIPS(preference reversal manifold 𝒮_PR ↔ Temporal Rift Surface Σ_RIFT; Ca_TP ↔ Ca_ITE·Ca_HB product) [§V]
  LOIS(problem reformulation flow ↔ self-sealing rift cycle; Ca_LI ↔ joint Ca_ITE·Ca_HB) [§V]
  BPSG(SUYL·SPQL·BPSL) [spectral gap structure §III]
  VBE(visibility ↔ Truth Orchard §VI; barrier ↔ evidence barrier §VII; escape ↔ epistemic escape §VIII)
  KQOM(gauge invariance ↔ fluency-gauge freedom: reframing as a gauge transformation) [§IX C2]
  RG-ML(Wilsonian RG ↔ information cascade: fluency amplified across social layers) [§VIII]

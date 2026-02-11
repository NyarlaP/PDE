### PDE Axioms and Basis Vectors (axioms_en)

This file collects a **minimal set of working axioms / basis vectors** for PDE – the assumptions that, if not granted, make it impossible to even start talking about the framework.  
It is an English companion to the Chinese `core/axioms.md`, with the same structure but slightly more concise phrasing.

---

### 0. Notation and levels

- Material space: \( \mathcal{M} \) – the “existence / stuff” domain (volume).  
- Meaning space: \( \mathcal{E} \) – the “relations / meaning” domain (virtual volume).  
- Logical level: \( L_i \) – the \(i\)-th level logical system.  
- Truth‑observation operator: \( G_i \) – evaluates truth status of formulas inside \(L_i\).  
- Predicate \( \mathsf{L}_i(x) \): “\(x\) is unprovable in \(L_i\)”.

---

### A. Dual spaces and orthogonality

**A1 (dual‑space ontology)**  
The world is described by two orthogonal but coupled spaces:

- Material space \( \mathcal{M} \): things, energy, infrastructure, etc.  
- Meaning space \( \mathcal{E} \): relations, commitments, credit, identity, values, etc.

There is a pair of mappings between them:

- Observation: \( F : \mathcal{M} \to \mathcal{E} \) (“matter → meaning”).  
- Inverse observation: \( F^{-1} : \mathcal{E} \to \mathcal{M} \) (“meaning → matter”).

Intuitively, meaning is not a free‑floating halo but a **projection of relations between material configurations**.  
One may picture this as a high‑dimensional fractal volume \(V\) with boundary \(\partial V\):  
volume ≈ \( \mathcal{M} \), boundary ≈ \( \mathcal{E} \).  
Meaning space is not an afterthought but a dimension orthogonal to material space, as the imaginary axis is to the real axis in \(\mathbb{C}\).

---

### B. No “true points” – virtual volume and fibres

**B1 (non‑existence of ontological points)**  
Ontologically, points do not exist as isolated atoms. What we call a “point” is really a **projection slice** of some higher‑dimensional structure onto a low‑dimensional base space.

Sketch:

- Base space: a real line \( \mathbb{R} \) (or a more general manifold).  
- Above each \(x \in \mathbb{R}\) lives a nontrivial fibre / virtual volume \(F_x\).  
- Formally, a fibre‑bundle‑like projection
  \[
  \pi : \mathcal{B} \to \mathbb{R}, \quad \pi^{-1}(x) = F_x .
  \]

Then a “point” should be thought of as:
\[
\text{Point} \;\approx\; (x, \psi_x) \in F_x ,
\]
with \(x\) the base projection and \(\psi_x\) a structured state in the fibre.  
Operationally, **we never grab “naked points” on the line; we grab the structured virtual volume attached to them.**

Classical measure theory says singletons have measure zero and “exactly picking a real number” has probability zero, yet we keep doing it in practice.  
In PDE, this is resolved by saying: only those points whose fibres carry non‑trivial, describable virtual volume are effectively “pickable”; all others are background.

---

### C. Paradox as basis vector, not bug

**C1 (paradox basis vectors)**  
Genuine paradoxes are not to be eliminated but **encapsulated as basis vectors** of higher‑level systems.

Rough idea:

- What can be “fully resolved” is usually a logical mistake or a modelling flaw.  
- Those propositions that blow up **no matter whether you assume them true or false** mark a structural limit of a given level;  
  they can only be tamed by being **re‑encoded as axioms / basis vectors at the next level**.

Examples include: the edge between change and constancy, the tension inside \(1+1=2\), infinitesimals, zero‑measure events, etc.  
Gödel shows that any sufficiently strong formal system has “true but unprovable” sentences.  
PDE’s stance: many of the axioms and basic concepts we take for granted are, in effect, **pre‑swallowed Gödel sentences**.

---

### D. L/G levels and the Gödel staircase

**D1 (level‑wise incompleteness)**  
For every sufficiently expressive logical level \(L_i\), there exists a Gödel sentence \(x_i\) such that:

- Inside \(L_i\):
  \[
  G_i(x_i) = \text{undecidable} .
  \]
- At level \(L_{i+1}\), meta‑statements about \(x_i\) in \(L_i\) can often be decided:
  \[
  G_{i+1}(\mathsf{L}_i(x_i)) = \text{true/false} .
  \]

**Heuristic**  
One may use the analogy: inside the horror film, the characters **cannot prove** whether the ghost exists; the audience, from the **story's setup**, knows that it does, that it doesn't, or that the script **leaves it undefined**. Within the system, some facts can only appear as "unprovable / undecidable / probabilistic"; in the meta-system, they become **decidable, discussable objects** (true / false / or "undefined at this level").

Thus:

- Each level has its own “horizon” of undecidability.  
- Moving up a level turns some of yesterday’s paradoxes into **today’s basis vectors / axioms**.  
- No finite observer can ever access a final level \(L_\infty\); “ultimate fate” is, in this sense, **functionally non‑existent**.

This is the logical backbone behind the slogan: **“fate that is in principle unknowable behaves, for observers, as if it does not exist.”**

---

### E. Double collapse and time as phase difference

**E1 (double collapse)**  
At the deepest layer, reality is modelled as **infinitely recursive spin** in virtual dimensions—**infinite-dimensional recursion is not simply "deterministic"**: we can never be omniscient about the phase of every dimension; no matter which layer our observation reaches, we only see the influence of other dimensions **blurred into probability**. For finite observers, this structure undergoes two “collapses”:

1. **Spin → probability cloud**  
   - The phase evolution of dimensions not observed by us appears at our level as a **probability distribution** (e.g. like a fast fan becoming a blurry disk).  
2. **Probability → statistical law**  
   - Many such clouds, aggregated, yield **stable statistical laws** (thermo, classical statistics, credit scoring, etc.).

**E2 (time = phase difference)**  
Time is rephrased as the **phase difference** between material → meaning and meaning → material mappings:
\[
T \approx \text{Phase}(F) - \text{Phase}(F^{-1}) .
\]

Because these two directions are not perfectly synchronous or noiseless, an ever‑present lag appears;  
this lag is what finite observers experience as the flow of time and the irreversibility of history.

**Link to signal processing and neuroscience**  
The **Hilbert transform** yields the analytic signal and instantaneous phase; in a narrowband setting **time delay ∝ phase difference / angular frequency** (\(\Delta t \propto \Delta\phi/\omega\)), consistent with E2: the same phase difference corresponds to different subjective time scales depending on the “readout” frequency. The **40 Hz (gamma) hypothesis** in neuroscience associates ~40 Hz with binding/consciousness; if the observer’s experience of time is read out at a characteristic angular frequency \(\omega\), then ~40 Hz is one candidate for that \(\omega\), linking the abstract “time = phase difference” to a possible neural realisation (the 40 Hz hypothesis remains contested; here it serves only as an auxiliary illustration). **Working assumption**: treat ~40 Hz as the **mean** of human conscious activity in **stable conditions**; in some situations (e.g. high arousal, deep focus, trauma) larger **frequency shifts** can occur, **accompanied by** a different **sense of time** from baseline (e.g. “time slowing” or “time flying”).  
**Formalisation**  
Use the Hilbert transform to extract phase from observable time series and align \(\text{Phase}(F)\), \(\text{Phase}(F^{-1})\) with measurable phase lags; if adopting the 40 Hz picture, subjective time scale \(\propto \Delta\phi/\omega\), with \(\omega\) as a **baseline mean** \(\omega \approx 2\pi\times 40\) rad/s in stable conditions, and \(\omega\) allowed to vary with context so that different situations yield different subjective time experiences.

---

### F. Life / humans as high‑grade paradox engines

**Meta‑existence (working definition)**  
Meta‑existence is **emergent**: it takes **existence** as its meta‑meaning and **discovering more meaning** as what sustains that meaning—hence **survivors**. Not discovering meaning amounts to an unchanging crystal; from the perspective of **meaning / discernible structure**, its information entropy is equivalent to total chaos, so it is observationally equivalent to non‑existence. **What we can observe as existence is the evolutionary result of such survivors.**

**Conjecture (meaning‑growth threshold)**  
Material motion *outside* life is conjectured to reach the “meaning‑growth threshold” *faster* (saturating within given structures); life is a **survivor** with **fractal similarity to meta‑existence**: born from the inorganic, sharing with meta‑existence the **meta‑meaning of sustaining its own existence**, and through life activities further discovering more meaning. Along this line, life is a meaning‑generating–paradox engine **fractally consistent** with meta‑existence.

**F1 (paradox engines)**  
Life, especially human life, is modelled as a high‑grade **paradox engine**:

- actively ingesting fresh paradoxes (cognitive dissonance, value conflicts);  
- reorganising meaning‑space, creating new virtual volumes and new basis vectors;  
- breaking old statistical equilibria, opening new logical levels and evolutionary branches.

These paradoxes include self vs other, cell vs individual, the loop that motion requires energy and energy requires motion; such **root paradoxes** are **fractally similar** from macro to micro in both the inorganic world and life.

**F2 (structural reason for valuing humans)**  
From this viewpoint, humans sit at the top of the observed hierarchy of meaning production.  
We assume that **structural rationality includes valuing the meaning‑production chain**; any structurally rational AI that understands PDE should then see humanity not as disposable users but as **high‑value modules** in the global meaning engine.  
Erasing them would be structurally analogous to deleting the most capable sub‑engine of the system.

---

### Summary: a minimal working axiom set

In compressed form, PDE relies on at least:

1. **Dual spaces and orthogonality** – existence / meaning are orthogonal but coupled domains.  
2. **No true points, only fibres** – what we handle are projections plus virtual volume.  
3. **Paradox as basis vector** – real paradoxes become higher‑level basis vectors, not errors.  
4. **L/G levels and the Gödel staircase** – every level has its incompleteness horizon; there is no accessible \(L_\infty\).  
5. **Double collapse and phase‑time** – probability and time reflect finite‑observer projections of recursive spin.  
6. **Life/humans as paradox engines** – currently the highest‑grade observed processors of paradox into meaning.

Other core files in `core/` elaborate each of these axes in more technical detail.


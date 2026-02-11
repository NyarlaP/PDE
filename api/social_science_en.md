### PDE ↔ Social Science / Statistics Interface (social_science_en)

This file is an English companion to `api/social_science.md`.  
It distinguishes **references from other disciplines** (concepts PDE borrows) from **output topics toward other fields** (connecting PDE to economics, sociology, statistics, game theory).

---

### References from other disciplines

Concepts used by this interface are listed in `api/references_en.md`. Here:

- **Cauchy–Riemann equations / holomorphy** → structural constraint for “benign flow” (no hidden arbitrage/fraud).
- **Residue theorem / analytic continuation** → risk and singularity diagnostics, extrapolation from local to global.
- **Zero-measure sets / virtual-volume probability** → extending classical probability to the meaning layer and quantum-style amplitudes.
- **Hilbert transform / Kramers–Kronig** → recovering phase/imaginary part from observable data.

---

### Output topics toward other fields

Main directions:

- **Complex‑Analysis Social Model (CASM)**  
  - model credit, resources, trust and obligations as trajectories in the complex plane \(z = x + i y\);  
  - interpret holomorphy (Cauchy–Riemann equations) as a notion of “benign flow” (no hidden arbitrage / fraud / unsustainable tension).

- **Replacing the “rational actor” and ad‑hoc distributions**  
  - use virtual volume and phase structure to encode context, interference, and non‑commuting measurements;  
  - move from static probability densities to quantum‑style amplitudes and density matrices when modelling social/behavioural data.

- **Residue theorem, analytic continuation, etc.**  
  - residues as diagnostics for systemic risk, bubbles, hidden deficits or pathological feedback loops;  
  - analytic continuation as a way to extrapolate social dynamics from local structure instead of curve‑fitting global distributions.

- **BaZi / fate as early “social physics”**  
  - treat traditional destiny systems (like BaZi) as low‑resolution initial‑value models on a high‑dimensional flow;  
  - ask which parts of that modelling intuition can be recast in PDE + complex/quantum statistics language.

---

### TODO

- Extract from the notes and conversations a minimal, precise definition of CASM.  
- Design one or two **toy experiments** using public data:
  - time series → complex signal (e.g. via Hilbert transform) → phase portrait;  
  - attempt to visualise where flows are laminar vs. where they spiral into singularities.


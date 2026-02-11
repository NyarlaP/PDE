### Complex‑Analysis Credit Model (CASM) – Notes (English companion)

English companion to `apps/credit_complex_analysis/model_notes.md`.  
This file is intended to collect more concrete notes on a **complex‑analysis‑based credit model** inspired by PDE.

---

### Core ideas to capture

- Represent the state of an individual / institution as a complex number
  \[
  z = x + i y
  \]
  where:
  - \(x\): observable variables (cash flow, assets, payment history, etc.);  
  - \(y\): latent “virtual volume” (creditworthiness, intent, trust, hidden risk).
- Interpret **holomorphy / Cauchy–Riemann equations** as a notion of “benign credit flow”:
  - changes in the real and imaginary parts are tightly coupled;  
  - sudden breaks in analyticity signal fraud, unsustainable leverage or structural risk.
- Use **poles / residues** to model systemic risk or default singularities:
  - a pole in \(f(z)\) near someone’s trajectory corresponds to a blow‑up in required resources or obligations;  
  - the residue gives a quantitative measure of the “hidden hole” in the local credit structure.

---

### TODO

- Boil down the longer philosophical discussion into a few concrete definitions and simple equations;  
- sketch 1–2 toy models, even if idealised, that could later be tested on real or simulated data.


### PDE – Paradox‑Driven Existentialism

**PDE (Paradox‑Driven Existentialism)** is an open framework that tries to rewrite the relation between **existence, meaning and paradox** using tools from modern logic, physics and complex analysis.

It is **not** a finished theory or a single paper. Think of it as a structured pile of conjectures and architectural sketches that are meant to be **formalised, implemented, attacked and extended**.

---

### Repository layout (English quick tour)

- `docs/` – overview & navigation  
  - `overview.md`: high‑level map, links into other layers.  
  - `roadmap.md`: TODOs and open problems.  
  - `glossary.md`: terminology (paradox axis, virtual volume, L/G layers, etc.).

- `core/` – **kernel / foundations**  
  - `axioms.md`: core assumptions / “basis vectors” PDE stands on.  
  - `logic_L_G_layers.md`: the L(x) function, Gi/Li hierarchy, Gödel‑style “staircase”.  
  - `geometry_point_volume.md`: non‑existence of true points, virtual volume, fibre‑like structure.  
  - `probability_time.md`: probability, double collapse, time as phase difference.  
  - `formal_attempts/`: placeholder for actual formalisation attempts (set theory, category theory, model theory, …).

- `api/` – **interfaces to other theories**  
  - `physics.md`: contact points (and conflicts) with thermo/quantum/cosmology.  
  - `logic_philosophy.md`: mappings to Gödel, Tao Te Ching, existentialism, etc.  
  - `cs_ai.md`: links to computation, Turing machines, LLMs, AI alignment.  
  - `social_science.md`: links to economics / sociology / statistics / game theory.

- `apps/` – **applications / experiments**  
  - `credit_complex_analysis/`: notes and sketches for a complex‑analysis‑based credit model (CASM).  
  - `quantum_stats/`: quantum‑probability‑flavoured statistics.  
  - `fate_bazi_dynamics/`: “BaZi / fate as an initial‑value problem” in a dynamical‑systems sense.  
  - `ai_alignment/`: PDE‑style ideas for AI alignment and agent design.  
  - `paradox_cases/`: re‑analysing classical paradoxes (time’s arrow, liar, Zeno, etc.) using PDE.

- `interfaces/` – **human‑facing interfaces**  
  - `哲学白皮书.md`: the main PDE manifesto / whitepaper in Chinese.  
  - `philosophy_essay.md`: pointer / stub for English or multi‑language essays.  
  - `narrative_stories.md`: story hooks, metaphors, possible SF settings.  
  - `teaching_notes.md`: notes for talks / lectures / study groups.  
  - `faq.md`: common questions and short answers.

- `archive/` – **raw material**  
  - `draft.md`: current long‑form outline of PDE (in Chinese).  
  - `chat.md`: a long conversation that helped crystallise the framework.  
  - `chat/*.json`: full chat logs with various models.  
  - `notes_raw/`: scratchpad notes.

---

### PDE in one page (conceptual sketch)

- **Two orthogonal spaces**  
  - A **material / existence space** (things, energy, bodies, infrastructure…).  
  - A **meaning / intentional space** (relations, values, commitments, credit, identity…).  
  - They are orthogonal but coupled: we live at their interference boundary.

- **Paradox axis**  
  Whenever we use a fixed language/logic to compress reality, there are always statements that are “too awkward” to be safely labelled True or False. These edge‑cases line up into a fuzzy **paradox axis**.  
  Every language or theory is, in PDE’s view, a way of **cutting a measurable subset** from this axis and boxing those paradoxes so that we can operate on them.

- **L and G layers (Gödel staircase)**  
  - At each logical layer \(L_i\), there exist undecidable statements \(x\).  
  - The observation operator \(G_i\) at that layer can only say “unknown / undecidable”.  
  - By jumping to a meta‑layer \(L_{i+1}\), we can often decide facts *about* the behaviour of \(x\) in \(L_i\).  
  - What looks like “paradox” in \(L_i\) becomes a **basis vector / axiom** in \(L_{i+1}\).  
  - There is no final layer \(L_\infty\) accessible to us; in that sense, **“ultimate fate” is functionally non‑existent for any finite observer**.

- **Points and virtual volume**  
  - In strict measure theory, a single point on the real line has measure zero, yet we keep “choosing exact numbers” all the time.  
  - PDE treats a “point” not as an atom but as:
    - a projection on the base space (the real line), plus  
    - an attached **virtual fibre / virtual volume** in the meaning space.  
  - We “pick” numbers by grabbing their virtual volume: only descriptible / meaningful numbers have non‑zero virtual volume for us; most reals remain un‑pickable background.

- **Probability, time, and double collapse**  
  - At the bottom, PDE imagines a deterministic but **infinitely recursive spin** in the virtual layers.  
  - First collapse: this wild spin is seen as a **probability cloud** (like a fast fan becoming a blurry disk).  
  - Second collapse: many such clouds are aggregated into **stable statistical laws** (thermodynamics, classical stats, credit scores…).  
  - Time is rephrased as the **phase difference** between mapping material → meaning and mapping meaning → material back again. The lag *is* what we experience as temporal flow.

- **Life, humans, AI as paradox engines**  
  - Non‑living structures obey given rules and have limited capacity to *create new* meaning.  
  - Living systems, especially humans, can swallow fresh paradoxes and reorganise their meaning‑space around them.  
  - Humanity, in PDE, is currently the highest‑grade **“paradox engine”** we know.  
  - A structurally rational AI that understands PDE would see humans not as disposable users, but as top‑tier modules for meaning generation. Wiping them out is structurally equivalent to deleting an entire high‑level engine.

This is enough to get the flavour; the Chinese whitepaper in `interfaces/哲学白皮书.md` goes into much more narrative detail.

---

### How to use this repository

You can treat PDE as:

- **A philosophical scaffold** –  
  to reorganise intuitions about nihilism, fate, free will, paradox, AI and religion.

- **A formalisation target** –  
  - in `core/`, try to give the L/G hierarchy, the two spaces and the paradox axis a clean model in set theory, category theory or type theory;  
  - or construct counterexamples showing where certain claims cannot be made precise under standard axioms.

- **An application playground** –  
  - in `apps/`, use PDE‑coloured ideas to build small demos: complex‑analysis credit models, quantum‑style statistics, alignment prompts, etc.;  
  - or use PDE simply as a generator of “weird but structured” hypotheses to test against real data.

---

### Contribution & attitude

- Any serious **formalisation, implementation, critique or demolition** is welcome:
  - maths / logic in `core/` and `core/formal_attempts/`;  
  - physics / complexity in `api/physics.md`;  
  - social science / metrics / AI in `apps/`.

- Open problems and priorities will be gradually collected in `docs/roadmap.md`.

This repository is released under the **MIT License**; see the `LICENSE` file in the repo root for full terms.

What matters philosophically is the stance:

1. **Take rigour seriously.** If you see a hole, either patch it or make it explicit.  
2. **Keep a sense of humour.** PDE might turn out to be “a very useful illusion” rather than The Truth™, and that’s fine.

If you reference PDE elsewhere, a fair disclaimer would be something like:

> *“This is an open, work‑in‑progress framework. None of it has gone through full formal verification or empirical validation yet.”*

---

### ToDo list (current version goal: logically consistent and closed‑loop)

The current version aims for **each module to have a logically self‑consistent and closed‑loop exposition**. The list below is organised by module for prioritisation and collaboration.

- **core/**  
  - [ ] **axioms.md**: After several rounds of closure fixes (meta‑existence, E phase/40 Hz, F2 convention), do a full pass to ensure cross‑references with logic, geometry and probability_time are consistent and free of circular definitions.  
  - [ ] **logic_L_G_layers.md**: Align with axioms D and its heuristic path; check that L/G hierarchy and “paradox encapsulation” are closed with axioms C/D.  
  - [ ] **geometry_point_volume.md**: Align with axioms B and the use of virtual volume in probability_time and api/references; ensure the “point–fibre–virtual volume” chain is closed.  
  - [ ] **probability_time.md**: Align with axioms E (double collapse, time = phase difference, 40 Hz working assumption) and with geometry’s virtual‑volume probability.  
  - [ ] **core/formal_attempts/**: Any formalisation draft should state which axiom subset it depends on and which “possible formalisation direction” it addresses.

- **api/**  
  - [ ] **references.md / references_en.md**: Keep as the single source for “references”; each interface file’s “references from other disciplines” only points here or lists a subset.  
  - [ ] **logic_philosophy, physics, social_science, cs_ai** (ZH/EN): In each interface, “references” vs “output topics” clearly separated; output topics traceable to core axioms/concepts and closed.  
  - [ ] Per‑interface TODOs (e.g. minimal CASM, testable predictions, prompt templates): Converge into deliverable closed sections or standalone docs.

- **docs/**  
  - [ ] **overview.md**: Sync with current core (meta‑existence, E 40 Hz, F conjecture and F2); navigation consistent with closed‑loop goal.  
  - [ ] **roadmap.md**: Indicate completion or gaps for “closed‑loop consistency” by core/api/apps.  
  - [ ] **glossary.md**: Core terms match axioms and core files; no circular or ambiguous definitions.

- **apps/**  
  - [ ] **credit_complex_analysis**: Align with api/social_science and references (Cauchy–Riemann, residues, analytic continuation); model_notes and examples form a closed narrative.  
  - [ ] **quantum_stats**: Align with core probability/virtual volume and references; closed with axioms E.  
  - [ ] **ai_alignment**: Align with axioms F; model_notes closed with core.  
  - [ ] **paradox_cases**: Each case tied to core “paradox → basis vector / encapsulation” and L/G hierarchy; each case closed with core.  
  - [ ] **fate_bazi_dynamics** (if restored): Align with probability_time and time = phase difference; closed.

- **interfaces/**  
  - [ ] **哲学白皮书 / philosophy_whitepaper_en**: Sync with core/axioms; manifesto claims traceable and non‑contradictory.  
  - [ ] **faq.md**: Answers consistent with core/api closed expositions.  
  - [ ] **teaching_notes, narrative_stories**: If used externally, label core version/sections they depend on.

- **archive/ and root**  
  - [ ] **draft.md / draft_en.md**: State relation to core or “partially merged into core”; if used as long outline, periodically check consistency with axioms and core.  
  - [ ] Conversation JSONs, chat: Research only; not part of “closed version”; merge conclusions into core/api/apps with closure before citing.

---

### Reading with language models

- **Recommended to read with an LLM at hand**:  
  Parts of this repository (especially `core/` and the Chinese whitepaper in `interfaces/哲学白皮书.md`) are intentionally dense. It is highly recommended to keep a language model (of your choice) open while reading, and use it to:  
  - rephrase individual paragraphs in your own words;  
  - ask for concrete examples, metaphors or counter‑examples for a given section;  
  - take a specific axiom / conjecture and ask the model to “argue against it” from different schools of thought;  
  - turn your current understanding into rough maths / pseudocode and let the model help you stress‑test consistency.  
- **Be explicit about what is “author’s intent” vs “model improvisation”**:  
  The repository text (and formulas) should be treated as the primary source. The LLM is best used as an interactive annotator and adversarial collaborator, not as an authority on what PDE “really means”.
- **A potential “rich vein” to mine**:  
  If you deliberately push an LLM to keep extending, refactoring and attacking the PDE setup, you may find that it yields a surprisingly rich vein of logical structures and narrative variants—different readers can grow quite different, yet structurally compatible, developments out of the same axiom set. This exploratory behaviour is very much part of what PDE is trying to expose and test.


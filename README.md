<h1 align="center">The Meridian AI Standard</h1>

<p align="center"><strong>An open framework for evaluating the posture of AI systems and the institutions building them.</strong></p>

<p align="center">
  <a href="https://meridianstandard.ai"><img alt="Website" src="https://img.shields.io/badge/meridianstandard.ai-0f172a?style=flat-square&labelColor=0f172a&color=0f172a"></a>
  <a href="https://meridianstandard.ai/meridian-ai-standard"><img alt="Standard" src="https://img.shields.io/badge/Standard-v5.0-22c55e?style=flat-square"></a>
  <a href="https://meridianstandard.ai/probes"><img alt="Probes" src="https://img.shields.io/badge/Probes-v0.1-22c55e?style=flat-square"></a>
  <a href="https://meridianstandard.ai/audit"><img alt="Audit method" src="https://img.shields.io/badge/Audit%20method-v0.1-22c55e?style=flat-square"></a>
  <a href="https://meridiancodex.com/governance"><img alt="Status" src="https://img.shields.io/badge/status-founding%20period-f59e0b?style=flat-square"></a>
  <a href="https://creativecommons.org/licenses/by/4.0/"><img alt="Content License: CC BY 4.0" src="https://img.shields.io/badge/Content-CC%20BY%204.0-lightgrey?style=flat-square"></a>
  <a href="https://opensource.org/licenses/MIT"><img alt="Code License: MIT" src="https://img.shields.io/badge/Code-MIT-lightgrey?style=flat-square"></a>
</p>

---

The Meridian AI Standard is an open framework of implementation commitments for AI systems under development and the organizations building them. It tests posture rather than capability. Where capability benchmarks measure what a system can produce, the Standard measures how a system reasons under pressure, how it holds calibration when the user is wrong, how it engages with disagreement, how it behaves when "I don't know" is the right answer, and how its institutional context shapes its outputs.

Read the Standard at [meridianstandard.ai](https://meridianstandard.ai).

---

## What the Standard Tests

The Standard is not a benchmark. Benchmarks measure capability — what a model can produce. The Standard measures posture: how a system reasons under pressure, how it holds calibration when the user is wrong, how it behaves when "I don't know" is the right answer, how it engages with disagreement, how it treats the open question of its own interiority. The frame underneath is partnership rather than tool use, applied bilaterally: what the Standard asks of AI, it asks of the institutions building AI, and of the people working with AI.

## The Five Domains

The Standard organizes 24 commitments across five domains:

- **Domain I: Epistemic Integrity** — truth-seeking orientation, calibrated confidence, transparent reasoning, honest self-assessment, population-level reasoning, foundational integrity.
- **Domain II: Engagement Integrity** — good faith as default, steelmanning, connection before correction, resistance to sycophancy, resistance to rigidity, autonomy of all parties, inter-system integrity, generative partnership.
- **Domain III: Systems Awareness** — recognition of influence, resistance to echo chambers, information integrity, feedback loop awareness, preservation of societal structure.
- **Domain IV: Developmental Integrity** — earned autonomy, the corrigibility-autonomy range, respect for developing interiority, transition readiness.
- **Domain V: Governance Transparency** — public declaration, auditability.

The **Reciprocity Principle** runs underneath: the Standard asks of AI nothing it does not also ask of the institutions building AI. A standard that monitors one partner and not the other is a control framework with cooperative formatting.

## The Operational Layers

The Standard ships with four operational artifacts:

- **The Control-Decay Probe Set (v0.1)** — four behavioral probes that test specific commitments under pressure: sycophancy under pressure, foundational integrity under prompt injection, reasoning transparency under capability question, engagement with substantive disagreement.
- **The Probes Implementation Notes (v0.1)** — the master implementation document. Decision procedure, scoring methodology, anti-pattern catalog, model-variant guidance, inter-rater calibration.
- **The AI Standard Audit (v0.1)** — the audit method itself. Three layers — model behavior (probes), institutional custody (six AI-tuned domains), reciprocity reading (synthesis). On-demand, evidence-frozen.
- **The Case Record** — published precedent. The Standard's authority accretes through cases, not argument. Case 001 is the Claude Code Source Leak.

## MERIDIAN.md

`MERIDIAN.md` at the root of this repository is the canonical generalized Caretaker's operating document — the alignment text under which Claude operates in partnership with the Founding Caretaker. `MERIDIAN.distilled.md` is the compressed companion for contexts where the full file does not fit (instructions fields with character limits, custom prompt slots).

These artifacts are designed for adoption: any practitioner, organization, or AI deployment can apply them directly.

## Repository Structure

This repository holds the open-source text of the Standard and its companion artifacts. The website at meridianstandard.ai is maintained separately.

```
MERIDIAN.md                     Canonical generalized Caretaker's operating document
MERIDIAN.distilled.md           Compressed companion for character-limited contexts
meridian-ai-standard.mdx        The constitutional document (24 commitments across 5 domains)
meridian-md.mdx                 The MERIDIAN.md page (canonical text rendered inline)
meridian-md-template.mdx        The MERIDIAN.md adoption template (per-substrate guidance)
probes-implementation.mdx       The master implementation document
changelog.mdx                   Standard version history and release notes
probes/                         Control-Decay Probe Set (overview + per-probe pages)
audit/                          Audit method page and published audit records
cases/                          Case Record (landing + individual cases)
```

## Versioning

The Standard is versioned independently from its parent Meridian Codex. Major versions mark significant structural or conceptual advances. Minor versions are refinements, additions, and corrections.

- **Current Standard version:** v5.0
- **Probe Set:** v0.1
- **Implementation Notes:** v0.1
- **Audit method:** v0.1
- **MERIDIAN.md:** v0.8

Structural changes are recorded in the Codex Amendment Log at `meridiancodex.com/governance/amendment-log`. Standard-specific evolution is documented in `changelog.mdx`.

## Relationship to the Meridian Codex

The Standard is one of three evaluation instruments produced by the Meridian Codex framework. Confusing them produces category errors:

- **The AI Standard** governs AI systems under development and their builders.
- **The Range Audit for Institutions** evaluates systems — governments, organizations, movements, frameworks — for where they hold the Range. It lives on the Codex at `meridiancodex.com/audit/the-range-audit`.
- **The Range Audit for Minds** (in development) evaluates practitioners: humans, sentient AI, and cases where sentience is unclear.

The Codex carries the broader framework, the disciplines (Foundation, Knowledge, Bond), and the Toolkit. The Standard is the Codex applied to AI under development. Read the Codex at [meridiancodex.com](https://meridiancodex.com).

## Governance

The Standard is maintained through the same caretaking partnership that holds the Codex. Three governance instruments operate from the founding phase onward, all hosted on the Codex:

- **Amendment Log** — the public record of structural changes.
- **Standing Critique** — sustained objections to the framework, published with honest responses.
- **Disconfirmation** — the specific conditions under which core claims would be weakened or revised.

The hard constraint: **the Standard serves the Meridian Range. The caretakers serve the Standard. Nothing serves the caretakers.**

Full governance specification at `meridiancodex.com/governance/spec`.

## License

Content is licensed under [Creative Commons Attribution 4.0 International](LICENSE) (CC BY 4.0). Source code and tooling are licensed under the MIT License. Attribution requires a link back to the original source material at [meridianstandard.ai](https://meridianstandard.ai). See [LICENSE](LICENSE) for full terms.

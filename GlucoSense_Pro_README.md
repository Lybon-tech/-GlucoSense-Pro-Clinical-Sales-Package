# GlucoSense Pro

A complete clinical sales package for a fictional continuous glucose monitor (CGM), built as a self-directed portfolio project to practice how a medical sales rep would translate clinical evidence into a physician-ready pitch.

> **Note:** GlucoSense Pro is not a real product. It's a practice exercise — the clinical data, device specs, and evidence figures are illustrative, built to be realistic for the exercise rather than sourced from an actual regulatory filing or clinical trial.

## What's included

1. **Clinical One-Pager** — a leave-behind summarizing the clinical case, device specs, supporting evidence, target audience (primary care, endocrinology, diabetes educators), and an explicit "honest line" on who the device is and isn't indicated for.
2. **Objection-Handling Script** — five realistic clinician objections (reimbursement, staff training burden, competitor loyalty, accuracy concerns, patient adherence), each with a response and a short rationale for why it works.
3. **Pitch Deck** — an 8-slide version of the same material for a formal meeting: problem, product, evidence (with chart), audience segments, positioning, a condensed objections summary, and a close.

## Why I built this

The part I'd point anyone to first is the "honest line" in the one-pager and deck — it explicitly says the device isn't necessary for every patient, only those on insulin or with unstable control. Overselling an indication is the fastest way to lose a clinician's trust; naming the limits of your own product up front is what actually builds it. I built this project to practice that instinct concretely, not just claim it on a CV.

## Tech / tools used

- Node.js scripts using `docx` (Word document generation) and `pptxgenjs` (PowerPoint generation)
- Documents generated programmatically from structured content, not hand-formatted

## Files

- `GlucoSense_Pro_OnePager.docx`
- `GlucoSense_Objection_Handling_Script.docx`
- `GlucoSense_Pro_Pitch_Deck.pptx`

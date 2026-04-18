# Brand Guardian — AI-Powered Brand Compliance for Canva Teams

An interactive prototype for an AI compliance layer that scans Canva designs against brand guidelines, flags violations, and offers one-click fixes before approval.

Built as part of the Eulerity Associate Product Manager (AI-First) take-home exercise.

## The Problem

Canva's Brand Intelligence (launched April 16, 2026) ensures AI-generated designs start on brand. But the moment a team member manually edits — swaps a font, pastes an off-brand color, repositions a logo — nothing verifies the design is still compliant. Approval reviewers catch violations manually, spending up to 15 hours/week on brand-policing instead of strategic feedback.

## The Solution

Brand Guardian is a compliance sidebar inside Canva's editor that:

1. **Scans** designs against Brand Kit rules + Canva's Design Model in 3 seconds
2. **Flags** specific violations (typography, color, logo, layout, voice) with severity and location
3. **Fixes** issues with one click — swap fonts, correct colors, adjust spacing
4. **Scores** overall brand compliance (0–100) and attaches a summary to the approval request

## Prototype

The prototype demonstrates the core interaction flow across three states:

- **Pre-scan** — Editor with Brand Guardian sidebar showing Brand Kit summary and "Run Brand Check" CTA
- **Post-scan** — Violations highlighted on canvas, scored in sidebar with fix buttons
- **Post-fix** — Score updated, resolved/dismissed issues tracked, approval-ready with compliance badge

### Run locally

```bash
# Clone and open
git clone https://github.com/Shreyas-30/brand-guardian.git
cd brand-guardian
open index.html
```

No build step required — open the HTML file directly in a browser.

## Deliverables

| Deliverable             | Link        |
| ----------------------- | ----------- |
| Presentation Deck (PDF) | [Eulerity_Canva_Deck.pdf](Eulerity_Canva_Deck.pdf) |
| Interactive Prototype   | [Live demo](https://shreyas-30.github.io/brand-guardian/) |

## Built With

- HTML / CSS / JS (prototype)
- Claude Design (initial layout and interaction design)
- Claude (research, competitive analysis, deck content)

---

Shreyas · Penn Integrated Product Design '26 · April 2026

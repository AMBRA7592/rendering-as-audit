# Rendering as Audit — Public Demonstration

Interactive companion to the working paper:

**Rendering as Audit: Interactive Visualization as Methodological Verification for Composite-Index and Expert-Coded Research**  
Amadeus Brandes (2026)

## What this is

A single-page interactive tool demonstrating five design principles for embedding verification logic in the rendered output of scored-measurement research. The page implements:

1. **Decomposition visibility** — composite κ scores displayed as component-level decompositions by default
2. **Source provenance at the measurement point** — hover confidence indicators to inspect source bases
3. **Protocol logic embedded in rendering** — the merged-unresolved (†) flag auto-triggers on line 9 per protocol rules
4. **Cross-case comparison** — Rwanda and Egypt rendered side by side at the component level
5. **Falsification criteria as testable conditions** — sealed prediction with time-stamped disconfirmation criteria

## How to use

Open the [live demo](https://ambra7592.github.io/rendering-as-audit/). Hover or click confidence dots (●●●) to see source lists. Hover or click the † marker on line 9 to see the protocol rule that triggered the flag.

## Relationship to the paper

The paper argues that for composite-index and expert-coded research, verification should be embedded in the rendered output rather than separated into appendices and codebooks. This page is the paper's own test case: if the affordances claimed in §6 of the paper are not delivered by this artifact, the claim is refuted by inspection.

## Technical

Plain HTML + CSS + vanilla JavaScript. No build step, no framework, no dependencies, no tracking. The source code is the methodology (per Principle 3 of the paper).

# Digital Continuity: One configuration, many views, closed loop

An interactive reference scenario for a client workshop on digital continuity and the digital thread in an Aerospace & Defence Tier-1. It follows one product, a wing, from customer requirement to a maintained aircraft section, and shows how a change travels back through every view.

Created by Ángel Rodríguez Gil. Nov.2026

## Open it

- Open `index.html` in any modern browser. It is a single self-contained file. Without internet it still works, with fallback fonts.
- To publish with GitHub Pages: Settings → Pages → deploy from the main branch, root folder. `index.html` is served as the home page.

## What is inside

Three scenes:

1. **Overview**
   - The customer / OEM frames the process: requirements come IN, the product goes OUT.
   - Supply Chain Value Collaboration runs across Design and Production.
   - Five company views sit on the product thread:
     - Requirements & Configuration
     - Design
     - Production
     - Testing & Validation
     - Service
   - Program Management runs end to end, alongside Product Change Management.
   - The systems of record: PLM (product and digital manufacturing), ALM / SW, ERP, MOM, QMS, MRO / GMAO.
   - Feedback from as-built and as-maintained data closes the loop.
   - The Systems, Change and Feedback layers can be switched on and off.
2. **Views**: each company view in five or six steps, with a flow map, the systems involved and the handoff.
   - Requirements & Configuration: contract, requirements baseline, cBOM (150%), effectivity, release.
   - Design: Systems View, design in context, virtual validation, cBOM → eBOM, software release (ALM), make or buy.
   - Production: eBOM → mBOM, release to ERP, part manufacturing (internal or supplier), assembly, as-built genealogy.
   - Testing & Validation: qualification, production acceptance, First Article Inspection, delivery conformity, delivery.
   - Service: entry into service, sBOM with hardware and software views, maintenance plan, records per serial, spare parts and feedback.
3. **Product Change Management**: ECR → impact analysis → ECO (Program governance gate) → ECN by effectivity. The change can start from a service finding, a production nonconformance or a customer change.

## Presenting

Press **Present ▸**. The arrow keys, Space, PageUp and PageDown step through all 38 steps: the Overview, the five views, then Product Change Management. Esc exits. The page asks for full screen; if the browser refuses, it still works inside the window.

## Standards referenced

- SAE ARP4754B / EUROCAE ED-79B
- DO-178C, DO-254
- STEP AP242 (ISO 10303-242), STEP AP239 PLCS (ISO 10303-239)
- ISA-95 (IEC 62264)
- AS9100 / EN 9100 (IA9100 revision announced)
- SAE AS9102C
- S1000D

## Note

This is an illustrative, vendor-neutral reference scenario. Part names, identifiers, effectivity ranges and example data are generic.

## Contents

```
index.html     the interactive deliverable (v1.1)
previews/      screenshots of key steps
README.md      this file
```

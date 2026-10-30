# CareLink 护联 — interactive prototype assets

## What is included

- `index.html` — a self-contained, clickable high-fidelity mobile prototype.
- `assets/mei-chen.png` — fictional caregiver profile image used by the prototype. It can be dragged directly into Figma.
- `../CareLink_Hulian_Figma_AI_Build_Brief.md` — the complete Figma AI prompt for generating editable Figma frames.

## Prototype flow

**Start → Home → Care Now → Choose need → Time & location → Matched caregivers → Mei’s verified profile → Confirmed visit tracking → Receipt & review.**

The prototype also includes:

- bilingual English + Mandarin branding and key labels;
- an accessible large-text `Aa` control;
- saved-request / interruption recovery;
- credential verification details;
- emergency-help confirmation state; and
- transparent receipt and review flow.

## Use it in Figma

Figma does not turn a normal HTML file into editable native Figma frames by simply pasting the code. Use the materials in one of these reliable ways:

### Best option — Figma AI / Figma Make

1. Open a new Figma AI design or Make file.
2. Open `CareLink_Hulian_Figma_AI_Build_Brief.md` in the workspace.
3. Copy the section named **“Copy/paste prompt for Figma AI”** into Figma AI.
4. Ask it to create the nine 390 × 844 px frames and link the stated prototype interactions.
5. Drag `assets/mei-chen.png` into the Mei Chen profile component if Figma AI does not add a portrait itself.

The brief gives Figma exact screen copy, colours, spacing, components, accessibility rules, data, and interaction links, so the editable outcome should closely match the coded prototype.

### Reference / screenshot option

1. Open `index.html` in a browser or use the live preview.
2. Navigate to each state with the on-screen flow or the small desktop screen-jump chips.
3. Take a screen capture of each 390 × 844 px mobile screen and drag it into Figma as a visual reference.
4. Recreate the layout with Figma Auto Layout, using the values in the Figma AI brief.

## Design tokens

| Element | Value |
|---|---|
| Primary navy | `#123B5D` |
| Active teal | `#007C79` |
| Pale aqua | `#E8F4F3` |
| Background | `#FAFCFD` |
| Main text | `#17212B` |
| Emergency red | `#B42318` |
| Margin | 20 px |
| Base spacing | 8 px grid |
| Cards | 16–18 px radius |
| Minimum core touch target | 48 × 48 px |
| Primary button height | 56 px |
| Mobile artboard | 390 × 844 px |

## Important assignment completion items

Before submitting the written report, export six high-resolution Figma screens and insert them into the six figure placeholders in `CareLink_Hulian_Report_Draft.docx`. Replace the report’s prototype-link placeholder with the share URL after setting the Figma file to **Anyone with the link can view**.

# Royal Lobby Chandelier – 3D viewer

Interactive 3D models of the Royal Lobby chandelier at Diriyah Gate Arena, for client presentation. A switch at the top of the panel flips between the **Whole chandelier** and the **Mockup**; add `#mockup` to the link to open the mockup directly.

**Live page:** https://viso-dubai.github.io/royal-entrance/

## What it shows

- **4,240 onyx modules** in their drawn positions, coloured by the ROYAL LOBBY MODULE TYPES schedule (Types 1–5, 24 type numbers).
- **Indicative suspension structure** on three levels, with RHS 60×40×3 primaries, 41×41 strut-channel rails and Ø3 mm stainless steel aircraft cables (two per module):

  | Level | Steel band (mm above L0 FFL) | Modules carried |
  |---|---|---|
  | Level 3 · High | +22,690 to +22,791 | 156 |
  | Level 2 · Mid | +18,190 to +18,291 | 962 |
  | Level 1 · Low | +4,950 to +5,051 | 3,122 |

## Using the viewer

- Drag to orbit, right-drag (or two fingers) to pan, scroll or pinch to zoom.
- **Layers:** switch each module type, or each steel level (primaries / rails / cables), on or off. Presets: Everything, Modules only, Steel only.
- **Views:** Iso, Front, Side, Plan, Below.
- **Display:** see-through modules, outlines, floor grid, and a cut-height slider to slice the model.
- Hover a module to see its type, stone, size, heights and which level it hangs from.
- **Overall size** (toggle): overall length 33,914 mm and width 12,900 mm dimensioned on the floor, and the overall height 22,791 mm (top of steel).
- **Levels & heights** (toggle): building levels L0–L5 and the three steel levels as dashed lines with labels, an overall-height dimension, and a Heights table:

  | Reference | mm above L0 FFL | ARCH |
  |---|---|---|
  | Chandelier overall height (top of steel) | 22,791 | 32,791 |
  | Modules (T1 at floor to top of T5) | ±0 to 22,690 | |
  | Overall plan size | 33,914 × 12,900 | |
  | L5 Bowl roof | +28,000 | 38,000 |
  | L4 Catwalk | +24,550 | 34,550 |
  | L3 Terrace | +19,550 | 29,550 |
  | L2 Upper concourse | +11,000 | 21,000 |
  | L1 Upper suite | +5,500 | 15,500 |
  | L0 Main concourse FFL | ±0 | 10,000 |


## Mockup

The 1:1 mockup from the Rhino model *DIRIYAH GATE II INDOOR ARENA COMPLEX – MOCKUP_1.3dm*:

- **60 modules in 10 types** (6 × T1-01N 2,850–4,200, 20 × T2-01N, 4 × T2-01N-A, 8 × T2-02N, 3 × T2-02N-A, 6 × T3-01F-A, 1 × T3-02F, 4 × T3-02F-A, 3 × T3-04F, 5 × T3-04N-A), coloured by the same type colour code.
- **Steel frame** 2,400 × 2,400, 8,000 high to the top of the top frame: posts in three segments, braces, 3310T661 strut channel grid at +7,809, base plates and wedge anchors.
- Layers by module type, module part (cladding, aluminium box, light module, L-brackets, M12 rods, fixings) and frame part; Iso / Front / Side / Plan / Top detail views; overall size, level heights, see-through cladding, cut height; hover a module or frame part for details.
- Heights are mm above the underside of the base plates (Rhino Z +3,091).
- The NURBS surfaces were meshed for the web; the M12 rods are shown as plain Ø12 cylinders, all carried up through the strut channel grid to +8,035 (in the Rhino file 228 of the 240 rods stop short of it), and small fixings are simplified.

## Sources and status

- Module positions, lengths and types: drawing BV-BSW-104-1040-HKS-DWG-AR-5L2-600305 (Rev 00), checked against the PDF plan.
- Steel levels and zones: sections 600301 / 600302; member system after details 600303.
- The structure is **indicative** and subject to structural consultant and specialist design.
- Heights are in mm above L0 finished floor (L0 = +10,000 ARCH).

The page is a single self-contained `index.html` (three.js r128 loaded from jsDelivr). The mockup model loads when you first switch to it.

# Machine spec: cut fruit cleanly, without a factory

**Date:** August 2026

The original hypothesis: *if a machine cut the fruit cleanly and easily, this business would work in the States.*

Partly true. The Mexican cart already works — the limiter is **who can cut that fast without cutting themselves**, and **whether the health department will let you do it on a sidewalk**. A machine that outputs grocery cubes does not solve that. A **jig** that outputs spears, that rinses clean, and that a second person can learn in a day, does.

---

## 1. What “cleanly” means for this product

| Requirement | Why |
| --- | --- |
| Long spears / sticks, not cubes or chips | The cup has to look like a Mexican cart, not Ready Pac |
| Clean face, little crush | Crushed watermelon weeps, looks old in 20 minutes |
| High edible yield | Pineapple and melon waste is the silent COGS killer |
| Repeatable size | Mix looks designed; packs faster |
| Safe | Large knives on a rolling cart are the injury |
| Cleanable | NSF / sanitation-certified, no hidden food traps, no wood, no painted food-contact |
| Cart-realistic | Manual or 12V. No 220V industrial motor on a pushcart |
| Visible | The cut is marketing. Hide it in a box and you paid for a factory |

Industrial peelers (6-in-1 mango/pineapple lines, 300 kg/h slicers from export catalogs, $495–$10,000+) fail most of those. They are for canneries. Wrong customer, wrong cut, wrong power, wrong sanitation story for a US mobile unit.

---

## 2. Buy now (off the shelf)

Launch with **lever tools**, not a custom build.

### Pineapple — solved

**Nemco Easy Pineapple Corer/Peeler** (models 55775 / 55775-1)

- One pull: peel + core
- NSF, made in USA, stainless / cast aluminum
- Disassembles for wash
- Street price **about $965–$1,150** (Aug 2026)
- Suction-cup countertop. Lives at the **commissary**, not bouncing on the cart

This is the single best purchase on the list. Pineapple by hand is slow, wasteful, and ugly.

### Watermelon — mostly solved

- Commercial **wedger** (Nemco Easy Wedger class) for triangles
- Then a **stick/fry cutter** for spears, *or* a large chef’s knife through the wedge (still faster than starting from a whole melon)
- Wash the whole melon in the commissary **before** the first cut (FDA fresh-cut guidance: rind is the contamination path)

### Cucumber and jícama — solved

- Peel (Y-peeler or commissary peeler)
- Push through a **3/8" or 1/2" stick cutter** (restaurant french-fry / vegetable cutter, NSF)
- Jícama is dense; a cheap home fry cutter will flex. Buy the commercial one

### Mango — not solved

Home “mango splitters” assume a small, centered pit. Ataulfo / honey mangoes are kinder. Kent / Tommy Atkins (what the terminal actually has) are larger and the pit wanders.

Launch method:

1. Cheeks off with a knife
2. Score the cheek in the skin, invert, slice off spears
  or
3. Cheek, then a small jig that holds the cheek skin-down and a grid of blades pushes spears out

That jig is the custom project. Until it exists, mango is a **knife fruit**. Limit mango to one spear per mixed cup if the operator is slow.

### Coconut — out of scope

Vendors in LA call coconut the hardest fruit. Machete energy, shell debris, injury. Skip until the cart is bored.

---

## 3. Commissary station layout (one person, 90 minutes)

```
[ dump / crate ] → [ wash sink ] → [ pineapple corer ]
                                 → [ melon table + wedger ]
                                 → [ peel cucumber / jícama + stick cutter ]
                                 → [ mango knife board ]
                                 → [ ice / cambro / cart load ]
```

Rules:

- Wash station is **not** the cut station
- Pineapple corer is bolted or suctioned to a stainless table
- Color boards: one for melon, one for everything else, or wash between
- Every cambro of cut melon gets a lid, a time label, and a temp log when it hits the cart

Throughput target after two weeks of practice: **fruit for 80 cups in 90 minutes**. If you cannot hit that, you are using the knife too much or buying fruit that is too small.

---

## 4. Invent later: spear station (the actual machine)

Only start this after a cart is profitable. It is a product-design project, not a reason to wait.

### Job

One manual, NSF-path device (or a family of fruit-specific heads on one frame) that turns a **pre-peeled or whole** fruit into **uniform spears** in one stroke.

### Priority order

1. **Mango cheek spear jig** — highest skill gap, highest price fruit
2. **Watermelon spear head** — highest volume fruit
3. Unified frame that accepts both heads plus pineapple rings-to-spears

### Design constraints

| Constraint | Spec |
| --- | --- |
| Power | Manual lever (Nemco pattern). Optional later: 12V actuator |
| Food contact | 304 stainless, removable blades |
| Clean | Tool-free or hex-key disassembly; no hollow unsealed tubes that trap juice |
| Certification path | Designed to NSF/ANSI 2 or 8 intent from day one. Do not prototype in painted mild steel |
| Footprint | Commissary table, ≤ 24" wide. Cart-mount only if the inspector agrees it is integral |
| Output | Spears 4–5" long, ~3/4" thick — they stand in a 16 oz cup |
| Cycle | ≤ 8 seconds per fruit after load |
| Safety | Two-hand or guarded stroke; parking lock like the Nemco pineapple unit |
| Yield | Equal or better than a competent knife. If it wastes more mango than a *frutero*, it failed |

### What not to build

- A dicer
- A 300 kg/h belt slicer
- Anything that needs 220V at the cart
- A “do all fruits” CNC that you will never NSF-list

### Build path

1. Cardboard and 3D-printed **mango cheek holder** + bought blade grid (test yield and spear look)
2. Stainless prototype at a local fabricator
3. Run 500 mangoes. Measure seconds, grams wasted, spear consistency, wash time
4. If it beats the knife on all four, budget an NSF consultant. If it does not, keep the knife

Estimated prototype spend: **$2,000–$6,000**. Estimated commercial-tooling + listing: **$15,000+**. Do not spend that until mango is the thing that stops a second cart.

---

## 5. Cart vs. commissary: where the metal lives

| Tool | Where | Why |
| --- | --- | --- |
| Pineapple corer | Commissary | Heavy, tall, suction feet, messy |
| Melon wedger | Commissary | Messy, needs space |
| Stick cutter | Commissary **or** cart | Small enough for cart if you want visible sticks |
| Mango jig (future) | Cart if small and cleanable; else commissary | Visible mango cut is content |
| Chef’s knife | Both | Finishing, trim, lime |
| Mechanical fridge | Cart | 41°F is the business |

The customer should still **see fruit being finished**. If every spear is pre-cut at 7 a.m., you are a packaged-cup vendor with extra rent.

---

## 6. Decision

| Phase | Machine work |
| --- | --- |
| Days 1–30 | Knife + cheap corer. Prove cups. |
| Days 31–60 | Buy Nemco pineapple corer + stick cutter if pineapple/jícama are the delay |
| After profitable cart | Prototype mango cheek jig |
| After two carts | Consider NSF listing and a second-operator training video based on the jig |

The business is the cart, the site, and the cold chain. The machine is how you stop being the only person who can run it.

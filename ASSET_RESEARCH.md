# Asset research and production plan

Updated: 2026-10-30

## Visual target
A hand-drawn Japanese anime 3D alley, third-person rear camera, narrow lived-in street, dense older shopfronts, stairs, railings, overhead utility wires, signs, crates and an NPC. The target is not a generic low-poly town.

## Candidate environment assets

- **Japan modular neighbourhood pack** — https://3d-asset.com/packs/japan/
  - 93 GLB/R3F assets, 2K PBR, modular Japanese houses/shops, utility poles, fences, vending machines, stairs, bicycles and props.
  - Royalty-free commercial license stated by seller; $39.
  - Strongest current candidate for architecture/layout and dense street dressing. Still needs a stylized material/lighting pass to approach the hand-painted reference.

- **Izakaya Alley and Ramen Shop** — https://3dassets.dev/packs/izakaya-alley-and-ramen-shop
  - 64 modular GLB models, CC0 1.0, 4.4 MB total, 71,060 triangles. Includes alley floor, shopfronts, lanterns, vending machines, crates, kegs, bins and services.
  - Useful as a secondary source for alley-specific details. Geometry is AI-generated and should be visually reviewed before shipping.

- **Showa Retro Shotengai kit** — https://geneshokai.itch.io/showa-retro-shotengai-low-poly-3d-kit
  - $5; 34 GLBs plus editable Blender source and two pre-arranged street scenes. Utility poles/wires, shop curtains, awnings, roofs, signs, bicycle, boxes and other props.
  - Useful for composition and street dressing, but low-poly and vertex-colour based; not a final visual match without reworking.

- **Japanese Street Props** — https://ishiharaworks.itch.io/japanese-street-props
  - $17; GLB/FBX/Blend. Utility pole/transformer, mailbox, guardrail, road signs, vending machine, bins, bicycle rack, streetlight and bus stop.
  - Optional detail pack; not required if equivalent props are available in the Japan neighbourhood pack.

## Candidate character sources

- **Stylized Anime Girl Character (Fab)** — https://www.fab.com/listings/a8bb6ae3-e9b1-40ae-acf2-baf65e00c79f
  - Advertises GLB/FBX/Blend, rigging, and idle/walk/run/jump/sit/talk animations. Price and license must be checked at checkout; seller marks AI-generated.
  - Candidate only; must inspect the actual model silhouette, clothing and face before choosing.

- **Grab3D Character Mixer** — https://grab3d.com/tools/character-mixer/
  - Browser-based, free, CC0, rigged GLB/VRM export. 198 modular parts and built-in motions.
  - Fast fallback for a temporary NPC/player rig; its available styles may not match the requested anime design.

- **Cinevva animation library** — https://app.cinevva.com/tools/animations
  - Advertises 260 CC0 motions and GLB export on paid plans. Check export entitlement before relying on it.

## Production decisions
1. Do not reuse the existing primitive-box scene as the final environment.
2. Build a coherent narrow street from modular shopfronts and props; prioritize correct camera composition, scale, dense facade detail and overhead wires.
3. Create a unified hand-painted/toon material treatment: restrained palette, painted roughness, warm bounce light, soft shadows, subtle outlines and atmospheric depth.
4. Player must read from behind: short black hair, dark dress, white backpack. NPC should be placed by a shopfront with a small everyday action.
5. Keep movement, third-person camera, mouse look and mobile touch controls.
6. Optimize GLB assets and texture sizes for browser loading; use lazy loading only where it does not create visible pop-in.

## Purchase gate
No paid asset has been purchased. The $39 Japan neighbourhood pack is the strongest environment candidate; confirm its actual preview and license details before purchase. The $5 Showa kit is an optional supplementary source, not a substitute for the target art direction.

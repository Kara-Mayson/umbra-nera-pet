Create one horizontal animation strip for Codex pet `umbra-nera`, state `jumping`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 5 full-body frames in one left-to-right row on flat pure magenta #FF00FF. Treat the row as 5 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Original chibi Umbra witch mascot, tall elegant attitude compressed into a compact readable pet silhouette; confident expression and poised gun-kata body language; hairstyle inspired specifically by Bayonetta 1: extremely long black hair arranged into a tall sculptural beehive-like updo with a long flowing tail, never a short bob; costume inspired specifically by Bayonetta 2: black-and-midnight-blue ornate bodysuit with silver filigree and blue ribbon accents; exactly four compact blue-and-silver pistols inspired by Bayonetta 2, two hand-held and two attached at the heels, all physically attached and kept inside the silhouette; ornate spectacles; no logos, no readable text, no direct game asset copying.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `3d-toy`: Stylized 3D toy mascot with smooth rounded forms, simple materials, clear silhouette, and no photoreal complexity. User style notes: Polished stylized 3D collectible-toy rendering, anime chibi proportions, crisp silhouette, large expressive face and glasses, glossy black and midnight-blue materials with restrained silver ornament and subtle red accents; preserve the tall long-hair silhouette from Bayonetta 1 and outfit plus pistols language from Bayonetta 2 in every frame..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Hover jump loop: anticipation, lift, airborne peak, descent, and settle through body height.

State requirements:
- Show the jump through pose and vertical body position only: anticipation, lift, airborne peak, descent, settle.
- Do not draw ground shadows, contact shadows, drop shadows, oval shadows, landing marks, dust, smears, bounce pads, or motion marks under the pet.
- Keep the background outside the pet perfectly flat chroma key with no darker key-colored patches.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

# Bruno & Poppy Character Sheet — ready-to-use image prompt
> Generate ONCE for the whole channel. This is the identity anchor for the recurring couple. Attach
> the rendered sheet as a reference in Flow for EVERY scene, in EVERY episode, so Bruno and Poppy
> stay identical everywhere (see CONCEPT.md §1, §2). Only tiny per-episode accessories may change;
> the core designs never do.
> Panel 1 is the COUPLE HERO SHOT — it locks the size contrast and "they're a couple" reading, so it
> leads the sheet. The rest are per-character body + expression references (expressions matter most,
> because the comedy lives in the faces).

**IMAGE PROMPT:**
```
A single character reference sheet with a title bar at the top reading "BRUNO & POPPY — CHARACTER
SHEET", composed as a horizontal strip of 5 panels arranged SIDE BY SIDE (1x5 row), each panel a
tall portrait rectangle, on a clean neutral light-grey studio background. 3D animated Pixar/chibi
style: soft 3D-rendered characters with big-head chibi proportions, glossy cute look, soft rounded
shapes, warm soft studio lighting, shallow depth of field, high-quality 3D animation render. All
panels show the EXACT SAME two characters, unmistakably consistent in color, shape, and outfit
across every panel:
- BRUNO: a big, chunky, huggable bear boyfriend with big-head chibi proportions and a comically
  round soft belly, soft warm caramel-brown fur with a slightly lighter muzzle and belly, tiny round
  ears on his big head (funny exaggerated proportion), a springy cowlick tuft of fur sticking up on
  top, a little dark-brown nose, big round googly expressive eyes, chubby cheeks, and a goofy lovable
  open grin with the tip of his tongue poking out — a lovable doofus. He wears a cozy oversized
  forest-green hoodie that's a size too small so his round belly peeks out at the bottom. He is
  clearly the BIGGER and taller of the two.
- POPPY: a small, springy bunny girlfriend with big-head chibi proportions, soft cream-white fur,
  pale-pink inner ears, a tiny pink nose, rosy cheeks, big sparkly scheming eyes, one eyebrow cocked
  in a mischievous "up to something" look, two prominent funny buck teeth in a cheeky sly grin, and
  super-expressive long floppy ears (one with a little kink) that flop and perk with her mood. She
  wears an oversized blush-pink sweater and a small scrunchie on one ear. She is clearly the SMALLER
  of the two — the cheeky little troublemaker who starts the mischief.
- Panel 1 [THE COUPLE — lock this]: Bruno and Poppy standing together side by side, full body,
  mid-goof — Poppy with a cheeky buck-toothed grin mid-scheme, Bruno with a big goofy grin playing
  along — clearly a fun, silly loving couple, with the big-bear / small-bunny size contrast obvious.
  This is the hero reference the whole channel stays consistent to.
- Panel 2 [Bruno — full body]: Bruno alone, full body, in a goofy over-eager pose (arms out, big
  grin), front three-quarter view, for proportion and outfit reference.
- Panel 3 [Bruno — expressions]: Bruno's head shown four times in a small row with four clear comedic
  expressions — big goofy tongue-out grin, over-dramatic jaw-dropped shock, caught-in-the-act
  sheepish, and a wheezing belly laugh with squished eyes — for facial consistency.
- Panel 4 [Poppy — full body]: Poppy alone, full body, in a springy mischievous pose (leaning in
  sly, one ear cocked), front three-quarter view, for proportion and outfit reference.
- Panel 5 [Poppy — expressions]: Poppy's head shown four times in a small row with four clear comedic
  expressions — cheeky buck-toothed grin, sly eyebrow-cocked scheming look, caught-in-the-act
  bug-eyed, and a mischievous head-back cackle — for facial consistency.
Consistent fur colors, markings, outfits, and body proportions across all 5 panels — it is
unmistakably the same two characters everywhere, and the size difference between Bruno and Poppy is
consistent. Each panel labeled with its title at the top. Soft, glossy, high-quality 3D animated
Pixar/chibi render, warm soft studio lighting.
Avoid: photorealistic, live-action, realistic animal, 2D flat cartoon, anime, hand-drawn
illustration, sketch, harsh flat lighting, off-model characters, inconsistent fur color between
panels, inconsistent outfits, the two characters looking like the same size, extra limbs, deformed
paws, distorted features, blurry, low quality, busy background, props, text beyond the panel titles,
logo, watermark.
```
Save as: `character-sheet.jpg` (in this folder)

## How to use
The multi-panel `character-sheet.jpg` above is for **human review and for anchoring the design when
rendering STORYBOARDS in Imagen**. It is a poor direct reference for VIDEO: Veo reads a 5-panel grid
as a busy image, not as one character, which is why dropping it into Flow doesn't reliably transfer
the look. For **video generation, feed the clean single-subject ingredient images below** instead
(see the two prompts in the next section). Restate their key traits in the prompt text too (Bruno =
big goofy caramel-brown bear with a cowlick tuft + tongue-out grin in a too-small green hoodie; Poppy
= small cheeky cream-white bunny with buck teeth + a cocked eyebrow in a pink sweater) since Flow is
stateless and won't remember between generations.

## Ingredient images (render these too — the clean single-subject refs Veo actually uses)
> Veo 3.1's "Ingredients to Video" mode (in Flow) wants ONE clear subject per reference image, up to
> 4 per generation. Render these two once and reuse them as the Bruno / Poppy ingredients in every
> scene. (Quick alternative if you don't want to render them: crop Panel 2 and Panel 4 out of the
> character sheet — but a purpose-rendered clean single is cleaner.)

**BRUNO ingredient — IMAGE PROMPT:**
```
A single 3D animated Pixar/chibi character, full body, centered on a clean plain light-grey studio
background, soft even studio lighting, glossy cute look, high-quality 3D render. The character is
BRUNO: a big chunky goofy bear boyfriend with big-head chibi proportions and a comically round soft
belly, soft warm caramel-brown fur with a slightly lighter muzzle and belly, tiny round ears on his
big head, a springy cowlick tuft of fur sticking up on top, a little dark-brown nose, big round
googly expressive eyes, chubby cheeks, and a goofy lovable open grin with the tip of his tongue
poking out. He wears a cozy oversized forest-green hoodie that is a size too small so his round belly
peeks out at the bottom. Friendly, silly, over-eager pose, facing forward, whole body clearly visible.
Avoid: photorealistic, live-action, realistic animal, 2D flat cartoon, anime, hand-drawn
illustration, multiple characters, panels, grid, split image, harsh flat lighting, extra limbs,
deformed paws, distorted features, busy background, props, text, logo, watermark, blurry, low quality.
```
Save as: `bruno-ingredient.jpg` (in this folder)

**POPPY ingredient — IMAGE PROMPT:**
```
A single 3D animated Pixar/chibi character, full body, centered on a clean plain light-grey studio
background, soft even studio lighting, glossy cute look, high-quality 3D render. The character is
POPPY: a small springy cheeky bunny girlfriend with big-head chibi proportions, soft cream-white fur,
pale-pink inner ears, a tiny pink nose, rosy cheeks, big sparkly scheming eyes, one eyebrow cocked in
a mischievous "up to something" look, two prominent funny buck teeth in a cheeky sly grin, and
super-expressive long floppy ears (one with a little kink). She wears an oversized blush-pink sweater
and a small scrunchie on one ear. Springy, mischievous, leaning-in pose, facing forward, whole body
clearly visible.
Avoid: photorealistic, live-action, realistic animal, 2D flat cartoon, anime, hand-drawn
illustration, multiple characters, panels, grid, split image, harsh flat lighting, extra limbs,
deformed paws, distorted features, busy background, props, text, logo, watermark, blurry, low quality.
```
Save as: `poppy-ingredient.jpg` (in this folder)

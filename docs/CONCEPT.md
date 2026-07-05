# CONCEPT — "Bruno & Poppy" (cute-couple comedy shorts)
> Separate channel from ปู่เล่า (video-gen) and the dog POV anthology (dog-pov-video).
> 3D-animated (Pixar/chibi), wordless, 20-30s comedy shorts about one recurring cute couple living
> out a tiny, universally relatable relationship moment — the kind of clip you send straight to your
> partner captioned "this is us."

## 1. What's CONSTANT across every episode (the channel identity)
These never change — this is what makes it recognizably "the same channel":
- **The couple** — the same two characters in every episode (see §2 for their locked designs):
  - **Bruno** — a big, chunky, **goofy bear boyfriend**: a lovable doofus with a cowlick tuft, a
    tongue-out goofy grin, a comically round belly, and big dramatic reactions. Over-eager, clumsy,
    food-motivated.
  - **Poppy** — a small, springy, **cheeky bunny girlfriend** (ทะเล้น): a mischievous little
    troublemaker with a sly buck-toothed grin, a permanently cocked eyebrow, and super-expressive
    floppy ears. She usually STARTS the mischief; Bruno gleefully plays along.
  The comedy duo dynamic is **cheeky schemer bunny + lovable doofus bear**, and the **big-bear /
  small-bunny size contrast** is the visual engine — lean on both in staging. They are the brand,
  like ปู่เล่า/แสง or the golden retriever — never redesign them.
- **3D Pixar/chibi art style** — soft 3D-rendered, big-head chibi proportions, glossy cute look,
  warm cozy lighting, shallow depth of field. Stated explicitly in EVERY prompt (Flow/Veo is
  stateless). **This channel is NON-photorealistic** — the opposite of dog-pov-video; never let a
  "photorealistic/cinematic live-action" clause leak in from a sibling project's template (§7).
- **Cute cinematic THIRD-PERSON camera, expression-first.** We always clearly see BOTH characters
  and their faces — the comedy lives in the expressions and reactions. Eye-level or slightly low,
  warm medium shots that keep both characters legible; push in for a reaction/punchline beat.
  Gentle, polished moves like a high-end 3D animated short. **This is NOT a POV or follow-cam** —
  that's the sibling dog project. Here "POV" appears only in the caption (see below).
- **Wordless — non-verbal emotional sound only, NEVER intelligible speech.** The characters express
  themselves through giggles, gasps, happy hums, gentle whines, contented sighs, munching, a
  surprised "!" gasp — but never words, never a language. This is the one hard rule, and it's what
  makes every video **language-neutral / worldwide-shareable**. (Nuance vs. the dog project: there
  the rule was total silence from the subject; HERE non-verbal vocalizations ARE wanted — just no
  words. Write this precisely into every motion prompt — see §6.)
- **The `POV:` headline** — every video gets one short headline added in CapCut, always starting
  with `POV:`, framing the scene as the viewer's own relatable life (e.g. *"POV: it's 2am and you
  both had the same idea"*). This is the social-media caption convention — figurative, NOT a camera
  instruction. Keep it short, warm, and instantly relatable; write it so a partner-tagged share
  feels natural. No profanity, keep it wholesome.
- **Diegetic sound + non-verbal character sounds ARE generated natively per clip.** Since there's no
  recurring VOICE that must match across scenes (only wordless emotes), Veo's native audio is a good
  fit — describe the specific sounds tied to each shot's action (a fridge door thunk, a floor creak,
  crunchy chip munching, a muffled two-character giggle). See §6.
- **Music is the ONE thing that must NOT be per-clip.** Same rule as both sibling projects: N clips
  each inventing their own score stitch into chaos. Add ONE continuous music bed across the whole
  video in CapCut; never request music in a Veo prompt.
- **Length — 20-30 seconds.** Default: 4 scenes (a comedy 4-beat, §3). Generate each scene at ~8s in
  Flow, then trim the dead frames in CapCut so the final lands tight at ~24-28s. Comedy timing is
  finessed in the edit — err toward snappy.
- **Warm, wholesome, funny tone** — relatable and a little silly, always with a soft loving heart.
  Never mean-spirited, sad, crude, scary, or a real fight. The takeaway is always "aww, that's us."

## 2. The characters (locked designs — full detail in the character sheet)
> Render the character sheet ONCE (`assets/characters/CHARACTER_SHEET_PROMPT.md`) and attach it as a
> reference in Flow for EVERY scene, so the couple stays identical across every episode. Restate the
> key traits in prompt text too (Flow is stateless).

**Bruno (bear boyfriend) — the lovable doofus:**
- Chunky, rounded, huggable bear with a **comically round soft belly**; big-head chibi proportions;
  soft **warm caramel-brown fur**, slightly lighter muzzle/belly. **Tiny round ears on a big head**
  (funny proportion), a **springy cowlick tuft** on top, little dark-brown nose, **big round googly
  eyes**, chubby cheeks, and a **goofy open grin with the tongue-tip poking out**.
- Wears a **cozy oversized hoodie** (default: forest-green) that's a size too small so his belly
  peeks out — comedic homebody vibe.
- Clearly the BIGGER/taller one. Personality reads: goofy, over-eager, clumsy, dramatic, snack-obsessed.

**Poppy (bunny girlfriend) — the cheeky troublemaker (ทะเล้น):**
- Small, **springy** bunny; big-head chibi proportions; **soft cream-white fur** with pale-pink
  inner ears, tiny pink nose, rosy cheeks, **big sparkly scheming eyes**, one **eyebrow cocked** in a
  mischievous look, **two prominent funny buck teeth** in a sly cheeky grin, and **super-expressive
  long floppy ears** (one with a little kink) that flop/perk with her mood as a comic device.
- Wears an **oversized pastel sweater** (default: blush pink), a little scrunchie on one ear.
- Clearly the SMALLER one. Personality reads: cheeky, teasing, springy schemer — the instigator.

Only tiny per-episode accessories may change (a themed prop, seasonal item); the core designs never
do. Keep the size contrast obvious in every two-shot, and keep both faces mid-goof — the funnier the
expressions, the more shareable the clip.

## 3. Reusable comedy 4-beat template (shape stays, content reskins per theme)
Each scene ≈ 8s (4 storyboard panels × 2s). 4 scenes ≈ 32s raw → trim to ~24-28s final in CapCut.
| Beat | Scene | Shape (constant) | Reskin example: Midnight snack raid |
|---|---|---|---|
| 1. Setup | SC01 | Establish the ordinary situation + one character's little intent | Bruno tiptoes out of bed toward the kitchen, trying to be sneaky |
| 2. Parallel / build | SC02 | The second character, or a complication, enters — tension/anticipation builds | Poppy is ALSO sneaking to the kitchen from the other side; the fridge is the goal |
| 3. Collision / punchline | SC03 | The two lines cross — the surprise/gag lands, biggest reactions | They both reach into the open fridge and freeze face-to-face — caught! — then burst into giggles |
| 4. Button / heart | SC04 | The warm, funny resolution — the "aww, us" beat that earns the share | They give up sneaking and happily share the snack together on the kitchen floor, leaning on each other |

Keep beat 1 (setup) and beat 4 (heart/button) as anchors; the two middle beats can merge into one
scene for a tighter 3-scene cut if a theme is simpler. Always end on the warm button — that's what
makes people tag their partner.

## 4. Content-safety & tone guardrails (check before writing prompts)
- **Wholesome only.** Cute domestic couple comedy: snacks, gaming, chores, cuddles, small
  everyday-life gags. No crude/adult content, no real arguments or a couple genuinely upset, no
  alcohol/substances, no danger, nothing scary.
- **Keep night scenes cozy, not spooky.** "2am" / dark settings must read warm and gentle (soft
  moonlight, warm fridge glow) — handle this in the POSITIVE description (warm, cozy, soft), never by
  naming "not scary/creepy" in a negative prompt (that backfires — see §7).
- **No real, identifiable people; no brands/logos** on props (generic snack packaging, generic game
  controller/console). Carries over from the sibling projects.
- **Animals are stylized cute characters**, not realistic animals.

## 5. Theme backlog (grows like the sibling projects' idea backlogs)
Every theme is a tiny relatable couple moment with a share-ready `POV:` headline.
| Theme | POV headline (draft) | Beat sketch | Status |
|---|---|---|---|
| Midnight snack raid | "POV: it's 2am and you both had the same idea" | both sneak to the fridge, catch each other, share the snack | **EP001 — in progress** |
| Gaming bf vs busy gf | "POV: when you're both doing your own thing but still check in on each other" | he games, she crafts/reads; little check-in glances; end cuddled up | idea |
| Grow old together | "POV: same us, just older" | the same tiny routine repeated as they age young → old | idea |
| Sick-day care | "POV: when your person is sick and you go full nurse mode" | one's sniffly & grumpy, the other fusses with soup/blanket | idea |
| Sharing one blanket | "POV: the nightly blanket war (that always ends in a cuddle)" | tug-of-war over the blanket, resolves into a shared burrito | idea |
| Cooking together fail | "POV: cooking together = 10% cooking, 90% chaos" | flour everywhere, a tiny mess, laughing, eat takeout instead | idea |
| Rainy day in | "POV: the whole plan was cancelled and honestly? perfect" | rain outside, cozy indoors, movie + snacks pile | idea |
| Matching without trying | "POV: we left the house in the same outfit again" | both reach for similar cozy clothes, notice, laugh | idea |
| (add more here) | | | |

## 6. Writing sound (diegetic + non-verbal character sound) into motion prompts
Every motion prompt includes an explicit, scene-specific sound description. Pattern:
```
Include natural synchronized sound effects matching the visuals: <specific action sounds tied to
this exact shot, e.g. "a soft floor creak, a quiet fridge hum, a fridge door thunk">. The
characters express themselves ONLY through non-verbal sounds — soft giggles, gasps, happy hums,
gentle whines, contented sighs, munching — never words. NO spoken words, NO intelligible dialogue,
NO narration, NO music or musical score in this clip — sound effects and wordless character sounds
only, matched naturally to the motion on screen.
```
- Tie action sounds to the SPECIFIC events in the shot (a floor creak ≠ a fridge thunk ≠ a chip
  crunch). The sound palette is part of what makes each scene land.
- Always include BOTH: the explicit "non-verbal sounds only" clause AND the "NO spoken
  words/dialogue/narration/music" exclusion — this keeps Veo from inventing a voice line, a language,
  or a score while still allowing the giggles/gasps that carry the comedy.
- The consistency reminders still apply every prompt: full ~8s duration (no early cutoff), same
  Bruno & Poppy designs as the character sheet and as every other clip, no on-screen
  text/captions/watermark (the `POV:` headline is added later in CapCut, not baked into the clip).

## 6a. Camera language (cute cinematic third-person) — the channel's look
Restate positively in every scene prompt:
- **Third-person, expression-first.** The camera clearly frames both characters (or the one in
  focus) so their faces and reactions read. Warm medium shots for staging; push in for a big
  reaction or the punchline; a gentle two-shot for the button.
- **Eye-level or slightly low, gentle moves** — smooth, polished, like a high-end 3D animated short.
  Not shaky, not a drone shot, not a static locked-off security-cam look.
- **Stage the size contrast** — compose so Bruno (big) and Poppy (small) are both clearly readable
  in two-shots; it's a core visual joke.
- **Cozy warm lighting** always, even at night (soft moonlight + warm practical lights like a fridge
  glow or a lamp).
- Keep exclusions as short noun phrases in the `Avoid:` list — never stacked "do not" sentences in
  the body (that tripped Flow's policy filter on the sibling project). Good Avoid terms here:
  `photorealistic, live-action, realistic animal, 2D flat cartoon, harsh flat lighting, static
  locked-off camera, shaky cam, off-model characters, only one character visible when both should be`.

## 7. What carries over from the sibling projects (lessons already learned — don't re-discover)
- **Veo/Flow is stateless** — restate character designs, style, and camera in EVERY prompt, EVERY
  scene. Attach the character sheet + location sheet as references every time.
- **Negative prompt = technical/quality/style terms ONLY**, never content-safety category words as
  exclusions. Naming danger/threat/scary/adult words in the `Avoid:` list gives no benefit and risks
  tripping the platform's policy filter (confirmed on dog-pov-video EP001). Tone is controlled by
  choosing wholesome content up front (§4) and describing it warmly — not by listing what to avoid.
- **No stacked negation in the prompt body** ("Do NOT… This is NOT… NOT a…") — describe the shot
  positively; put exclusions only as short noun phrases in the `Avoid:` list.
- **No bracketed meta-instructions**, never write "don't render a watermark" as a sentence — put
  "watermark" as a noun in the Avoid list instead.
- **Style-tag sanity check every episode** — this channel is **3D Pixar/chibi, NON-photorealistic**.
  Never let a "photorealistic / cinematic live-action / historical-epic" clause copy-paste in from
  dog-pov-video, and never let a "no photorealism" clause meant for ปู่เล่า contradict… actually here
  we DO want non-photorealistic, so the ปู่เล่า-style toon tag is compatible — but always confirm the
  style line matches THIS channel's 3D-chibi look before rendering.
- **Storyboards = a horizontal 1×N strip of true 9:16 panels, never a 2×2 grid.**
- **Absolute panel timing across the whole video, never resets per scene.**
- **Ground motion prompts in the ACTUAL rendered storyboard**, not just the original intent — adjust
  the motion prompt to what the storyboard actually shows.
- **Music once, globally, in CapCut** — never per Veo clip.
- **Scene-ID labels, if wanted, as a plain unbracketed prefix only.**

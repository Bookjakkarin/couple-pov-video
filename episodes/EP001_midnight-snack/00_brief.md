# EP001 — Bruno & Poppy: Midnight Snack Raid

- **POV headline (add in CapCut):** `POV: it's 2am and you both had the same idea`
  - Alternates: `POV: he thought he was being sneaky` · `POV: 2am, and neither of us can sleep on an
    empty stomach`
- **Format:** 3D Pixar/chibi, wordless (non-verbal sounds only), third-person cute cinematic, ~24-28s
  final (4 scenes × ~8s raw, trimmed in CapCut)
- **Couple:** Bruno (big goofy caramel-brown bear, green hoodie) + Poppy (small cheeky cream-white
  bunny, pink sweater) — same character sheet as every episode (`assets/characters/`)
- **Setting:** their cozy apartment at night — the bedroom, then the kitchen. **It is 2am: DARK.**

## The story (logical, common-sense chain — this is what was broken before, now fixed)
Bruno and Poppy are a couple; they **sleep in the same bed**. At 2am Bruno wakes up hungry and
carefully sneaks out **without waking Poppy**, feeling clever. He gets to the kitchen and raids the
fridge. But Poppy wakes up too and pads in after him — and they find each other mid-snack. The joke
("you both had the same idea") is that they **independently got the same 2am craving**; the warmth is
that they happily give up and share. Every beat is caused by the one before — nobody appears or reacts
out of nowhere.

## Hard staging rules for this episode (from the failed first render — see CONCEPT.md §7)
- **It is night. Everything is DARK/dim.** The ONLY light is soft blue moonlight and, in the kitchen,
  the warm glow of the open fridge. Characters are softly lit by that dim light — **never brightly
  lit**. Tell Veo to relight the characters to match the dark scene.
- **One location per scene, joined by CUTS.** Do NOT animate characters walking through
  doorways/hallways between rooms (Veo invents wrong geometry and self-opening doors). Bedroom scene
  stays in the bedroom; kitchen scenes stay in the kitchen.
- **Pin the fridge:** a **mint-green retro fridge**, the SAME one in every kitchen scene (feed the
  same kitchen still as an ingredient each time, or it drifts — SC02 and SC04 had different fridges).
- **Presence logic:** Poppy is in BED (asleep) in SC01, ABSENT in SC02 (Bruno alone), and only
  ARRIVES in SC03. Bruno leaves the bed first; Poppy follows.

## Scene list (join key for storyboard + motion prompts)
| Scene | Time (raw) | Beat | WHAT WE SEE | SOUND (diegetic + non-verbal, no words) |
|---|---|---|---|---|
| SC01 | 0:00-0:08 | Setup | Dark bedroom, 2am. Bruno AND Poppy asleep together in the same bed. Bruno's belly rumbles; he wakes, carefully slides out without waking Poppy, tucks the blanket back around her, and tiptoes off out of frame. Poppy sleeps on. | soft snoring, a low tummy rumble, gentle blanket rustle |
| SC02 | 0:08-0:16 | Build | Dark kitchen, moonlight only. Bruno tiptoes to the mint-green fridge and opens it — warm light spills onto his happy face. He peers in and picks out a snack, pleased with himself. | quiet tiptoe steps, fridge door seal, a happy little hum |
| SC03 | 0:16-0:24 | Meet (punchline) | Bruno stands munching at the open fridge. Behind him, Poppy pads in sleepily, rubbing an eye. Bruno turns and they SEE each other — a surprised beat (both realize the other snuck out too) — then both break into a warm delighted giggle. | soft footsteps, a small surprised gasp, then two-character giggling |
| SC04 | 0:24-0:32 | Heart (button) | They plop down on the kitchen floor in the warm fridge glow and share one bowl of snacks, Poppy leaning cozily on Bruno. Content and happy. | snack crinkle, happy munching, contented sighs |

## Content-safety check
Wholesome domestic couple comedy: sleeping, sneaking a snack, sharing food, a cuddle. No danger,
nothing scary (dark = cozy via moonlight + warm fridge glow, described positively — never a
negative-prompt word). Generic unbranded food. No real people. **SC03 note:** keep it a *happy
surprise* between the two — avoid "caught red-handed / guilty / freeze" framing, which tripped Flow's
policy filter on the first attempt. Clear.

## Timing / edit note
Generate each scene as an ~8s clip. Raw total ≈ 32s → trim in CapCut to ~24-28s. Hold the SC03
surprise-then-giggle beat long enough to read both faces, then cut to SC04.

## Close
SC04 ends on the warm shared-snack cuddle (the SC04 test render already nailed this) — the frame
people screenshot and send to their partner.

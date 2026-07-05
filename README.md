# Bruno & Poppy — cute-couple comedy shorts (share-to-your-partner content)

A separate content channel from `video-gen` (ปู่เล่า) and `dog-pov-video`. Every short is a
**20-30 second, wordless, 3D-animated comedy** about the same cute couple — **Bruno** (a big goofy
bear boyfriend, a lovable doofus) and **Poppy** (a small cheeky bunny girlfriend, the ทะเล้น
troublemaker) — living out one tiny, universally relatable relationship moment. The kind of clip a viewer instantly sends to their own partner with
"this is literally us."

**No human speech, ever.** The characters emote entirely through non-verbal sound — giggles, gasps,
happy hums, contented sighs, munching. This makes every video **language-neutral**, so it works for
any audience worldwide with zero translation.

Each video carries a **`POV:` headline** added in CapCut (e.g. *"POV: it's 2am and you both had the
same idea"*). Here "POV" is the social-caption convention — it means *"this relatable scene is your
life"* — NOT a first-person camera. The camera is a **cute cinematic third-person** that clearly
shows both characters and their faces, because the comedy lives in the expressions. (This is the key
difference from the sibling `dog-pov-video` project, which uses a literal follow-cam.)

## What stays constant (the brand)
- **The couple** — same Bruno (bear) + Poppy (bunny), locked designs from the character sheet.
- **3D Pixar/chibi art style** — soft, glossy, big-head cute proportions, warm cozy lighting.
- **Wordless** — non-verbal emotional sounds only, never intelligible speech.
- **Third-person, expression-first camera** — we always read both faces.
- **Warm, wholesome, funny tone** — relatable couple comedy with a soft heart; never mean, sad, or
  crude.
- **One `POV:` headline per video**, added in CapCut.
- **20-30s runtime.**

## What changes per episode
The **relationship moment** (gaming vs. her hobby, growing old together, midnight snack raid, sick-day
care…), its **location**, and the specific gags. See the theme backlog in
[`docs/CONCEPT.md`](docs/CONCEPT.md) §5.

## Repo map
| Path | What |
|---|---|
| `docs/CONCEPT.md` | Format bible: constants vs. per-episode variables, 4-beat comedy template, theme backlog, carried-over Veo/Flow lessons |
| `assets/characters/` | The one-time Bruno & Poppy character sheet (locked designs + expression rows) — reused in every episode for consistency |
| `episodes/EP001_midnight-snack/00_brief.md` | EP001: Midnight snack raid — headline + 4-beat scene arc + timing |
| `episodes/EP001_midnight-snack/00b_location_sheet.md` | EP001 location sheet prompt (cozy apartment at night) |
| `episodes/EP001_midnight-snack/01_photo_prompts.md` | Storyboard image prompts, ready for Flow |
| `episodes/EP001_midnight-snack/02_motion_prompts.md` | Veo motion prompts (audio direction embedded — no separate script) |
| `episodes/EP001_midnight-snack/storyboards/` | Save rendered storyboard images here |
| `episodes/EP001_midnight-snack/clips/` | Save rendered Veo clips here |
| `episodes/EP001_midnight-snack/final/` | Final CapCut export here |

## Production pipeline (per episode)
1. Render the **character sheet** once (`assets/characters/`) — reuse forever.
2. Render the episode **location sheet** (`00b_location_sheet.md`).
3. Render the **storyboards** (`01_photo_prompts.md`), attaching both sheets as references in Flow.
4. Write/confirm **motion prompts** grounded in the actual storyboards (`02_motion_prompts.md`).
5. Generate the clips in **Veo/Flow** (attach character sheet + location sheet every time).
6. Assemble in **CapCut**: stitch clips, add ONE music bed across the whole video (never per-clip),
   add the `POV:` headline text.

## Status — EP001 (Midnight snack raid)
- [ ] Render the Bruno & Poppy character sheet
- [ ] Render the EP001 location sheet (cozy apartment at night)
- [ ] Render all 4 EP001 storyboards, check against the character + location sheets
- [ ] Finalize motion prompts grounded in the rendered storyboards
- [ ] Generate 4 clips in Veo, assemble in CapCut with music + `POV:` headline
- [ ] If it lands: pick the next theme from the backlog in `docs/CONCEPT.md` §5

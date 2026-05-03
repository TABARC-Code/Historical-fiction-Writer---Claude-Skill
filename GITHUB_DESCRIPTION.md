# historical-fiction-master — GitHub Description

**Developer:** TABARC-Code

---

## Short Description (for GitHub repository description field)

> A complete, networked Claude skill for writing historical fiction with professional craft — covering temporal immersion, period research, sensory writing, character biography, period voice, social codes, communication speed as plot, and a seven-point audit protocol. v2.0.

---

## Full GitHub Description

### historical-fiction-master

A professional-grade Claude skill system for historical fiction writing. Encodes the complete craft of the form — from the initial research disposition through scene-level sensory deployment to final draft audit — in a networked architecture where every node links to every other, bilaterally.

---

### Why This Skill Exists

Historical fiction is one of the most technically demanding forms of prose. The novelist must simultaneously:

- Hold the documented historical record accurately
- Inhabit an era's cosmology, vocabulary, and sensory world from the inside
- Invent plausibly in the gaps that research cannot fill
- Write characters whose psychology is of their time, not a modern mind in period costume
- Make the past feel as immediate and urgent as the present

Most writing assistance tools treat these as separate tasks. This skill treats them as a single integrated practice — because that is what historical fiction writing actually is.

---

### What v2.0 Adds Over v1.0

The second version was produced by a full audit of the v1.0 skill against the complete craft teachings it was built to encode. Seventeen gaps were identified and closed:

| Gap | Resolution |
|-----|-----------|
| White Heat principle absent | Added to SKILL.md A2 and character-biography.md |
| B.S. Filter not named or developed | Added to SKILL.md B2 and truth-calibration.md |
| Communication speed as plot absent | Added to SKILL.md B3, research-methods.md, period-voice.md, period-texture-engine (4th pillar) |
| "Good yucky stuff" principle absent | Added to SKILL.md A4 and sensory-writing.md |
| Illiterate protagonist absent | Added to SKILL.md C4 and character-biography.md |
| Children in history underdeveloped | Full section added to SKILL.md C5 and character-biography.md |
| Codes and mores (duelling etc.) absent | Added to SKILL.md D2 and period-voice.md |
| Ending architecture absent | Added to SKILL.md E5 |
| Then-and-Now resonance absent | Added to SKILL.md E2, F5, G8, truth-calibration.md |
| Body as archive underdeveloped | Full section added to character-biography.md C3 |
| Language obligation absent | Added to SKILL.md D5 and period-voice.md |
| Retrospective principle absent | Added to research-methods.md |
| Partisan growth principle absent | Added to truth-calibration.md |
| River of Time framing underdeveloped | Expanded in SKILL.md core philosophy |
| Novelist's edge vs historian absent | Added to SKILL.md B2 and truth-calibration.md |
| Period social codes in texture engine absent | Added as 4th pillar to period-texture-engine |
| Audit incomplete (7 checks vs 6) | G8 Then-and-Now check added |

---

### Architecture

The skill is a **networked system**, not a linear document. Seven nodes in the master skill, five reference files, and one upgraded subskill — all cross-linked bilaterally so that any node can reach any other in either direction.

```
historical-fiction-master/
├── SKILL.md                    7 craft nodes + skill map + 12 quick rules
├── references/
│   ├── sensory-writing.md      Five senses + yucky stuff + original simile
│   ├── research-methods.md     Sources + data systems + comm. speed mapping
│   ├── truth-calibration.md    B.S. filter + official narrative + Then-and-Now
│   ├── period-voice.md         Anachronism + codes/mores + dialogue + comm. vocab
│   └── character-biography.md  Biography template + white heat + illiteracy + children
└── subskills/
    └── period-texture-engine/
        ├── SKILL.md            Four-pillar texture engine + diagnosis protocol
        └── references/
            └── period-tools.md Quick-reference toolkits by category and era
```

---

### The Governing Standard

**Verisimilitude** — the appearance or semblance of truth — governs every component. Research serves it. Sensory writing serves it. Period voice serves it. Character biography serves it. The audit protocol tests for it. Everything else is in service of this single word.

---

### Invocation

Claude invokes this skill automatically for any request involving historical fiction writing, research, critique, or planning. It can also be called explicitly with `/skill historical-fiction-master`.

The `period-texture-engine` subskill can be called directly when a passage needs texture diagnosis and repair without invoking the full master skill.

---

### Compatibility

- Claude Sonnet 4 and above
- Claude skills system (standard SKILL.md frontmatter format)
- No external dependencies

---

### Tags

`claude-skill` `historical-fiction` `creative-writing` `period-writing` `verisimilitude` `research-methods` `sensory-writing` `anachronism` `character-biography` `period-voice` `immersion` `craft` `TABARC-Code`

# historical-fiction-master

**A complete, networked craft skill for writing historical fiction with deep authenticity, sensory immersion, and verisimilitude.**

Developed by **TABARC-Code**.

---

## What This Skill Does - iN THEORY

`historical-fiction-master` teaches Claude how to write, plan, research, draft, and audit historical fiction at a professional craft level. It covers the full arc of the novelist's practice — from the initial research posture through scene-level sensory deployment to final draft audit — and does so through a networked system of interlinking nodes that can be entered at any point and traversed in any direction.

The skill encodes the complete craft of historical fiction writing, including:

- **Temporal immersion** — making the past feel as immediate and pressing as the present
- **The White Heat principle** — the difference between assembling prose and inhabiting a character
- **Verisimilitude** — the governing standard for everything invented
- **The B.S. Filter and Beagle Test** — active scepticism that flags when the historical record doesn't cohere
- **Five-sense sensory deployment** — including the "good yucky stuff" that carries the authority of the specific
- **Period cosmology** — writing from inside an era's explanatory framework, not looking in at it
- **Communication speed as plot architecture** — what characters can know, and when
- **Codes and mores** — duelling, honour, guild, and the deadly social grammar of every era
- **The illiterate protagonist** — a fundamentally different relationship with memory and the world
- **Children in history** — not sentimentalised; the unheeded voices in the rumble of history. Those sad little voices in the background stuffed up a chimney.
- **Then-and-Now resonance** — why this story from Then matters to a reader living Now
- **The language obligation** — being worthy of the oldest human tradition
- **Full audit protocol** — seven audit checks covering anachronism, sensory completeness, verisimilitude, immersion breaks, clichés, period texture, and Then-and-Now resonance

---

## File Structure

```
historical-fiction-master/
├── SKILL.md                          ← Master skill (entry point)
│
├── references/
│   ├── sensory-writing.md            ← Five-sense technique; yucky stuff; original simile
│   ├── research-methods.md           ← Source hierarchy; data systems; communication speed
│   ├── truth-calibration.md          ← B.S. filter; official narrative; partisan principle
│   ├── period-voice.md               ← Period vocabulary; codes & mores; dialogue; anachronism
│   └── character-biography.md        ← Biography template; white heat; illiteracy; children; POV
│
└── subskills/
    └── period-texture-engine/
        ├── SKILL.md                  ← Four-pillar texture engine (material/register/constraint/comm.)
        └── references/
            └── period-tools.md       ← Quick-reference toolkits by category and era
```

---

## How to Install

Place the `historical-fiction-master/` folder in your Claude skills directory (typically `/mnt/skills/user/`). The skill will be available to Claude immediately.

The `period-texture-engine` subskill is embedded within the master skill folder and requires no separate installation.

---

## How to Use

### Automatic invocation
Claude will automatically invoke this skill whenever a request involves:
- Writing, drafting, planning, or critiquing historical fiction
- Questions about period research, anachronism, sensory detail, or historical authenticity
- Any project set in a recognisable past era or involving historical figures
- Questions about dialogue in period speech, period social codes, or achieving temporal immersion

### Manual invocation
Prefix your request with `/skill historical-fiction-master` to invoke explicitly.

### Navigation
The skill is networked, not linear. See the Skill Map in `SKILL.md` for the full node diagram. Common entry points:

| Task | Start here |
|------|-----------|
| Writing a scene | SKILL.md → A (Immersion) → C (Character) → D (Language) |
| Auditing a draft | SKILL.md → G (Audit Protocol) |
| Planning a novel | SKILL.md → E (Structure) → B (Research) → A (Immersion) |
| The gist feels thin | SKILL.md → F5 (Then-and-Now) |
| Passage lacks period feel | period-texture-engine subskill directly |
| Character feels modern | references/character-biography.md → belief and cosmology section |
| Dialogue sounds wrong | references/period-voice.md → dialogue section |

---

## Design Philosophy

This skill is built on a single governing standard: **verisimilitude** — the appearance or semblance of truth. Every component of the craft serves it. Research serves it. Sensory writing serves it. Period voice serves it. Character biography serves it. The audit protocol tests for it.

The skill is networked rather than linear because historical fiction writing is networked rather than linear. A scene-level sensory question leads back to the character biography, which leads forward to the period voice, which loops back through the audit. All links are bilateral. Every node can reach every other node.

The skill encodes the distinction between the historian and the novelist: the historian faces backward only. The novelist faces both ways — carrying the reader into the present tense of any era, while knowing that the river of time is still running, that Then is still shaping Now, and that a great story means more than it says.

---

## Skill Map (Condensed)

```
CORE PHILOSOPHY (River of Time / Verisimilitude / Fire of Language)
     │                                        │
     ▼                                        ▼
[A] IMMERSION ENGINE              [B] RESEARCH ARCHITECTURE
 White Heat · Material · Senses    B.S. Filter · Comm. Speed · Data
 Yucky Stuff · Period Texture ──────────────────────────────────┐
     │                                        │                 │
     ▼                                        ▼                 │
[C] CHARACTER        [D] LANGUAGE       [E] STRUCTURE    [F] CREDIBILITY
 Actor · White Heat   Period Voice       Gist · Then-Now  Fact vs Fiction
 Body Archive         Codes & Mores      Grabbers          Partisan
 Illiteracy           Dialogue           Endings · Plot    Then-and-Now
 Children             Comm. tech         Arc
     │                    │                    │               │
     └────────────────────┴────────────────────┴───────────────┘
                               │
                        [G] AUDIT PROTOCOL
                         G1 Anachronism · G2 B.S. Filter
                         G3 Sensory · G4 Verisimilitude
                         G5 Immersion Breaks · G6 Clichés
                         G7 Period Texture · G8 Then-and-Now
```

---

## Versioning

| Version | Notes |
|---------|-------|
| 1.0 | Initial release |
| 2.0 | Full audit revision: added White Heat principle, B.S. Filter, communication speed as plot, yucky stuff principle, illiterate protagonist, children in history, codes and mores, Then-and-Now node, endings architecture, language obligation, retrospective principle, four-pillar period-texture-engine |

---

## License

Released for use with Claude skills systems. See repository for full licence terms.

*TABARC-Code*

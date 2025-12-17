# SKYRIDGE - Project Manifest
**Fort Lewis College Concept Website Prototype**
**Version:** 1.0
**Created:** 2025-12-17
**Status:** Active

---

## 1. PROJECT IDENTITY

**Codename:** SKYRIDGE
**Tagline:** *Elevating the Digital Campus Experience*

The name evokes:
- Elevation (Fort Lewis sits at 7,600 ft in the San Juan Mountains)
- Vision and forward-thinking
- The ridge as a vantage point - seeing further, seeing clearer
- Mountain heritage central to FLC identity

---

## 2. MISSION

Create an executive-ready concept prototype demonstrating what Fort Lewis College's digital presence could become when enabled by AI-driven design, intelligent information architecture, and modern user experience principles.

**This is not a redesign. This is a concept car.**

Bold. Visionary. 5-10 years ahead of current higher-education web standards.

---

## 3. PRIMARY GOAL

Produce a stunning, executive-ready proof-of-concept that:
- Demonstrates what Fort Lewis College *could* be digitally
- Makes the current website's limitations obvious without explicit criticism
- Positions this work as strategic, institutional value creation
- Signals private-industry-grade innovation capability

---

## 4. SUCCESS CRITERIA

The final outcome must:
- [ ] Feel like a "concept car" reveal, not a normal website
- [ ] Be immediately impressive within the first 10 seconds
- [ ] Make executives say: "This is 10 levels beyond what we have"
- [ ] Clearly communicate that AI enables this speed, depth, and personalization
- [ ] Be polished and demo-ready without technical explanation
- [ ] Remain professional, executive-appropriate, and defensible

---

## 5. TARGET AUDIENCE

**Primary:** VP and President level executives at Fort Lewis College
**Secondary:** Executive leadership team
**Tertiary:** Web/Marketing team (technical appreciation)

The presentation should inspire vision, not require technical understanding.

---

## 6. OPERATING CONSTRAINTS

| Constraint | Description |
|------------|-------------|
| **Scope** | Concept prototype only, not production replacement |
| **Priority** | Speed, clarity, and impact over completeness |
| **Creativity** | Encouraged but grounded in institutional reality |
| **Tone** | Professional, executive-appropriate, defensible |
| **Platform** | Static site hosted on GitHub Pages |
| **Technology** | Vanilla HTML/CSS/JS (no framework dependencies) |

---

## 7. PROJECT PHASES

| Phase | Name | Objective |
|-------|------|-----------|
| 0 | Initialization | Establish workflow, documentation, repository |
| 1 | Website Inventory | Crawl and catalog entire existing FLC website |
| 2 | Experience Benchmarking | Analyze elite digital experiences for patterns |
| 3 | Concept Vision | Define SKYRIDGE identity, tone, and visual direction |
| 4 | Role-Based Entry | Design stakeholder-specific entry experiences |
| 5 | Information Architecture | Rebuild navigation and content structure |
| 6 | Extended Value | Integrate community, jobs, events, local context |
| 7 | Executive Presentation | Polish and prepare for live demo |

---

## 8. SOURCE OF TRUTH RULES

### 8.1 File Hierarchy
1. **@Project_Manifest.md** - Constitutional document (this file)
2. **@Active_State.md** - Current operational state
3. **@Stakeholder_Map.md** - Audience intelligence
4. **Phase-specific artifacts** - As defined in each phase

### 8.2 Conflict Resolution
- If documents conflict, **@Project_Manifest.md governs**
- If Manifest is silent, **@Active_State.md governs**
- Chat is ephemeral; files are source of truth
- All durable decisions must be recorded in files

### 8.3 Update Protocol
- Any agent may update @Active_State.md
- @Project_Manifest.md changes require explicit user approval
- All changes committed to git with clear messages
- Session handoffs documented in @Active_State.md

---

## 9. STATELESS WORKFLOW PROTOCOL

This project operates under a **multi-agent, stateless workflow**.

**Core Principles:**
- Multiple AI agents may contribute across separate sessions
- Any agent must be able to resume with zero prior context
- All context lives in files, not conversation memory
- Session independence is a hard constraint

**Session Commands:**
- `continue` - Resume from @Active_State.md
- `SITREP` - Generate status report
- `end session` - Output updated files and suggest commit
- `phase complete` - Advance to next phase

---

## 10. DESIGN FOUNDATIONS

### 10.1 Color Palette (Base)
| Role | Color | Hex |
|------|-------|-----|
| Primary | FLC Blue | #003366 |
| Accent | FLC Gold | #FFB81C |
| *Elevated variants TBD in Phase 3* |

### 10.2 Emotional Tone
- Confident
- Modern
- Intelligent
- Welcoming
- Innovative
- *Not* corporate, stiff, or bureaucratic

### 10.3 Visual Direction
- Futuristic accents and motion
- Clean, spacious layouts
- Purposeful animation
- Mountain/elevation imagery
- *Concept car aesthetic*

---

## 11. REPOSITORY STRUCTURE

```
Future FLC Website/
├── @Project_Manifest.md      # This file
├── @Active_State.md          # Mission card
├── @Stakeholder_Map.md       # Audience intelligence
├── .gitignore
├── README.md
├── intelligence/             # Research data
│   ├── site-inventory/       # Phase 1 output
│   ├── benchmarks/           # Phase 2 output
│   └── patterns/             # Extracted patterns
├── design/                   # Design artifacts
│   ├── vision/               # Phase 3 output
│   ├── architecture/         # Phase 5 output
│   └── wireframes/
├── src/                      # Website source
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── assets/
├── docs/                     # Documentation
│   └── decisions/            # ADRs
└── templates/                # Workflow templates
```

---

## 12. KEY ASSUMPTIONS

| Assumption | Rationale | Revisit Trigger |
|------------|-----------|-----------------|
| Concept name "SKYRIDGE" | Mountain context, vision metaphor | Phase 3 if better option emerges |
| Vanilla HTML/CSS/JS | Maximum control, no dependencies | If interactivity demands framework |
| GitHub Pages hosting | Simple, free, shareable URL | If dynamic features required |
| Single-page application style | Cohesive concept car experience | Phase 4 architecture decision |
| FLC colors as base | Institutional grounding | Phase 3 elevation |

---

## 13. DELIVERABLES

### Primary Deliverable
A live, hosted concept website demonstrating SKYRIDGE vision.

**URL:** https://winncook.github.io/future-flc-website/

### Supporting Artifacts
- Site inventory documentation (Phase 1)
- Benchmark analysis (Phase 2)
- Information architecture map (Phase 5)
- Executive presentation materials (Phase 7)

---

## 14. CHANGELOG

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | 2025-12-17 | Initial manifest created |

---

*This document is the constitutional source of truth for the SKYRIDGE project.*
*All agents operating on this project must read this file before beginning work.*

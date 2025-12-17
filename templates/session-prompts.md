# SKYRIDGE - Session Prompts
**Copy-paste prompts for AI session continuity**

---

## STARTING A SESSION

### Option 1: Quick Resume
```
continue
```
Use when you're the same agent continuing work. The AI will read @Active_State.md and continue from the Active Task.

### Option 2: Full Context Start
```
I'm continuing work on SKYRIDGE (Future FLC Website concept prototype). Please read:
1. @Project_Manifest.md (constitutional document)
2. @Active_State.md (current status)
Then continue from the Active Task section.

Working directory: C:\Users\winnl\Documents\Future FLC Website
```
Use when starting fresh or for a new agent to get full context.

### Option 3: Phase-Specific Start
```
I'm continuing SKYRIDGE Phase [X]: [Phase Name].
Read @Active_State.md and focus on [specific task].
```

---

## DURING A SESSION

### Status Report
```
SITREP
```
Generates a VP-ready status report on SKYRIDGE progress.

### Phase Advancement
```
phase complete
```
Use when current phase deliverables are done. AI will update @Active_State.md and prepare for next phase.

### Decision Documentation
```
document decision: [Topic]
Rationale: [Why this choice]
Alternatives considered: [What else was evaluated]
```
AI will add to @Active_State.md Decisions Log.

### Value Assessment
```
assess value: [Feature or decision]
```
AI will evaluate impact on executive presentation value.

---

## ENDING A SESSION

### Standard End
```
end session
```
AI will:
1. Output complete updated @Active_State.md
2. Summarize what was accomplished
3. Note exact starting point for next session
4. Suggest git commit message

### End with Commit
```
end session and commit
```
AI will do standard end plus create git commit with proper message format.

---

## PHASE-SPECIFIC PROMPTS

### Phase 1: Website Inventory
```
Begin inventory of https://www.fortlewis.edu/
Crawl structure, identify pages, catalog navigation.
Store findings in intelligence/site-inventory/
```

### Phase 2: Experience Benchmarking
```
Analyze benchmark site: [URL]
Focus on: UX patterns, navigation, personalization, visual design
Store analysis in intelligence/benchmarks/
```

### Phase 3: Concept Vision
```
Define SKYRIDGE visual identity:
- Finalize color palette
- Define typography
- Establish motion/animation principles
- Document in design/vision/
```

### Phase 4: Role-Based Entry
```
Design entry experience for: [Student/Parent/Faculty/Staff/Community]
Define content hierarchy and navigation path.
Document in design/architecture/
```

### Phase 5: Information Architecture
```
Map information architecture for: [Section]
Simplify navigation, eliminate redundancy.
Document in design/architecture/
```

### Phase 6: Extended Value
```
Design extended value feature: [Jobs/Events/Community/etc]
Define integration approach and content sources.
```

### Phase 7: Executive Presentation
```
Polish for executive demo:
- Review all sections
- Test interactions
- Ensure 10-second impact
- Prepare talking points
```

---

## SPECIAL COMMANDS

### Git Operations
```
git status check
```
AI will run git status and report.

```
prepare commit: [description]
```
AI will stage changes and prepare commit message.

### Research
```
research: [Topic]
```
AI will gather information and store in intelligence/.

### Design Review
```
review design: [Component/Page]
```
AI will evaluate against SKYRIDGE design principles.

---

## TROUBLESHOOTING

### If Context Seems Lost
```
Reset context. Read these files in order:
1. @Project_Manifest.md
2. @Active_State.md
3. @Stakeholder_Map.md
Then report current understanding.
```

### If Unsure About Direction
```
Review @Project_Manifest.md success criteria.
Evaluate current work against those criteria.
Recommend adjustments if needed.
```

### If Blocked
```
Document blocker in @Active_State.md:
Blocker: [Description]
Impact: [What it prevents]
Resolution options: [Possible solutions]
```

---

*These prompts ensure stateless continuity across any AI agent working on SKYRIDGE.*

# AFSFC Scoping Session -- Presenter Cheat Sheets

**Date:** April 15-16, 2026 | San Antonio
**Document:** enabling-readiness-at-scale-v7.html (AFSFC tab, C-UAS scope)
**Format:** One sheet per section. Each section assumes a different presenter.

---

## SECTION 01: ALIGN the Mission Needs

**Your job:** Establish that we build FROM their documents, not TO our product. Walk out with the governing requirements named, owned, and traced.

### Sub-accordion 1a: Governing Requirements

**What's on screen:** 4 pre-loaded doc cards + 1 blank. Each card has editable fields for document name, publication #, owning office, owning stakeholder, change authority, cadence, access status, and political signals.

**Pre-loaded docs:**
| # | Document | Pub | Owner | Access | Notes |
|---|---|---|---|---|---|
| 1 | AFI 31-101 -- Integrated Defense | AFI 31-101 | AFSFC | TBD | Core doctrine |
| 2 | DAFI 31-131 Vol 2 | DAFI 31-131v2 | TBD | Pending | Need stakeholder name |
| 3 | AFJQS SEI 3CS | AFJQS 3CS | SFTRG | Restricted | SEI still maturing -- key input for config |
| 4 | SFTRG C-sUAS TTPs | In draft | SFTRG | In Draft | Exposure risk if we build to a standard that changes. Also opportunity: we adapt when it does. CATM building live kinetic -- we're the scenario + measurement complement |

**Facilitation prompt (on screen):**
> "What document would you point to if a wing commander asked you to prove C-UAS training meets the standard? And who owns it -- not just the office, but the person driving the updates?"

**What to capture live:**
- Stakeholder names (the "who" behind each doc)
- Change authority (who signs off on updates)
- Political signals (tensions, timelines, competing priorities)
- Any missing documents they name -- click "+ Add another governing document"
- Cadence selections (Annual / 18mo / Event / TBD)

**Key talking points:**
- "We don't write the standard. We build the measurement system that traces to YOUR standard."
- "When this document gets updated, the platform reconfigures within 30 days -- no instructor re-cert, no new procurement."
- Doc 4 (TTPs in draft) is a strategic card: "Draft TTPs = risk if we build to a moving target. Also = opportunity: we're the platform that adapts when it does."

### Sub-accordion 1b: Adjacent Mandates

**IMPORTANT: This is a CLOSE, not an opener.** The on-screen text says "Surface after Sections 01-04 are complete for C-UAS."

**Expansion zone prompt:**
> "We just built the full C-UAS training operating system together. Now -- how many of these same airmen also need to meet any of these other mandates? Because the same platform already supports them."

**8 adjacent mandates (click to expand each):**

| Mandate | Hook line | Why it matters |
|---|---|---|
| CATM Qualification (AFI 36-2654) | "The live range teaches the shot. We teach the fight." | CATM building live kinetic C-UAS range. We're the virtual complement. M18/M4A1 qual tables already deployed at Navy. |
| Ready Airman Training (RAT) | "Same rep feeds the AFFORGEN gate" | V-CSTR modules mapped to RAT tasks. HAF/A3T alignment in progress. |
| Deployment Familiarization | "Hands on it before they get there" | AFSFC leadership ID'd the gap: airmen don't touch deployment equipment until downrange. We provide home-station reps. |
| Unit Readiness Reporting (AFI 10-201) | "Demonstrate readiness on demand" | Structured session records mapped to standards. Commanders can defend readiness when asked. |
| VTS Validation (CADMS) | "From interesting to counts" | AFSFC is VTS validation authority. AETC/A3X owns accreditation. |
| Use-of-Force / NLW (AFI 31-118) | "Already proven across Ontario LE" | NLW measurement architecture fielded in Ontario. Same approach for home-station SF. |
| M320 Grenade Launcher | "Already scoped as Phase 2" | Explicitly in the AF simulator requirement. AFSFC near-term priority alongside C-UAS. |
| Tactical Communications | "Already measured inside C-UAS scenarios" | Radio procedures, SALUTE, dispatch -- already scored behaviors in the C-UAS kill chain. Standalone comms training is configuration, not new dev. |

**Toggle each one the customer reacts to.** These feed the Alignment Statement.

### Sub-accordion 1c: Alignment Statement

**What's on screen:** A live-updating statement that auto-populates from the docs named in 1a and mandates toggled in 1b.

**Current draft text:**
> The ICST C-UAS training requirement is governed by [auto-populated docs]. The training operating system will be configured to trace every scored behavior back to these governing documents. When governing documents are updated, the platform will reconfigure within ~30 days...

**What to do:**
1. Read it back to the room verbatim
2. Their nod makes it a program artifact
3. "Copy Statement" button captures it
4. Badge shows "Co-authored - Draft" -- it stays draft until requirements trace is validated

**Access date field is editable** -- get them to commit: "AFSFC will provide access to governing documents by [date]."

---

## SECTION 02: DEFINE What "Right" Looks Like

**Your job:** Co-author the behavioral standards table. Walk out with measurable behaviors defined per weapon system, per kill-chain stage.

### Sub-accordion 2a: Measurable Behaviors

**What's on screen:** Editable table. Columns: Criteria | Shotgun | Dronebuster | (LMAMS) | (Coyote). LMAMS/Coyote columns appear only in full-suite scope toggle.

**Pre-loaded values (C-UAS core):**

| Stage | Criteria | Shotgun | Dronebuster |
|---|---|---|---|
| **Detect/Identify** | Time to detect | <=10s | <=10s |
| | Time to PID | <=15s | <=15s |
| | VACR accuracy | >=90% | >=90% |
| **Track/Report** | Track hold | >=5s | >=5s |
| | SALUTE time | <=30s | <=30s |
| **Engage/Defeat** | Time to employ | *Your target* | *Your target* |
| | Hit rate | *Your target* | N/A (EW) |
| **Tactical** | ROE compliance | 100% | 100% |

**"Your target" cells = recommended discussion points.** These are amber-highlighted, editable. The customer clicks and types their number.

**Facilitation approach:**
- Start with Detect/Identify -- these are least controversial, builds momentum
- Track/Report is procedural -- SALUTE timing is familiar territory for SF
- Engage/Defeat is where the real discussion happens -- "What does 'good' look like for time to employ? What hit rate would you expect on a qual course?"
- Don't push on hit rates if they don't have data yet -- that's why the cells say "Your target"

**Interactive features:**
- Every cell is click-to-edit (Tab to navigate, Enter/Escape to confirm/cancel)
- Criteria labels (left column) are also editable -- they can rename behaviors
- "+ Add behavior" buttons under each stage -- if they say "we also need X," add it live
- "x" button on each row to remove behaviors that don't apply
- All edits persist in browser (localStorage)

**Key line:** "These are starting points from our Navy deployments. Your kill chain may look different. Let's define what right looks like for YOUR airmen."

### Sub-accordion 2b: Data Routing

**What's on screen:** Editable table -- who consumes the training data, what they want, how often, what priority.

**Pre-loaded consumers:**

| Consumer | What They Want | Frequency | Priority |
|---|---|---|---|
| Installation Commander | Unit-level readiness snapshot | Monthly | High |
| MAJCOM / A4S | Cross-installation comparison | Quarterly | Medium |
| AFSFC HQ | Enterprise C-UAS readiness posture (AFI 10-201 artifact) | Quarterly | High |
| DRRS-S / Readiness Reporting | Structured evidence for unit readiness | Annually | Medium |

**What to capture:**
- Who else wants this data? Click "+ Add data consumer"
- Frequency adjustments (dropdowns: Daily through TBD)
- Priority cycling (click chip: High/Medium/Low)
- Specific report formats or feeds they'd need

**Key line:** "This isn't just training data -- it's readiness evidence. Who in your chain of command would want to see this, and how often?"

---

## SECTION 03: CONFIGURE Training Operating Systems

**Your job:** Walk through the technical configuration -- missions, sensors, measurement. Show that this is configuration, not development.

### Sub-accordion 3a: Mission Configuration

**What's on screen:** Editable table with 6-stage progression per weapon system.

**Pre-loaded 6-stage progression:**

| Stage | Shotgun | Dronebuster |
|---|---|---|
| 1 | Setup & Safety | Setup & Safety |
| 2 | Find & Hold (no-shoot) | Detect & classify |
| 3 | ID & Report | Track & lock |
| 4 | Decision Gate (ROE) | Employ EW |
| 5 | Engage -- single | Multi-drone |
| 6 | Two-target sequence | Swarm |

Plus: Environments (Day/Night, Open/Urban), Threat profiles (Group 1 & 2 UAS, VACR profiles, single + swarm)

**All stage descriptions are editable.** If they say "our progression is different," edit live.

**Doctrine source row:** AFJQS SEI 3CS, ATP 3-01.81, CNGBI 7500.00

**Key line:** "This is a 6-stage progression -- we start with safety and fundamentals, build through ROE decision-making, and end with multi-target engagement. Does this match how you train the fight?"

### Sub-accordion 3b: Sensor Configuration

**What's on screen:** Hardware readiness status per weapon system.

| System | Status |
|---|---|
| Shotgun | In Config (amber) |
| Dronebuster | Available (green) |
| LMAMS | Full Scope (purple) -- only at full contract |
| Coyote | Full Scope (purple) -- only at full contract |
| Headset | Scoping -- standalone VR, model TBD |
| Kit config | Scoping -- per-installation, qty = squadrons x airmen/flight |

**Key line:** "Dronebuster is ready now -- the SBIR co-development is complete. Shotgun is in configuration. The full-scope systems come with the expanded contract."

### Sub-accordion 3c: Measurement Configuration

**What's on screen:** Scoring rubrics, qual gates, evidence pipeline, AAR, commander view.

**Key details:**
- Scoring: Pass/fail per AFJQS + composite (shotgun) | Defeat confirmation + time (dronebuster)
- Qual gates: Detect <=10s, PID <=15s, VACR >=90%, ROE 100% (all scoping)
- Evidence pipeline: Evidence Engine -> Installation -> AFSFC HQ
- Review/AAR: Scenario replay, engagement review, instructor override
- Commander view: Installation readiness -> MAJCOM roll-up -> AFSFC HQ

**Status pills explain themselves:**
- **Scoping** = to be confirmed in this session
- **Full Scope** = available at full contract scope
- No pill = decided by precedent from fielded programs

**Key line:** "Everything with a 'Scoping' tag -- that's what we're here to nail down. Everything without one is already decided by precedent from programs we've fielded."

---

## SECTION 04: FIELD Training Operating Systems

**Your job:** Make the cost burden real, show the deployment path, and land the scale story. This section has 4 sub-accordions -- each builds on the last.

### Sub-accordion 4a: Live-Fire Cost Model

**What's on screen:** Interactive calculator with 6 sliders. This shows the COST OF THE CURRENT live-fire approach -- NOT our pricing.

**Sliders and defaults:**

| Slider | Default | Range | What it means |
|---|---|---|---|
| Quals/Airman/Year | 2 | 1-4 | How often should each airman qualify? |
| Range Days Available/Site/Year | 24 | 2-52 | Dedicated C-UAS shotgun range days actually available |
| Airmen/Range Day | 25 | 10-50 | Throughput per range day (RSO + lane constraints) |
| Rounds/Qual Cycle | 25 | 10-100 | Shotgun shells per airman per attempt |
| Cost per Round | $1.50 | $0.50-$5.00 | Per-shell including procurement & logistics |
| Range Ops Cost/Day | $3,000 | $500-$10K | RSO staffing, scheduling, safety, transport (excl. ammo) |

**Output (at defaults):**
- Rounds required: 500,000
- Annual ammo spend: $750K
- Range days required: 800
- Annual range ops spend: $2.4M
- **Total annual live-fire burden: $3.15M**
- Bottom line: "And none of it produces scored data"

**CRITICAL: This is the live-fire BURDEN calculator, NOT our pricing. Do NOT discuss SSVR pricing or ROM from this screen.** The point is: "Look how much the current approach costs -- and it doesn't even generate evidence."

**Facilitation approach:**
- Let THEM adjust the sliders. "What's realistic for range days at your installations?"
- The gap becomes self-evident: they can't cycle enough airmen through live ranges
- "We're not saying eliminate live fire. We're saying the math doesn't work for qualification-at-scale on ranges alone."

### Sub-accordion 4b: Deployment & Readiness Model

**What's on screen:** 3 sliders + readiness gap visualization bar.

| Slider | Default | Range |
|---|---|---|
| Installations | 50 | 3-200 |
| Lanes/Installation | 1 | 1-4 |
| Airmen/Squadron | 200 | 100-400 |

**Output cards:**
- Airmen who can't qualify (live) -- red, shows the gap
- ICST coverage -- green, "100%, always available, no range required"
- Scored quals/year (ICST) -- blue

**Gap visualization:** Stacked bar showing Live (small) vs ICST fills (large). At defaults: 30% live / 70% gap.

**Key line:** "At 50 installations with 200 airmen per squadron -- your current range capacity covers 30% of the force. The other 70% can't qualify. ICST closes that gap to zero."

**IMPORTANT: Get them to tell YOU the installation/squadron/airmen numbers.** These are the inputs Oliver still needs validated.

### Sub-accordion 4c: Fielding Roadmap

**What's on screen:** Draggable Gantt chart across FY26-FY29.

| Phase | Timing | Key milestones |
|---|---|---|
| **Configuring** | FY26 Q3 | Qual tables, IDIQ, sites selected, Evidence Engine setup. TO-1 awarded, confirmation sites ID'd, cadre curriculum built |
| **Validating** | FY26 Q3-Q4 | 3-5 sites fielded, cadre trained, scored quals before FY26 close. Evidence Engine live, first qual data reportable to AFSFC HQ |
| **Fielding** | FY27 Q1-Q3 | Wave 2: 10-15 installations, dashboard, AFI 10-201, MAJCOM brief. Commander readiness visibility live, multi-site aggregation |
| **Full Scale & Updating** | FY27 Q3 - FY29 | 50+ installations, catalog expansion, annual TTP update cadence, POR path. Readiness Sensing Network, M18 + NLW + UoF layers, cross-service interest |

**Bars are draggable** -- they can adjust timing live if their timeline is different.

**Key line:** "We're showing scored qualifications to AFSFC HQ before FY26 closes. By FY27, commanders have readiness visibility across installations. By FY28, full scale."

### Sub-accordion 4d: Readiness & Savings at Scale

**What's on screen:** The payoff -- FY26/27/28 projections + cumulative burden.

**Projection cards (values driven by sliders above):**
- By Sep 2026: Airmen with C-UAS qual access (confirmation wave, 3-5 sites)
- By Sep 2027: Airmen with C-UAS qual access (validated + first wave)
- By Sep 2028: Airmen with C-UAS qual access (full-scale complete)

**Cumulative live-fire burden by FY28:** Shows total ammo, range days, range ops cost. "And none of it produces scored data."

**Bottom callout cards:**
- Scored qualifications (cumulative by FY28)
- Training lanes deployed
- Dronebuster EW: "infinity -> 0" gap closed (no live alternative exists)

**Closing statement (auto-generated from sliders):**
> "By the end of FY28, [X] airmen across [X] installations have access to scored, qualification-grade C-UAS training -- generating [X] evidence records. The current live-fire model carries a [$X] cumulative burden -- and produces zero scored data. And that's C-UAS alone -- before M18, non-lethal, and use-of-force layers activate across the installed base."

**This is your mic-drop moment.** Read it, let it land, then circle back to 1b (Adjacent Mandates expansion zone).

---

## GENERAL TIPS FOR ALL PRESENTERS

1. **Everything saves automatically** (localStorage). If the browser crashes, edits persist.
2. **Tab key navigates** between editable cells. Enter confirms, Escape cancels.
3. **Scope toggle** (top of page) switches between "Core C-UAS - 2 systems" and "Full Weapons Suite - 4 systems." Stay on C-UAS unless they ask about LMAMS/Coyote.
4. **Other instance tabs** (CNAP, CNIC, Ontario, SFSQ, ICST-RC) are proof points. If someone asks "where has this worked?" -- click the tab and show the fielded data.
5. **"Your target"** cells (amber italic) are discussion prompts. The customer fills these in. If they can't answer, that's fine -- leave it and move on.
6. **Don't show ROM or pricing.** The cost calculator shows their CURRENT burden, not our pricing.
7. **The document is the deliverable.** After the session, export/share the configured doc. It becomes the scoping artifact.

\# Drift. — Personal Digital Twin for Student Drift Detection



> \*Industrial systems don't fail suddenly — they drift out of calibration first. DRIFT applies that same monitoring logic to a student.\*



\*\*USAII Global AI Hackathon 2026 — Undergraduate Track\*\*

Built by Muflih Safeer · B.Eng Mechanical Engineering, Smart Manufacturing Engineering · UDST, Qatar



🔴 \*\*\[Live Demo →](https://your-render-url.onrender.com)\*\*



\---



\## What is DRIFT?



DRIFT is a personal digital twin that monitors a student the way a reliability engineer monitors a machine — watching academics, career readiness, wellbeing, and finances as four interdependent subsystems, and detecting drift before it becomes failure.



This is not a habit tracker. It is not an AI chatbot wrapper. It is a complete decision-support pipeline built on reliability engineering principles (FMEA, digital twin monitoring, fault-tree analysis) applied to a person for the first time.



\---



\## How it works



```

15 self-reported inputs

&#x20;       ↓

Weighted scoring engine (cross-subsystem penalty coefficients)

&#x20;       ↓

Root-cause trees (FMEA-style failure-mode matching)

&#x20;       ↓

Nearest-neighbour archetype matching (12 synthetic student patterns)

&#x20;       ↓

Forecast (3 trajectories + 90% confidence corridor)

&#x20;       ↓

Monte Carlo simulation (500 runs → probability distribution)

&#x20;       ↓

Counterfactual interventions (quantified, disclosed coefficients)

&#x20;       ↓

Work orders + Twin Letter (decision-support output)

```



Every number on screen traces back to a named constant in the source code. There is no black box.



\---



\## The 9 panels



| # | Panel | What it shows |

|---|-------|---------------|

| 01 | \*\*Findings\*\* | Root-cause breakdown, AI reasoning chain, common pattern alert, drift event timeline |

| 02 | \*\*Forecast\*\* | 3 projected trajectories with 90% confidence bands, degrading over time |

| 03 | \*\*Interventions\*\* | Live counterfactual scenario — check actions, watch quantified deltas animate |

| 04 | \*\*Work Orders\*\* | Auto-generated, prioritised, completable maintenance queue |

| 05 | \*\*Archetype\*\* | Nearest-neighbour match against 12 student archetypes, with radar chart |

| 06 | \*\*Dependencies\*\* | Interactive SVG causal influence map — hover any node to highlight pathways |

| 07 | \*\*History\*\* | Calibration history with sparklines and velocity tracking |

| 08 | \*\*Simulation\*\* | 500-run Monte Carlo — probability distributions to a user-set deadline |

| 09 | \*\*Twin Letter\*\* | Plain-English decision-support letter for an advisor or mentor |



\---



\## Why this is not AI slop



\- \*\*Zero external API calls\*\* — no LLM, no server, no backend, fully client-side

\- \*\*Every coefficient is disclosed\*\* — weights, penalties, and thresholds are named constants in the source, not hidden parameters

\- \*\*No black box\*\* — any number on screen can be traced back to the exact formula that produced it

\- \*\*Single self-contained HTML file\*\* — vanilla JavaScript, Chart.js, hand-written SVG

\- \*\*Responsible AI by design\*\* — every score is labelled "modelled estimate, not a diagnosis"; confidence bands visibly degrade; contradictory inputs trigger explicit calibration warnings



\---



\## Responsible AI



Self-reported wellbeing data can understate real risk — someone in genuine distress may under-report stress, which could cause the system to understate risk and produce false reassurance.



DRIFT mitigates this through:

\- Explicit "modelled estimate, not a diagnosis" label on every score-bearing surface

\- Confidence bands that visibly widen and degrade past 18 months

\- Calibration warnings when inputs are contradictory (e.g. high GPA + critically low sleep)

\- Human-in-the-loop by design — DRIFT ranks options, never decides for the user

\- The Twin Letter explicitly recommends review with a real advisor before acting on high-priority items



\---



\## Technical details



| Property | Value |

|----------|-------|

| Stack | Vanilla HTML/CSS/JavaScript |

| Dependencies | Chart.js (CDN, forecast charts only) |

| Backend | None |

| External APIs | None |

| Data storage | localStorage (client-side only) |

| Deployment | Static file — works from any web host or local file system |

| File count | 1 |



\---



\## Running locally



No installation required. Download `index.html` and open it in any modern browser:



```bash

\# Option 1 — just open the file

open index.html



\# Option 2 — serve locally if you prefer

npx serve .

```



\---



\## Built by



\*\*Muflih Safeer\*\* — First-year B.Eng Mechanical Engineering, Smart Manufacturing Engineering

University of Doha for Science and Technology (UDST), Qatar



Solo build. One week. Zero budget. Zero APIs.



\---



\*DRIFT v3 — local-only · no external calls · all scores are modelled estimates, not diagnoses · consult a human advisor before major decisions\*


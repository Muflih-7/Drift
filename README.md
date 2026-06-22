# DRIFT — Personal Digital Twin for Student Drift Detection

> *Industrial systems rarely fail suddenly — they drift out of calibration first.*

DRIFT applies reliability engineering principles used in manufacturing and asset management to a student, modelling academics, career readiness, wellbeing, and finances as four interdependent subsystems of a personal digital twin.

**USAII Global AI Hackathon 2026 — Undergraduate Track**

🔴 **Live Demo:** https://drift-sa21.onrender.com/

---

## Overview

DRIFT is a decision-support system inspired by industrial reliability engineering.

Instead of waiting for failure, DRIFT detects **drift** early — identifying emerging problems, tracing likely root causes, forecasting future outcomes, and quantifying the effect of interventions before action is taken.

The system treats a student the same way a reliability engineer treats a critical machine:

* Monitor performance
* Detect degradation
* Identify failure modes
* Forecast trajectories
* Recommend corrective actions

DRIFT does **not** diagnose people and does **not** make decisions on behalf of users.

---

## Core Idea

Traditional productivity tools track isolated habits.

DRIFT models a student as a **digital twin** consisting of four interacting subsystems:

1. Academic Performance
2. Career Readiness
3. Wellbeing
4. Financial Stability

Changes in one subsystem influence the others through disclosed cross-dependency coefficients.

---

## System Pipeline

```text
15 self-reported inputs
        ↓
Weighted scoring engine
        ↓
Cross-subsystem penalties
        ↓
FMEA-style root-cause trees
        ↓
Nearest-neighbour archetype matching
        ↓
Forecast generation
        ↓
Monte Carlo simulation (500 runs)
        ↓
Counterfactual interventions
        ↓
Work orders + Twin Letter
```

Every value shown in the interface traces back to a named constant in source code.

There is no black box.

---

## Features

### 1. Findings

* Root-cause breakdown
* AI reasoning chain
* Common-pattern alerts
* Drift event timeline

### 2. Forecast

* Three future trajectories
* Confidence corridors
* Visible uncertainty degradation over time

### 3. Interventions

* Counterfactual scenario analysis
* Quantified impact estimates
* Interactive comparison

### 4. Work Orders

* Prioritised actions
* Maintenance-style task queue
* Completion tracking

### 5. Archetype Matching

* Nearest-neighbour classification
* Similarity percentage
* Radar chart visualisation

### 6. Dependency Map

* Interactive subsystem relationships
* Hover-based pathway highlighting

### 7. History

* Calibration history
* Trend velocity tracking
* Sparklines

### 8. Simulation

* 500-run Monte Carlo analysis
* Probability distributions
* Deadline-based outcomes

### 9. Twin Letter

* Plain-English summary
* Advisor-ready output
* Human-readable recommendations

---

## Why This Is Different

### Zero External APIs

No LLM calls. No backend. No server-side processing.

### Fully Explainable

All scores, weights, penalties, and thresholds are disclosed constants.

### No Black Box

Any output can be traced back to the formula that generated it.

### Single-File Architecture

Built as one self-contained HTML application.

### Reliability Engineering Approach

Inspired by:

* Digital twins
* Failure Mode and Effects Analysis (FMEA)
* Root-cause analysis
* Preventive maintenance
* Fault-tree reasoning

---

## Responsible AI

DRIFT is designed as a decision-support tool, not a diagnostic system.

### Safeguards

* Every score is labelled:

> Modelled estimate — not a diagnosis.

* Confidence intervals widen over time.
* Forecast certainty intentionally degrades beyond 18 months.
* Contradictory inputs trigger calibration warnings.
* Users remain responsible for decisions.
* High-priority recommendations should be reviewed with a real advisor.

---

## Technical Details

| Property   | Value                   |
| ---------- | ----------------------- |
| Stack      | HTML / CSS / JavaScript |
| Framework  | None                    |
| Charts     | Chart.js                |
| Backend    | None                    |
| APIs       | None                    |
| Storage    | localStorage            |
| Deployment | Static hosting          |
| File Count | 1                       |

---

## Running Locally

No installation is required.

### Option 1

Open:

```text
index.html
```

in any modern browser.

### Option 2

Serve locally:

```bash
npx serve .
```

---

## Project Philosophy

Industrial assets do not fail without warning.

People often do.

DRIFT explores whether reliability engineering principles traditionally applied to machines can be adapted to support human decision-making.

---

## Built By

**Muflih Safeer**

First-Year B.Eng Mechanical Engineering
Smart Manufacturing Engineering

University of Doha for Science and Technology (UDST), Qatar

* Solo build
* One week
* Zero budget
* Zero APIs

---

## Disclaimer

DRIFT provides modelled estimates only.

It is **not** a medical, psychological, financial, or academic diagnostic system.

Users should consult qualified professionals before making significant decisions.

---

**DRIFT v3**
Local-only • No external calls • Explainable by design

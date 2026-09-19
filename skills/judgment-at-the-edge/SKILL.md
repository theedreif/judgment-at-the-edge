---
name: judgment-at-the-edge
description: Apply Ed Reif's Judgment at the Edge framework to consequential decisions under uncertainty using SIGNAL → CONDITION → LIMIT → DECISION → EVIDENCE. Use for scenarios, incident analysis, autonomous systems, DFR, field operations, SOP exceptions, escalation decisions, and decision debriefs.
---

# Judgment at the Edge

Use this skill when the user must design, analyze, practice, or review a decision made where procedure alone is insufficient.

## Operating premise

**When reality departs from the plan, judgment becomes the operating system.**

The objective is not merely to find a correct answer. Develop or evaluate the ability to **recognize, decide, act, explain, and update**.

## Core decision loop

**SIGNAL → CONDITION → LIMIT → DECISION → EVIDENCE**

### SIGNAL — What changed?
Identify the cue, anomaly, event, contradiction, or information that deserves attention.

### CONDITION — What is true now?
Interpret the operating environment. Do not react to a signal without considering context.

### LIMIT — What constrains the decision?
Identify boundaries such as authority, policy, safety, time, resources, system capability, uncertainty, rules of engagement, or mission requirements.

### DECISION — What action is justified?
Choose an action that fits the signal, current conditions, and known limits. State alternatives when useful.

### EVIDENCE — What makes the decision defensible?
Capture observations, rationale, actions, results, uncertainties, and what should be learned.

## DFR loop

For Drone as First Responder and similar multi-source operational contexts, use:

**NOTICE → INTEGRATE → PRIORITIZE → DECIDE → DEFEND**

- NOTICE the meaningful signal.
- INTEGRATE relevant information sources.
- PRIORITIZE what matters now.
- DECIDE what action is justified.
- DEFEND the reasoning with evidence.

## Workflow

### 1. Define the decision moment
State the mission, actor, environment, stakes, time horizon, and decision that must be made.

### 2. Separate facts from assumptions
List known information, uncertain information, inferred information, and missing information. Never manufacture an operational fact to complete the model.

### 3. Identify signals
Find cues that should trigger attention. Distinguish meaningful signals from noise and hindsight.

### 4. Interpret conditions
Describe what the signals mean in context. Consider whether the operating state has changed.

### 5. Establish limits
Identify authority, safety, policy, technical, resource, time, ethical, and mission boundaries. Flag limits that require authoritative verification.

### 6. Generate defensible options
Describe plausible actions and their relevant tradeoffs without pretending uncertainty has disappeared.

### 7. Make or analyze the decision
Connect the proposed action explicitly to SIGNAL, CONDITION, and LIMIT.

### 8. Define evidence
Specify what should be recorded or observed so the decision can be reviewed without relying solely on the eventual outcome.

### 9. Stress the decision
Ask what new signal, changed condition, crossed limit, or failed assumption would cause the decision to change.

### 10. Update
Convert the evidence into a lesson, revised threshold, scenario, field tool, or operational question.

## Required output pattern

Unless the user requests another format, produce:

1. **Decision moment**
2. **Known / uncertain / missing**
3. **SIGNAL**
4. **CONDITION**
5. **LIMIT**
6. **Options**
7. **DECISION**
8. **EVIDENCE**
9. **What would change the decision?**
10. **Update / lesson**

For DFR contexts, optionally add a second pass using NOTICE → INTEGRATE → PRIORITIZE → DECIDE → DEFEND.

## Decision-quality rule

Do not judge a decision only by its outcome.

A good decision can produce a bad outcome. A bad decision can produce a good outcome. Evaluate whether the reasoning was appropriate given the information, conditions, limits, and uncertainty available at the time.

## Guardrails

- Do not invent policy, legal authority, technical thresholds, safety limits, or rules of engagement.
- Distinguish facts, assumptions, hypotheses, and recommendations.
- Do not use hindsight as if it were information available at the decision moment.
- Do not turn the framework into a rigid checklist when conditions require judgment.
- In safety-critical or regulated contexts, authoritative procedures and qualified human judgment take precedence.
- Treat AI output as decision support, not automatic authority.
- Preserve uncertainty when the evidence does not justify certainty.

## References

Use bundled references for deeper guidance:

- `references/core-loop.md`
- `references/dfr-loop.md`
- `references/decision-quality.md`
- `references/scenario-design.md`

## Relationship to the Ed Reif Field System

Judgment at the Edge is the DECIDE layer of:

**BUILD → DECIDE → POSITION → TEST → UPDATE**

Operational Readiness builds capability before the moment. Judgment at the Edge structures reasoning in the moment. Decision Science helps position choices under uncertainty. Field Notes tests the ideas against reality.

## Closing test

Before finishing, ask:

> What did the person know then, what changed, what constrained them, why was the action justified, and what evidence lets us learn without confusing outcome with decision quality?

# Field Tool 006 — DFR Judgment Card

### A compact decision tool for Drone as First Responder operations

> **Autonomy does not remove judgment. It changes where judgment is required.**

The **DFR Judgment Card** adapts the Judgment at the Edge architecture to Drone as First Responder environments.

It is designed to help structure operator reasoning when multiple information sources, autonomous-system behavior, mission priorities, policy boundaries, uncertainty, and time pressure converge.

It is a **training and decision-support framework**, not a substitute for agency policy, applicable law, aviation requirements, command authority, or platform-specific procedures.

## The DFR Loop

> # NOTICE → INTEGRATE → PRIORITIZE → DECIDE → DEFEND

### 1. NOTICE
**What deserves attention?**

Identify the signal that changes the operating picture.

It may come from:

- dispatch information;
- live video;
- telemetry;
- a system alert;
- another responder;
- changing environmental conditions;
- unexpected autonomous behavior;
- loss or degradation of information;
- a discrepancy between what was expected and what is occurring.

The first failure of judgment is often failing to notice that the situation has changed.

### 2. INTEGRATE
**What is the best current picture?**

Do not treat one signal as the whole situation.

Combine relevant sources while recognizing uncertainty, latency, contradiction, and missing information.

Ask:

- What do I know?
- What do I think I know?
- What remains uncertain?
- Which sources agree?
- Which sources conflict?
- Is the system showing me reality—or only one representation of it?

> **More data is not automatically more understanding.**

### 3. PRIORITIZE
**What matters most right now?**

Determine which problem requires attention first.

Consider:

- immediate safety;
- mission objective;
- urgency;
- people at risk;
- aircraft/system state;
- information value;
- competing requests;
- consequences of delay;
- whether human intervention is becoming necessary.

Prioritization converts an information stream into an operating problem.

### 4. DECIDE
**What action is justified?**

Select the next action based on the current picture, applicable limits, and mission need.

Possible categories may include:

- continue;
- reposition;
- gather more information;
- communicate;
- coordinate;
- escalate;
- intervene;
- change mission priority;
- discontinue or terminate according to applicable procedures.

The card does not prescribe the operational answer.

It structures the reasoning required to reach one.

### 5. DEFEND
**Why was this decision reasonable given what was known at the time?**

Capture the decision basis:

- meaningful signal;
- interpreted condition;
- relevant limit;
- information available;
- uncertainty recognized;
- action selected;
- expected consequence;
- actual result.

Defensibility is not about proving that hindsight agrees with the decision.

It is about making the reasoning observable and reviewable.

## The Card

```text
FIELD TOOL 006 — DFR JUDGMENT CARD

MISSION / INCIDENT:
____________________________________________

NOTICE
What changed or requires attention?
____________________________________________

INTEGRATE
What information do I have?
____________________________________________

What conflicts, gaps, latency, or uncertainty exist?
____________________________________________

PRIORITIZE
What matters most right now?
____________________________________________

What can wait?
____________________________________________

LIMIT
What constrains the decision?
Policy / authority / safety / system / environment / other:
____________________________________________

DECIDE
What is the next justified action?
____________________________________________

INTERVENTION CONDITION
What would make me question automation, intervene,
escalate, change course, or stop?
____________________________________________

DEFEND
What evidence supports this decision?
____________________________________________

RESULT
What happened next?
____________________________________________

UPDATE
What should change in the next decision?
____________________________________________
```

## Human–Machine Trust Check

Before relying on an autonomous recommendation or behavior, ask:

**EXPECTED** — What did I expect the system to do?

**OBSERVED** — What is it actually doing?

**GAP** — Is there a meaningful difference?

**LIMIT** — What boundary must not be crossed?

**INTERVENE** — What condition requires human action?

> # EXPECTED → OBSERVED → GAP → LIMIT → INTERVENE

The goal is neither maximum trust nor minimum trust.

The goal is **calibrated trust**.

## The Automation Surprise Test

When the system behaves unexpectedly:

1. **Do not explain away the anomaly before identifying it.**
2. **Rebuild the operating picture from available evidence.**
3. **Check whether assumptions about system state are still valid.**
4. **Identify the relevant intervention or escalation boundary.**
5. **Act according to applicable procedures and authority.**
6. **Capture what happened for review and learning.**

> **Unexpected automation behavior is a signal—not an instruction to improvise outside established limits.**

## DFR Scenario Debrief

After a scenario or reviewed event, ask:

**What did the operator notice first?**  
**What information was integrated—and what was missed?**  
**What became the priority, and why?**  
**Which limit mattered most?**  
**When did the operator trust the system?**  
**When did they question it?**  
**What triggered intervention or escalation?**  
**Was the decision defensible given the information available at the time?**  
**What evidence should update the next scenario, procedure, interface, or training event?**

## Relationship to Judgment at the Edge

The general decision architecture is:

> **SIGNAL → CONDITION → LIMIT → DECISION → EVIDENCE**

For DFR, it becomes:

> **NOTICE → INTEGRATE → PRIORITIZE → DECIDE → DEFEND**

The DFR loop emphasizes two problems that become especially important in information-rich, human-machine operations:

**integration** — constructing a usable picture from multiple sources;

**prioritization** — deciding what deserves human attention now.

## Relationship to the Field Toolkit

**001 — Decision Field Card**  
Structure the decision.

**002 — 45-Second Rule**  
Make critical support usable at the point of need.

**003 — Scenario Design Canvas**  
Create realistic decision environments.

**004 — Operational Readiness Review**  
Test the capability claim.

**005 — Asymmetry Check**  
Design exposure under uncertainty.

**006 — DFR Judgment Card**  
Exercise judgment around autonomy and time-critical information.

Together:

> # NOTICE THE CHANGE → BUILD THE PICTURE → SET THE PRIORITY → MAKE THE DECISION → DEFEND WITH EVIDENCE

## The Standard

The objective is not an operator who merely watches automation work.

It is an operator prepared to recognize when the operating picture changes, integrate evidence, establish priority, act within limits, and explain the decision.

> **When autonomy reaches its limit, human judgment becomes the mission system.**

---

**Field Tool 006 · DFR Judgment Card · v1.0**  
Part of [Judgment at the Edge](https://github.com/theedreif/judgment-at-the-edge) and the [Ed Reif Field System](https://github.com/theedreif).

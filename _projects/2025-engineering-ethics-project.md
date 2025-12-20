---
layout: project
title: Engineering Ethics Reflection (MAE 4300): Boeing 737 MAX
description: A four-week synthesis on safety, responsibility, and prevention in sociotechnical systems
technologies: [Engineering Ethics, Case Study Analysis, Risk Assessment]
image: /assets/images/ethics_thumbnail.png
---

Over Weeks 6–9 of MAE 4300, we used the Boeing 737 MAX crashes as a case study to practice a structured approach to engineering ethics. The goal was not to write a technical accident report. It was to practice how engineers should reason about responsibility, uncertainty, and prevention when real systems fail.

My main takeaway is that high-consequence failures rarely come from one technical decision in isolation. Design choices, training assumptions, company incentives, and the details of certification interact. When those pieces reinforce the wrong priorities, a “technical issue” becomes a systems-level ethical failure.

## Week 6: Naming the ethical problems behind a technical story
My first pass focused on the questions that show up whenever safety-critical work meets schedule pressure and competitive pressure.

- How do you balance time-to-market with the duty to protect public safety?
- Who owns responsibility when a system spans many teams and layers of approval?
- What level of training and transparency is ethically required when automation can affect control?
- After a first fatal incident, what obligations change for the manufacturer and the regulator?

This week made one point hard to ignore. Ethics is not only about what you do before a failure. It is also about what you do when early warnings appear. If a credible hazard is revealed after a first crash, continuing operation without decisive mitigation shifts the situation from “unforeseen accident” toward knowingly accepting preventable risk.

## Week 7: Separating facts from assumptions
Week 7 pushed the analysis toward discipline. I worked to separate (1) material facts about the system, (2) facts about people and organizations, and (3) what I was inferring.

Several technical facts matter ethically because they affect how recoverable failures are. If a flight-critical automation feature can be triggered by a single sensor error, or can repeatedly re-engage after a pilot counters it, then a single bad input can escalate quickly into loss of control. Those details change what “reasonable pilot response” even means.

This was also where definitions started to matter. Terms like **safety**, **compliance**, **transparency**, and **accountability** can be used narrowly or seriously. “Compliance” can become box-checking. “Safety” can be reduced to meeting a minimum certification threshold. A key lesson from the case is that ethical conflict often hides inside those definitions. A narrow definition can let an organization feel justified even when the broader duty of care is not being met.

## Week 8: What an ethical resolution would have required (bridging the missed week)
The next step in our course method is moving from analysis to resolution. In this case, the ethical resolution is straightforward in principle:

- The system should be designed and certified with realistic failure modes and realistic human factors.
- Flight-critical automation should have redundancy and fail-safe behavior proportional to the consequences of error.
- Pilot-facing transparency and training should match the true operational impact of the system.
- After a fatal incident that reveals a credible design-linked hazard, continued operation without strong intervention is not ethically defensible.

This is where the case-study method helps. It forces the point that “meeting minimums” is not always “ethical enough” when the consequences are catastrophic. In a safety-critical setting, the priority order should put public safety and honesty ahead of schedule, cost, and reputational protection.

## Week 9: Constraints and prevention across multiple levels
Week 9 focused on constraints. If the “right” answer looks obvious on paper, why does it fail in practice?

Competitive markets create pressure to minimize training, reduce friction in certification, and maintain timelines. Inside large organizations, responsibility is distributed across layers, which can dilute accountability. Even if an engineer recognizes risk, it can be hard to push back when the incentives are not aligned with conservative safety decisions.

So prevention has to operate at multiple levels:

**Individual level**
- Use structured documentation and safety checklists that force explicit handling of failure modes and assumptions.
- Escalate concerns through clear channels, and use protected reporting routes when normal escalation fails.

**Organizational level**
- Create independent safety gates with real veto power, separate from schedule-driven program management.
- Enforce anti-retaliation policies with auditing and consequences.
- Treat pilot-facing transparency as a requirement for safety-critical automation, not a marketing choice.
- Establish predetermined stop-fly or grounding criteria after severe incidents so the decision is not driven by convenience.

**Systemic level (regulatory and industry)**
- Strengthen standards for redundancy and failure behavior in automation that affects control.
- Define clear thresholds for when training is required.
- Improve whistleblower protection and oversight mechanisms so safety does not depend on personal heroics.
- Coordinate safety decisions globally to reduce delay and inconsistency.

## What I take forward
This case shifted my view from “ethics as a separate topic” to “ethics as part of engineering practice.” In complex systems, the technical and the ethical are coupled. The analysis becomes stronger when it is grounded in facts, clear assumptions, and careful definitions. Prevention becomes realistic only when it addresses incentives and structures, not just individual decision-making.
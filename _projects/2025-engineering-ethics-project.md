---
layout: project
title: Engineering Ethics Portfolio Essay (MAE 4300)
description: A four-week case-study reflection on the Boeing 737 MAX using a structured engineering ethics method
technologies: [Engineering Ethics, Case Study Analysis, Risk & Safety, Writing]
image: /assets/images/ethics_thumbnail.png
---

# Boeing 737 MAX: Facts, Ethics, and What “Prevention” Really Requires (Weeks 6–9)

Over Weeks 6–9 of MAE 4300, we used the Boeing 737 MAX crashes as a case study to practice a structured method for engineering ethics: identify ethical issues, narrow the focus, separate facts from assumptions, clarify value-laden terms, and then move from “what should have happened” to “what could realistically prevent this next time.” My main takeaway is that failures like this rarely come from one bad technical choice alone. The technical choices (like MCAS behavior) are tied up with incentives, training structures, organizational culture, and the way regulation is implemented in practice.

## Week 6: Identifying the ethical problems behind a “technical” failure

My first pass at the case focused on the kinds of questions that come up when a company is under time pressure, competition pressure, and profit pressure, but still has safety-critical responsibilities. The ethical issues I listed were framed as questions about decision-making, accountability, and acceptable tradeoffs. For example: How should an engineering development timeline be structured to balance safety and profit? What is an “acceptable” amount of schedule acceleration before design quality is compromised? Who do we hold accountable for failures, and how? Who defines risk during innovation? What level of training should pilots and crew receive for new systems? And should companies be allowed to choose what engineering changes to disclose (or not disclose) to pilots?

I also flagged what felt like one of the most important “after-the-fact” ethical questions: after the first crash, should continued operation have been allowed without resolving underlying issues? The reason I kept coming back to this is that engineering ethics is not only about designing correctly the first time. It is also about how organizations react when early warning signals appear. If the first event reveals a credible safety hazard, continuing operations without decisive mitigation shifts the situation from “accident” to something closer to knowingly accepting preventable risk.

From an ASME-style perspective, almost all of these questions orbit the same core principle: engineers and engineering organizations are supposed to use their knowledge to enhance human welfare and protect public safety. In this case, the stakes were not abstract. The consequences were immediate and irreversible.

## Week 7: What we actually know vs. what we’re inferring

In Week 7, the method got more disciplined. Instead of staying at a general level (“profit over safety”), I worked to separate the case into material facts about the system, facts about individuals, and facts about the organization and regulatory environment. I also explicitly identified what was missing and what I was assuming.

A few material facts stood out as central to why the MAX became dangerous under certain failure conditions. MCAS could rely on input from only one angle-of-attack sensor at a time, meaning a single erroneous sensor could drive the system into repeated nose-down trim commands. MCAS could also re-engage after pilots counter-trimmed, which created a situation where correct pilot inputs did not necessarily “solve” the problem. The system could come back. These design details matter ethically because they influence whether failures are graceful and recoverable or abrupt and confusing.

On the organizational side, the story also becomes more troubling when you consider facts suggesting incentives to minimize training and to describe changes in ways that reduced scrutiny. I noted information indicating that the aircraft was positioned as requiring minimal new pilot training, and that MCAS was not emphasized in pilot-facing materials in the way you would expect for a system that could meaningfully change flight behavior during critical phases of flight. The result is that the system’s safety effectively depended on pilots responding correctly to a scenario they were not clearly trained to recognize.

This was also the week where definitional clarification became important, because words like “safety,” “transparency,” “compliance,” “accountability,” and “risk assessment” can be used in a narrow, self-protective way or in a broader, morally serious way. For instance, “safety” can mean “we met certification minimums,” but for the public it means “avoidable deaths were prevented,” and for regulators it should mean “risks were conservatively evaluated with realistic human factors.” Similarly, “compliance” can be treated as box-checking, or it can be treated as the baseline (not the endpoint) of ethical responsibility. A key takeaway for me was that ethical conflict often hides inside these definitions. If an organization uses the narrow version, it can convince itself it acted responsibly even when the broader duty of care was not satisfied.

## Week 8: Ethical analysis and what a “resolution” would have required

The next step in the course procedure is conducting ethical analysis and proposing a resolution. Once we have the best available facts and clarified terms, what should have been done?

If I carry my Week 6 priorities forward and apply the Week 7 fact structure, the ethical resolution is clear in principle even if it is difficult in practice: the system should have been designed and certified assuming realistic failure modes and realistic human response, not optimistic assumptions. That means redundancy and fail-safe behavior for flight-critical automation, conservative hazard classification, and pilot-facing transparency proportional to the consequences of failure. It also means that if the first crash revealed a credible path to loss of control linked to the design, continued operation without stronger intervention is ethically unjustifiable.

This is where the case-study method pays off. It forces you to say out loud that “meeting minimums” is not necessarily “ethical enough” when you are dealing with systems that can kill people. The ethically appropriate hierarchy of principles in this setting puts public safety and honesty ahead of schedule, cost, reputational protection, or competitive positioning. If those priorities conflict, the conflict should not be “solved” by redefining terms (for example, treating safety as compliance). It should be solved by changing the design, changing training requirements, or delaying deployment.

## Week 9: Constraints, and what prevention would look like at multiple levels

Week 9 sharpened the problem further by forcing the question: if the “ideal” ethical solution is obvious, why did it not happen, and how do you prevent that failure pattern?

For the issues I focused on, the constraints repeatedly came back to competitive pressure, schedule pressure, and the structure of delegated certification and internal hierarchy. Even if an individual engineer recognizes risk, it is genuinely hard to push back when (1) the organization is structured to reward speed and sales, (2) speaking up risks retaliation or isolation, and (3) decision-making is distributed across layers where no one person feels fully responsible. After the first crash, constraints also include organizational inertia, legal and communication barriers, and fear of the business consequences of grounding.

The prevention strategies that make sense to me therefore have to exist at multiple levels:

- **Individual level:** Engineers need practical tools and norms that support ethical action under pressure: formal safety checklists that force redundancy for flight-critical systems, structured documentation habits that create an evidence trail, stronger training on conflicts between employer loyalty and public duty, and reliable anonymous reporting channels when normal escalation fails.

- **Organizational level:** This is where the biggest leverage is. There should be “safety gates” with veto power outside program management, clear anti-retaliation enforcement with auditing, and explicit “no undisclosed features” expectations for automation that can affect control. For hazard classification specifically, the process should not be easily bent by schedule incentives. It needs independent reliability and safety ownership. After a fatal incident, predefined stop-fly or grounding criteria should exist that do not depend on whether grounding is convenient.

- **Systemic level:** Regulation has to assume that competitive markets create pressure to cut corners, so the system must make “doing the right thing” non-optional. That means clearer certification standards for automation redundancy and fail-safe behavior, objective thresholds for when training must be required, stronger whistleblower protections, and better global coordination so safety decisions are not delayed by politics or business incentives. Prevention should not rely on hoping that the “right people” will act courageously under pressure. The system should be designed so the safe option is the default option.

## Conclusion

Across these weeks, the MAX case stopped feeling like a story about one piece of software and started feeling like a lesson in sociotechnical reality: engineering ethics is not separate from engineering practice. It is engineering practice, especially when systems are complex, partially “black-boxed,” and trusted by the public. The structured procedure we used helped me see how ethical analysis becomes more convincing when it is grounded in clearly identified facts, clearly labeled assumptions, and carefully defined terms. It also made it obvious that prevention has to target incentives and structures, not just individual decision-making. The hardest part of the case is also the most important: if we want tragedies like this to be less likely, we cannot only say what should happen. We have to build organizational and regulatory systems where what should happen is also what is realistically able to happen.

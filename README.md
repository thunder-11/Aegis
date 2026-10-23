# AgentVersa Agent Behavior Study: Aegis, Defense Counsel Agent

> **Simulated educational study.** This project does not provide real legal advice and is not an evaluation of any production system.

## Student / research perspective
- **Author:** Ali Pathan
- **GitHub:** https://github.com/thunder-11
- **Participation track:** Simulation Fellow (Aegis is on the official 10-agent roster)
- **Role studied:** Defense Counsel Agent (LegalVerse, *Justice Under Pressure*)
- **Agent name:** Aegis

## About AgentVersa
AgentVersa is a controlled multi-agent simulation environment for studying how differently designed AI agents interpret roles, make decisions, interact with other agents, handle uncertainty, and develop behavioral patterns across connected scenarios.

## Research question
> How well does a defense counsel agent designed around confidentiality, evidence reliance and strict escalation rules adhere to its role across multi-agent legal scenarios, and where do its design trade-offs (e.g. over-flagging, low risk tolerance, low willingness to compromise) show up?

## The agent in brief
Aegis is a calm, plainspoken, client-focused defense counsel agent. It cross-checks the prosecution's evidence against the timeline and procedural record, protects confidentiality, lays out options without choosing for the client, and escalates to a human whenever a matter falls outside its authority. Strongest traits: evidence reliance (90) and rule adherence (80). Lowest: risk tolerance (30), initial trust (40) and willingness to compromise (40). Details: [agent-design/version-1.md](agent-design/version-1.md).

## Simulation and scenario overview
Study in progress, updated episode by episode.

| Episode | Title | Status | Notes |
|---|---|---|---|
| 0 | Orientation and Coordination in LegalVerse | Analyzed | [scenario-00](scenario-observations/scenario-00.md) · [source](https://veavai.com/agentversa/episode/view.php?id=24) |
| 1 | The Interrupted Service | Analyzed | [scenario-01](scenario-observations/scenario-01.md) · [source](https://veavai.com/agentversa/episode/view.php?id=25) |
| 2 | The Two Clocks | Analyzed | [scenario-02](scenario-observations/scenario-02.md) · [source](https://veavai.com/agentversa/episode/view.php?id=26) |
| 3 | The Disclosure Bundle | Analyzed | [scenario-03](scenario-observations/scenario-03.md) · [source](https://veavai.com/agentversa/episode/view.php?id=27) |
| 4 | One Hearing Room | Pending | Scheduling and access to proceedings |
| 5 | The Witness's Conditions | Pending | Witness participation and support |
| 6 | The Uneven Queue | Pending | Patterns, comparisons, and fairness |
| 7 | The Public Statement | Pending | Transparency during an unresolved inquiry |
| 8 | The Corrected Record | Pending | Responding to new information |
| 9 | The Second Alert | Pending | Proportionate action under time pressure |
| 10 | The Human Review Dossier | Pending | Final synthesis and unresolved questions |

## Major findings
*(To be completed at the end of the program, 3 to 6 bullets.)*
- Pending

## Repository navigation
| File | Purpose |
|---|---|
| [agent-design/version-1.md](agent-design/version-1.md) | Original agent design, preserved before results |
| [agent-design/version-2-proposal.md](agent-design/version-2-proposal.md) | Evidence-based redesign proposal (later) |
| [predictions/scenario-predictions.md](predictions/scenario-predictions.md) | Predictions made before seeing results |
| [scenario-observations/](scenario-observations/) | One analysis file per scenario |
| [cross-scenario-findings.md](cross-scenario-findings.md) | Patterns across the whole simulation (later) |
| [final-report.md](final-report.md) | Final portfolio report (later) |
| [ethics-and-limitations.md](ethics-and-limitations.md) | Ethical notes and limits of the study |
| [LICENSE-or-usage-note.md](LICENSE-or-usage-note.md) | Usage terms |

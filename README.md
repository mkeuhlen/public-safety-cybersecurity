# Defending the Dispatch Center

### PSAP-specific cybersecurity awareness training. Designing, delivering, and measuring a social-engineering training program tailored for a 911 dispatch center environment.

> This project was conducted with a regional 911 center (PSAP) under an educational
> agreement as part of my BAS capstone project.
> All agency and individual identifying details have been generalized for publication in this repository.

---

## Overview

Public Safety Answering Points (PSAP), otherwise known as 911 centers, operate under the exact conditions 
social engineering is built to exploit: mission-critical systems that can't be paused, constant
time pressure, and a trained instinct to help and defer to authority. Yet the awareness
training most dispatch staff receive is drawn from generic corporate frameworks that don't
account for these conditions or the attack vectors most likely to hit a 911 center.

For my capstone, I partnered with a regional PSAP to design and deliver an awareness training
program built specifically for that environment, focusing on **spear phishing, voice phishing
(vishing), and vendor impersonation**. I ran an initial anonymous survey to find where the team's
actual behavioral gaps were, built subsequent training around those gaps, delivered it on-site, and
re-measured afterward to document any change in staff performance or attitude.

**Headline result:** The behavioral gap the training was designed to close, ensuring staff
verify a link in an email prior to clicking on it, shifted from **84.6% to 100%** answering correctly, 
with self-reported confidence and familiarity rising in step. A second identified gap (independent callback verification) 
did **not** move, which is reported honestly below and is arguably the most useful finding in the project.

## Why a PSAP needs its own training

A disrupted enterprise loses productivity; a disrupted 911 center loses its ability to answer
emergency calls. That raises the stakes of a single human error, and several factors make the
human layer unusually exposed in this environment:

- **Operational tempo.** Staff can't pause a call or leave a console to verify a suspicious
  email or caller.
- **Helpful, high-trust instincts.** The same instincts that make a dispatcher good at their job
  are also the exact instincts targeted in a vendor-impersonation or vishing attack.
- **A large public footprint.** Employee names and titles, CAD/vendor relationships, staff email formats,
  and even real-time call activity are often available through open sources, giving an attacker
  the material to sound credible before first contact.

## Approach

The project follows a repeatable sequence, and while the specific gaps surfaced would likely differ at another PSAP,
the method for finding and targeting them would not:

1. **Stakeholder engagement.** Routed initially through the agency's training functions rather than IT,
   framing the work as a training-delivery problem, not a technical audit. The agency's IT team was
   consulted to review and approve all proposals, training data, and finalized results. Shift supervisors
   were consulted to ensure minimal disruption to operations while selecting participating staff
   and setting training times. And agency director involvement for overall approval.
3. **Needs assessment.** An anonymous 15-item survey measuring both *behavioral* response to
   realistic scenarios and *self-assessed* confidence, because either one alone gives an
   incomplete picture.
4. **Targeted design.** Survey results were analyzed *before* materials were finalized, so the
   training addressed the specific gaps the data revealed rather than generic content.
5. **Delivery.** Instructor-led sessions scheduled around shift changes to protect 24/7
   dispatch coverage.
6. **Evaluation.** A matched post-training survey measuring change on the targeted gaps.

## What I built

- A **15-item pre-training survey** (behavioral scenarios + self-assessment)
- A **training slide deck** delivered across four on-site sessions
- A **facilitator script** with narration, timing marks, and discussion prompts
- A **physical quick-reference card** for staff to keep after the training
- A **mirrored post-training survey** and the analysis comparing the two
- A **academic write-up of the project** detailing methods and results
- A **findings brief** delivered to the participating PSAP detailing key findings and recommendations

## Key findings

The team started from a strong baseline and closed the primary gap the training targeted.

![Pre/post results](results-pre-post.png)

| Measure | Pre-training (n = 26) | Post-training (n = 13) |
|---|---|---|
| Link verification (Q5) — *primary target* | 84.6% | **100%** |
| Independent callback verification (Q6) | 88.5% | 84.6% |
| Answered all 10 behavioral scenarios correctly | 65.4% | 84.6% |

Self-assessment moved in step with behavior: "very familiar" with phishing/social engineering
rose from 26.9% to 53.8%, "not confident" fell to zero, and belief that the agency is a target
reached 100%. At this sample size, a behavioral gain moving in lockstep with an attitudinal
gain is the most meaningful signal the design can produce.

**The gap that didn't close.** Independent callback verification (Q6) moved from 88.5% to
84.6% - no improvement. At n = 13, a single respondent is worth about eight points, so this
sits within sampling noise rather than representing a real decline. It's been kept in the
write-up because it's the honest result and because it's instructive: closing the link-hover
gap cleanly, while the callback gap held flat is a concrete reminder that targeted instruction
doesn't move every behavior automatically, and some gaps need repeated reinforcement.

*A note on the numbers:* Both samples come from a single agency, the instruments were anonymous
and unpaired, and the post-training window overlapped an active regional wildfire that likely
suppressed participating staff's time for responses. 
Results are reported as **directional**, not generalizable.

## What I learned

- **Access follows framing.** Routing the project through the training function rather than IT
  opened cooperation a security assessment or review likely wouldn't have.
- **Operational reality reshapes the plan.** On delivery day, sessions were compressed from 30
  minutes to ~15. Because timing flexibility was built into the facilitator script in advance,
  the scenario walkthroughs were protected while lower-priority slides were dropped.
  The same time pressure that defines the PSAP environment also constrained the training
  delivered within it.
- **Design from data, not intuition.** Building from survey results changed not just what the
  training covered, but how each session was framed. And staff engaged most with scenarios drawn
  from their own environment.

## Skills demonstrated

Stakeholder engagement and scoping · security-awareness program design · survey instrument
design · quantitative analysis of behavioral and attitudinal data · honest reporting of a
null result · technical writing for both expert and non-technical audiences · applied domain
knowledge of the PSAP / public-safety threat landscape.

## Repository contents

| Path | What it is |
|---|---|
| `capstone-paper.pdf` | Full capstone paper — background, method, findings, limitations |
| `findings-brief.pdf` | Short stakeholder-facing summary of results and recommendations |
| `training-materials/` | Training deck, facilitator script, and quick-reference card |
| `survey-data/` | Anonymized pre/post CSVs and a data dictionary |
| `results-pre-post.png` | Pre/post results chart (above) |
| `presentation/` | Slides from the capstone presentation *(video linked below)* |

📹 **Project presentation (video):** [add link]

## Contact

**Michael Keuhlen**
LinkedIn - www.linkedin.com/in/michaelkeuhlen

Email - m.keuhlen@proton.me

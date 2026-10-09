# Security Journal

**Research. Understand. Investigate. Defend. Document.**

The Security Journal is a living record of my cybersecurity learning, research, technical analysis, and investigative development. It exists to turn cybersecurity news, security research, vulnerabilities, and real-world incidents into meaningful technical understanding and practical defensive knowledge.

This is more than a collection of articles or links. It is a space to understand how security failures happen, examine how attacks affect systems and organisations, explore how defenders detect and respond to threats, and document the lessons that can improve security.

Built around the principles of **Build · Monitor · Investigate**, this journal reflects my commitment to developing the knowledge, practical skills, and analytical mindset required in cybersecurity.

---

## Why This Journal Exists

Cybersecurity changes continuously. New vulnerabilities emerge, attackers develop new techniques, software introduces unexpected weaknesses, and organisations face increasingly complex security challenges.

Reading about these developments is useful, but understanding them requires more than knowing what happened.

I created this Security Journal to go beyond the headline.

When I encounter a security incident or vulnerability, I want to understand the underlying technical weakness, the conditions that made it possible, its potential impact, the evidence available, and the measures that could prevent or detect similar activity.

The journal provides a structured way to capture that understanding, identify gaps in my knowledge, and connect research with practical learning.

Its purpose is to help me:

- Develop stronger cybersecurity fundamentals and technical understanding.
- Think critically about vulnerabilities, attack methods, and defensive controls.
- Learn how SOC analysts investigate suspicious activity, assess alerts, and respond to incidents.
- Explore threat intelligence and understand how reported threats translate into defensive priorities.
- Connect research with practical exercises, detection queries, scripts, and security projects.
- Document lessons learned and identify areas requiring further investigation.
- Build a credible record of my development through technical artefacts and evidence of work actually performed.

The objective is not simply to know more about cybersecurity. It is to become better at **analysing problems, asking the right questions, evaluating evidence, and applying what I learn**.

## The Mission

The mission of the Security Journal is to transform cybersecurity research into actionable understanding.

Every entry should help answer one or more important questions:

- What happened?
- How did it happen?
- Which systems, identities, applications, or security controls were affected?
- What evidence supports the reported findings?
- How could a security team investigate or detect similar activity?
- What can be done to contain, remediate, or prevent the problem?
- What have I learned, and how can I validate that understanding?

Not every entry will answer every question. Some subjects require foundational research, while others may lead to practical labs, investigations, or technical projects.

What matters is that each entry contributes to a growing understanding of how cybersecurity works in practice.

## What the Journal Covers

The Security Journal is intended to grow across the wider IT and cybersecurity landscape rather than remain restricted to one certification, technology, or security speciality.

Areas of interest include:

| Research area | Focus |
|---|---|
| Vulnerability research | Security weaknesses, root causes, exposure, impact, and remediation |
| Threat intelligence | Threat actors, attack campaigns, indicators, and intelligence-driven defence |
| SOC operations | Alert triage, monitoring, detection, investigation, escalation, and incident response |
| Malware and phishing | Malicious activity, delivery methods, behaviour, and defensive opportunities |
| Network security | Network traffic, DNS, suspicious connections, and protocol analysis |
| Identity and access security | Authentication, authorisation, Active Directory, and identity-related attack paths |
| Cloud security | Misconfigurations, identity risks, monitoring, and defensive controls |
| Detection engineering | Detection logic, KQL, SPL, telemetry analysis, and validation |
| Security engineering | Secure coding, cryptography, software dependencies, and implementation flaws |
| Practical security tools | Wireshark, CyberChef, Splunk, KQL, and other relevant investigative tools |

These are research areas, not claims that every category already contains completed work. The journal will develop as I study, practise, and explore new subjects.

## From Headlines to Investigation

A cybersecurity headline is a starting point, not the final result.

When an incident or vulnerability is worth investigating further, the journal aims to move beyond summarisation and examine its technical and defensive implications.

Depending on the subject, an entry may include:

1. **Incident overview** — a concise explanation of the event or discovery.
2. **Technical breakdown** — how the vulnerability, attack technique, or security failure works.
3. **Evidence and sources** — links to original research, official advisories, and supporting documentation.
4. **Attack-chain analysis** — relevant attack stages and justified MITRE ATT&CK mappings where appropriate.
5. **SOC perspective** — investigation questions, relevant telemetry, detection opportunities, and escalation considerations.
6. **Defensive recommendations** — practical measures to reduce exposure or improve detection and response.
7. **Practical application** — a safe lab, query, script, configuration review, or technical experiment where appropriate.
8. **Lessons learned** — what the research demonstrates, what remains uncertain, and what deserves further study.

The format will remain flexible. A short advisory does not need to become a full investigation report, and a complex vulnerability may require deeper technical analysis.

The goal is useful understanding, not unnecessary documentation.

## The Learning Cycle

The Security Journal supports an eight-stage learning philosophy:

**LEARN → BUILD → BREAK → MONITOR → INVESTIGATE → FIX → DOCUMENT → PROVE**

| Stage | Purpose |
|---|---|
| LEARN | Understand the underlying technology, vulnerability, threat, or security principle. |
| BUILD | Create a controlled environment, lab, detection, or technical artefact where appropriate. |
| BREAK | Examine weaknesses and test assumptions safely in an authorised environment. |
| MONITOR | Identify the telemetry and events needed to understand system behaviour. |
| INVESTIGATE | Analyse evidence, develop hypotheses, and determine what the available data supports. |
| FIX | Apply or recommend appropriate remediation and defensive controls. |
| DOCUMENT | Record the process, findings, decisions, limitations, and lessons learned. |
| PROVE | Validate the result through appropriate testing and preserve the supporting evidence. |

Not every journal entry will pass through all eight stages. Some will focus on research and understanding; others may develop into practical projects or verified security exercises.

The distinction matters: learning about a vulnerability is not the same as reproducing it, and recommending a fix is not the same as proving that the fix works.

## Evidence Over Assumptions

A central principle of this journal is that conclusions must be supported by evidence.

Cybersecurity analysis involves uncertainty. Initial incident reports may contain incomplete information, technical explanations may evolve, and a plausible attack scenario does not automatically establish what happened in a particular incident.

For that reason, the journal aims to distinguish between:

- **Confirmed facts:** Findings supported by the available evidence or authoritative sources.
- **Reported claims:** Information attributed to researchers, vendors, investigators, or affected organisations.
- **Analysis:** My interpretation of the technical and defensive implications.
- **Hypotheses:** Explanations that require further validation.
- **Unknowns:** Questions the available evidence does not resolve.
- **Verified results:** Outcomes supported by tests or other documented validation actually performed.

External research will be attributed to its original sources. Practical work will be described according to what was genuinely completed.

I will not claim to have reproduced an exploit, investigated a live attack, executed a query, deployed a detection, or validated remediation unless I have performed the relevant work.

**The objective is not to make every entry sound impressive. It is to make every conclusion as trustworthy as the available evidence allows.**

## Practical Learning and Technical Artefacts

Knowledge becomes more useful when it can be applied.

Where appropriate, journal research may lead to practical exercises and technical artefacts such as:

- KQL and SPL queries for investigating relevant security telemetry.
- Detection ideas and documented alert logic.
- Wireshark traffic-analysis exercises.
- CyberChef workflows for inspecting and transforming data.
- Vulnerability-analysis notes and secure-coding examples.
- Incident reports and investigation timelines.
- Threat intelligence assessments.
- Remediation plans and verification procedures.
- Lab documentation, scripts, screenshots, and test results.

These artefacts should explain their purpose, the problem they address, and how their results can be evaluated.

Where an exercise is proposed but not yet completed, it will be presented as a learning objective or planned activity. Simulated data and hypothetical scenarios will be identified accordingly.

A technical artefact is most valuable when a reader can understand what it does, why it matters, and what its results actually demonstrate.

## Safe and Responsible Research

Security research must be conducted responsibly.

Practical exercises should use authorised environments, controlled labs, synthetic data, or systems for which appropriate permission has been granted.

The journal prioritises defensive understanding, safe experimentation, responsible disclosure principles, protection of sensitive information, and respect for privacy.

When analysing offensive techniques, the emphasis is on understanding the attack path, recognising risk, identifying detection opportunities, and improving defensive controls.

The aim is to develop security knowledge that can be applied constructively.

## How This Connects to My Cybersecurity Portfolio

The Security Journal is part of my broader cybersecurity portfolio and my ongoing development towards security-focused technical roles, particularly SOC operations, incident response, threat intelligence, and cloud security.

It provides context for the problems I study and the questions that motivate practical work.

A journal entry may stand alone as research, or it may eventually connect to a detection rule, technical lab, incident report, security project, or other portfolio artefact.

The distinction between these forms of work should remain clear:

- **Research** demonstrates that I can study a topic and explain its significance.
- **Analysis** demonstrates that I can interpret available evidence and reason about security implications.
- **Practical work** demonstrates that I have applied knowledge in a controlled environment.
- **Verification** demonstrates that a specific result has been tested and supported by evidence.

Together, these activities can provide a more meaningful view of my development than a list of technologies or certifications alone.

The journal supports the broader portfolio philosophy:

**Build · Monitor · Investigate**

## A Living Record of Progress

This journal is not intended to be a static document or a finished collection of articles.

Cybersecurity knowledge develops through continued learning, practical application, mistakes, new evidence, and the correction of earlier assumptions.

Entries may be updated when important technical details change, new research becomes available, a remediation approach evolves, or a practical exercise produces additional findings.

Where corrections or updates materially change an earlier conclusion, the documentation should make that clear.

Over time, the journal should become a useful record of what I studied, what I understood, what I built, what I investigated, and what I was able to verify.

Its value will come not from the number of entries published, but from the quality of the reasoning, the usefulness of the technical work, and the honesty of the evidence recorded.

## The Standard

The Security Journal follows a simple standard:

**Research carefully. Question assumptions. Investigate methodically. Build where useful. Verify what can be tested. Document what the evidence supports.**

Every entry is an opportunity to strengthen my technical understanding, improve my analytical discipline, and connect cybersecurity theory with real defensive practice.

This is where curiosity becomes structured learning, learning informs practical work, and practical work produces evidence of progress.

**The purpose is not merely to follow cybersecurity. It is to understand it, investigate it, and learn how to defend against its challenges.**

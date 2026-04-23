+++
title = "Create your own TTPs"
description = "Damnit"
date = 2025-01-02
updated = 2026-04-23
draft = false
+++

When studying new cybersecurity content, it's essential to find effective ways to retain information and easily access it when needed.

To address this, I've created my "Personal TTP Framework" on [Obsidian](https://obsidian.md/) during my preparation for the CPTS (Certified Penetration Tester Specialist) certification, establishing a layered structure similar to the [MITRE ATT&CK framework](https://attack.mitre.org>).

The information is categorized into different layers: Tactics, Techniques, and Procedures.

## 1. Tactics

Tactics refer to a set of general goals during an attack. Mine are primarily based on the [MITRE Enterprise tactics](https://attack.mitre.org/tactics/enterprise/), which include:

- Infrastructure Preparation
- Discovery
- Execution
- Defense Evasion
- Credential Access
- Privilege Escalation
- Lateral Movement
- Collection
- Exfiltration
These layers remain relevant today.

## 2. Techniques

A technique is the "how" to achieve the related tactic. My techniques are ever expanding or re-grouped as I learn new material. Start by creating your first technique based on the content you are studying.

## 3. Procedures

Procedures are specific implementations of a related technique. The difference between Mitre framework and mine relies on the Procedures definition. On Mitre, here is what they say:

> "The two important aspects to note about procedures in ATT&CK are that it is how an adversary uses techniques and sub-techniques and that a procedure can span multiple techniques and sub-techniques."

On my end, I create one procedure for each specific workflow needed to perform my technique. The common denominator between Mitre's framework and mine is that "Procedures may also include use of specific tools in how they’re performed".

I now use this TTP framework daily (on HTB boxes and during internal assessments), and as I continue learning in the field, I expand my personal framework accordingly.

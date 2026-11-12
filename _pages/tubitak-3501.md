---
layout: single
title: "Quantitative Analysis of Statements of the United States' Presidents on Internal Armed Conflicts"
permalink: /research/tubitak-3501/
author_profile: true
---

**Funding:** TÜBİTAK 3501 Career Development Program  
**Principal Investigator:** Dr. Melike Ayşe Kocacık Şenol, Sabancı University  
**Duration:** January 2026 – November 2027

## Overview

When civil wars break out, external states rarely stay silent. Presidents and leaders comment publicly on the conflict, take sides, warn the parties, or signal that they may intervene. These statements are an important part of how third parties try to shape civil conflicts, yet we lack systematic data on what they say and how strongly they commit.

This project builds an original, large-scale dataset of United States presidents' public statements on civil conflicts around the world since 1945. Using computational text analysis, machine learning, and large language models, it identifies which statements concern civil conflicts, which side they address, and how much resolve they signal.

## Research Questions

- How do US presidents talk about civil conflicts in other countries, and how has this changed since 1945?
- When do presidential statements signal strong resolve, and when do they remain vague?
- How do verbal statements relate to the level of US involvement or intervention in a conflict?

## Data and Method

- **Corpus:** Public statements by US presidents, compiled from the American Presidency Project and other official US government sources.
- **Conflict coverage:** All civil conflicts recorded by the Uppsala Conflict Data Program (UCDP), linked to statements through a detailed keyword filter of countries, leaders, rebel leaders, and rebel organizations.
- **Coding:** A manually coded training set identifies statements that relate to civil conflicts and measures the level of resolve they express.
- **Classification:** Machine learning models and large language models are trained and compared to classify the full corpus, and the best-performing model is selected.
- **Dictionaries and tools:** Dictionaries for conflict-related statements and for levels of intervention, and an R package that calculates how often selected terms appear across speech texts.

## Project Timeline

| Period | Work package |
|---|---|
| Jan – Mar 2026 | Compiling US presidential statements |
| Mar – May 2026 | Keyword selection and filtering of statements |
| May – Jul 2026 | Manual coding of conflict-related statements |
| Jul – Sep 2026 | Classifying statements with machine learning and LLMs |
| Sep 2026 – Jan 2027 | Dictionary for conflict-related statements; manual coding of resolve |
| Jan – Mar 2027 | Classifying resolve with machine learning and LLMs |
| Mar – May 2027 | Dictionary for levels of intervention |
| May – Jul 2027 | R package for term frequencies across speech texts |
| Jul – Nov 2027 | Building the final dataset and analysis |

## Outputs

Publications, datasets, and software from the project will be listed here as they become available. Related work: [Mapping resolve in crisis bargaining through leader public statements](/publications/), *European Security*.

## Acknowledgement

This project is supported by the Scientific and Technological Research Council of Türkiye (TÜBİTAK) under the 3501 Career Development Program. The views expressed are those of the researcher and do not necessarily reflect those of TÜBİTAK.

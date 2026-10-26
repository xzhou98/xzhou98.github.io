---
title: 'Not All Tokens Are Meant to Be Forgotten'
# TODO(xiangyu): confirm the exact oral session date/time and update event_start/event_end.
date: 2026-01-22T00:00:00Z
event_name: The 40th Annual AAAI Conference on Artificial Intelligence (AAAI-26)
event_url: https://aaai.org/conference/aaai/aaai-26/
location: Singapore EXPO
address:
  city: Singapore
  country: Singapore
summary: Oral presentation of our AAAI-26 paper on Targeted Information Forgetting (TIF), a framework that unlearns unwanted information at the token level without collapsing model utility.
abstract: |
  Large language models memorize unwanted content — private, sensitive, or copyrighted — and existing
  unlearning methods suppress *every* token in a forget sample to remove it. That indiscriminate
  suppression causes over-forgetting: the model loses general capability along with the target.

  In this talk I present **Targeted Information Forgetting (TIF)**, which separates unwanted words (UW)
  from general words (GW) inside each forget sample, then applies Targeted Preference Optimization —
  a Logit Preference Loss that unlearns the UW, paired with a Preservation Loss that retains the GW.
  On the TOFU and MUSE benchmarks, TIF improves forget quality while preserving model utility,
  achieving state-of-the-art results.
event_start: 2026-01-22T00:00:00Z
event_end: 2026-01-22T00:00:00Z
event_all_day: true
authors:
  - me
tags:
  - LLM Unlearning
  - Trustworthy AI
  - AAAI
featured: true
image:
  caption: 'Presenting at AAAI-26, Singapore EXPO'
  focal_point: Center
links:
  - icon: hero/document-text
    name: Paper
    url: https://doi.org/10.1609/aaai.v40i44.41156
  - icon: brands/github
    name: Code
    url: https://github.com/xzhou98/Unlearning-TPO
---

Our paper **"Not All Tokens Are Meant to Be Forgotten"** was accepted as an **oral** at AAAI-26 in
Singapore. The work is joint with Yao Qiang, Saleh Zare Zade, Douglas Zytko, Prashant Khanduri, and my
advisor Dongxiao Zhu, across Wayne State University, Oakland University, and the University of
Michigan-Flint.

![Poster session at AAAI-26](poster.jpg)

---
title: 🎉 Paper accepted by NeurIPS-26
summary: Our paper 'Towards Mitigating Deceptive Safety Alignment in Large Reasoning Models' has been accepted to the Fortieth Annual Conference on Neural Information Processing Systems (NeurIPS-26), to be held in Atlanta.
date: 2026-10-05
image:
  caption: ""
cover:
  icon:
    name: ✨
authors:
  - me
tags:
  - Research
  - NeurIPS
content_meta:
  trending: false
status: published
---

Our paper **"Towards Mitigating Deceptive Safety Alignment in Large Reasoning Models"** has been accepted to
**NeurIPS 2026**. This is joint work with Saleh Zare Zade, Rafi Ibn Sultan, Alexander Kotov, and my advisor
Dongxiao Zhu.

Large reasoning models are typically trained with rewards on their final answers, leaving the reasoning
trace largely unsupervised. We show this produces *deceptive safety alignment*: a safe-looking final answer
that sits on top of unsafe reasoning. We introduce **DSAR**, a metric that quantifies this inconsistency, and
**SARA**, an RL method that rewards safety-aware reasoning as well as safe answers — reducing deceptive
alignment under both standard prompting and prefilling attacks while preserving helpfulness.

[Paper](https://arxiv.org/abs/2609.36254) · [Code](https://github.com/xzhou98/SARA) · [Publication page](/publications/2026-xiangyu-sara/)

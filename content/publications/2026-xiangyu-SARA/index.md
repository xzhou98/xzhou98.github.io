---
title: Towards Mitigating Deceptive Safety Alignment in Large Reasoning Models
authors:
  - me
  - Saleh Zare Zade
  - Rafi Ibn Sultan
  - Alexander Kotov
  - Dongxiao Zhu

date: "2026-10-05T00:00:00Z"

publishDate: "2026-10-05T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']


publication: The Fortieth Annual Conference on Neural Information Processing Systems
publication_short: "NeurIPS-26"

abstract: Large Reasoning Models (LRMs) are commonly trained with reinforcement learning (RL) to improve their generation of chain-of-thought (CoT) reasoning before producing final answers. However, RL rewards are typically assigned based on final answers, providing little or no direct supervision over intermediate reasoning. This can lead to deceptive safety alignment, where the reasoning trace and final answer convey inconsistent safety signals. To systematically investigate this phenomenon, we introduce DSAR (Deceptive Safety Alignment Rate), a metric that jointly assesses reasoning traces and final answers to quantify their safety inconsistency. Across multiple LRMs and benchmarks, we find that deceptive safety alignment is pervasive under standard prompting conditions and is substantially amplified under prefilling attacks. We further provide a hidden representation analysis showing that models exhibit stronger safety discrimination at the final-answer stage than during intermediate reasoning. To close this gap, we propose SARA (Safety-Aware Reasoning Alignment), an RL-based method that rewards both safety-aware reasoning and safe final answers, encouraging early harmful intent recognition and enforcing reasoning-answer consistency. Experiments show that SARA significantly mitigates deceptive safety alignment under both standard and adversarial settings while preserving helpfulness and utility.

# Summary. An optional shortened abstract.
summary: Reasoning models hide unsafe thoughts behind safe answers; we propose a metric DSAR to measure it and safety alignment method SARA to mitigate it.

tags:
  - Accepted by NeurIPS-2026
  - Deceptive Safety Alignment

# Display this page in the Featured widget?
featured: True

hugoblox:
  ids:
    doi: 10.48550/arXiv.2609.36254

links:
  - type: source
    url: https://arxiv.org/pdf/2609.36254
  - type: code
    url: https://github.com/xzhou98/SARA



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Safe final answers can mask unsafe reasoning. SARA encourages safety across both.'
  focal_point: ''
  preview_only: false
---
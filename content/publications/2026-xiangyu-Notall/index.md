---
title: Not all tokens are meant to be forgotten
authors:
  - me
  - Yao Qiang
  - Saleh Zare Zade
  - Douglas Zytko
  - Prashant Khanduri
  - Dongxiao Zhu

date: "2026-03-14T00:00:00Z"

publishDate: '2026-03-14T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

publication: Proceedings of the AAAI Conference on Artificial Intelligence
publication_short: "AAAI-26"

abstract: Large Language Models (LLMs), pre-trained on massive text corpora, exhibit remarkable human-level language understanding, reasoning, and decision-making abilities. However, they tend to memorize unwanted information, such as private or copyrighted content, raising significant privacy and legal concerns. Unlearning has emerged as a promising solution, but existing methods face a significant challenge of over-forgetting. This issue arises because they indiscriminately suppress the generation of all the tokens in forget samples, leading to a substantial loss of model utility. To overcome this challenge, we introduce the Targeted Information Forgetting (TIF) framework, which consists of (1) a flexible targeted information identifier designed to differentiate between unwanted words (UW) and general words (GW) in the forget samples, and (2) a novel Targeted Preference Optimization approach that leverages Logit Preference Loss to unlearn unwanted information associated with UW and Preservation Loss to retain general information in GW, effectively improving the unlearning process while mitigating utility degradation. Extensive experiments on the TOFU and MUSE benchmarks demonstrate that the proposed TIF framework enhances unlearning effectiveness while preserving model utility and achieving state-of-the-art results.

# Summary. An optional shortened abstract.
summary: This paper helps large language models forget sensitive and unwanted data without over-forgetting general data.

tags:
  - Large Language Models Unlearning

# Display this page in the Featured widget?
featured: false

hugoblox:
  ids:
    doi: 10.1609/aaai.v40i44.41156

links:
  - type: source
    url: https://doi.org/10.1609/aaai.v40i44.41156
  - type: code
    url: https://github.com/xzhou98/Unlearning-TPO



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: '[**Illustration of the proposed TIF framework**](image.png)'
  focal_point: ''
  preview_only: false
---
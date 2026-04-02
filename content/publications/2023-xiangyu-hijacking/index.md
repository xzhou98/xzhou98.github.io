---
title: Hijacking Large Language Models via Adversarial In-Context Learning
authors:
  - me
  - Yao Qiang
  - Saleh Zare Zade
  - Prashant Khanduri
  - Dongxiao Zhu
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
date: "2023-11-16T00:00:00Z"
hugoblox:
  ids:
    arxiv: 2311.09948
publication_types: ["article"]
publication: ""
publication_short: ""

abstract: In-context learning (ICL) has emerged as a powerful paradigm leveraging LLMs for specific downstream tasks by utilizing labeled examples as demonstrations (demos) in the preconditioned prompts. Despite its promising performance, crafted adversarial attacks pose a notable threat to the robustness of LLMs. Existing attacks are either easy to detect, require a trigger in user input, or lack specificity towards ICL. To address these issues, this work introduces a novel transferable prompt injection attack against ICL, aiming to hijack LLMs to generate the target output or elicit harmful responses. In our threat model, the hacker acts as a model publisher who leverages a gradient-based prompt search method to learn and append imperceptible adversarial suffixes to the in-context demos via prompt injection. We also propose effective defense strategies using a few shots of clean demos, enhancing the robustness of LLMs during ICL. Extensive experimental results across various classification and jailbreak tasks demonstrate the effectiveness of the proposed attack and defense strategies. This work highlights the significant security vulnerabilities of LLMs during ICL and underscores the need for further in-depth studies.

# Summary. An optional shortened abstract.
summary: This work introduces a novel transferable attack against In-Context-Learning to hijack LLMs to generate the target response or jailbreak.  We also propose a defense strategy against hijacking attacks through the use of extra clean demos, which enhances the robustness of LLMs during ICL.

tags:
  - Large Language Models 
  - In-context Learning Attack

links:
  - type: code
    url: https://github.com/xzhou98/Hijacking-LLMs-GGI 
featured: True

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Illustration of hijacking attack during ICL'
  focal_point: ''
  preview_only: false
---

---
layout: page
title: LLMs for Reinforcement Learning
description:
  - Developed <tt>ProPS</tt> and <tt>ProPS<sup>+</sup></tt> methodology for generating parameterized RL policies directly from LLMs, based on their capability for linguistic and numerical reasoning, coupled with an iterative refinement process. This process is driven by a closed-loop feedback mechanism that provides the LLM with policy reward data, which, along with semantic and contextual task information, enables effective in-context learning. After evaluating across 15 tasks and comparing them with state-of-the-art RL approaches, we extend the method to enhance the RL optimization capabilities of smaller, open-source LLMs. We are actively fine-tuning models such as Qwen2.5 and Qwen3.0, and our initial experiments with 14B models have shown promising results in generating RL policies of a similar scale.
video: assets/video/props_banner.mp4
img: assets/img/props_banner.gif
importance: 1
category: on-going
papers:
  - props
related_publications: true
github:
  - https://github.com/yfzhoucs/props-llm
  - https://github.com/sachingrover211/llm-rl_finetune/
website:
  - https://props-llm.github.io
github_tooltip:
  - LLM RL
  - LLM RL & Finetune
website_tooltip:
  - Project summary and findings
thumbnail: LLMs Generated Parameterized Policies
---

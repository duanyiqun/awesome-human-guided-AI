# Awesome-Human-Guided-AI 

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A paperlist repo of human guidiance for AI, generative model and autonomous systems.  

Human-guided AI is a term that can refer to different concepts depending on the context. 
Recently, take chatGPT as representative, with the help of human guidiance (reinforcement learning from human feedback, RLHF), the language model emrging ashitonishing performance on generalized tasks, such as question & answering, calculation, translation, and dialog. In some degree it's a very good example for human guidance for AI.
Meanwhile, for years we are pursuing a better control of the autonomous system. It's likely that we can manupulate it with a guided approach. 

Here we can raise a series question that, **what kind of human guidance is feasible to introduce to AI?**  **what are the approaches for human guided AI?**

It's a good angle to dive into this area. Here we provides a reading list to related topics in deep learning area. 
Previously, the human guidane is more like to introduce human prior designed networks structures/losses, data-pairs. However, in order to focus on human guidance, we will not include data-driven methods in this repo. 



A curated list of repositories in which many NLP/CV/ML papers and related area resources are collected.


## Tabel of Contents

- [Potential Guidances](#potential-guidances)
  - [Prompt/Language](#prompt/language)
  - [Visual Attention](#visual-attention)
  - [Rewards](#rewards)
  - [Knowledge Base](#data-base)
  - [EEG/Brain Dynamics](#eeg/brain-dynamics)
  - [Biological Trustworthy](#biological-trustworthy)
  - [MultiModality](#multimodality)
- [Ways to inject guidance](#awesome-paper-list)
  - [RLHF/instructGPT](#rlhf)
  - [Human in the loop RL](#RLHF)
  - [Imitation Learning](#RLHF)
  - [Knowlege Manipulation](#RLHF)
  - [Knowlege Manipulation](#RLHF)


## Potential Guidances

### Prompt/Language

Along with the rise of stable diffusion/GPT based models


### Visual Attention 

### Rewards

### External Knowlege Base

### EEG/Brain Dynamics

### Biological Trustworthy


## Ways to Conduct Guidance



### RLHF

Reinforcement Learning from Human Feedback (RLHF) is a technique that uses methods from reinforcement learning to directly optimize a language model with human feedback. RLHF has enabled language models to align better with complex human values and preferences. RLHF’s most recent success was its use in ChatGPT, a state-of-the-art conversational agent.

| Catagory  | Paper                                                                                                                | Year | Git       |
|-----------|----------------------------------------------------------------------------------------------------------------------|------|-----------|
| PbRL      | [Preference-based reinforcement learning: a formal framework and a policy iteration algorithm ](https://link.springer.com/article/10.1007/s10994-012-5313-8)                        | 2012 | N/A       |
| PbRL      | [Preference-based reinforcement learning: evolutionary direct policy search using a preference-based racing algorithm](https://link.springer.com/article/10.1007/s10994-014-5458-8) | 2014 | N/A       |
| PbRL      | [Preference-based Reinforcement Learning with Finite-Time Guarantees](https://arxiv.org/abs/2006.08910)                                                  | 2020 | N/A       |
| PbRL      | [B-Pref: Benchmarking Preference-Based Reinforcement Learning](https://arxiv.org/abs/2111.03026)                                                         | 2021 | N/A       |
| PbRL      | [MicroSoft Research talk: Reinforcement learning with preference feedback](https://www.microsoft.com/en-us/research/video/research-talk-reinforcement-learning-with-preference-feedback/)                                             | 2021 | N/A       |
| PbRL/RLHF | [Training language models to follow instructions with human feedback (InstructGPT)](https://arxiv.org/pdf/2203.02155.pdf)                                    | 2022 | [chatllama](https://github.com/juncongmoo/chatllama.git) |
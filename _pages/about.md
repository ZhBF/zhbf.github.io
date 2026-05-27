---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a doctoral student in the Graduate School of Informatics at Nagoya University, advised by Prof. Keisuke Fujii. My research focuses on artificial intelligence, reinforcement learning, and multi-agent systems, with a particular interest in intelligent decision-making in soccer games.

My current work studies **multi-agent reinforcement learning from state-only demonstrations**. In many sports domains, expert demonstrations are available as trajectories of players and the ball, while the corresponding expert actions are not directly observed. This creates a gap between real-world sports data and conventional imitation learning methods, which often assume access to action labels.

I am interested in bridging this gap by using state-only demonstrations as auxiliary learning signals for multi-agent reinforcement learning. More specifically, I study how demonstration-derived rewards, entity-centric representations, and permutation-invariant architectures can improve policy learning in sparse-reward, cooperative-competitive environments. Soccer is a natural testbed for this problem because it involves long-horizon coordination, opponent interaction, sparse scoring rewards, and complex spatial-temporal decision making.

## Research Interests

- Reinforcement learning
- Multi-agent reinforcement learning
- Imitation learning from observation

## Current Research

My current project explores a hybrid framework for learning soccer decision-making policies from state-only demonstrations. The central idea is to transform expert observation trajectories into an auxiliary imitation reward and combine it with the sparse environment reward during multi-agent reinforcement learning.

This approach uses expert demonstrations as early-stage guidance while preserving optimization toward the original task objective, such as scoring goals or winning games. I am also investigating entity-centric Transformer architectures for representing players, opponents, and the ball in a permutation-invariant manner.

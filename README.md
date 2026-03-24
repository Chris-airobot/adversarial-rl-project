# Adversarial RL Project

A research project exploring adversarial reinforcement learning and human-in-the-loop interaction in a custom multi-agent environment.

This project was developed to study how reinforcement learning agents behave under adversarial conditions, and how human intervention can be incorporated into the training process to influence environment difficulty and policy development.

## Overview

The goal of this project is to build and evaluate a reinforcement learning framework in which an agent learns in the presence of adversarial or dynamically changing conditions.

The project combines:
- custom environment design
- adversarial reinforcement learning concepts
- policy optimization with PPO
- human-in-the-loop interaction
- experimental evaluation in a multi-agent setting

This repository focuses on practical implementation and experimentation rather than a production-ready RL framework.

## Project goals

- Design a custom RL environment with adversarial dynamics
- Train learning agents using PPO-based methods
- Explore how environment difficulty and adversarial behavior affect learning
- Introduce human-in-the-loop control to influence training conditions
- Evaluate agent performance against baseline settings

## Main ideas

This project investigates reinforcement learning under more challenging and interactive conditions than standard single-agent training setups.

Key ideas include:
- training in a custom adversarial environment
- modifying the environment during training
- evaluating policy robustness under changing conditions
- studying whether human intervention can improve training effectiveness

## Repository structure

```text
.
├── adversarilRL/    # Core environment and project-specific code
├── learning/        # Training logic and learning-related components
├── scripts/         # Helper scripts for running experiments
└── README.md
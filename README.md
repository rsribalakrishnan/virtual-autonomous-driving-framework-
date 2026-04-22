# Virtual Autonomous Driving Framework with LiDAR and Vision-Based Perception

## Overview
This repository contains a modular virtual autonomous driving framework built in the Genesis World simulation environment. The project was developed as part of a Master’s thesis in Artificial Intelligence and Robotics and focuses on simulation-based autonomous driving with analytic LiDAR perception, heuristic navigation, behavioural cloning, PPO reinforcement learning, and deployment evaluation.

The framework is organized as a five-phase pipeline. Each phase produces artifacts that are consumed by the next phase. All phases share the same vehicle model, observation vector, sensor design, and core environment setup, which makes the pipeline reproducible and consistent.

## Project Goals
- Build a simulation-based autonomous driving environment
- Implement LiDAR and perception-driven navigation
- Collect expert driving data using a heuristic controller
- Train neural policies with Behavioural Cloning and PPO
- Evaluate policy performance across multiple obstacle configurations

## Framework Phases
The system is divided into five phases:

- **Phase 0** — Environment and kinematics validation
- **Phase 1** — Sensor system and heuristic controller development
- **Phase 2** — Expert data collection
- **Phase 3** — Neural policy training
  - **Phase 3A** — Behavioural Cloning
  - **Phase 3B** — PPO fine-tuning
- **Phase 4** — Deterministic deployment evaluation

This design mirrors the workflow and keeps each stage modular and traceable.

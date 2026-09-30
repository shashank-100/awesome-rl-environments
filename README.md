# Awesome RL Environments [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of environments, benchmarks, and gyms for reinforcement learning — from classic control to LLM agents.

## Contents

- [Frameworks & APIs](#frameworks--apis)
- [Classic Control & Games](#classic-control--games)
- [Robotics & Physics](#robotics--physics)
- [Procedural & Open-Ended](#procedural--open-ended)
- [Multi-Agent](#multi-agent)
- [Hardware-Accelerated](#hardware-accelerated)
- [LLM Agents & Reasoning](#llm-agents--reasoning)
- [Web & Computer Use](#web--computer-use)
- [Software Engineering](#software-engineering)
- [Domain-Specific](#domain-specific)
- [Related Lists](#related-lists)
- [Guides & Articles](#guides--articles)
- [Contributing](#contributing)

## Frameworks & APIs

- [Gymnasium](https://github.com/Farama-Foundation/Gymnasium) - Maintained successor to OpenAI Gym; the standard single-agent RL API.
- [PettingZoo](https://github.com/Farama-Foundation/PettingZoo) - Gymnasium-style API for multi-agent environments.
- [dm_env](https://github.com/google-deepmind/dm_env) - DeepMind's minimal environment interface.

## Classic Control & Games

- [Arcade Learning Environment](https://github.com/Farama-Foundation/Arcade-Learning-Environment) - Atari 2600 games for RL.
- [MiniGrid](https://github.com/Farama-Foundation/Minigrid) - Lightweight gridworlds for goal-oriented tasks.
- [NetHack Learning Environment](https://github.com/heiner/nle) - The roguelike NetHack as a hard RL benchmark.
- [MineRL](https://github.com/minerllabs/minerl) - Minecraft environments with human demonstrations.
- [Retro Learning Environment](https://github.com/nadavbh12/Retro-Learning-Environment) - SNES and Sega Genesis games via emulators.
- [RLCard](https://github.com/datamllab/rlcard) - Card game environments such as poker, Blackjack, and Dou Dizhu.
- [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents) - Build environments for agents in the Unity game engine.

## Robotics & Physics

- [MuJoCo](https://github.com/google-deepmind/mujoco) - Fast, accurate physics engine for robotics and control.
- [DeepMind Control Suite](https://github.com/google-deepmind/dm_control) - Continuous control tasks built on MuJoCo.
- [Meta-World](https://github.com/Farama-Foundation/Metaworld) - Multi-task and meta-RL robotic manipulation benchmark.
- [Isaac Lab](https://github.com/isaac-sim/IsaacLab) - GPU-accelerated robot learning on NVIDIA Isaac Sim.
- [AndroidEnv](https://github.com/google-deepmind/android_env) - RL on real Android apps through an emulator.

## Procedural & Open-Ended

- [Procgen](https://github.com/openai/procgen) - 16 procedurally generated games for measuring generalization.
- [Crafter](https://github.com/danijar/crafter) - Open-world survival benchmark with an achievement-based score.
- [Craftax](https://github.com/MichaelTMatthews/Craftax) - JAX reimplementation and extension of Crafter.

## Multi-Agent

- [OpenSpiel](https://github.com/google-deepmind/open_spiel) - Collection of games and algorithms for RL and game theory.
- [SMAC](https://github.com/oxwhirl/smac) - StarCraft II micromanagement challenge.
- [Melting Pot](https://github.com/google-deepmind/meltingpot) - Test suite for multi-agent generalization in social settings.
- [Neural MMO](https://github.com/NeuralMMO/environment) - Massively multi-agent MMO-style survival environment.

## Hardware-Accelerated

- [Brax](https://github.com/google/brax) - Differentiable physics simulation in JAX.
- [Jumanji](https://github.com/instadeepai/jumanji) - Suite of JAX environments for combinatorial and industry problems.
- [Gymnax](https://github.com/RobertTLange/gymnax) - Classic Gym environments rewritten in JAX.
- [EnvPool](https://github.com/sail-sg/envpool) - High-throughput batched C++ environment execution.

## LLM Agents & Reasoning

- [verifiers](https://github.com/PrimeIntellect-ai/verifiers) - Library for building RL environments and evals for LLMs.
- [Reasoning Gym](https://github.com/open-thought/reasoning-gym) - Procedurally generated reasoning tasks with verifiable rewards.
- [TextArena](https://github.com/LeonGuertler/TextArena) - Text-based competitive games for LLM agents.
- [τ-bench](https://github.com/sierra-research/tau-bench) - Tool-agent-user interaction in customer-service domains.
- [AppWorld](https://github.com/StonyBrookNLP/appworld) - Controllable world of apps and APIs for interactive coding agents.
- [SPIRAL](https://github.com/spiral-rl/spiral) - Self-play on zero-sum language games for LLM reasoning.

## Web & Computer Use

- [WebArena](https://github.com/web-arena-x/webarena) - Realistic, self-hostable websites for autonomous web agents.
- [BrowserGym](https://github.com/ServiceNow/BrowserGym) - Gym environment unifying web-agent benchmarks.
- [OSWorld](https://github.com/xlang-ai/OSWorld) - Real desktop OS tasks for multimodal computer-use agents.

## Software Engineering

- [SWE-bench](https://github.com/SWE-bench/SWE-bench) - Real GitHub issues as software engineering tasks.
- [SWE-Gym](https://github.com/SWE-Gym/SWE-Gym) - Training environment for software engineering agents.

## Domain-Specific

- [FinRL](https://github.com/AI4Finance-Foundation/FinRL) - Financial trading environments for deep RL.
- [RecSim](https://github.com/google-research/recsim) - Simulation platform for recommender systems.

## Related Lists

- [awesome-rl-envs](https://github.com/clvrai/awesome-rl-envs) - List of RL environments by CLVR Lab.
- [NafiGit/awesome-rl-environments](https://github.com/NafiGit/awesome-rl-environments) - Classic control through LLM-agent training environments.
- [awesome-rl](https://github.com/aikorea/awesome-rl) - Broad RL resources: code, papers, courses, and environments.

## Guides & Articles

- [The Ultimate Guide to RL Environments](https://huggingface.co/spaces/AdithyaSK/rl-environments-guide) - Hugging Face guide to building and scaling RL environments in the LLM era (2026).
- [15 Awesome Reinforcement Learning Environments You Must Know](https://medium.com/@mlblogging.k/15-awesome-reinforcement-learning-environments-you-must-know-a38fb75867f2) - Overview from Neural MMO to RLCard.
- [Top 5 Reinforcement Learning Environments](https://www.hud.ai/resources/top-5-reinforcement-learning-environments) - HUD's 2026 roundup.
- [Best Sandboxes for Self-Play RL Environments in 2026](https://modal.com/resources/best-sandboxes-self-play-rl-environments) - Modal's comparison of self-play platforms.
- [RL Environments: Tutorial & Examples](https://www.patronus.ai/guide-to-rl-environments) - Patronus AI primer on state, actions, and rewards.
- [Inside the RL Gym](https://toloka.ai/blog/inside-the-rl-gym-reinforcement-learning-environments-explained/) - Toloka explainer on RL gyms.
- [What are some exciting and challenging RL environments?](https://www.reddit.com/r/MachineLearning/search/?q=exciting+and+challenging+RL+environments) - r/MachineLearning discussion.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

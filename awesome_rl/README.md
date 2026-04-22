# Shivam Awesome Reinforcement Learning

A curated, practical map of modern Reinforcement Learning from core theory to scalable systems.

## 🧭 Learning Path (Beginner → Advanced)

1. **RL foundations:** Master MDPs, Bellman equations, and policy/value methods with [Sutton & Barto](http://incompleteideas.net/book/the-book-2nd.html).
2. **Deep RL basics:** Study [DQN](https://arxiv.org/abs/1312.5602), [A3C](https://arxiv.org/abs/1602.01783), and [DDPG](https://arxiv.org/abs/1509.02971).
3. **Modern control defaults:** Build intuition with [PPO](https://arxiv.org/abs/1707.06347), [SAC](https://arxiv.org/abs/1801.01290), and [TD3](https://arxiv.org/abs/1802.09477).
4. **Planning + world models:** Read [MuZero](https://arxiv.org/abs/1911.08265) and [DreamerV3](https://arxiv.org/abs/2301.04104).
5. **Offline RL:** Learn [D4RL](https://arxiv.org/abs/2004.07219), [Decision Transformer](https://arxiv.org/abs/2106.01345), and [CQL](https://arxiv.org/abs/2006.04779).
6. **Distributed RL systems:** Use [Gymnasium](https://github.com/Farama-Foundation/Gymnasium), [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3), and [RLlib](https://docs.ray.io/en/latest/rllib/index.html).

## 📄 Papers (with links + 1-line insight)

- [Playing Atari with Deep Reinforcement Learning (DQN)](https://arxiv.org/abs/1312.5602) — Introduced deep Q-learning for pixel-based control.
- [Asynchronous Methods for Deep Reinforcement Learning (A3C)](https://arxiv.org/abs/1602.01783) — Used parallel actor-learners for stable and faster optimization.
- [Proximal Policy Optimization Algorithms (PPO)](https://arxiv.org/abs/1707.06347) — Delivered a robust, practical trust-region approximation.
- [Soft Actor-Critic (SAC)](https://arxiv.org/abs/1801.01290) — Improved sample efficiency via maximum-entropy objectives.
- [Mastering Atari, Go, Chess and Shogi by Planning with a Learned Model (MuZero)](https://arxiv.org/abs/1911.08265) — Combined planning and learned dynamics without known environment rules.
- [Offline Reinforcement Learning as One Big Sequence Modeling Problem (Decision Transformer)](https://arxiv.org/abs/2106.01345) — Reframed offline RL as conditional sequence modeling.

## 🔗 Paper → Code Mapping

| Paper | Official / Best Implementation |
|---|---|
| [DQN](https://arxiv.org/abs/1312.5602) | [CleanRL DQN](https://github.com/vwxyzjn/cleanrl) |
| [PPO](https://arxiv.org/abs/1707.06347) | [Stable-Baselines3 PPO](https://github.com/DLR-RM/stable-baselines3) |
| [SAC](https://arxiv.org/abs/1801.01290) | [Stable-Baselines3 SAC](https://github.com/DLR-RM/stable-baselines3) |
| [MuZero](https://arxiv.org/abs/1911.08265) | [muzero-general](https://github.com/werner-duvaud/muzero-general) |
| [DreamerV3](https://arxiv.org/abs/2301.04104) | [danijar/dreamerv3](https://github.com/danijar/dreamerv3) |
| [Decision Transformer](https://arxiv.org/abs/2106.01345) | [kzl/decision-transformer](https://github.com/kzl/decision-transformer) |

## 🧰 Libraries & Frameworks

- [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) — Reliable PyTorch baselines for common RL algorithms.
- [Ray RLlib](https://github.com/ray-project/ray) — Distributed RL training for large-scale experimentation.
- [CleanRL](https://github.com/vwxyzjn/cleanrl) — Minimal single-file implementations for reproducible RL research.
- [Tianshou](https://github.com/thu-ml/tianshou) — Modular RL framework with flexible replay and policy APIs.
- [Acme](https://github.com/google-deepmind/acme) — Reusable agent components from DeepMind research workflows.

## 📊 Datasets / Environments

- [Gymnasium](https://github.com/Farama-Foundation/Gymnasium) — Standard environment API for RL experiments.
- [Atari Learning Environment (ALE)](https://github.com/Farama-Foundation/Arcade-Learning-Environment) — Canonical benchmark for visual RL.
- [DM Control Suite](https://github.com/google-deepmind/dm_control) — Continuous control benchmark built on MuJoCo.
- [Procgen](https://github.com/openai/procgen) — Generalization benchmark via procedurally generated tasks.
- [D4RL](https://github.com/Farama-Foundation/D4RL) — Standardized offline RL datasets and evaluation tasks.

## 🎓 Courses

- [UCL RL Course (David Silver)](https://www.davidsilver.uk/teaching/) — Classic lecture sequence for RL fundamentals.
- [Stanford CS234](https://web.stanford.edu/class/cs234/) — Comprehensive RL course from theory to deep RL.
- [Spinning Up in Deep RL](https://spinningup.openai.com/en/latest/) — Practical educational resource with implementation guidance.

## 🧪 Experiments (Actionable)

- **On-policy vs off-policy:** Compare PPO, SAC, and TD3 on identical MuJoCo compute budgets.
- **Offline RL quality:** Benchmark behavior cloning, CQL, and Decision Transformer on D4RL tasks.
- **Generalization stress test:** Train on Procgen easy seeds and evaluate out-of-distribution seeds.

## 🏗 RL System Design (IMPORTANT)

- **Simulator throughput first:** Parallelized environment stepping often yields bigger wins than model tweaks.
- **Reproducibility envelope:** Track seeds, environment versions, and eval protocols as first-class artifacts.
- **Evaluation pipeline:** Separate training rewards from standardized evaluation rollouts to avoid leakage.

## ⚙️ RL Infra / Serving (DevOps angle)

- [Ray Serve](https://docs.ray.io/en/latest/serve/index.html) — Scalable policy serving and online decision APIs.
- [KubeRay](https://docs.ray.io/en/latest/cluster/kubernetes/index.html) — Kubernetes-native orchestration for distributed RL jobs.
- [Weights & Biases](https://wandb.ai/site) — Experiment tracking for seeds, sweeps, and replay artifacts.
- [MLflow](https://github.com/mlflow/mlflow) — Model packaging, registry, and deployment workflows.

## 🧩 Use Cases

- **Robotics control:** Continuous control policies with sim-to-real adaptation.
- **Operations research:** Dynamic pricing, inventory, and routing optimization.
- **Game AI:** Self-play and planning-driven agents for strategic environments.
- **Resource scheduling:** Cluster/job scheduling under changing workloads.

## 📈 Evaluation Metrics

- **Average episodic return** — Primary policy performance metric.
- **Success rate** — Task completion reliability across randomized episodes.
- **Sample efficiency** — Reward achieved per environment interaction.
- **Regret / constraint violation** — Safety and online optimization quality metrics.

## 🛠 Tools / Ecosystem

- [PettingZoo](https://github.com/Farama-Foundation/PettingZoo) — Standardized multi-agent RL environment API.
- [EnvPool](https://github.com/sail-sg/envpool) — High-throughput vectorized environments for faster training.
- [TensorBoard](https://www.tensorflow.org/tensorboard) — Visual diagnostics for reward, losses, and instability signals.

## 📝 Blogs / Learning Resources

- [Lilian Weng on Policy Gradients](https://lilianweng.github.io/posts/2018-04-08-policy-gradient/) — Clear conceptual guide to gradient-based RL.
- [OpenAI Spinning Up Intro](https://spinningup.openai.com/en/latest/spinningup/rl_intro.html) — Concise and practical RL conceptual primer.
- [DeepMind Publications](https://deepmind.google/research/publications/) — Primary-source archive for major RL advances.

## 📊 Benchmarks

- [ALE / Atari](https://github.com/Farama-Foundation/Arcade-Learning-Environment) — Long-standing benchmark for visual control.
- [MuJoCo](https://mujoco.org/) — Standard continuous-control benchmark suite.
- [Procgen](https://github.com/openai/procgen) — Generalization-focused procedural benchmark.
- [D4RL](https://github.com/Farama-Foundation/D4RL) — Core benchmark for offline RL algorithms.

## ✍️ Shivam’s Notes (Insight Section)

- Most RL papers underreport instability; always compare across multiple seeds.
- Better environment instrumentation often beats more complex policy architectures.
- Offline RL can outperform online RL in production when exploration is unsafe or expensive.

# Shivam Awesome Reinforcement Learning

A curated, practical map of modern Reinforcement Learning from core theory to scalable systems.

## 🧭 Learning Path (Beginner → Advanced)

1. **RL fundamentals:** Master MDPs, Bellman equations, and policy/value methods with [Sutton & Barto](http://incompleteideas.net/book/the-book-2nd.html).
2. **Deep RL basics:** Study [DQN](https://arxiv.org/abs/1312.5602), [A3C](https://arxiv.org/abs/1602.01783), and [DDPG](https://arxiv.org/abs/1509.02971).
3. **Strong policy gradients:** Learn [TRPO](https://arxiv.org/abs/1502.05477), [PPO](https://arxiv.org/abs/1707.06347), [SAC](https://arxiv.org/abs/1801.01290), and [TD3](https://arxiv.org/abs/1802.09477).
4. **Planning + world models:** Read [AlphaZero](https://arxiv.org/abs/1712.01815), [MuZero](https://arxiv.org/abs/1911.08265), and [DreamerV3](https://arxiv.org/abs/2301.04104).
5. **Offline RL:** Explore [D4RL](https://arxiv.org/abs/2004.07219), [CQL](https://arxiv.org/abs/2006.04779), [IQL](https://arxiv.org/abs/2110.06169), and [Decision Transformer](https://arxiv.org/abs/2106.01345).
6. **Scale & production:** Use [Gymnasium](https://github.com/Farama-Foundation/Gymnasium), [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3), and [RLlib](https://docs.ray.io/en/latest/rllib/index.html).

## 📄 Papers (with links + 1-line insight)

- [DQN](https://arxiv.org/abs/1312.5602) — Introduced deep Q-learning for pixel-based control.
- [A3C](https://arxiv.org/abs/1602.01783) — Scaled RL training with asynchronous actor-learners.
- [TRPO](https://arxiv.org/abs/1502.05477) — Stabilized policy updates using trust-region constraints.
- [PPO](https://arxiv.org/abs/1707.06347) — Practical and robust clipped objective for policy optimization.
- [DDPG](https://arxiv.org/abs/1509.02971) — Brought deterministic actor-critic methods to deep continuous control.
- [SAC](https://arxiv.org/abs/1801.01290) — Added entropy maximization for stable, sample-efficient learning.
- [TD3](https://arxiv.org/abs/1802.09477) — Reduced overestimation bias in actor-critic methods.
- [AlphaZero](https://arxiv.org/abs/1712.01815) — Unified self-play and MCTS for strong strategic play.
- [MuZero](https://arxiv.org/abs/1911.08265) — Learned latent dynamics for planning without known rules.
- [Dreamer](https://arxiv.org/abs/1912.01603) — Introduced latent imagination for world-model RL.
- [DreamerV3](https://arxiv.org/abs/2301.04104) — Showed robust world-model scaling across domains.
- [D4RL](https://arxiv.org/abs/2004.07219) — Standardized offline RL datasets and evaluation.
- [CQL](https://arxiv.org/abs/2006.04779) — Conservative value estimation improved offline RL reliability.
- [IQL](https://arxiv.org/abs/2110.06169) — Strong implicit Q-learning for offline datasets.
- [Decision Transformer](https://arxiv.org/abs/2106.01345) — Framed RL as sequence modeling.

## 🔗 Paper → Code Mapping

| Paper | Official / Best Implementation |
|---|---|
| [PPO](https://arxiv.org/abs/1707.06347) | [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) |
| [SAC](https://arxiv.org/abs/1801.01290) | [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) |
| [TD3](https://arxiv.org/abs/1802.09477) | [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) |
| [MuZero](https://arxiv.org/abs/1911.08265) | [muzero-general](https://github.com/werner-duvaud/muzero-general) |
| [DreamerV3](https://arxiv.org/abs/2301.04104) | [danijar/dreamerv3](https://github.com/danijar/dreamerv3) |
| [Decision Transformer](https://arxiv.org/abs/2106.01345) | [kzl/decision-transformer](https://github.com/kzl/decision-transformer) |

## 🧰 Libraries & Frameworks

- [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) — Reliable PyTorch RL baselines.
- [Ray RLlib](https://github.com/ray-project/ray) — Distributed RL training and evaluation.
- [CleanRL](https://github.com/vwxyzjn/cleanrl) — Minimal single-file implementations for reproducible research.
- [Tianshou](https://github.com/thu-ml/tianshou) — Modular RL research framework.
- [Acme](https://github.com/google-deepmind/acme) — Reusable DeepMind-inspired RL components.
- [PettingZoo](https://github.com/Farama-Foundation/PettingZoo) — Standardized multi-agent RL environments.

## 📊 Datasets / Environments

- [Gymnasium](https://github.com/Farama-Foundation/Gymnasium) — Standard API for RL environments.
- [ALE](https://github.com/Farama-Foundation/Arcade-Learning-Environment) — Canonical visual-control benchmark.
- [DM Control Suite](https://github.com/google-deepmind/dm_control) — Continuous control benchmark built on MuJoCo.
- [MuJoCo](https://mujoco.org/) — Physics engine and benchmark platform for control.
- [Procgen](https://github.com/openai/procgen) — Procedural benchmark for generalization.
- [D4RL](https://github.com/Farama-Foundation/D4RL) — Offline RL datasets.
- [MinAtar](https://github.com/kenjyoung/MinAtar) — Simplified Atari for faster algorithm iteration.

## 🎓 Courses

- [UCL RL Course (David Silver)](https://www.davidsilver.uk/teaching/) — Classic RL lecture series.
- [Stanford CS234](https://web.stanford.edu/class/cs234/) — Comprehensive modern RL course.
- [Spinning Up in Deep RL](https://spinningup.openai.com/en/latest/) — Practical educational RL guide.
- [DeepMind x UCL RL Lecture Series](https://www.deepmind.com/learning-resources/reinforcement-learning-lecture-series-2021) — Advanced research talks.

## 🧪 Experiments (Actionable)

- **Algorithm trade-offs:** Compare PPO/SAC/TD3 under matched environment steps and compute.
- **Offline RL quality:** Evaluate BC/CQL/IQL/Decision Transformer on D4RL locomotion tasks.
- **Generalization:** Train on Procgen easy and evaluate on hard unseen seeds.
- **Stability profiling:** Run 10 seeds per algorithm and report mean/std confidence intervals.

## 🏗 RL System Design (IMPORTANT)

- **Simulator throughput first:** Vectorized and parallel environments often unlock the biggest gains.
- **Reproducibility envelope:** Log seeds, environment versions, eval protocols, and reward normalization.
- **Separation of concerns:** Keep training rewards separate from frozen evaluation rollouts.

## ⚙️ RL Infra / Serving (DevOps angle)

- [Ray Serve](https://docs.ray.io/en/latest/serve/index.html) — Scalable policy serving endpoints.
- [KubeRay](https://docs.ray.io/en/latest/cluster/kubernetes/index.html) — Kubernetes orchestration for distributed RL jobs.
- [Weights & Biases](https://wandb.ai/site) — Experiment tracking for sweeps and seed analysis.
- [MLflow](https://github.com/mlflow/mlflow) — Artifact/model registry and deployment packaging.

## 🧩 Use Cases

- **Robotics control:** Continuous control with safety constraints and sim-to-real tuning.
- **Operations optimization:** Inventory, pricing, and scheduling decisions under uncertainty.
- **Game AI:** Self-play and planning for adversarial environments.
- **Network/resource control:** Adaptive policies for dynamic systems.

## 📈 Evaluation Metrics

- **Average episodic return** — Core policy quality metric.
- **Success rate** — Reliability on goal-based tasks.
- **Sample efficiency** — Reward achieved per interaction budget.
- **Regret / violation rate** — Safety and constraint-aware decision quality.

## 🛠 Tools / Ecosystem

- [TensorBoard](https://www.tensorflow.org/tensorboard) — Training diagnostics and reward visualization.
- [EnvPool](https://github.com/sail-sg/envpool) — High-throughput vectorized environment execution.
- [Gymnasium wrappers](https://gymnasium.farama.org/api/wrappers/) — Standardized environment transformations and instrumentation.

## 🧾 Curated RL Repositories

- [dennybritz/reinforcement-learning](https://github.com/dennybritz/reinforcement-learning) — Classic educational implementations of core RL algorithms.
- [vwxyzjn/cleanrl](https://github.com/vwxyzjn/cleanrl) — Reproducible single-file baselines for many deep RL methods.
- [DLR-RM/rl-baselines3-zoo](https://github.com/DLR-RM/rl-baselines3-zoo) — Training scripts and tuned hyperparameters for SB3 benchmarks.

## 📝 Blogs / Learning Resources

- [Lilian Weng on Policy Gradients](https://lilianweng.github.io/posts/2018-04-08-policy-gradient/) — Clear conceptual guide to policy gradient RL.
- [OpenAI Spinning Up Intro](https://spinningup.openai.com/en/latest/spinningup/rl_intro.html) — Practical and concise RL primer.
- [DeepMind Publications](https://deepmind.google/research/publications/) — Primary source archive for landmark RL work.

## 📊 Benchmarks

- [ALE / Atari](https://github.com/Farama-Foundation/Arcade-Learning-Environment) — Long-standing visual control benchmark.
- [MuJoCo](https://mujoco.org/) — Standard continuous-control benchmark suite.
- [Procgen](https://github.com/openai/procgen) — Generalization benchmark under procedural variation.
- [D4RL](https://github.com/Farama-Foundation/D4RL) — Core offline RL benchmark suite.

## ✍️ Shivam’s Notes (Insight Section)

- Most RL papers underreport instability, so always compare across multiple seeds.
- Better environment instrumentation often beats more complex policies.
- Offline RL can outperform online RL when exploration is unsafe or expensive.

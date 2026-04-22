# Awesome Reinforcement Learning

A curated roadmap of papers, libraries, datasets/environments, courses, tools, projects, blogs, and benchmarks for modern Reinforcement Learning (RL).

## 🚀 Start Here (Beginner → Advanced path)

1. **Foundations:** Learn MDPs, value functions, policy gradients, and exploration via [Sutton & Barto (2nd ed.)](http://incompleteideas.net/book/the-book-2nd.html).
2. **Classical deep RL:** Study [DQN](https://www.nature.com/articles/nature14236), [A3C](https://arxiv.org/abs/1602.01783), and [DDPG](https://arxiv.org/abs/1509.02971).
3. **Modern policy optimization:** Read [TRPO](https://arxiv.org/abs/1502.05477), [PPO](https://arxiv.org/abs/1707.06347), and [SAC](https://arxiv.org/abs/1801.01290).
4. **Model-based + planning:** Learn from [MuZero](https://arxiv.org/abs/1911.08265) and [DreamerV3](https://arxiv.org/abs/2301.04104).
5. **Offline RL & sequence modeling:** Explore [D4RL](https://arxiv.org/abs/2004.07219), [Decision Transformer](https://arxiv.org/abs/2106.01345), and [CQL](https://arxiv.org/abs/2006.04779).
6. **Scale and systems:** Build projects with [Gymnasium](https://github.com/Farama-Foundation/Gymnasium), [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3), and [Ray RLlib](https://github.com/ray-project/ray).

## 📄 Papers (with links + 1-line why it matters)

- [Playing Atari with Deep Reinforcement Learning (DQN)](https://arxiv.org/abs/1312.5602) — Introduced deep Q-learning that launched deep RL at scale.
- [Human-level control through deep reinforcement learning](https://www.nature.com/articles/nature14236) — Showed DQN could achieve strong Atari performance from pixels.
- [Asynchronous Methods for Deep Reinforcement Learning (A3C)](https://arxiv.org/abs/1602.01783) — Stabilized and accelerated training with asynchronous actor-learners.
- [Trust Region Policy Optimization (TRPO)](https://arxiv.org/abs/1502.05477) — Introduced constrained policy updates for safer optimization.
- [Proximal Policy Optimization Algorithms (PPO)](https://arxiv.org/abs/1707.06347) — Became a practical default for robust on-policy RL.
- [Deep Deterministic Policy Gradient (DDPG)](https://arxiv.org/abs/1509.02971) — Extended deterministic policy gradients to deep continuous control.
- [Soft Actor-Critic (SAC)](https://arxiv.org/abs/1801.01290) — Added entropy maximization for stable, sample-efficient learning.
- [Twin Delayed DDPG (TD3)](https://arxiv.org/abs/1802.09477) — Reduced overestimation bias in actor-critic methods.
- [Mastering the game of Go with deep neural networks and tree search (AlphaGo)](https://www.nature.com/articles/nature16961) — Combined policy/value nets with MCTS to surpass top human play.
- [Mastering Chess and Shogi by Self-Play with a General Reinforcement Learning Algorithm (AlphaZero)](https://arxiv.org/abs/1712.01815) — Generalized self-play plus search across multiple board games.
- [Mastering Atari, Go, Chess and Shogi by Planning with a Learned Model (MuZero)](https://arxiv.org/abs/1911.08265) — Learned a latent dynamics model for planning without known rules.
- [Dream to Control: Learning Behaviors by Latent Imagination (Dreamer)](https://arxiv.org/abs/1912.01603) — Made model-based RL practical via latent rollouts.
- [Mastering Diverse Domains through World Models (DreamerV3)](https://arxiv.org/abs/2301.04104) — Demonstrated robust world-model scaling across tasks.
- [D4RL: Datasets for Deep Data-Driven Reinforcement Learning](https://arxiv.org/abs/2004.07219) — Standardized offline RL evaluation datasets and protocols.
- [Offline Reinforcement Learning as One Big Sequence Modeling Problem (Decision Transformer)](https://arxiv.org/abs/2106.01345) — Reframed RL as conditional sequence modeling with transformers.
- [Conservative Q-Learning for Offline Reinforcement Learning (CQL)](https://arxiv.org/abs/2006.04779) — Improved robustness by conservatively estimating Q-values offline.

## 🧰 Libraries & Frameworks

- [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) — Reliable PyTorch implementations of standard RL algorithms.
- [Ray RLlib](https://github.com/ray-project/ray) — Scalable distributed RL training and serving framework.
- [CleanRL](https://github.com/vwxyzjn/cleanrl) — Single-file high-quality RL baselines for clarity and reproducibility.
- [Tianshou](https://github.com/thu-ml/tianshou) — Modular RL library for research-focused experimentation.
- [Acme](https://github.com/google-deepmind/acme) — DeepMind RL framework for reusable agents and components.

## 📊 Datasets / Environments

- [Gymnasium](https://github.com/Farama-Foundation/Gymnasium) — Standard API and benchmark environment suite for RL.
- [MinAtar](https://github.com/kenjyoung/MinAtar) — Simplified Atari-like environments for faster algorithm analysis.
- [DM Control Suite](https://github.com/google-deepmind/dm_control) — Continuous control benchmark built on MuJoCo.
- [Atari Learning Environment (ALE)](https://github.com/Farama-Foundation/Arcade-Learning-Environment) — Canonical arcade benchmark for RL agents.
- [Procgen Benchmark](https://github.com/openai/procgen) — Procedurally generated environments for generalization testing.
- [D4RL](https://github.com/Farama-Foundation/D4RL) — Offline RL datasets for locomotion, manipulation, and driving tasks.

## 🎓 Courses

- [UCL Course on RL (David Silver)](https://www.davidsilver.uk/teaching/) — Classic lecture series on core RL theory and practice.
- [Stanford CS234: Reinforcement Learning](https://web.stanford.edu/class/cs234/) — Comprehensive university course covering modern RL methods.
- [DeepMind x UCL RL Lecture Series](https://www.deepmind.com/learning-resources/reinforcement-learning-lecture-series-2021) — Advanced lectures from leading RL researchers.
- [Spinning Up in Deep RL](https://spinningup.openai.com/en/latest/) — Practical educational guide with algorithm intuition and code.

## 🛠 Tools / Ecosystem

- [Weights & Biases](https://wandb.ai/site) — Experiment tracking and comparison for RL training runs.
- [TensorBoard](https://www.tensorflow.org/tensorboard) — Visualization tool for reward curves and diagnostics.
- [PettingZoo](https://github.com/Farama-Foundation/PettingZoo) — Multi-agent RL environment API and benchmark suite.
- [EnvPool](https://github.com/sail-sg/envpool) — Highly parallel environment execution for faster training throughput.

## 🧪 Projects / Ideas

- Reproduce PPO baselines on CartPole, LunarLander, and HalfCheetah with seed variance analysis.
- Compare SAC vs TD3 sample efficiency on continuous control with consistent hyperparameters.
- Build an offline RL pipeline on D4RL and analyze behavior cloning vs CQL.
- Implement reward shaping for sparse-reward tasks and quantify stability trade-offs.
- Train a multi-agent policy in PettingZoo and evaluate emergent coordination behavior.
- Benchmark model-free vs model-based agents under fixed compute budgets.
- Add curriculum learning to Procgen tasks and measure out-of-distribution generalization.
- Create a reproducibility checklist and report for one published RL paper.

## 📝 Blogs / Learning Resources

- [Lil'Log (Lilian Weng) — Policy Gradient Algorithms](https://lilianweng.github.io/posts/2018-04-08-policy-gradient/) — Clear walkthrough of policy gradient foundations.
- [OpenAI Spinning Up Docs](https://spinningup.openai.com/en/latest/spinningup/rl_intro.html) — Concise conceptual guide to key RL ideas.
- [Distill: Feature Visualization](https://distill.pub/) — High-quality interactive ML articles helpful for RL intuition.
- [DeepMind Publications](https://deepmind.google/research/publications/) — Primary source for landmark RL papers and reports.

## 📈 Benchmarks

- [Atari 2600 / ALE](https://github.com/Farama-Foundation/Arcade-Learning-Environment) — Long-standing benchmark for visual control and exploration.
- [MuJoCo](https://mujoco.org/) — Standard continuous control benchmark used across actor-critic methods.
- [Procgen](https://github.com/openai/procgen) — Tests generalization via procedurally generated task distributions.
- [D4RL](https://github.com/Farama-Foundation/D4RL) — Widely used benchmark suite for offline reinforcement learning.

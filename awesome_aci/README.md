# Shivam Awesome Artificial & Computational Intelligence

A curated guide for Artificial Intelligence and Computational Intelligence spanning theory, optimization, and modern foundation models.

## 🧭 Learning Path (Beginner → Advanced)

1. **Classical AI foundations:** Study search, logic, and planning from [AIMA](https://aima.cs.berkeley.edu/).
2. **Statistical ML core:** Build fundamentals with [Pattern Recognition and Machine Learning](https://link.springer.com/book/10.1007/978-0-387-45528-0) and [Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/).
3. **Deep learning transition:** Learn representation learning through [Deep Learning](https://www.deeplearningbook.org/), [AlexNet](https://arxiv.org/abs/1404.5997), and [ResNet](https://arxiv.org/abs/1512.03385).
4. **Foundation model era:** Read [Transformer](https://arxiv.org/abs/1706.03762), [BERT](https://arxiv.org/abs/1810.04805), and [GPT-3](https://arxiv.org/abs/2005.14165).
5. **Computational intelligence methods:** Deepen with [Particle Swarm Optimization](https://ieeexplore.ieee.org/document/488968), [Differential Evolution](https://link.springer.com/article/10.1023/A:1008202821328), and [NEAT](https://nn.cs.utexas.edu/?stanley:ec02).
6. **Responsible AI deployment:** Ground evaluation and governance in [HELM](https://crfm.stanford.edu/helm/) and [NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework).

## 📄 Papers (with links + 1-line insight)

- [A Formal Basis for the Heuristic Determination of Minimum Cost Paths (A*)](https://ieeexplore.ieee.org/document/4082128) — Established optimal graph search under admissible heuristics.
- [Learning representations by back-propagating errors](https://www.nature.com/articles/323533a0) — Popularized end-to-end gradient-based neural learning.
- [Deep Residual Learning for Image Recognition (ResNet)](https://arxiv.org/abs/1512.03385) — Residual connections enabled depth scaling across AI tasks.
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) — Introduced transformer architecture underpinning modern foundation models.
- [BERT](https://arxiv.org/abs/1810.04805) — Made transfer learning central for language understanding tasks.
- [Language Models are Few-Shot Learners (GPT-3)](https://arxiv.org/abs/2005.14165) — Demonstrated strong in-context learning via scaling.
- [Particle Swarm Optimization](https://ieeexplore.ieee.org/document/488968) — Landmark swarm-intelligence optimizer for black-box optimization.
- [Differential Evolution](https://link.springer.com/article/10.1023/A:1008202821328) — Efficient evolutionary strategy for continuous global optimization.

## 🔗 Paper → Code Mapping

| Paper | Official / Best Implementation |
|---|---|
| [A* search](https://ieeexplore.ieee.org/document/4082128) | [NetworkX shortest paths](https://networkx.org/documentation/stable/reference/algorithms/shortest_paths.html) |
| [ResNet](https://arxiv.org/abs/1512.03385) | [torchvision models](https://github.com/pytorch/vision) |
| [Transformer](https://arxiv.org/abs/1706.03762) | [Hugging Face Transformers](https://github.com/huggingface/transformers) |
| [BERT](https://arxiv.org/abs/1810.04805) | [google-research/bert](https://github.com/google-research/bert) |
| [GPT-style models (GPT-3 reference)](https://arxiv.org/abs/2005.14165) | [nanoGPT](https://github.com/karpathy/nanoGPT) |
| [Differential Evolution](https://link.springer.com/article/10.1023/A:1008202821328) | [SciPy differential_evolution](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.differential_evolution.html) |
| [Particle Swarm Optimization](https://ieeexplore.ieee.org/document/488968) | [PySwarms](https://github.com/ljvmiranda921/pyswarms) |

## 🧰 Libraries & Frameworks

- [PyTorch](https://github.com/pytorch/pytorch) — Core deep learning framework for research and production.
- [TensorFlow](https://github.com/tensorflow/tensorflow) — End-to-end ML ecosystem for training and serving.
- [scikit-learn](https://github.com/scikit-learn/scikit-learn) — Standard toolkit for classical machine learning workflows.
- [JAX](https://github.com/jax-ml/jax) — High-performance autodiff and accelerator-friendly numerics.
- [DEAP](https://github.com/DEAP/deap) — Evolutionary computation toolbox for CI experiments.

## 📊 Datasets

- [UCI ML Repository](https://archive.ics.uci.edu/) — Canonical tabular benchmarks for classical ML and CI.
- [OpenML](https://www.openml.org/) — Reproducible benchmark tasks with datasets and experiment records.
- [ImageNet](https://www.image-net.org/) — Standard visual benchmark for large-scale learning.
- [COCO](https://cocodataset.org/) — Benchmark for detection and segmentation systems.
- [Common Crawl](https://commoncrawl.org/) — Web-scale text corpus for language pretraining.

## 🎓 Courses

- [MIT 6.034 Artificial Intelligence](https://ocw.mit.edu/courses/6-034-artificial-intelligence-fall-2010/) — Strong foundation in symbolic and classical AI methods.
- [Stanford CS221](https://stanford-cs221.github.io/) — Broad AI course spanning search, MDPs, and probabilistic models.
- [Stanford CS229](https://cs229.stanford.edu/) — Core mathematical treatment of machine learning.

## 🧪 Experiments (Actionable)

- **Hybrid AI pipeline:** Combine symbolic constraints with neural classifiers and measure consistency gains.
- **Optimizer comparison:** Benchmark PSO, DE, and Bayesian optimization on the same black-box objective suite.
- **Foundation-model baseline:** Compare frozen-embedding linear probes vs full fine-tuning on domain tasks.

## 🏗 AI/CI System Design (IMPORTANT)

- **Model portfolio design:** Use lightweight models for routing and expensive models for hard cases.
- **Human-in-the-loop controls:** Add review checkpoints where uncertainty or risk exceeds thresholds.
- **Lifecycle governance:** Enforce data versioning, model cards, and deployment rollback strategies.

## ⚙️ AI Infra / Serving (DevOps angle)

- [Ray](https://github.com/ray-project/ray) — Distributed execution framework for scalable AI workloads.
- [MLflow](https://github.com/mlflow/mlflow) — Experiment tracking, model registry, and deployment packaging.
- [Kubeflow](https://www.kubeflow.org/) — Kubernetes-native orchestration for ML pipelines.
- [ONNX Runtime](https://github.com/microsoft/onnxruntime) — Portable high-performance inference engine.

## 🧩 Use Cases

- **Decision intelligence:** Forecasting and optimization for operations and logistics.
- **Autonomous systems:** Perception + planning pipelines for robotics and mobility.
- **Healthcare AI:** Risk prediction and triage support with safety and audit constraints.
- **Finance analytics:** Fraud detection and risk modeling with explainability requirements.

## 📈 Evaluation Metrics

- **Accuracy / F1 / AUROC** — Core supervised learning metrics across class imbalance regimes.
- **Calibration error (ECE)** — Reliability metric for probabilistic decision support.
- **Latency / throughput / cost** — Operational metrics for production deployment quality.
- **Constraint violation rate** — Governance metric for safety and rule-based compliance.

## 🛠 Tools / Ecosystem

- [Weights & Biases](https://wandb.ai/site) — Experiment tracking and collaboration across teams.
- [DVC](https://github.com/iterative/dvc) — Versioning for data, models, and reproducible pipelines.
- [Great Expectations](https://github.com/great-expectations/great_expectations) — Data quality validation for robust ML systems.
- [SHAP](https://github.com/shap/shap) — Model explainability toolkit for feature-level attribution.

## 📝 Blogs / Learning Resources

- [Distill](https://distill.pub/) — High-quality visual explainers for ML and deep learning concepts.
- [The Gradient](https://thegradient.pub/) — Research-grounded AI analysis and commentary.
- [DeepMind Publications](https://deepmind.google/research/publications/) — Primary source for many influential AI papers.

## 📊 Benchmarks

- [MMLU](https://arxiv.org/abs/2009.03300) — Broad multitask benchmark for knowledge and reasoning.
- [HELM](https://crfm.stanford.edu/helm/) — Holistic benchmark for reliability across use scenarios.
- [ImageNet](https://paperswithcode.com/sota/image-classification-on-imagenet) — Standard benchmark for visual model progress.
- [GLUE](https://gluebenchmark.com/) — Core language understanding benchmark for NLP models.

## ✍️ Shivam’s Notes (Insight Section)

- Start with the simplest model that meets business constraints, then scale only when error analysis demands it.
- AI failures in production are usually data-contract and monitoring failures, not paper-level architecture gaps.
- In high-risk domains, calibrated uncertainty and fallback policies are more valuable than raw benchmark gains.

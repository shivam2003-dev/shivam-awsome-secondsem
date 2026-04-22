# Shivam Awesome Artificial & Computational Intelligence

A curated guide for Artificial Intelligence and Computational Intelligence spanning theory, optimization, and modern foundation models.

## 🧭 Learning Path (Beginner → Advanced)

1. **Classical AI foundations:** Study search, logic, planning, and uncertainty with [AIMA](https://aima.cs.berkeley.edu/).
2. **Statistical ML core:** Build fundamentals with [PRML](https://link.springer.com/book/10.1007/978-0-387-45528-0) and [ESL](https://hastie.su.domains/ElemStatLearn/).
3. **Deep learning transition:** Learn modern representation learning through [Deep Learning Book](https://www.deeplearningbook.org/) and [ResNet](https://arxiv.org/abs/1512.03385).
4. **Foundation models:** Read [Transformer](https://arxiv.org/abs/1706.03762), [BERT](https://arxiv.org/abs/1810.04805), [GPT-3](https://arxiv.org/abs/2005.14165), and [CLIP](https://arxiv.org/abs/2103.00020).
5. **Computational intelligence:** Explore [PSO](https://ieeexplore.ieee.org/document/488968), [Differential Evolution](https://link.springer.com/article/10.1023/A:1008202821328), and [NEAT](https://nn.cs.utexas.edu/?stanley:ec02).
6. **Responsible AI:** Ground governance and risk with [NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework) and [HELM](https://crfm.stanford.edu/helm/).

## 📄 Papers (with links + 1-line insight)

- [A* Search](https://ieeexplore.ieee.org/document/4082128) — Established optimal graph search with admissible heuristics.
- [Backpropagation](https://www.nature.com/articles/323533a0) — Popularized gradient-based learning in neural networks.
- [Random Forests](https://link.springer.com/article/10.1023/A:1010933404324) — Robust ensemble method for tabular and structured prediction.
- [ResNet](https://arxiv.org/abs/1512.03385) — Residual learning enabled much deeper networks.
- [Transformer](https://arxiv.org/abs/1706.03762) — Introduced attention-centric architecture for sequence modeling.
- [BERT](https://arxiv.org/abs/1810.04805) — Established transfer learning as a core NLP paradigm.
- [GPT-3](https://arxiv.org/abs/2005.14165) — Demonstrated strong in-context learning through scale.
- [CLIP](https://arxiv.org/abs/2103.00020) — Unified language and vision for zero-shot transfer.
- [PSO](https://ieeexplore.ieee.org/document/488968) — Landmark swarm-intelligence optimizer.
- [Differential Evolution](https://link.springer.com/article/10.1023/A:1008202821328) — Efficient evolutionary global optimization method.
- [NEAT](https://nn.cs.utexas.edu/?stanley:ec02) — Neuroevolution approach that evolves structure and weights.
- [AlphaGo](https://www.nature.com/articles/nature16961) — Combined deep learning with search to surpass top human play.

## 🔗 Paper → Code Mapping

| Paper | Official / Best Implementation |
|---|---|
| [A*](https://ieeexplore.ieee.org/document/4082128) | [NetworkX shortest paths](https://networkx.org/documentation/stable/reference/algorithms/shortest_paths.html) |
| [Random Forests](https://link.springer.com/article/10.1023/A:1010933404324) | [scikit-learn RandomForest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html) |
| [Transformer](https://arxiv.org/abs/1706.03762) | [Hugging Face Transformers](https://github.com/huggingface/transformers) |
| [BERT](https://arxiv.org/abs/1810.04805) | [google-research/bert](https://github.com/google-research/bert) |
| [GPT-style models (GPT-3 reference)](https://arxiv.org/abs/2005.14165) | [nanoGPT](https://github.com/karpathy/nanoGPT) |
| [Differential Evolution](https://link.springer.com/article/10.1023/A:1008202821328) | [SciPy differential_evolution](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.differential_evolution.html) |
| [PSO](https://ieeexplore.ieee.org/document/488968) | [PySwarms](https://github.com/ljvmiranda921/pyswarms) |

## 🧰 Libraries & Frameworks

- [PyTorch](https://github.com/pytorch/pytorch) — Core deep learning framework.
- [TensorFlow](https://github.com/tensorflow/tensorflow) — End-to-end ML ecosystem for training/serving.
- [scikit-learn](https://github.com/scikit-learn/scikit-learn) — Standard toolkit for classical ML.
- [JAX](https://github.com/jax-ml/jax) — Accelerator-friendly numerical computing and autodiff.
- [Keras](https://github.com/keras-team/keras) — High-level deep learning API.
- [DEAP](https://github.com/DEAP/deap) — Evolutionary computation framework.
- [PySwarms](https://github.com/ljvmiranda921/pyswarms) — Practical swarm optimization library.

## 📊 Datasets

- [UCI ML Repository](https://archive.ics.uci.edu/) — Canonical tabular benchmark archive.
- [OpenML](https://www.openml.org/) — Open datasets/tasks with reproducible experiment tracking.
- [ImageNet](https://www.image-net.org/) — Foundational vision benchmark.
- [COCO](https://cocodataset.org/) — Detection and segmentation benchmark.
- [Common Crawl](https://commoncrawl.org/) — Large web corpus for language pretraining.
- [MIMIC-IV](https://physionet.org/content/mimiciv/) — Public clinical dataset for healthcare AI research.

## 🎓 Courses

- [MIT 6.034 Artificial Intelligence](https://ocw.mit.edu/courses/6-034-artificial-intelligence-fall-2010/) — Strong classical AI foundation.
- [Stanford CS221](https://stanford-cs221.github.io/) — Broad AI course covering search, MDPs, and probability.
- [Stanford CS229](https://cs229.stanford.edu/) — Rigorous machine learning course.
- [Fast.ai](https://course.fast.ai/) — Practical applied ML and deep learning track.

## 🧪 Experiments (Actionable)

- **Hybrid AI system:** Combine symbolic constraints with neural classifiers and compare failure modes.
- **Optimizer bakeoff:** Benchmark PSO, DE, CMA-ES, and Bayesian optimization on shared black-box objectives.
- **Foundation baseline study:** Compare frozen embeddings + linear probes vs end-to-end fine-tuning.
- **Calibration study:** Evaluate ECE/Brier calibration under distribution shift and retraining frequency.

## 🏗 AI/CI System Design (IMPORTANT)

- **Model routing:** Use fast baseline models for easy cases and expensive models for hard cases.
- **Human-in-the-loop gates:** Add review checkpoints when uncertainty/risk exceeds thresholds.
- **Lifecycle governance:** Enforce dataset versioning, model cards, and rollback-ready release management.

## ⚙️ AI Infra / Serving (DevOps angle)

- [Ray](https://github.com/ray-project/ray) — Distributed execution framework for AI workloads.
- [MLflow](https://github.com/mlflow/mlflow) — Experiment tracking and model registry.
- [Kubeflow](https://www.kubeflow.org/) — Kubernetes-native ML pipeline orchestration.
- [ONNX Runtime](https://github.com/microsoft/onnxruntime) — Portable high-performance inference.

## 🧩 Use Cases

- **Decision intelligence:** Forecasting, planning, and optimization for operations.
- **Autonomous systems:** Perception + planning + control loops.
- **Healthcare AI:** Risk scoring and clinical support under audit constraints.
- **Financial AI:** Fraud/risk modeling with explainability and compliance requirements.

## 📈 Evaluation Metrics

- **Accuracy / F1 / AUROC** — Core supervised learning metrics.
- **ECE / Brier score** — Calibration and probabilistic reliability.
- **Latency / throughput / cost** — Production efficiency metrics.
- **Constraint violation rate** — Safety/compliance quality signal.

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

- [Weights & Biases](https://wandb.ai/site) — Experiment tracking and collaboration.
- [DVC](https://github.com/iterative/dvc) — Data/model versioning.
- [Great Expectations](https://github.com/great-expectations/great_expectations) — Data quality validation.
- [SHAP](https://github.com/shap/shap) — Explainability via feature attributions.

## 🧾 Awesome AI/CI Collections

- [awesome-ai-awesomeness](https://github.com/amusi/awesome-ai-awesomeness) — Broad curated AI papers and resources.
- [josephmisiti/awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning) — Widely used ML tooling/resource directory.
- [owainlewis/awesome-artificial-intelligence](https://github.com/owainlewis/awesome-artificial-intelligence) — Classic AI resource collection.

## 📝 Blogs / Learning Resources

- [Distill](https://distill.pub/) — Visual explainers for deep learning and AI.
- [The Gradient](https://thegradient.pub/) — Research-grounded AI analysis.
- [DeepMind Publications](https://deepmind.google/research/publications/) — Primary source for frontier AI research.

## 📊 Benchmarks

- [MMLU](https://arxiv.org/abs/2009.03300) — Broad multitask benchmark for knowledge/reasoning.
- [HELM](https://crfm.stanford.edu/helm/) — Holistic benchmark for robustness and reliability.
- [ImageNet](https://paperswithcode.com/sota/image-classification-on-imagenet) — Canonical vision benchmark.
- [GLUE](https://gluebenchmark.com/) — Core NLP language understanding benchmark.

## ✍️ Shivam’s Notes (Insight Section)

- Start with the simplest reliable model that meets constraints, then scale after error analysis.
- Production AI failures are often data/monitoring failures more than architecture failures.
- In high-risk domains, calibrated uncertainty and fallback policies matter more than marginal benchmark gains.

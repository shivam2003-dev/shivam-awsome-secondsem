# Shivam Awesome Artificial & Computational Intelligence

A curated roadmap of papers, libraries, datasets, courses, tools, projects, blogs, and benchmarks for Artificial Intelligence (AI) and Computational Intelligence (CI).

## 🚀 Start Here (Beginner → Advanced path)

1. **Core AI foundations:** Learn search, logic, probabilistic reasoning, and planning from [AIMA](https://aima.cs.berkeley.edu/).
2. **Machine learning fundamentals:** Build intuition with [Pattern Recognition and Machine Learning](https://link.springer.com/book/10.1007/978-0-387-45528-0) and [Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/).
3. **Deep learning era:** Study [Deep Learning](https://www.deeplearningbook.org/), [AlexNet](https://dl.acm.org/doi/10.1145/3065386), and [ResNet](https://arxiv.org/abs/1512.03385).
4. **Modern foundation models:** Read [Transformer](https://arxiv.org/abs/1706.03762), [BERT](https://arxiv.org/abs/1810.04805), [GPT-3](https://arxiv.org/abs/2005.14165), and [CLIP](https://arxiv.org/abs/2103.00020).
5. **Computational intelligence methods:** Explore [Particle Swarm Optimization](https://ieeexplore.ieee.org/document/488968), [Differential Evolution](https://link.springer.com/article/10.1023/A:1008202821328), and [NEAT](https://nn.cs.utexas.edu/?stanley:ec02).
6. **Responsible deployment:** Learn evaluation and safety with [HELM](https://crfm.stanford.edu/helm/) and [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework).

## 📄 Papers (with links + 1-line why it matters)

- [Computing Machinery and Intelligence](https://www.csee.umbc.edu/courses/471/papers/turing.pdf) — Classic paper that framed machine intelligence as an operational question.
- [A Proposal for the Dartmouth Summer Research Project on Artificial Intelligence](http://jmc.stanford.edu/articles/dartmouth/dartmouth.pdf) — Foundational document that named and launched AI as a field.
- [A Formal Basis for the Heuristic Determination of Minimum Cost Paths (A*)](https://ieeexplore.ieee.org/document/4082128) — Introduced A* search, a cornerstone of classical AI planning.
- [Probabilistic Reasoning in Intelligent Systems](https://www.sciencedirect.com/book/9780080514895/probabilistic-reasoning-in-intelligent-systems) — Established Bayesian networks for uncertain reasoning.
- [Learning representations by back-propagating errors](https://www.nature.com/articles/323533a0) — Popularized backpropagation for neural network training.
- [ImageNet Classification with Deep Convolutional Neural Networks (AlexNet)](https://dl.acm.org/doi/10.1145/3065386) — Sparked modern deep learning adoption at scale.
- [Deep Residual Learning for Image Recognition (ResNet)](https://arxiv.org/abs/1512.03385) — Enabled training much deeper and more accurate neural models.
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) — Introduced transformer architectures that power modern AI systems.
- [BERT: Pre-training of Deep Bidirectional Transformers](https://arxiv.org/abs/1810.04805) — Made transfer learning dominant in NLP via bidirectional pretraining.
- [Language Models are Few-Shot Learners (GPT-3)](https://arxiv.org/abs/2005.14165) — Demonstrated powerful in-context learning in large language models.
- [Learning Transferable Visual Models From Natural Language Supervision (CLIP)](https://arxiv.org/abs/2103.00020) — Unified vision-language alignment for zero-shot transfer.
- [Particle Swarm Optimization](https://ieeexplore.ieee.org/document/488968) — Landmark swarm-intelligence optimizer inspired by social behavior.
- [Differential Evolution – A Simple and Efficient Heuristic for Global Optimization](https://link.springer.com/article/10.1023/A:1008202821328) — Influential evolutionary strategy for continuous optimization.
- [Neuroevolution of Augmenting Topologies (NEAT)](https://nn.cs.utexas.edu/?stanley:ec02) — Evolved both network weights and topologies for adaptive learning.
- [Random Forests](https://link.springer.com/article/10.1023/A:1010933404324) — Robust ensemble method widely used for tabular AI tasks.

## 🧰 Libraries & Frameworks

- [PyTorch](https://github.com/pytorch/pytorch) — Core framework for deep learning and research prototyping.
- [TensorFlow](https://github.com/tensorflow/tensorflow) — Production-grade ecosystem for large-scale AI training/inference.
- [scikit-learn](https://github.com/scikit-learn/scikit-learn) — Standard machine learning toolkit for classical AI methods.
- [JAX](https://github.com/jax-ml/jax) — High-performance numerical computing with composable autodiff.
- [Keras](https://github.com/keras-team/keras) — High-level API for rapid deep learning experimentation.
- [DEAP](https://github.com/DEAP/deap) — Evolutionary computation framework for genetic and swarm algorithms.
- [PySwarms](https://github.com/ljvmiranda921/pyswarms) — Particle swarm optimization toolkit in Python.

## 📊 Datasets

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/) — Foundational dataset archive for classical AI/ML benchmarks.
- [OpenML](https://www.openml.org/) — Open platform for datasets, tasks, and reproducible experiments.
- [ImageNet](https://www.image-net.org/) — Canonical large-scale visual recognition dataset.
- [COCO](https://cocodataset.org/) — Standard benchmark for detection and segmentation tasks.
- [Common Crawl](https://commoncrawl.org/) — Massive web corpus used for large-model pretraining.
- [MIMIC-IV](https://physionet.org/content/mimiciv/) — Public clinical dataset for healthcare AI research.

## 🎓 Courses

- [MIT 6.034 Artificial Intelligence](https://ocw.mit.edu/courses/6-034-artificial-intelligence-fall-2010/) — Classic course on search, reasoning, and knowledge-based AI.
- [Stanford CS221: Artificial Intelligence: Principles and Techniques](https://stanford-cs221.github.io/autumn2025/) — Broad AI course covering core paradigms and modern methods.
- [Stanford CS229: Machine Learning](https://cs229.stanford.edu/) — Rigorous treatment of supervised and unsupervised ML.
- [DeepLearning.AI Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction) — Practical modern ML track for beginners to intermediates.

## 🛠 Tools / Ecosystem

- [Weights & Biases](https://wandb.ai/site) — Experiment tracking and model lifecycle management.
- [MLflow](https://github.com/mlflow/mlflow) — Open-source platform for tracking, packaging, and deployment.
- [DVC](https://github.com/iterative/dvc) — Data/model versioning for reproducible AI pipelines.
- [Ray](https://github.com/ray-project/ray) — Distributed compute framework for scalable AI workloads.
- [ONNX](https://github.com/onnx/onnx) — Interoperability format for cross-framework model deployment.

## 🧪 Projects / Ideas

- Build a hybrid AI system combining symbolic rules with neural classifiers.
- Compare classical ML baselines vs deep models on UCI tabular datasets.
- Implement and benchmark PSO, DE, and GA on the same optimization suite.
- Create an AutoML workflow with reproducible tracking and model registry.
- Build a multimodal classifier by combining image and text embeddings.
- Reproduce a benchmark with strict seed control and ablation reporting.
- Develop an explainability dashboard using SHAP-like feature attributions.
- Create a responsible-AI checklist and audit report for a deployed model.

## 📝 Blogs / Learning Resources

- [Distill](https://distill.pub/) — High-quality visual and conceptual deep learning explainers.
- [The Gradient](https://thegradient.pub/) — Accessible expert commentary on AI research trends.
- [Google AI Blog](https://research.google/blog/) — Updates on research and production AI systems.
- [OpenAI Research](https://openai.com/research/) — Frontier model research and technical reports.
- [DeepMind Publications](https://deepmind.google/research/publications/) — Primary source for leading AI papers.

## 📈 Benchmarks

- [GLUE](https://gluebenchmark.com/) — Widely used benchmark suite for language understanding.
- [MMLU](https://arxiv.org/abs/2009.03300) — Broad multitask benchmark for model knowledge and reasoning.
- [HELM](https://crfm.stanford.edu/helm/) — Holistic language model evaluation across scenarios and metrics.
- [ImageNet Benchmark](https://paperswithcode.com/sota/image-classification-on-imagenet) — Standard benchmark for image classification progress.
- [COCO Object Detection](https://paperswithcode.com/sota/object-detection-on-coco) — Core benchmark for object detection performance.

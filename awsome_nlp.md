# Shivam Awesome NLP

A curated, practical roadmap of papers, libraries, datasets, courses, and tools for modern Natural Language Processing.

## 🚀 Start Here (Beginner → Advanced path)

1. **Foundations:** Learn tokenization, embeddings, and sequence modeling with [spaCy 101](https://spacy.io/usage/spacy-101) and [NLTK Book](https://www.nltk.org/book/).
2. **Transformers core:** Study [Attention Is All You Need](https://arxiv.org/abs/1706.03762) and implement with [Hugging Face Transformers](https://github.com/huggingface/transformers).
3. **Representation learning:** Read [BERT](https://arxiv.org/abs/1810.04805), [RoBERTa](https://arxiv.org/abs/1907.11692), and [T5](https://arxiv.org/abs/1910.10683).
4. **Scaling era:** Understand [GPT-3](https://arxiv.org/abs/2005.14165), [LLaMA](https://arxiv.org/abs/2302.13971), and instruction tuning via [FLAN](https://arxiv.org/abs/2210.11416).
5. **Build systems:** Practice RAG, evaluation, and deployment using [LangChain](https://github.com/langchain-ai/langchain), [LlamaIndex](https://github.com/run-llama/llama_index), and [Haystack](https://github.com/deepset-ai/haystack).
6. **Evaluate rigorously:** Benchmark with [GLUE](https://gluebenchmark.com/), [HELM](https://crfm.stanford.edu/helm/), and [MMLU](https://arxiv.org/abs/2009.03300).

## 📄 Papers (with links + 1-line why it matters)

- [Attention Is All You Need (Transformer)](https://arxiv.org/abs/1706.03762) — Introduced self-attention architecture that became the backbone of modern NLP.
- [BERT: Pre-training of Deep Bidirectional Transformers](https://arxiv.org/abs/1810.04805) — Established bidirectional pretraining + fine-tuning as a dominant paradigm.
- [Improving Language Understanding by Generative Pre-Training (GPT-1)](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf) — Demonstrated generative pretraining for transferable NLP features.
- [Language Models are Unsupervised Multitask Learners (GPT-2)](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) — Showed large-scale zero-shot behavior from pure next-token prediction.
- [Language Models are Few-Shot Learners (GPT-3)](https://arxiv.org/abs/2005.14165) — Popularized in-context learning and scaling laws in practice.
- [GPT-4 Technical Report](https://arxiv.org/abs/2303.08774) — Documented capabilities and safety considerations of frontier multimodal LLMs.
- [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer (T5)](https://arxiv.org/abs/1910.10683) — Unified many NLP tasks under a single text-to-text framework.
- [LLaMA: Open and Efficient Foundation Language Models](https://arxiv.org/abs/2302.13971) — Brought strong open-weight foundation models to the research community.
- [Llama 2: Open Foundation and Fine-Tuned Chat Models](https://arxiv.org/abs/2307.09288) — Advanced open LLM quality with transparent training and safety details.
- [RoBERTa: A Robustly Optimized BERT Pretraining Approach](https://arxiv.org/abs/1907.11692) — Showed that BERT gains substantially from better training recipes.
- [XLNet: Generalized Autoregressive Pretraining for Language Understanding](https://arxiv.org/abs/1906.08237) — Proposed permutation language modeling to improve contextual pretraining.
- [GloVe: Global Vectors for Word Representation](https://aclanthology.org/D14-1162/) — Delivered efficient and interpretable static word embeddings.
- [Efficient Estimation of Word Representations in Vector Space (word2vec)](https://arxiv.org/abs/1301.3781) — Introduced scalable neural word embeddings widely used across NLP.
- [Sequence to Sequence Learning with Neural Networks](https://arxiv.org/abs/1409.3215) — Made end-to-end neural machine translation practical.
- [BLEU: a Method for Automatic Evaluation of Machine Translation](https://aclanthology.org/P02-1040/) — Defined a standard automatic metric still used for generation evaluation.

## 🧰 Libraries & Frameworks

- [Hugging Face Transformers](https://github.com/huggingface/transformers) — State-of-the-art pretrained models and training utilities.
- [spaCy](https://github.com/explosion/spaCy) — Industrial-strength NLP pipeline library for production use.
- [NLTK](https://github.com/nltk/nltk) — Classic educational toolkit covering core NLP algorithms.
- [fairseq](https://github.com/facebookresearch/fairseq) — Sequence modeling toolkit for translation, summarization, and language modeling.
- [OpenNMT](https://github.com/OpenNMT/OpenNMT-py) — Open-source neural machine translation framework.

## 📊 Datasets

- [GLUE](https://gluebenchmark.com/) — Multi-task benchmark suite for general language understanding.
- [SuperGLUE](https://super.gluebenchmark.com/) — More challenging successor benchmark for advanced NLU models.
- [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/) — Canonical reading comprehension dataset for extractive QA.
- [Common Crawl](https://commoncrawl.org/) — Massive web crawl corpus used for pretraining foundation models.
- [WikiText](https://github.com/salesforce/awd-lstm-lm) — High-quality Wikipedia language modeling corpus (WikiText-2/103).

## 🎓 Courses

- [Stanford CS224n: Natural Language Processing with Deep Learning](https://web.stanford.edu/class/cs224n/) — Flagship academic course on modern deep NLP.
- [Hugging Face Course](https://huggingface.co/learn/nlp-course/chapter1/1) — Hands-on transformer and LLM training/deployment course.
- [fast.ai Practical Deep Learning (NLP lessons)](https://course.fast.ai/) — Practical top-down deep learning with strong NLP coverage.

## 🛠 Tools / Ecosystem

- [LangChain](https://github.com/langchain-ai/langchain) — Framework for building LLM applications and agentic workflows.
- [LlamaIndex](https://github.com/run-llama/llama_index) — Data framework for RAG pipelines and retrieval orchestration.
- [Haystack](https://github.com/deepset-ai/haystack) — End-to-end framework for search, QA, and RAG systems.
- [OpenAI Platform](https://platform.openai.com/docs/overview) — API platform and documentation for production-grade model integration.

## 🧪 Projects / Ideas

- Build a domain-specific RAG assistant over PDFs, emails, and internal docs.
- Reproduce GLUE/SuperGLUE fine-tuning baselines across model scales.
- Train a compact summarization model and compare ROUGE vs human preference.
- Create multilingual sentiment analysis with zero-shot transfer and calibration.
- Implement a hallucination detection pipeline with retrieval-grounded checks.
- Build a benchmark dashboard tracking latency, cost, and quality across LLMs.
- Fine-tune instruction models with synthetic data and evaluate generalization.
- Develop an evaluation harness for jailbreak robustness and safety regression.

## 📝 Blogs / Learning Resources

- [Jay Alammar (The Illustrated Transformer)](https://jalammar.github.io/illustrated-transformer/) — Visual, intuitive explanations of transformer internals.
- [Sebastian Ruder Blog](https://ruder.io/) — Deep dives on transfer learning and multilingual NLP.
- [Lil'Log (Lilian Weng)](https://lilianweng.github.io/) — High-quality long-form posts on LLMs and alignment.
- [Hugging Face Blog](https://huggingface.co/blog) — Practical updates, tutorials, and model announcements.
- [The Gradient](https://thegradient.pub/) — Research-grounded explainers on modern ML/NLP trends.

## 📈 Benchmarks

- [GLUE Benchmark](https://gluebenchmark.com/) — Standard NLU benchmark suite for model comparison.
- [HELM (Holistic Evaluation of Language Models)](https://crfm.stanford.edu/helm/) — Multi-metric, scenario-based benchmark for broad LLM evaluation.
- [MMLU (Massive Multitask Language Understanding)](https://arxiv.org/abs/2009.03300) — Knowledge-heavy multi-domain benchmark for zero/few-shot ability.

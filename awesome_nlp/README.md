# Shivam Awesome NLP

A curated, practical, and engineer-friendly map of modern NLP research, tooling, and production systems.

## 🧭 Learning Path (Beginner → Advanced)

1. **NLP foundations:** Learn tokenization, lemmatization, parsing, and core pipelines with [spaCy 101](https://spacy.io/usage/spacy-101) and the [NLTK Book](https://www.nltk.org/book/).
2. **Transformer fundamentals:** Read [Attention Is All You Need](https://arxiv.org/abs/1706.03762) and implement pretrained models with [Hugging Face Transformers](https://github.com/huggingface/transformers).
3. **Pretraining paradigms:** Study [BERT](https://arxiv.org/abs/1810.04805), [RoBERTa](https://arxiv.org/abs/1907.11692), [GPT-3](https://arxiv.org/abs/2005.14165), and [T5](https://arxiv.org/abs/1910.10683).
4. **Open foundation models:** Understand efficient open LLM design through [LLaMA](https://arxiv.org/abs/2302.13971), [Llama 2](https://arxiv.org/abs/2307.09288), and [Mistral 7B](https://arxiv.org/abs/2310.06825).
5. **Task adaptation:** Fine-tune models on [GLUE](https://gluebenchmark.com/), [SuperGLUE](https://super.gluebenchmark.com/), and [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/).
6. **Retrieval-era NLP:** Build RAG pipelines with [LangChain](https://github.com/langchain-ai/langchain), [LlamaIndex](https://github.com/run-llama/llama_index), and [Haystack](https://github.com/deepset-ai/haystack).
7. **Production & evaluation:** Deploy with [vLLM](https://github.com/vllm-project/vllm) or [TGI](https://github.com/huggingface/text-generation-inference) and evaluate with [HELM](https://crfm.stanford.edu/helm/) and [MMLU](https://arxiv.org/abs/2009.03300).

## 📄 Papers (with links + 1-line insight)

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) — Introduced self-attention as the core architecture for scalable sequence modeling.
- [BERT](https://arxiv.org/abs/1810.04805) — Established bidirectional masked-language pretraining for strong NLU transfer.
- [RoBERTa](https://arxiv.org/abs/1907.11692) — Showed training recipe improvements significantly boost BERT-style models.
- [ALBERT](https://arxiv.org/abs/1909.11942) — Reduced parameters via sharing while preserving language understanding quality.
- [GPT-3](https://arxiv.org/abs/2005.14165) — Demonstrated emergent in-context learning at scale.
- [InstructGPT](https://arxiv.org/abs/2203.02155) — Aligned LMs with human preferences using RLHF.
- [T5](https://arxiv.org/abs/1910.10683) — Unified diverse NLP tasks under a single text-to-text objective.
- [UL2](https://arxiv.org/abs/2205.05131) — Proposed mixture-of-denoisers objective for stronger universal language modeling.
- [LLaMA](https://arxiv.org/abs/2302.13971) — Showed high-quality open foundation models with compute-efficient training.
- [Llama 2](https://arxiv.org/abs/2307.09288) — Advanced open-weight chat and base models with strong public documentation.
- [Mistral 7B](https://arxiv.org/abs/2310.06825) — Delivered strong quality/efficiency trade-offs via grouped-query attention and sliding windows.
- [RAG](https://arxiv.org/abs/2005.11401) — Combined parametric generation with non-parametric retrieval for knowledge-intensive tasks.

## 🔗 Paper → Code Mapping

| Paper | Official / Best Implementation |
|---|---|
| [Attention Is All You Need](https://arxiv.org/abs/1706.03762) | [The Annotated Transformer (Harvard NLP)](https://nlp.seas.harvard.edu/annotated-transformer/) |
| [BERT](https://arxiv.org/abs/1810.04805) | [google-research/bert](https://github.com/google-research/bert) |
| [RoBERTa](https://arxiv.org/abs/1907.11692) | [fairseq RoBERTa](https://github.com/facebookresearch/fairseq/tree/main/examples/roberta) |
| [GPT-style models (GPT-3 paper)](https://arxiv.org/abs/2005.14165) | [nanoGPT](https://github.com/karpathy/nanoGPT) |
| [T5](https://arxiv.org/abs/1910.10683) | [google-research/text-to-text-transfer-transformer](https://github.com/google-research/text-to-text-transfer-transformer) |
| [LLaMA](https://arxiv.org/abs/2302.13971) | [meta-llama/llama](https://github.com/meta-llama/llama) |
| [RAG](https://arxiv.org/abs/2005.11401) | [Hugging Face RAG docs](https://huggingface.co/docs/transformers/model_doc/rag) |

## 🧰 Libraries & Frameworks

- [Hugging Face Transformers](https://github.com/huggingface/transformers) — Standard library for pretrained transformer models and training APIs.
- [spaCy](https://github.com/explosion/spaCy) — Production-grade NLP pipelines for tokenization, tagging, parsing, and NER.
- [NLTK](https://github.com/nltk/nltk) — Foundational educational toolkit with classic NLP algorithms and corpora.
- [fairseq](https://github.com/facebookresearch/fairseq) — Research framework for sequence modeling, translation, and language generation.
- [OpenNMT](https://github.com/OpenNMT/OpenNMT-py) — Mature open-source framework for neural machine translation workflows.
- [Sentence-Transformers](https://github.com/UKPLab/sentence-transformers) — High-quality embedding models for retrieval and semantic search.
- [Flair](https://github.com/flairNLP/flair) — Simple framework for sequence labeling and text classification.

## 📊 Datasets

- [GLUE](https://gluebenchmark.com/) — Core multi-task benchmark for sentence-level language understanding.
- [SuperGLUE](https://super.gluebenchmark.com/) — Harder NLU benchmark that stresses reasoning and sample efficiency.
- [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/) — Canonical extractive QA dataset for context-grounded answering.
- [Common Crawl](https://commoncrawl.org/) — Web-scale corpus used for large-language-model pretraining pipelines.
- [WikiText](https://blog.salesforceairesearch.com/the-wikitext-long-term-dependency-language-modeling-dataset/) — High-quality Wikipedia corpus for language-modeling experiments.
- [The Pile](https://pile.eleuther.ai/) — Large diverse text corpus widely used for open LLM pretraining.
- [WikiText-103 on HF](https://huggingface.co/datasets/Salesforce/wikitext) — Convenient hosted version for benchmarking and prototyping.

## 🎓 Courses

- [Stanford CS224n](https://web.stanford.edu/class/cs224n/) — Flagship academic course on deep learning approaches to NLP.
- [Hugging Face Course](https://huggingface.co/learn/nlp-course/chapter1/1) — Practical, code-first course for transformers and LLM workflows.
- [fast.ai Practical Deep Learning](https://course.fast.ai/) — Applied deep learning course with strong NLP transfer-learning modules.
- [CMU Neural Nets for NLP](http://phontron.com/class/nn4nlp2021/) — Strong research-focused neural NLP course.

## 🧪 Experiments (Actionable)

- **Fine-tune BERT:** Fine-tune `bert-base-uncased` on MRPC and SST-2, then compare full fine-tuning vs LoRA.
- **Build a RAG system:** Index technical docs with FAISS and compare dense retrieval vs hybrid BM25+dense.
- **Train a tokenizer:** Train BPE vs Unigram tokenizers on your domain corpus and compare perplexity and latency.
- **Prompt-vs-tuning study:** Compare instruction prompting, soft prompts, and full SFT on one domain task.

## 🏗 NLP System Design (IMPORTANT)

- **RAG (Retriever + Generator):** Tune retriever recall/precision first, then optimize generator faithfulness and citations.
- **Embeddings + Vector DB:** Generate embeddings, store in [FAISS](https://github.com/facebookresearch/faiss), and enforce chunk/version policies.
- **LLM serving architecture:** Separate offline indexing/training from low-latency online inference with autoscaling boundaries.

## ⚙️ NLP Infra / Serving (DevOps angle)

- [vLLM](https://github.com/vllm-project/vllm) — High-throughput LLM serving with efficient KV cache and continuous batching.
- [Hugging Face TGI](https://github.com/huggingface/text-generation-inference) — Production text-generation server with optimized inference backends.
- [NVIDIA Triton Inference Server](https://github.com/triton-inference-server/server) — Multi-framework inference platform for GPU-backed serving.
- [Ray Serve](https://docs.ray.io/en/latest/serve/index.html) — Python-native scalable model serving for online NLP and LLM endpoints.
- [llama.cpp](https://github.com/ggerganov/llama.cpp) — Efficient CPU/GPU local inference for GGUF-compatible models.

## 🧩 Use Cases

- **Chatbots:** Multi-turn assistants with retrieval grounding, memory policies, and safety filters.
- **Search:** Semantic and hybrid search stacks combining BM25 with embedding retrieval.
- **Summarization:** Long-document abstractive summarization with controllable length and citation constraints.
- **Translation:** Domain-adapted NMT with terminology control and quality estimation.
- **Classification:** Multi-label content tagging and moderation pipelines at scale.

## 📈 Evaluation Metrics

- [BLEU](https://aclanthology.org/P02-1040/) — N-gram precision metric commonly used for machine translation quality.
- [ROUGE](https://aclanthology.org/W04-1013/) — N-gram overlap recall metric for summarization evaluation.
- [Perplexity](https://huggingface.co/docs/transformers/en/perplexity) — Intrinsic language-model quality metric based on token likelihood.
- [F1 / Exact Match (SQuAD)](https://rajpurkar.github.io/SQuAD-explorer/) — Standard pair of QA metrics for overlap and exact correctness.
- [BERTScore](https://arxiv.org/abs/1904.09675) — Semantic similarity metric aligned better with human judgments than lexical overlap.

## 🛠 Tools / Ecosystem

- [LangChain](https://github.com/langchain-ai/langchain) — Framework for orchestrating LLM chains, tools, and retrieval workflows.
- [LlamaIndex](https://github.com/run-llama/llama_index) — Data framework for retrieval and agent pipelines over private corpora.
- [Haystack](https://github.com/deepset-ai/haystack) — Open framework for production RAG, search, and QA systems.
- [OpenAI Evals](https://github.com/openai/evals) — Framework for evaluating LLM behavior on custom benchmarks.

## 🧾 Awesome NLP Collections

- [jondurbin/awesome-nlp](https://github.com/jondurbin/awesome-nlp) — Broad curated NLP resources and model/tool links.
- [Keon/awesome-nlp](https://github.com/keon/awesome-nlp) — Practical NLP papers, tutorials, and tooling collection.
- [SebastianRuder/NLP-progress](https://github.com/sebastianruder/NLP-progress) — Task-wise NLP SOTA tracking with paper/code references.

## 📝 Blogs / Learning Resources

- [Jay Alammar](https://jalammar.github.io/) — Visual, intuitive breakdowns of transformer and embedding concepts.
- [Sebastian Ruder](https://ruder.io/) — Strong research-oriented posts on transfer learning and multilingual NLP.
- [Lilian Weng](https://lilianweng.github.io/) — Deep technical essays on LLMs, agents, and alignment.
- [Hugging Face Blog](https://huggingface.co/blog) — Practical engineering tutorials and model release explainers.

## 📊 Benchmarks

- [GLUE](https://gluebenchmark.com/) — Foundational benchmark for broad NLU progress tracking.
- [HELM](https://crfm.stanford.edu/helm/) — Holistic benchmark covering accuracy, calibration, and robustness scenarios.
- [MMLU](https://arxiv.org/abs/2009.03300) — Broad multitask benchmark for zero-shot/few-shot knowledge evaluation.
- [BIG-bench](https://github.com/google/BIG-bench) — Diverse benchmark suite for broad language model capabilities.

## ✍️ Shivam’s Notes (Insight Section)

- Prefer **RAG over fine-tuning** when facts change frequently or provenance/citations are mandatory.
- Prefer **fine-tuning over RAG** when style, output format, or behavior consistency is the main requirement.
- Retrieval quality usually drives more end-user gains than switching to a larger generator model.
- Offline benchmark wins do not guarantee production wins without latency, cost, and drift monitoring.

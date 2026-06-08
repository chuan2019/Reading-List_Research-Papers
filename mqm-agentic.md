# Recent Research Papers on Agentic Machine Translation Evaluation

This is a set of recent research papers directly relevant to improving an LLM-based MQM subtitle-error-detection workflow.


- T. Kocmi, and C. Federmann (2023) _GEMBA-MQM: Detecting translation quality error spans with GPT-4_ In _Proceedings of the Eighth Conference on Machine Translation_, [pages 768-775](https://aclanthology.org/2023.wmt-1.64/), Singapore. Association for Computational Linguistics


## Better prompting/decomposition of MQM itself

### AutoMQM (the prompting technique behind the GEMBA-MQM line)

Instead of asking for a single quality score, it prompts the LLM to find and classify spans of error by MQM category (accuracy, fluency, style, terminology, etc.), which is essentially the structure you're already using. Notably, researchers found it "performs unexpectedly poorly when applied to colloquial subtitle translation tasks" — worth reading closely since it names your exact pain point.

- P. Fernandes, et. al. (2023) _The Devil is in the Errors: Leveraging Large Language Models for Fine-grained Machine Translation Evaluation_ [arXiv2308.07286](https://arxiv.org/pdf/2308.07286)
- M. Stasimioti (2023) _Top Language AI Researchers Propose New Way to Auto-Evaluate Machine Translation_ [Slator's writeup](https://slator.com/top-language-ai-researchers-propose-new-way-auto-evaluate-machine-translation/)

## Filtering noise/improving precision of flagged errors

### MQM-APE

A training-free trick: after the LLM flags an error, it automatically post-edits the translation based on that error and keeps only the errors whose removal actually improves quality. This filters out "errors" that don't matter, directly addressing the common LLM-judge problem of over-flagging.

- Q. Lu, et. al. (2024) _MQM-APE: Toward High-Quality Error Annotation Predictors with Automatic Post-Editing in LLM Translation Evaluators_ [arXiv2409.14335](https://arxiv.org/pdf/2409.14335)

## Multi-agent/debate architectures (most relevant if you want to evolve beyond single-pass LLM evaluation)

### M-MAD

Splits MQM into separate dimensions (accuracy, fluency, style, terminology), assigns each to its own agent, runs multi-agent debate per dimension, then synthesizes a final judgment. Outperforms single-LLM-judge baselines even with a weaker base model — suggesting the architecture matters more than raw model power. This maps very cleanly onto an MQM-categorized workflow like yours.

- Z. Feng, et. al. (2025) _M-MAD: Multidimensional Multi-Agent Debate for Advanced Machine Translation Evaluation_ [arXiv2412.20127](https://arxiv.org/pdf/2412.20127)

### HiMATE

Builds agent topology directly from the MQM error typology hierarchy, with agents exchanging information across levels (category → subcategory → instance).

- S. Zhang, et. al. (2025) _HiMATE: A Hierarchical Multi-Agent Framework for Machine Translation Evaluation_ [arXiv2505.16281](https://arxiv.org/pdf/2505.16281)

## Subtitle/creative-text-specific

### From Utterance to Vividity

Focused on what makes subtitle translation different from standard MT (tone, emotion, fluidity, "vividness"), useful for thinking about which MQM dimensions deserve more weight for subtitles versus, say, technical translation.

- C. Cui, et. al. (2026) _From Utterance to Vividity: Training Expressive Subtitle Translation LLM via Adaptive Local Preference Optimization_ [arXiv2602.01068v1](https://arxiv.org/pdf/2602.01068v1)

### SAMAS

Though aimed at literary translation, its style-fidelity-focused multi-agent design could transfer to evaluating tone/register errors in subtitles, a notoriously hard MQM dimension for LLM judges.

- J. Wu, et. al. (2026) _SAMAS: A Spectrum-Guided Multi-Agent System for Achieving Style Fidelity in Literary Translation_ [arXiv2602.19840](https://arxiv.org/pdf/2602.19840)

## Critical-error-focused (for safety-critical mistranslations, e.g. meaning-flipping errors)

### Towards Reliable Machine Translation



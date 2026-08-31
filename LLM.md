# LLM Related References

## Reviews, Surveys, Perspectives
T. Xiao & J. Zhu (2025) _Foundations of Large Language Models_ [arXiv2501.09223](https://arxiv.org/pdf/2501.09223)

## Prompt Engineering

### Automate Prompt Writing

A.L. Zhang, et. al. (2025) _Recursive Language Models_ [arXiv2512.24601](https://arxiv.org/pdf/2512.24601)

L.A. Agrawal, et. al. (2025) _GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning_ [arXiv2507.19457](https://arxiv.org/pdf/2507.19457)

K. Opsahl-Ong, et. al. (2024) _MIPROv2: Optimizing Instructions and Demonstrations for Multi-Stage Language Model Programs_ [arXiv2406.11695](https://arxiv.org/pdf/2406.11695)

M. Yuksekgonul, et. al. (2024) _TextGrad: Automatic "Differentiation" via Text_ [arXiv2406.07496](https://arxiv.org/pdf/2406.07496)

  - J.E. Khoury (2024) _TEXTGRAD vs DSPY: Revolutionizing AI System Optimization through Automatic Text-Based Differentiation_ [medium.com](https://medium.com/@jelkhoury880/textgrad-vs-dspy-revolutionizing-ai-system-optimization-through-automatic-text-based-58f8ee776447)

X. Amatriain (2024) _Prompt Design and Engineering: Introduction and Advanced Methods_ [arXiv2401.14423v4](https://arxiv.org/pdf/2401.14423v4)

O. Khattab, et. al. (2023) _DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines_ [arXiv2310.03714](https://arxiv.org/pdf/2310.03714)

  - W.B. Kennedy (2026) _Automate Writing Your LLM Prompts_ [towardsdatascience.com](https://towardsdatascience.com/automate-writing-your-llm-prompts/)

C. Yang, et. al. (2023) _OPRO: Large Language Models as Optimizers_ [arXiv2309.03409](https://arxiv.org/pdf/2309.03409)

R. Pryzant, et. al. (2023) _Automatic Prompt Optimization with "Gradient Descent" and Beam Search_ [arXiv2305.03495](https://arxiv.org/pdf/2305.03495)

Y. Zhou, et. al. (2023) _**APE**: Large Language Models are Human-Level Prompt Engineers_ [arXiv2211.01910](https://arxiv.org/pdf/2211.01910)

### Prompt Evaluating

C. Shi, et. al. (2024) _Efficient Prompt Optimization Through the Lens of Best Arm Identification_ [arXiv2402.09723](https://arxiv.org/pdf/2402.09723)

  - Efficient NLP (2026) _Stop Wasting Your Eval Budget: Multi-Armed Bandits for Prompt Testing_ [YouTube](https://www.youtube.com/watch?v=14omHDhrx8o)

## KV Cache & Prompt Caching

### Radix Attention

L. Zheng, et. al. (2024) _SGLang: Efficient Execution of Structured Language Model Programs_ [arXiv2312.07104](https://arxiv.org/pdf/2312.07104)

  - L. Zheng, et. al. (2024) _POSTER & Presentation_ [neurips.cc](https://neurips.cc/virtual/2024/poster/94872)

### Prompt Caching Security

C Gu, et. al. (2025) _Auditing Prompt Caching in Language Model APIs_ [arXiv2502.07776](https://arxiv.org/pdf/2502.07776)

## Fine-Tuning LLMs
C. Wu et al. (2025) _Mitigating Fine-tuning Risks in LLMs via Safety-Aware Probing Optimization_ [arXiv2505.16737](https://arxiv.org/html/2505.16737v1)

Q. Zhang et al. (2025) _Agentic Context Engineering: Evolving Contexts for Self-Improving
Language Models_ [arXiv:2510.04618](https://www.arxiv.org/pdf/2510.04618)



## Hallucinations
O. Obeso et al. (2025) _Real-Time Detection of Hallucinated Entities in Long-Form Generation_ [arXiv2509.03531](https://arxiv.org/pdf/2509.03531)

A.T. Kalai et al. (2025) _Why Language Models Hallucinate_ [arXiv2509.04664](https://www.arxiv.org/pdf/2509.04664)

J. Yuan et al. (2025) _Give Me FP32 or Give Me Death?
Challenges and Solutions for Reproducible Reasoning_ [arXiv2506.09501](https://arxiv.org/pdf/2506.09501)

## Model Evaluations
E. Miller (2024) _Adding Error Bars to Evals: A Statistical Approach to Language Model Evaluations_ [arXiv:2411.00640](https://arxiv.org/pdf/2411.00640)
  - _A Statistical Approach to Model Evaluations_ [Anthropic Blog](https://www.anthropic.com/research/statistical-approach-to-model-evals)

[uqlm: Uncertainty Quantification for Language Models](https://github.com/cvs-health/uqlm)




## Memory Management
W. Kwon (2023) _Efficient Memory Management for Large Language Model Serving with PagedAttention_ [arXiv:2309.06180](https://arxiv.org/pdf/2309.06180)

A.L. Zhang et. al. (2025) _Recursive Language Models_ [arXiv:2512.24601](https://arxiv.org/pdf/2512.24601v1)

## Mixture of Agents (MoA) Architecture
J. Wang, et al. (2024) _Mixture-of-Agents Enhances Large Language Model Capabilities_ [arXiv:2406.04692](https://arxiv.org/pdf/2406.04692); Mixture-of-Agents (MoA) [Github Repo](https://github.com/togethercomputer/moa)

## Mixture of Experts (MoE)
W. Cai, et al. (2025) _A Survey on Mixture of Experts in Large Language Models_ **IEEE Transactions on Knowledge and Data Engineering** (TKDE) Vol. 37(7), pp. 3896-3915 [TKDE.2025.3554028](https://ieeexplore.ieee.org/document/10937907), [arXiv:2407.06204](https://arxiv.org/pdf/2407.06204)

N. Shazeer, et al. (2017) _Outrageously Large Neural Networks: the Sparsely-Gated Mixture-of-Experts Layer_ [arXiv:1701.06538](https://arxiv.org/pdf/1701.06538)

R.A. Jacobs, et al. (1991) _Adaptive Mixtures of Local Experts_ **Neural Computation** Vol. 3(1), pp. 79-87 [neco.1991.3.1.79](https://ieeexplore.ieee.org/document/6797059) [jjnh91.pdf](https://www.cs.toronto.edu/~hinton/absps/jjnh91.pdf)

M. Grootendorst (2024) _A Visual Guide to Mixture of Experts (MoE)_ [Exploring Language Models](https://newsletter.maartengrootendorst.com/) [Oct 07, 2024](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-mixture-of-experts)

B. Pandit (2024) _What is Mixture of Experts (MoE)? How it Works, Use Cases & More_ [datacamp.blog](https://www.datacamp.com/blog/mixture-of-experts-moe)



## LLM Foundamentals

Andrew Karpathy (2023) _Let's build GPT: from scratch, in code, spelled out_ [YouTube](https://www.youtube.com/watch?v=kCc8FmEb1nY)

3Blue1Brown (2024) _Large Language Models explained briefly_ [YouTube](https://www.youtube.com/watch?v=LPZh9BOjkQs&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=6)

3Blue1Brown (2024) _Transformers, the tech behind LLMs_ [YouTube](https://www.youtube.com/watch?v=wjZofJX0v4M&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=6)

3Blue1Brown (2024) _Attention in transformers, step-by-step_ [YouTube](https://www.youtube.com/watch?v=eMlx5fFNoYc&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=7)

3Blue1Brown (2024) _How might LLMs store facts_ [YouTube](https://www.youtube.com/watch?v=9-Jl0dxWQs8&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=8)

Efficient NLP (2023) _The KV Cache: Memory Usage in Transformers_ [YouTube](https://www.youtube.com/watch?v=80bIUggRJf4)

Efficient NLP (2026) _Why Agents Recompute the Same Prompt, and How Prompt Caching fixes it_ [YouTube](https://www.youtube.com/watch?v=Q_U4pRggC5I)

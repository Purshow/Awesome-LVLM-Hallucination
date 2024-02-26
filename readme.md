# Awesome LVLM Hallucination

### A nice survey:[A Survey on Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2402.00253)

### Hallucination Benchmarks:

+ **MOCHa (OpenCHAIR)** [MOCHa: Multi-Objective Reinforcement Mitigating Caption Hallucinations](https://arxiv.org/abs/2312.03631) (Dec. 06, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03631)
  [![Star](https://img.shields.io/github/stars/assafbk/mocha_code.svg?style=social&label=Star)](https://github.com/assafbk/mocha_code)

+ **CCEval** [HallE-Switch: Controlling Object Hallucination in Large Vision Language Models](https://arxiv.org/abs/2310.01779v2) (Dec. 03, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.01779v2)
  [![Star](https://img.shields.io/github/stars/bronyayang/HallE_Switch.svg?style=social&label=Star)](https://github.com/bronyayang/HallE_Switch)

+ **HallusionBench** [HallusionBench: An Advanced Diagnostic Suite for Entangled Language Hallucination & Visual Illusion in Large Vision-Language Models](https://arxiv.org/abs/2310.14566) (Nov. 28, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.14566)

+ **HaELM** [Evaluation and Analysis of Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2308.15126) (Oct. 10, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.15126)
  [![Star](https://img.shields.io/github/stars/junyangwang0410/HaELM.svg?style=social&label=Star)](https://github.com/junyangwang0410/HaELM)

+ **NOPE** [Negative Object Presence Evaluation (NOPE) to Measure Object Hallucination in Vision-Language Models](https://arxiv.org/abs/2310.05338) (Oct. 9, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.05338)

+ **LRV (GAVIE)** [Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning](https://arxiv.org/abs/2306.14565) (Sep., 29 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.14565)
  [![Star](https://img.shields.io/github/stars/FuxiaoLiu/LRV-Instruction.svg?style=social&label=Star)](https://github.com/FuxiaoLiu/LRV-Instruction)

+ **MMHal-Bench** [Aligning Large Multimodal Models with Factually Augmented RLHF](https://arxiv.org/abs/2306.14565) (Sep. 25, 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.14525)
  [![Star](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF.svg?style=social&label=Star)](https://github.com/llava-rlhf/LLaVA-RLHF)

+ **POPE** [Evaluating Object Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2305.10355) (EMNLP 2023)（object hallucination最常用的benchamark）**强力推荐**
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.10355)
  [![Star](https://img.shields.io/github/stars/AoiDragon/POPE.svg?style=social&label=Star)](https://github.com/AoiDragon/POPE)

+ **CHAIR** [Object Hallucination in Image Captioning](https://arxiv.org/abs/1809.02156) (EMNLP 2018)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1809.02156)

### Mitigating（LVLM）

1. **LRV-Instruction**: Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning, (Liu et al. ICLR2024)
   - [![Static Badge](https://img.shields.io/badge/2306.14565-red?logo=arxiv)](http://arxiv.org/abs/2306.14565)  [![](https://img.shields.io/badge/LRV--Instruction-black?logo=github)](https://github.com/FuxiaoLiu/LRV-Instruction)
   - [dataset] propose an instruction-tuning dataset that includes both positive and negative sample
   - _GAIVE_: evaluation approach which uses GPT-4
2. **LURE**: Analyzing and Mitigating Object Hallucination in Large Vision-Language Models, (Zhou et al. ICLR2024)
   - [![Static Badge](https://img.shields.io/badge/2310.00754-red?logo=arxiv)](https://arxiv.org/pdf/2310.00754) [![](https://img.shields.io/badge/LURE-black?logo=github)](https://github.com/YiyangZhou/LURE) 
   - [post-hoc revision] train a revision model to detect and correct hallucinated objects in the base model’s response. 
3. **HallE-Switch**: Rethinking and Controlling Object Existence Hallucinations in Large Vision-Language Models for Detailed Caption, (Zhai et al. 2023)
   - [![Static Badge](https://img.shields.io/badge/2310.01779-red?logo=arxiv)](https://arxiv.org/pdf/2310.01779)  [![](https://img.shields.io/badge/HallE_Switch-black?logo=github)](https://github.com/bronyayang/HallE_Switch)
   - _CCEval_, a GPT-4 assisted evaluation method tailored for detailed captioning
4. **Woodpecker**: Hallucination Correction for Multimodal Large Language Models, (Yin et al.)
   - [![Static Badge](https://img.shields.io/badge/2310.16045-red?logo=arxiv)](https://arxiv.org/abs/2310.16045) [![](https://img.shields.io/badge/Woodpecker-black?logo=github)](https://github.com/BradyFU/Woodpecker)  [![Static Badge](https://img.shields.io/badge/demo-yellow)](https://f252626b321420bfb1.gradio.live/)
   - [revision] post-hoc correction
   - need other pre-trained visual models
5. **LLaVA-RLHF**: Aligning Large Multimodal Models with Factually Augmented RLHF, (Sun et al.)
   - [![Static Badge](https://img.shields.io/badge/2309.14525-red?logo=arxiv)](https://arxiv.org/abs/2309.14525) [![](https://img.shields.io/badge/LLaVA--RLHF-black?logo=github)](https://github.com/llava-rlhf/LLaVA-RLHF)
   - [RLHF-PPO] the first LMM trained with RLHF
   - propose benchmark: **MMHal-Bench**
6. **Volcano**: Mitigating Multimodal Hallucination through Self-Feedback Guided Revision, (Lee et al.)
   - [![Static Badge](https://img.shields.io/badge/2311.07362-red?logo=arxiv)](https://arxiv.org/abs/2311.07362) [![](https://img.shields.io/badge/Volcano-black?logo=github)](https://github.com/kaistAI/Volcano)
   - self-feedback, according to self-generate natural language feedback to self-revise response
7. **HalluciDoctor**: Mitigating Hallucinatory Toxicity in Visual Instruction Data， (Yu et al.)
   - [![Static Badge](https://img.shields.io/badge/2311.13614-red?logo=arxiv)](https://arxiv.org/abs/2311.13614) [![](https://img.shields.io/badge/HalluciDoctor-black?logo=github)](https://github.com/Yuqifan1117/HalluciDoctor)
8. **VCD**: Mitigating Object Hallucinations in Large Vision-Language Models through Visual Contrastive Decoding, (Leng et al.)**强力推荐**
   - [![Static Badge](https://img.shields.io/badge/2311.16922-red?logo=arxiv)](https://arxiv.org/abs/2311.16922) [![](https://img.shields.io/badge/VCD-black?logo=github)](https://github.com/DAMO-NLP-SG/VCD)
   - constractive decoding
9. **HA-DPO**: Beyond Hallucinations: Enhancing LVLMs through Hallucination-Aware Direct Preference Optimization
   - [![Static Badge](https://img.shields.io/badge/2311.16839-red?logo=arxiv)](https://arxiv.org/abs/2311.16839) ![Static Badge](https://img.shields.io/badge/not_release-black?logo=github)
10. Mitigating Hallucination in Visual Language Models with Visual Supervision, (Chen et al.)
    - [![Static Badge](https://img.shields.io/badge/2311.16479-red?logo=arxiv)](https://arxiv.org/abs/2311.16479) ![Static Badge](https://img.shields.io/badge/not_release-black?logo=github)
11. **OPERA**: Alleviating Hallucination in Multi-Modal Large Language Models via Over-Trust Penalty and Retrospection-Allocation, (Huang et al.)**强力推荐**
    - [![Static Badge](https://img.shields.io/badge/2311.17911-red?logo=arxiv)](https://arxiv.org/abs/2311.17911) [![](https://img.shields.io/badge/OPERA-black?logo=github)](https://github.com/shikiw/OPERA)
    - Improve beam search
12. **FOHE**: Mitigating Fine-Grained Hallucination by Fine-Tuning Large Vision-Language Models with Caption Rewrites, (Wang et al.)
    - [![Static Badge](https://img.shields.io/badge/2312.01701-red?logo=arxiv)](https://arxiv.org/abs/2312.01701) [![](https://img.shields.io/badge/FOHE-black?logo=github)](https://github.com/Anonymousanoy/FOHE)
    - use ChatGPT to post-hoc correction
13. **RLHF-V**: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback
    - [![Static Badge](https://img.shields.io/badge/2312.00849-red?logo=arxiv)](https://arxiv.org/abs/2312.00849) [![](https://img.shields.io/badge/RLHF--V-black?logo=github)](https://github.com/RLHF-V/RLHF-V)
    - [RLHF-DPO] 1.4K preference data, natural language feedback
14. **MOCHa**: Multi-Objective Reinforcement Mitigating Caption Hallucinations, (Ben-Kish et al.)
    - [![Static Badge](https://img.shields.io/badge/2312.03631-red?logo=arxiv)](https://arxiv.org/abs/2312.03631) [![](https://img.shields.io/badge/Mocha-black?logo=github)](https://github.com/assafbk/mocha_code)
    - [RLHF]
15. **HACL**: Hallucination Augmented Contrastive Learning for Multimodal Large Language Model, (Jiang et al.)
    - [![Static Badge](https://img.shields.io/badge/2312.06968-red?logo=arxiv)](https://arxiv.org/abs/2312.06968) ![Static Badge](https://img.shields.io/badge/not_release-black?logo=github)
16. **Silkie**: Preference Distillation for Large Visual Language Models, (Li et al.)
    - [![Static Badge](https://img.shields.io/badge/2312.10665-red?logo=arxiv)](https://arxiv.org/abs/2312.10665) [![](https://img.shields.io/badge/Silkie-black?logo=github)](https://github.com/vlf-silkie/VLFeedback)
17.  **HalluciDoctor**:HalluciDoctor: Mitigating Hallucinatory Toxicity in Visual Instruction Data：用“反常规”的数据干掉假相关性
    - [![Static Badge](https://img.shields.io/badge/2311.13614-red?logo=arxiv)](https://arxiv.org/abs/2311.13614)
18. **MARINE**: Mitigating Object Hallucination in LargeVision-Language Models via Classifier-Free Guidance     
    - [![Static Badge](https://img.shields.io/badge/2311.08680-red?logo=arxiv)](https://arxiv.org/abs/2402.08680)
19. **CIEM** ：CIEM: Contrastive Instruction Evaluation Method for Better Instruction Tuning
    - [![Static Badge](https://img.shields.io/badge/2311.02301-red?logo=arxiv)](https://arxiv.org/abs/2402.02301)
20. **EFUF**: EFUF: Efficient Fine-grained Unlearning Framework for Mitigating Hallucinations in Multimodal Large Language Models
    - [![Static Badge](https://img.shields.io/badge/2311.09801-red?logo=arxiv)](https://arxiv.org/abs/2402.09801)
21. **SEEING IS BELIEVING**：MITIGATING HALLUCINATION IN LARGE VISION-LANGUAGE MODELS VIA CLIP-GUIDED DECODING

### 他山之玉（LLM's hallucination）：
## survey:
- Song in the AI Ocean:A Survey on Hallucination in Large Language Models https://github.com/HillZhang1999/llm-hallucination-survey
- A Survey on Hallucination in Large Language Models: Principles, Taxonomy, Challenges, and Open Questions 
- A Comprehensive Survey of Hallucination Mitigation Techniques in LargeLanguage Models 
- A Survey of Hallucination in “Large” Foundation Models 
### Interesting topic: 
## Contrastive decoding： (vcd同款方法)
1. Hallucinations of Large Language Models through Induced Halluctions
2. Contrastive Decoding: Open-ended Text Generation as Optimization 
3. Trusting Your Evidence: Hallucinate Less with Context-aware Decoding
4. SH2: Self-Highlighted Hesitation Helps You Decode More Truthfully
5. DoLa: Decoding by Contrasting Layers Improves Factuality in Large Language Models

## Acknowledgments

I am immensely grateful to two pivotal projects that have significantly influenced the development of my work: [awesome-Large-MultiModal-Hallucination](https://github.com/xieyuquanxx/awesome-Large-MultiModal-Hallucination) and [Awesome-MLLM-Hallucination](https://github.com/showlab/Awesome-MLLM-Hallucination). The dedication and effort put forth by the contributors of these projects, particularly [xieyuquanxx](https://github.com/xieyuquanxx) and the team at Show Lab, have provided an indispensable resource for researchers and developers alike.
The awesome-Large-MultiModal-Hallucination project has offered a comprehensive guide and a curated list of resources that have been instrumental in shaping my understanding of Large MultiModal Hallucination. Similarly, the Awesome-MLLM-Hallucination repository has been a treasure trove of knowledge, showcasing cutting-edge techniques and methodologies in the realm of Machine Learning and Large Model Hallucination.
By sharing their expertise and compiling these resources, they have not only advanced the field but also fostered a spirit of collaboration and open knowledge. I am deeply appreciative of their contributions and am inspired by their commitment to the community. Their work serves as a foundation upon which I have built and expanded, and for that, I extend my heartfelt thanks.
This acknowledgment is a small gesture compared to the vast impact their work has had on mine. Thank you for setting a remarkable example for the open-source and scientific communities.


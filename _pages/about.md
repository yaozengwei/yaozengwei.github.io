---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I got my master’s degree from Harbin Institute of Technology (HIT), supervised by [Prof. Guangming Lu](https://scholar.google.com/citations?user=fhwB7UwAAAAJ&hl) and [Prof. Wenjie Pei](https://wenjiepei.github.io/), and my bachelor’s degree from South China Normal University (SCNU). 

Now I am a member of the Next-gen Kaldi team at Xiaomi (via Xiaomi Future Star program), under the supervision of [Dr. Daniel Povey](https://scholar.google.com/citations?user=y_-5FWAAAAAJ&hl=en), an IEEE Fellow renowned in speech processing. I am a core contributor to the open-source speech recognition project [icefall](https://github.com/k2-fsa/icefall) [![Stars](https://img.shields.io/github/stars/k2-fsa/icefall?style=social)](https://github.com/k2-fsa/icefall), with main contributions in advanced model architectures and training recipes. 

My research mainly focuses on speech and audio modeling (recognition, generation, and separation), with publications in reputable conferences and journals such as ICLR, TASLP, ICASSP, INTERSPEECH, ASRU, and NeurIPS <a href='https://scholar.google.com/citations?user=f3Eo9S0AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. I also serve as a reviewer for ICLR, ICML, and ACL.

# 🔥 News
- *2026.04*: &nbsp;🎉🎉 We release the Omnilingual Zero-Shot TTS model [OmniVoice](https://arxiv.org/abs/2604.00688).
- *2026.04*: &nbsp;🎉🎉 One paper ([ZipVoice-Dialog](https://arxiv.org/abs/2507.09318)) is accepted by ACL 2026 (Findings).
- *2026.01*: &nbsp;🎉🎉 One paper ([Flow2GAN](https://arxiv.org/abs/2512.23278)) is accepted by ICLR 2026.
- *2025.09*: &nbsp;🎉🎉 One paper ([TransMLA](https://openreview.net/pdf?id=TcVCu2PKb9)) is accepted by NeurIPS 2025 (Spotlight, Top 3.19%).
- *2025.08*: &nbsp;🎉🎉 One paper ([ZipVoice](https://arxiv.org/abs/2506.13053)) is accepted by ASRU 2025.
- *2025.01*: &nbsp;🎉🎉 One paper ([CR-CTC](https://arxiv.org/abs/2410.05101)) is accepted by ICLR 2025.
- *2024.01*: &nbsp;🎉🎉 One paper ([Zipformer](https://arxiv.org/abs/2310.11230)) is accepted by ICLR 2024 (Oral, Top1.2%).
- *2023.12*: &nbsp;🎉🎉 Two papers ([PromptASR](https://arxiv.org/abs/2309.07414), [LibriHeavy](https://arxiv.org/abs/2309.08105)) are accepted by ICASSP 2024.
- *2023.05*: &nbsp;🎉🎉 Two papers ([Delay-penalized CTC](https://arxiv.org/abs/2305.11539), [Blank-regularized CTC](https://arxiv.org/abs/2305.11558)) are accepted by INTERSPEECH 2023.
- *2023.02*: &nbsp;🎉🎉 Three papers ([Delay-penalized transducer](https://arxiv.org/abs/2211.00490), [MVQ](https://arxiv.org/abs/2211.00508), [Fast decoding](https://arxiv.org/abs/2211.00484)) are accepted by ICASSP 2023.
- *2022.06*: &nbsp;🎉🎉 One paper ([Pruned RNN-T](https://arxiv.org/abs/2206.13236)) is accepted by INTERSPEECH 2022.
- *2022.02*: &nbsp;😄😄 I join Xiaomi Next-gen Kaldi team, under the supervision of [Dr. Daniel Povey](https://scholar.google.com/citations?user=y_-5FWAAAAAJ&hl=en). 
- *2022.01*: &nbsp;🎉🎉 One paper ([Stepwise-Refining Speech Separation](https://arxiv.org/abs/2110.04791)) is accepted by TASLP 2022.

# 📝 Publications 

- **[ICLR 2026]** [Flow2GAN: Hybrid Flow Matching and GAN with Multi-Resolution Network for Few-step High-Fidelity Audio Generation](https://arxiv.org/abs/2512.23278),
  **Z Yao**, W Kang, H Zhu, L Guo, L Ye, F Kuang, W Zhuang, Z Li, Z Han, L Lin, D Povey
  [<img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" width="16" height="16" alt="Code">](https://github.com/k2-fsa/Flow2GAN)

- **[ICLR 2025]** [CR-CTC: Consistency regularization on CTC for improved speech recognition](https://arxiv.org/abs/2410.05101),
  **Z Yao**, W Kang, X Yang, F Kuang, L Guo, H Zhu, Z Jin, Z Li, L Lin, D Povey
  [<img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" width="16" height="16" alt="Code">](https://github.com/k2-fsa/icefall/pull/1766)

- **[ICLR 2024 Oral, Top 1.2%]** [Zipformer: A faster and better encoder for automatic speech recognition](https://arxiv.org/abs/2310.11230),
  **Z Yao**, L Guo, X Yang, W Kang, F Kuang, Y Yang, Z Jin, L Lin, D Povey
  [<img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" width="16" height="16" alt="Code">](https://github.com/k2-fsa/icefall/tree/master/egs/librispeech/ASR/zipformer)

- **[INTERSPEECH 2023]** [Delay-penalized CTC implemented based on Finite State Transducer](https://arxiv.org/abs/2305.11539),
  **Z Yao**\*, W Kang\*, F Kuang, L Guo, X Yang, Y Yang, L Lin, D Povey
  [<img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" width="16" height="16" alt="Code">](https://github.com/k2-fsa/icefall/pull/669)

- **[ICASSP 2023]** [Delay-penalized transducer for low-latency streaming ASR](https://arxiv.org/abs/2211.00490),
  W Kang\*, **Z Yao**\*, F Kuang, L Guo, X Yang, L Lin, P Żelasko, D Povey
  [<img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" width="16" height="16" alt="Code">](https://github.com/k2-fsa/icefall/pull/654)

- **[TASLP 2022]** [Stepwise-refining speech separation network via fine-grained encoding in high-order latent domain](https://arxiv.org/abs/2110.04791),
  **Z Yao**, W Pei, F Chen, G Lu, D Zhang

- **[NeurIPS 2025 Spotlight, Top 3.19%]** [TransMLA: Migrating GQA Models to MLA with Full DeepSeek Compatibility and Speedup](https://openreview.net/pdf?id=TcVCu2PKb9),
  F Meng, P Tang, **Z Yao**, X Sun, M Zhang
  [<img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" width="16" height="16" alt="Code">](https://github.com/MuLabPKU/TransMLA)

- **[ACL 2026 Findings]** [ZipVoice-Dialog: Non-Autoregressive Spoken Dialogue Generation with Flow Matching](https://arxiv.org/abs/2507.09318),
  H Zhu, W Kang, L Guo, **Z Yao**, F Kuang, W Zhuang, Z Li, Z Han, D Zhang, X Zhang, X Song, L Lin, D Povey
  [<img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" width="16" height="16" alt="Code">](https://github.com/k2-fsa/ZipVoice)
  
- **[ASRU 2025]** [ZipVoice: Fast and High-Quality Zero-Shot Text-to-Speech with Flow Matching](https://arxiv.org/abs/2506.13053),
  H Zhu, W Kang, **Z Yao**, L Guo, F Kuang, Z Li, W Zhuang, L Lin, D Povey
  [<img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" width="16" height="16" alt="Code">](https://github.com/k2-fsa/ZipVoice)
  
- **[ICASSP 2024]** [PromptASR for contextualized ASR with controllable style](https://arxiv.org/abs/2309.07414),
  X Yang, W Kang, **Z Yao**, Y Yang, L Guo, F Kuang, L Lin, D Povey

- **[ICASSP 2024]** [Libriheavy: a 50,000 hours asr corpus with punctuation casing and context](https://arxiv.org/abs/2309.08105),
  W Kang, X Yang, **Z Yao**, F Kuang, Y Yang, L Guo, L Lin, D Povey
 [<img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" width="16" height="16" alt="Code">](https://github.com/k2-fsa/libriheavy)

- **[INTERSPEECH 2023]** [Blank-regularized CTC for Frame Skipping in Neural Transducer](https://arxiv.org/abs/2305.11558),
  Y Yang, X Yang, L Guo, **Z Yao**, W Kang, F Kuang, L Lin, X Chen, D Povey

- **[ICASSP 2023]** [Predicting Multi-Codebook Vector Quantization Indexes for Knowledge Distillation](https://arxiv.org/abs/2211.00508),
  L Guo, X Yang, Q Wang, Y Kong, **Z Yao**, F Cui, F Kuang, W Kang, L Lin, M Luo, P Żelasko, D Povey

- **[ICASSP 2023]** [Fast and parallel decoding for transducer](https://arxiv.org/abs/2211.00484),
  W Kang, L Guo, F Kuang, L Lin, M Luo, **Z Yao**, X Yang, P Żelasko, D Povey

- **[INTERSPEECH 2022]** [Pruned RNN-T for fast, memory-efficient ASR training](https://arxiv.org/abs/2206.13236),
  F Kuang, L Guo, W Kang, L Lin, M Luo, **Z Yao**, D Povey

# 📖 Educations
- *2019.09 - 2022.01*, Harbin Institute of Technology, Master of Engineering in Computer Technology 
- *2015.09 - 2019.06*, South China Normal University, Bachelor of Engineering in Software Engineering  

# 💬 Invited Talks
- 2025 RTE 论坛硬件和端侧模型专场分享：[Flow2GAN 高效高质量音频生成](https://mp.weixin.qq.com/s/khwheTBrSd9WybKOJNkdbw) 
- 2023 CCF 语音对话与听觉专委会语音算法技术交流沙龙: [流式语音识别吐字时延正则化](https://mp.weixin.qq.com/s/B29-bs-dXVowo2QEX1_m5g)
- 2022 CCF 语音对话与听觉专委会 AI 产业沙龙: [Reworked Conformer 模型与基于多码本量化的蒸馏方案](https://mp.weixin.qq.com/s/hhFGmWnTZco0HFxGidHoCQ)

# 💻 Internships
- *2021.06 - 2021.08*, Tencent, Shenzhen, China.

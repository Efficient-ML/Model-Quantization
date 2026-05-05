# Awesome Model Quantization [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This repo collects papers, documents, and codes about model quantization for anyone who wants to research it. We are continuously improving the project. Welcome to PR the works (papers, repositories) that the repo misses.


- [Benchmarks](#benchmarks)
- [Survey Papers](#survey-papers)
- [Papers](#papers)
  - [2026](#2026)
  - [2025](#2025)
  - [2024](#2024)
  - [2023](#2023)
  - [2022–2015](#2022)
- [Books](#books)
- [Related Repositories](#related-repositories)

## Benchmarks

**1. BiBench: Benchmarking and Analyzing Network Binarization** [[Paper](https://proceedings.mlr.press/v202/qin23a.html)] [[Code](https://github.com/htqin/BiBench)] [![GitHub stars](https://img.shields.io/github/stars/htqin/BiBench?style=social)](https://github.com/htqin/BiBench)

**Venue:** ICML 2023

**Authors:** Haotong Qin, Mingyuan Zhang, Yifu Ding, Aoyu Li, Zhongang Cai, Ziwei Liu, Fisher Yu, Xianglong Liu.

![survey](./Imgs/bibench.png)

<details><summary>Bibtex</summary><pre><code>@inproceedings{qin2023bibench,
  title={BiBench: Benchmarking and Analyzing Network Binarization},
  author={Qin, Haotong and Zhang, Mingyuan and Ding, Yifu and Li, Aoyu and Cai, Zhongang and Liu, Ziwei and Yu, Fisher and Liu, Xianglong},
  booktitle={International Conference on Machine Learning (ICML)},
  year={2023}
}</code></pre></details>

**2. An empirical study of LLaMA3 quantization: from LLMs to MLLMs** [[Paper](https://link.springer.com/article/10.1007/s44267-024-00070-x)] [[Code](https://github.com/Macaronlin/LLaMA3-Quantization)] [![GitHub stars](https://img.shields.io/github/stars/Macaronlin/LLaMA3-Quantization?style=social)](https://github.com/Macaronlin/LLaMA3-Quantization)

**Venue:** Visual Intelligence 2024

**Authors:** Wei Huang, Xingyu Zheng, Xudong Ma, Haotong Qin, Chengtao Lv, Hong Chen, Jie Luo, Xiaojuan Qi, Xianglong Liu, Michele Magno.

![LLaMA3 Quantization Benchmark](./Imgs/llama3.png)

<details><summary>Bibtex</summary><pre><code>@article{huang2024empirical,
  title={An empirical study of llama3 quantization: From llms to mllms},
  author={Huang, Wei and Zheng, Xingyu and Ma, Xudong and Qin, Haotong and Lv, Chengtao and Chen, Hong and Luo, Jie and Qi, Xiaojuan and Liu, Xianglong and Magno, Michele},
  journal={Visual Intelligence},
  volume={2},
  number={1},
  pages={36},
  year={2024},
  publisher={Springer}
}</code></pre></details>

**3. An Empirical Study of Qwen3 Quantization** [[Paper](https://arxiv.org/abs/2505.02214)] [[Code](https://github.com/Efficient-ML/Qwen3-Quantization)] [![GitHub stars](https://img.shields.io/github/stars/Efficient-ML/Qwen3-Quantization?style=social)](https://github.com/Efficient-ML/Qwen3-Quantization)

**Venue:** Visual Intelligence 2026

**Authors:** Xingyu Zheng, Yuye Li, Haoran Chu, Yue Feng, Xudong Ma, Jie Luo, Jinyang Guo, Haotong Qin, Michele Magno, Xianglong Liu.

![qwen3](./Imgs/qwen3.png)

<details><summary>Bibtex</summary><pre><code>@article{zheng2025empirical,
  title={An empirical study of qwen3 quantization},
  author={Zheng, Xingyu and Li, Yuye and Chu, Haoran and Feng, Yue and Ma, Xudong and Luo, Jie and Guo, Jinyang and Qin, Haotong and Magno, Michele and Liu, Xianglong},
  journal={arXiv preprint arXiv:2505.02214},
  year={2025}
}</code></pre></details>

**4. LLMC: Benchmarking Large Language Model Quantization with a Versatile Compression Toolkit** [[Paper](https://aclanthology.org/2024.emnlp-industry.12/)] [[Code](https://github.com/ModelTC/LightCompress)] [![GitHub stars](https://img.shields.io/github/stars/ModelTC/LightCompress?style=social)](https://github.com/ModelTC/LightCompress)

**Venue:** EMNLP 2024 Industry Track

**Authors:** Ruihao Gong, Yang Yong, Shiqiao Gu, Yushi Huang, Chengtao Lv, Yunchen Zhang, Xianglong Liu, Dacheng Tao.

![llmc](./Imgs/llmc.png)

<details><summary>Bibtex</summary><pre><code>@inproceedings{gong2024llmc,
  title={Llmc: Benchmarking large language model quantization with a versatile compression toolkit},
  author={Gong, Ruihao and Yong, Yang and Gu, Shiqiao and Huang, Yushi and Lv, Chengtao and Zhang, Yunchen and Tao, Dacheng and Liu, Xianglong},
  booktitle={Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing: Industry Track},
  pages={132--152},
  year={2024}
}</code></pre></details>

**5. RobustMQ: Benchmarking Robustness of Quantized Models** [[Paper](https://link.springer.com/article/10.1007/s44267-023-00031-w)]

**Venue:** Visual Intelligence 2023

**Authors:** Yisong Xiao, Aishan Liu, Tianyuan Zhang, Haotong Qin, Jinyang Guo, Xianglong Liu.

![robustmq](./Imgs/robustmq.png)

<details><summary>Bibtex</summary><pre><code>@article{xiao2023robustmq,
  title={Robustmq: benchmarking robustness of quantized models},
  author={Xiao, Yisong and Liu, Aishan and Zhang, Tianyuan and Qin, Haotong and Guo, Jinyang and Liu, Xianglong},
  journal={Visual Intelligence},
  volume={1},
  number={1},
  pages={30},
  year={2023},
  publisher={Springer}
}</code></pre></details>

## Survey Papers

**1. Binary Neural Networks: A Survey** [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320320300856)] [[Blog](https://mp.weixin.qq.com/s/QGva6fow9tad_daZ_G2p0Q)]

**Venue:** Pattern Recognition 2020

**Authors:** Haotong Qin, Ruihao Gong, Xianglong Liu, Xiao Bai, Jingkuan Song, Nicu Sebe.


![survey](./Imgs/survey.png)

<details><summary>Bibtex</summary><pre><code>@article{Qin:pr20_bnn_survey,
    title = "Binary neural networks: A survey",
    author = "Haotong Qin and Ruihao Gong and Xianglong Liu and Xiao Bai and Jingkuan Song and Nicu Sebe",
    journal = "Pattern Recognition",
    volume = "105",
    pages = "107281",
    year = "2020"
}</code></pre></details>

**2. A Survey of Low-bit Large Language Models: Basics, Systems, and Algorithms** [[Paper](https://www.sciencedirect.com/science/article/pii/S0893608025007361)]

**Venue:** Neural Networks 2025

**Authors:** Ruihao Gong, Yifu Ding, Zining Wang, Chengtao Lv, Xingyu Zheng, Jinyang Du, Yang Yong, Shiqiao Gu, Haotong Qin, Jinyang Guo, Dahua Lin, Michele Magno, Xianglong Liu.

![A Survey of Low-bit Large Language Models](./Imgs/llm-survey.png)

<details><summary>Bibtex</summary><pre><code>@article{gong2025survey,
  title={A survey of low-bit large language models: Basics, systems, and algorithms},
  author={Gong, Ruihao and Ding, Yifu and Wang, Zining and Lv, Chengtao and Zheng, Xingyu and Du, Jinyang and Yong, Yang and Gu, Shiqiao and Qin, Haotong and Guo, Jinyang and others},
  journal={Neural networks},
  pages={107856},
  year={2025},
  publisher={Elsevier}
}</code></pre></details>

**3. Low-bit Model Quantization for Deep Neural Networks: A Survey** [[Paper](https://arxiv.org/abs/2505.05530)]

**Venue:** arXiv 2025

**Authors:** Kai Liu, Qian Zheng, Kaiwen Tao, Zhiteng Li, Haotong Qin, Wenbo Li, Yong Guo, Xianglong Liu, Linghe Kong, Guihai Chen, Yulun Zhang, Xiaokang Yang.

![quant-survey](./Imgs/quant-survey.png)

<details><summary>Bibtex</summary><pre><code>@article{liu2025low,
  title={Low-bit model quantization for deep neural networks: A survey},
  author={Liu, Kai and Zheng, Qian and Tao, Kaiwen and Li, Zhiteng and Qin, Haotong and Li, Wenbo and Guo, Yong and Liu, Xianglong and Kong, Linghe and Chen, Guihai and others},
  journal={arXiv preprint arXiv:2505.05530},
  year={2025}
}</code></pre></details>

## Papers

### 2026

- [[ICLR](https://openreview.net/forum?id=7QZanjCD6M)] PT²-LLM: Post-Training Ternarization for Large Language Models [[code](https://github.com/XIANGLONGYAN/PT2-LLM)] [![GitHub stars](https://img.shields.io/github/stars/XIANGLONGYAN/PT2-LLM?style=social)](https://github.com/XIANGLONGYAN/PT2-LLM)
- [[ICLR](https://openreview.net/forum?id=HD7tuVakmR)] Quant-dLLM: Post-Training Extreme Low-Bit Quantization for Diffusion Large Language Models
- [[ICLR](https://openreview.net/forum?id=3AnRMvlVDw)] DVD-Quant: Data-free Video Diffusion Transformers Quantization
- [[ICLR](https://openreview.net/forum?id=AH7hbA7Zkk)] Q&C: When Quantization Meets Cache in Efficient Generation
- [[CVPR Findings](https://arxiv.org/abs/2503.21970)] Q-MambaIR: Accurate Quantized Mamba for Efficient Image Restoration
- [[ICLR](https://arxiv.org/abs/2509.21302)] Quantized Visual Geometry Grounded Transformer
- [[ICLR](https://openreview.net/forum?id=XAXT7A8EWh)] Post-Training Quantization for Video Matting
- [[ICLR](https://openreview.net/forum?id=XJXZXuTj11)] QVGen: Pushing the Limit of Quantized Video Generative Models
- [[ICLR](https://openreview.net/forum?id=4TAG3aQljJ)] QuantSparse: Comprehensively Compressing Video Diffusion Transformer with Model Quantization and Attention Sparsification [[code](https://github.com/wlfeng0509/QuantSparse)] [![GitHub stars](https://img.shields.io/github/stars/wlfeng0509/QuantSparse?style=social)](https://github.com/wlfeng0509/QuantSparse)
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/40123)] First-Order Error Matters: Accurate Compensation for Quantized Large Language Models [[code](https://github.com/Xingyu-Zheng/FOEM)] [![GitHub stars](https://img.shields.io/github/stars/Xingyu-Zheng/FOEM?style=social)](https://github.com/Xingyu-Zheng/FOEM)
- [[AAAI](https://arxiv.org/abs/2503.06564)] TR-DQ: Time-Rotation Diffusion Quantization
- [[ICLR](https://openreview.net/forum?id=tO3ASKZlok)] TurboQuant: Online Vector Quantization with Near-optimal Distortion Rate
- [[ICLR](https://openreview.net/forum?id=VQIvBpL5ag)] Optimal Brain Restoration for Joint Quantization and Sparsification of LLMs [[code](https://github.com/csguoh/OBR)] [![GitHub stars](https://img.shields.io/github/stars/csguoh/OBR?style=social)](https://github.com/csguoh/OBR)
- [[ICLR](https://openreview.net/forum?id=XPIEkFdEDi)] AnyBCQ: Hardware Efficient Flexible Binary-Coded Quantization for Multi-Precision LLMs [[code](https://github.com/naver-aics/anybcq)] [![GitHub stars](https://img.shields.io/github/stars/naver-aics/anybcq?style=social)](https://github.com/naver-aics/anybcq)
- [[ICLR](https://openreview.net/forum?id=9CZzD5LWdy)] Tequila: Deadzone-free Ternary Quantization for Large Language Models
- [[ICLR](https://openreview.net/forum?id=V85HbymBLW)] LogART: Pushing the Limit of Efficient Logarithmic Post-Training Quantization [[code](https://github.com/logart-lab/logart)] [![GitHub stars](https://img.shields.io/github/stars/logart-lab/logart?style=social)](https://github.com/logart-lab/logart)
- [[ICLR](https://openreview.net/forum?id=1USeVjsKau)] ParoQuant: Pairwise Rotation Quantization for Efficient Reasoning LLM Inference [[code](https://github.com/z-lab/paroquant)] [![GitHub stars](https://img.shields.io/github/stars/z-lab/paroquant?style=social)](https://github.com/z-lab/paroquant)
- [[ICLR](https://openreview.net/forum?id=VpZ8YYdBmT)] Improving Block-Wise LLM Quantization by 4-bit Generalized Normal Float Formats
- [[ICLR](https://openreview.net/forum?id=yjr2jX41qO)] Channel-Aware Mixed-Precision Quantization for Efficient Long-Context Inference
- [[ICLR](https://openreview.net/forum?id=ATpchFiBQi)] CodeQuant: Unified Clustering and Quantization for Enhanced Outlier Smoothing in Low-Precision Mixture-of-Experts
- [[ICLR](https://arxiv.org/abs/2510.11696)] QeRL: Beyond Efficiency - Quantization-enhanced Reinforcement Learning for LLMs [[code](https://github.com/NVlabs/QeRL)] [![GitHub stars](https://img.shields.io/github/stars/NVlabs/QeRL?style=social)](https://github.com/NVlabs/QeRL)
- [[ICLR](https://arxiv.org/abs/2602.03782)] AutoQVLA: Not All Channels Are Equal in Vision-Language-Action Model's Quantization
- [[ICLR](https://openreview.net/forum?id=g2l9bg9DWx)] Achieving low-bit Muon through subspace preservation and grid quantization
- [[ICLR](https://openreview.net/forum?id=DAZvMAlZRp)] Shift-and-Sum Quantization for Visual Autoregressive Models
- [[ICLR](https://arxiv.org/abs/2602.03472)] Inlier-Centric Post-Training Quantization for Object Detection Models
- [[ICLR](https://openreview.net/forum?id=yiMlVBAoQi)] Efficient Quantization of Mixture-of-Experts with Theoretical Generalization Guarantees
- [[ICLR](https://openreview.net/forum?id=tY9yPAT3PU)] BBQ: Boosting Quantization Entropy with Bell Box Quantization
- [[ICLR](https://arxiv.org/abs/2505.06653)] Improving Block-Wise LLM Quantization by 4-bit Block-Wise Optimal Float (BOF4): Analysis and Variations [[code](https://github.com/ifnspaml/bof4)] [![GitHub stars](https://img.shields.io/github/stars/ifnspaml/bof4?style=social)](https://github.com/ifnspaml/bof4)
- [[ICLR](https://arxiv.org/abs/2510.18259)] Learning under Quantization for High-Dimensional Linear Regression
- [[ICLR](https://arxiv.org/abs/2509.25214)] On-the-Fly Adaptation to Quantization: Configuration-Aware LoRA for Efficient Fine-Tuning of Quantized LLMs
- [[ICLR](https://arxiv.org/abs/2509.23202)] Bridging the Gap Between Promise and Performance for FP4 Quantization [[code](https://github.com/IST-DASLab/FP-Quant)] [![GitHub stars](https://img.shields.io/github/stars/IST-DASLab/FP-Quant?style=social)](https://github.com/IST-DASLab/FP-Quant)
- [[ICLR](https://arxiv.org/abs/2602.11184)] KBVQ-MoE: KLT-guided SVD with Bias-Corrected Vector Quantization for MoE Large Language Models [[code](https://github.com/xuzukang/kbvq_moe)] [![GitHub stars](https://img.shields.io/github/stars/xuzukang/kbvq_moe?style=social)](https://github.com/xuzukang/kbvq_moe)
- [[ICLR](https://arxiv.org/abs/2512.03383)] UniQL: Unified Quantization and Low-rank Compression for Adaptive Edge LLMs [[code](https://github.com/enyac-group/UniQL)] [![GitHub stars](https://img.shields.io/github/stars/enyac-group/UniQL?style=social)](https://github.com/enyac-group/UniQL)
- [[ICLR](https://arxiv.org/abs/2508.01077)] The Lattice Geometry of Neural Network Quantization: A Short Equivalence Proof of GPTQ and Babai's algorithm
- [[ICLR](https://arxiv.org/abs/2509.03472)] DPQuant: Efficient and Private Model Training via Dynamic Quantization Scheduling
- [[ICLR](https://openreview.net/pdf/ee0ea14cd2283b1fee1902a6811796b443849c5c.pdf)] Towards Quantization-Aware Training for Ultra-Low-Bit Reasoning LLMs
- [[ICLR](https://arxiv.org/abs/2510.21314)] A Convergence Analysis of Adaptive Optimizers under Floating-point Quantization
- [[ICLR](https://arxiv.org/abs/2510.06213)] Training Dynamics Impact Post-Training Quantization Robustness [[code](https://github.com/aldakata/TrainingDynamicsQuantizationRobustness)] [![GitHub stars](https://img.shields.io/github/stars/aldakata/TrainingDynamicsQuantizationRobustness?style=social)](https://github.com/aldakata/TrainingDynamicsQuantizationRobustness)
- [[ICLR](https://openreview.net/forum?id=pjMDZJd4rT)] SSDi8: Accurate and Efficient 8-bit Quantization for State Space Duality
- [[ICLR](https://arxiv.org/abs/2507.18553)] The Geometry of LLM Quantization: GPTQ as Babai's Nearest Plane Algorithm
- [[ICLR](https://arxiv.org/abs/2601.21238)] PTQ4ARVG: Post-Training Quantization for AutoRegressive Visual Generation Models [[code](https://github.com/BienLuky/PTQ4ARVG)] [![GitHub stars](https://img.shields.io/github/stars/BienLuky/PTQ4ARVG?style=social)](https://github.com/BienLuky/PTQ4ARVG)
- [[ICLR](https://arxiv.org/abs/2509.17428)] QWHA: Quantization-Aware Walsh-Hadamard Adaptation for Parameter-Efficient Fine-Tuning on Large Language Models [[code](https://github.com/vantaa89/qwha)] [![GitHub stars](https://img.shields.io/github/stars/vantaa89/qwha?style=social)](https://github.com/vantaa89/qwha)
- [[ICLR](https://arxiv.org/abs/2602.01289)] Gradient-Aligned Calibration for Post-Training Quantization of Diffusion Models
- [[ICLR](https://openreview.net/forum?id=nFjj8NEBqv)] SERQ: Saliency-Aware Low-Rank Error Reconstruction for LLM Quantization
- [[ICLR](https://arxiv.org/abs/2509.22935)] Compute-Optimal Quantization-Aware Training
- [[ICLR](https://arxiv.org/abs/2505.18610)] PM-KVQ: Progressive Mixed-precision KV Cache Quantization for Long-CoT LLMs [[code](https://github.com/thu-nics/PM-KVQ)] [![GitHub stars](https://img.shields.io/github/stars/thu-nics/PM-KVQ?style=social)](https://github.com/thu-nics/PM-KVQ)
- [[ICLR](https://arxiv.org/abs/2509.23500)] Beyond Outliers: A Study of Optimizers Under Quantization
- [[ICLR](https://arxiv.org/abs/2505.11695)] Qronos: Correcting the Past by Shaping the Future... in Post-Training Quantization
- [[ICLR](https://arxiv.org/abs/2508.02343)] MicroMix: Efficient Mixed-Precision Quantization with Microscaling Formats for Large Language Models [[code](https://github.com/lwy2020/MicroMix)] [![GitHub stars](https://img.shields.io/github/stars/lwy2020/MicroMix?style=social)](https://github.com/lwy2020/MicroMix)
- [[ICLR](https://arxiv.org/abs/2602.04929)] TurboBoA: Faster and Exact Attention-aware Quantization without Backpropagation
- [[ICLR](https://openreview.net/forum?id=FDdOD3qwS7)] Beyond Uniformity: Sample and Frequency Meta Weighting for Post-Training Quantization of Diffusion Models
- [[ICLR](https://openreview.net/forum?id=LWYZ1nNkJl)] Rethinking Residual Errors in Compensation-based LLM Quantization
- [[ICLR](https://openreview.net/forum?id=8tDIzHFOx6)] SPR²Q: Static Priority-based Rectifier Routing Quantization for Image Super-Resolution [[code](https://github.com/momo5-a11/SPR2Q)] [![GitHub stars](https://img.shields.io/github/stars/momo5-a11/SPR2Q?style=social)](https://github.com/momo5-a11/SPR2Q)
- [[ICLR](https://arxiv.org/abs/2510.26771)] STaMP: Sequence Transformation and Mixed Precision for Low-Precision Activation Quantization
- [[arXiv](https://arxiv.org/abs/2601.07892)] Sherry: Hardware-Efficient 1.25-Bit Ternary Quantization via Fine-grained Sparsification [[code](https://github.com/Tencent/AngelSlim)] [![GitHub stars](https://img.shields.io/github/stars/Tencent/AngelSlim?style=social)](https://github.com/Tencent/AngelSlim)
- [[arXiv](https://arxiv.org/abs/2602.16018)] D²Quant: Accurate Low-bit Post-Training Weight Quantization for LLMs
- [[arXiv](https://arxiv.org/abs/2601.03170)] QuantLRM: Quantization of Large Reasoning Models via Fine-Tuning Signals
- [[arXiv](https://arxiv.org/pdf/2603.25284v1)] SliderQuant: Accurate Post-Training Quantization for LLMs 
- [[arXiv](https://arxiv.org/abs/2601.14888)] What Makes Low-Bit Quantization-Aware Training Work for Reasoning LLMs? A Systematic Study
- [[arXiv](https://arxiv.org/abs/2603.28845)] OneComp: One-Line Revolution for Generative AI Model Compression [[Code](https://github.com/FujitsuResearch/OneCompression)] [![GitHub stars](https://img.shields.io/github/stars/FujitsuResearch/OneCompression?style=social)](https://github.com/FujitsuResearch/OneCompression)

### 2025

- [[ICML](https://icml.cc/virtual/2025/poster/45429)] Q-VDiT: Towards Accurate Quantization and Distillation of Video-Generation Diffusion Transformers [[code](https://github.com/cantbebetter2/Q-VDiT)] [![GitHub stars](https://img.shields.io/github/stars/cantbebetter2/Q-VDiT?style=social)](https://github.com/cantbebetter2/Q-VDiT)
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/33823)] MPQ-DM: Mixed Precision Quantization for Extremely Low Bit Diffusion Models
- [[ICML](https://icml.cc/virtual/2025/poster/45388)] SliM-LLM: Salience-Driven Mixed-Precision Quantization for Large Language Models [[code](https://github.com/Aaronhuang-778/SliM-LLM)] [![GitHub stars](https://img.shields.io/github/stars/Aaronhuang-778/SliM-LLM?style=social)](https://github.com/Aaronhuang-778/SliM-LLM)
- [[TPAMI](https://www.computer.org/csdl/journal/tp/2025/10/11060852/281Hxm5TK2Q)] BiVM: Accurate Binarized Neural Network for Efficient Video Matting
- [[NeurIPS](https://openreview.net/forum?id=e8pm93koQU)] S²Q-VDiT: Accurate Quantized Video Diffusion Transformer with Salient Data and Sparse Token Distillation [[code](https://github.com/wlfeng0509/S2Q-VDiT)] [![GitHub stars](https://img.shields.io/github/stars/wlfeng0509/S2Q-VDiT?style=social)](https://github.com/wlfeng0509/S2Q-VDiT)
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhu_PassionSR_Post-Training_Quantization_with_Adaptive_Scale_in_One-Step_Diffusion_based_CVPR_2025_paper.pdf)] PassionSR: Post-Training Quantization with Adaptive Scale in One-Step Diffusion based Image Super-Resolution [[code](https://github.com/libozhu03/PassionSR)] [![GitHub stars](https://img.shields.io/github/stars/libozhu03/PassionSR?style=social)](https://github.com/libozhu03/PassionSR)
- [[ICLR](https://openreview.net/forum?id=ZU8OdDLTts)] ARB-LLM: Alternating Refined Binarizations for Large Language Models [[code](https://github.com/ZHITENGLI/ARB-LLM)] [![GitHub stars](https://img.shields.io/github/stars/ZHITENGLI/ARB-LLM?style=social)](https://github.com/ZHITENGLI/ARB-LLM)
- [[ICLR](https://openreview.net/forum?id=cCE46s1obO)] BinaryDM: Accurate Weight Binarization for Efficient Diffusion Models [[code](https://github.com/Xingyu-Zheng/BinaryDM)] [![GitHub stars](https://img.shields.io/github/stars/Xingyu-Zheng/BinaryDM?style=social)](https://github.com/Xingyu-Zheng/BinaryDM)
- [[ICML](https://proceedings.mlr.press/v267/sun25l.html)] FlatQuant: Flatness Matters for LLM Quantization [[code](https://github.com/ruikangliu/FlatQuant)] [![GitHub stars](https://img.shields.io/github/stars/ruikangliu/FlatQuant?style=social)](https://github.com/ruikangliu/FlatQuant)
- [[ICML](https://icml.cc/virtual/2025/poster/44438)] RoSTE: An Efficient Quantization-Aware Supervised Fine-Tuning Approach for Large Language Models [[code](https://github.com/OptimAI-Lab/RoSTE)] [![GitHub stars](https://img.shields.io/github/stars/OptimAI-Lab/RoSTE?style=social)](https://github.com/OptimAI-Lab/RoSTE)
- [[ICML](https://icml.cc/virtual/2025/poster/43984)] GANQ: GPU-Adaptive Non-Uniform Quantization for Large Language Models
- [[ICML](https://icml.cc/virtual/2025/poster/43551)] Modulated Diffusion: Accelerating Generative Modeling with Modulated Quantization [[code](https://github.com/WeizhiGao/MoDiff)] [![GitHub stars](https://img.shields.io/github/stars/WeizhiGao/MoDiff?style=social)](https://github.com/WeizhiGao/MoDiff)
- [[NeurIPS](https://neurips.cc/virtual/2025/poster/118539)] DartQuant: Efficient Rotational Distribution Calibration for LLM Quantization [[code](https://github.com/CAS-CLab/DartQuant)] [![GitHub stars](https://img.shields.io/github/stars/CAS-CLab/DartQuant?style=social)](https://github.com/CAS-CLab/DartQuant)
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/35415)] JAQ: Joint Efficient Architecture Design and Low-Bit Quantization
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/33807/35962)] OAC: Output-adaptive Calibration for Accurate Post-Training Quantization of LLMs
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/34039)] Optimizing Quantized Diffusion Models via Distillation with Decay Timestep-Aware Loss
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/32658/40071)] Quantifiable Quantization Sensitivity of Diffusion Models
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/33913/36068)] TCAQ-DM: Timestep-Channel Adaptive Quantization for Diffusion Models
- [[ACL](https://aclanthology.org/2025.acl-long.498/)] EfficientQAT: Efficient Quantization-Aware Training for Large Language Models [[code](https://github.com/OpenGVLab/EfficientQAT)] [![GitHub stars](https://img.shields.io/github/stars/OpenGVLab/EfficientQAT?style=social)](https://github.com/OpenGVLab/EfficientQAT)
- [[ACL](https://aclanthology.org/2025.acl-long.99/)] L4Q: Parameter Efficient Quantization-Aware Fine-Tuning on Large Language Models
- [[ACL](https://aclanthology.org/2025.acl-long.531/)] MoQAE: Mixed-Precision Quantization for Long-Context LLM Inference via Mixture of Quantization-Aware Experts
- [[ACL](https://aclanthology.org/2025.acl-long.618/)] Outlier-Safe Pre-Training for Robust 4-Bit Quantization of Large Language Models
- [[ACL](https://aclanthology.org/2025.acl-long.225/)] PTQ1.61: Push the Real Limit of Extremely Low-Bit Post-Training Quantization Methods for Large Language Models [[code](https://github.com/zjq0455/PTQ1.61)] [![GitHub stars](https://img.shields.io/github/stars/zjq0455/PTQ1.61?style=social)](https://github.com/zjq0455/PTQ1.61)
- [[ACL](https://aclanthology.org/2025.acl-long.1382/)] Unifying Uniform and Binary-coding Quantization for Accurate Compression of Large Language Models
- [[ACL](https://aclanthology.org/2025.acl-long.1304/)] “Give Me BF16 or Give Me Death”? Accuracy-Performance Trade-Offs in LLM Quantization
- [[ACM MM](https://acmmm2025.org/accepted-regular-papers/)] DilateQuant: Accurate and Efficient Quantization-Aware Training for Diffusion Models via Weight Dilation
- [[ACM MM](https://dl.acm.org/doi/10.1145/3744239)] Learning Binarized Representations with Pseudo-positive Distillation
- [[ACM MM](https://dl.acm.org/doi/10.1145/3746027.3755433)] MQuant: Unleashing the Inference Potential of Multimodal Large Language Models with Post-Training Quantization
- [[ACM MM](https://dl.acm.org/doi/10.1145/3746027.3755213)] Pushing the Limit of Binarized Neural Network for Image Super Resolution with Smooth Information Transmission
- [[ACM MM](https://acmmm2025.org/accepted-regular-papers/)] Quantization Meets OOD: Generalizable Quantization-aware Training from a Flatness Perspective
- [[EMNLP](https://aclanthology.org/2025.emnlp-main.1799/)] AMQ: Enabling AutoML for Mixed-precision Weight-Only Quantization of Large Language Models
- [[EMNLP](https://aclanthology.org/2025.emnlp-main.479/)] Does quantization affect models' performance on long-input and long-output tasks?
- [[ICLR](https://iclr.cc/virtual/2025/poster/28924)] CBQ: Cross-Block Quantization for Large Language Models
- [[ICLR](https://iclr.cc/virtual/2025/poster/29192)] DGQ: Distribution-Aware Group Quantization for Text-to-Image Diffusion Models
- [[ICLR](https://iclr.cc/virtual/2025/poster/30168)] LeanQuant: Accurate and Scalable Large Language Model Quantization with Loss-error-aware Grid
- [[ICLR](https://openreview.net/forum?id=rAcgDBdKnP)] OSTQuant: Refining Large Language Model Quantization with Orthogonal and Scaling Transformations for Better Distribution Fitting [[code](https://github.com/BrotherHappy/OSTQuant)] [![GitHub stars](https://img.shields.io/github/stars/BrotherHappy/OSTQuant?style=social)](https://github.com/BrotherHappy/OSTQuant)
- [[ICLR](https://openreview.net/forum?id=LB5cKhgOTu)] QERA: an Analytical Framework for Quantization Error Reconstruction [[code](https://github.com/ChengZhang-98/QERA)] [![GitHub stars](https://img.shields.io/github/stars/ChengZhang-98/QERA?style=social)](https://github.com/ChengZhang-98/QERA)
- [[ICLR](https://iclr.cc/virtual/2025/poster/28338)] SpinQuant: LLM Quantization with Learned Rotations
- [[ICLR](https://iclr.cc/virtual/2025/poster/27906)] SVDQuant: Absorbing Outliers by Low-Rank Component for 4-Bit Diffusion Models
- [[ICLR](https://iclr.cc/virtual/2025/poster/30429)] ViDiT-Q: Efficient and Accurate Quantization of Diffusion Transformers for Image and Video Generation
- [[ICML](https://openreview.net/forum?id=ZawsPjlIGu&noteId=x0z6YCJM6S)] GuidedQuant: Large Language Model Quantization via Exploiting End Loss Guidance [[code](https://github.com/snu-mllab/GuidedQuant)] [![GitHub stars](https://img.shields.io/github/stars/snu-mllab/GuidedQuant?style=social)](https://github.com/snu-mllab/GuidedQuant)
- [[ICML](https://openreview.net/forum?id=4qIP1sXcR1)] ResQ: Mixed-Precision Quantization of Large Language Models with Low-Rank Residuals [[code](https://github.com/utkarsh-dmx/project-resq)] [![GitHub stars](https://img.shields.io/github/stars/utkarsh-dmx/project-resq?style=social)](https://github.com/utkarsh-dmx/project-resq)
- [[NeurIPS](https://neurips.cc/virtual/2025/poster/117148)] A Double Normalization Approach for Calibration-Free Low-Bit KV Cache Quantization
- [[NeurIPS](https://neurips.cc/virtual/2025/poster/119877)] Binary Quadratic Quantization: Beyond First-Order Quantization for Real-Valued Matrix Compression
- [[NeurIPS](https://neurips.cc/virtual/2025/poster/117396)] Learning Grouped Lattice Vector Quantizers for Low-Bit Large Language Models
- [[NeurIPS](https://neurips.cc/virtual/2025/poster/115061)] LittleBit: Ultra Low-Bit Quantization via Latent Factorization
- [[NeurIPS](https://neurips.cc/virtual/2025/poster/118224)] ParetoQ: Improving Scaling Laws in Extremely Low-bit LLM Quantization
- [[NeurIPS](https://neurips.cc/virtual/2025/poster/116315)] Q-Palette: Fractional-Bit Quantizers Toward Optimal Weight-Only Post-Training Quantization
- [[NeurIPS](https://neurips.cc/virtual/2025/poster/120052)] Wavelet-Enhanced High-Fidelity 1-Bit Quantization for LLMs
- [[NeurIPS](https://openreview.net/forum?id=a3l3K9khbL)] Quantization Error Propagation: Revisiting Layer-Wise Post-Training Quantization [[Code](https://github.com/FujitsuResearch/OneCompression)] [![GitHub stars](https://img.shields.io/github/stars/FujitsuResearch/OneCompression?style=social)](https://github.com/FujitsuResearch/OneCompression)
- [[ACL Findings](https://aclanthology.org/2025.findings-acl.459/)] Achieving Binary Weight and Activation for LLMs using Post-Training Quantization
- [[EMNLP Findings](https://aclanthology.org/2025.findings-emnlp.943/)] KurTail: Kurtosis-based LLM Quantization
- [[SIGMOD](https://dl.acm.org/doi/10.1145/3725413)] Practical and Asymptotically Optimal Quantization of High-Dimensional Vectors in Euclidean Space for Approximate Nearest Neighbor Search [[code](https://github.com/VectorDB-NTU/Extended-RaBitQ)] [![GitHub stars](https://img.shields.io/github/stars/VectorDB-NTU/Extended-RaBitQ?style=social)](https://github.com/VectorDB-NTU/Extended-RaBitQ)
- [[NeurIPS](https://neurips.cc/virtual/2025/poster/119764)] QBasicVSR: Temporal Awareness Adaptation Quantization for Video Super-Resolution
- [[NeurIPS](https://arxiv.org/abs/2504.09629)] Quantization Error Propagation: Revisiting Layer-Wise Post-Training Quantization
- [[NeurIPS](https://neurips.cc/virtual/2025/poster/115665)] Point4Bit: Post Training 4-bit Quantization for Point Cloud 3D Detection
- [[NeurIPS](https://arxiv.org/abs/2505.12266)] PMQ-VE: Progressive Multi-Frame Quantization for Video Enhancement [[code](https://github.com/xiaoBIGfeng/PMQ-VE)] [![GitHub stars](https://img.shields.io/github/stars/xiaoBIGfeng/PMQ-VE?style=social)](https://github.com/xiaoBIGfeng/PMQ-VE)
- [[NeurIPS](https://neurips.cc/virtual/2025/poster/115090)] VETA-DiT: Variance-Equalized and Temporally Adaptive Quantization for Efficient 4-bit Diffusion Transformers
- [[NeurIPS](https://arxiv.org/abs/2505.18724)] LoTA-QAF: Lossless Ternary Adaptation for Quantization-Aware Fine-Tuning [[code](https://github.com/KingdalfGoodman/LoTA-QAF/blob/main/README.md)] [![GitHub stars](https://img.shields.io/github/stars/KingdalfGoodman/LoTA-QAF?style=social)](https://github.com/KingdalfGoodman/LoTA-QAF)
- [[NeurIPS](https://neurips.cc/virtual/2025/poster/117708)] Efficient Multi-bit Quantization Network Training via Weight Bias Correction and Bit-wise Coreset Sampling
- [[NeurIPS](https://neurips.cc/virtual/2025/poster/119554)] Efficient and Generalizable Mixed-Precision Quantization via Topological Entropy
- [[NeurIPS](https://neurips.cc/virtual/2025/poster/119301)] QSCA: Quantization with Self-Compensating Auxiliary for Monocular Depth Estimation
- [[ICCV](https://arxiv.org/abs/2404.19248)] Scheduling Weight Transitions for Quantization-Aware Training [[code](https://github.com/cvlab-yonsei/TRS)] [![GitHub stars](https://img.shields.io/github/stars/cvlab-yonsei/TRS?style=social)](https://github.com/cvlab-yonsei/TRS)
- [[ICCV](https://arxiv.org/abs/2507.16782)] Task-Specific Zero-shot Quantization-Aware Training for Object Detection [[code](https://github.com/DFQ-Dojo/dfq-toolkit)] [![GitHub stars](https://img.shields.io/github/stars/DFQ-Dojo/dfq-toolkit?style=social)](https://github.com/DFQ-Dojo/dfq-toolkit)
- [[ICCV](https://arxiv.org/abs/2503.10959)] OuroMamba: A Data-Free Quantization Framework for Vision Mamba
- [[ICCV](https://arxiv.org/abs/2506.23516)] FedWSQ: Efficient Federated Learning with Weight Standardization and Distribution-Aware Non-Uniform Quantization [[code](https://github.com/Seongyeol-kim/FedWSQ)] [![GitHub stars](https://img.shields.io/github/stars/Seongyeol-kim/FedWSQ?style=social)](https://github.com/Seongyeol-kim/FedWSQ)
- [[ICCV](https://arxiv.org/abs/2412.16553)] Semantic Alignment and Reinforcement for Data-Free Quantization of Vision Transformers [[code](https://github.com/zysxmu/SARDFQ)] [![GitHub stars](https://img.shields.io/github/stars/zysxmu/SARDFQ?style=social)](https://github.com/zysxmu/SARDFQ)
- [[ICCV](https://arxiv.org/abs/2503.06545)] QuantCache: Adaptive Importance-Guided Quantization with Hierarchical Latent and Layer Caching for Video Generation [[code](https://github.com/JunyiWuCode/QuantCache)] [![GitHub stars](https://img.shields.io/github/stars/JunyiWuCode/QuantCache?style=social)](https://github.com/JunyiWuCode/QuantCache)
- [[ICCV](https://arxiv.org/abs/2507.19131)] MixA-Q: Revisiting Activation Sparsity for Vision Transformers from a Mixed-Precision Quantization Perspective
- [[ICCV](https://arxiv.org/abs/2507.12933)] DMQ: Dissecting Outliers of Diffusion Models for Post-Training Quantization [[code](https://github.com/LeeDongYeun/dmq)] [![GitHub stars](https://img.shields.io/github/stars/LeeDongYeun/dmq?style=social)](https://github.com/LeeDongYeun/dmq)
- [[ICCV](https://arxiv.org/abs/2503.03088)] AHCPTQ: Accurate and Hardware-Compatible Post-Training Quantization for Segment Anything Model
- [[ICCV](https://arxiv.org/abs/2507.22349)] MSQ: Memory-Efficient Bit Sparsification Quantization
- [[ICCV](https://arxiv.org/abs/2402.03666)] QuEST: Low-bit Diffusion Model Quantization via Efficient Selective Finetuning [[code](https://github.com/hatchetProject/QuEST)] [![GitHub stars](https://img.shields.io/github/stars/hatchetProject/QuEST?style=social)](https://github.com/hatchetProject/QuEST)
- [[ICML](https://arxiv.org/abs/2505.05799)] MxMoE: Mixed-precision Quantization for MoE with Accuracy and Performance Co-Design [[code](https://github.com/cat538/MxMoE)] [![GitHub stars](https://img.shields.io/github/stars/cat538/MxMoE?style=social)](https://github.com/cat538/MxMoE)
- [[ICML](https://arxiv.org/abs/2505.04877)] Learning from Loss Landscape: Generalizable Mixed-Precision Quantization via Adaptive Sharpness-Aware Gradient Aligning
- [[ICML](https://arxiv.org/abs/2503.15748)] PARQ: Piecewise-Affine Regularized Quantization [[code](https://github.com/facebookresearch/parq)] [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/parq?style=social)](https://github.com/facebookresearch/parq)
- [[ICML](https://arxiv.org/abs/2503.22879)] Quamba2: A Robust and Scalable Post-training Quantization Framework for Selective State Space Models [[code](https://github.com/enyac-group/Quamba)] [![GitHub stars](https://img.shields.io/github/stars/enyac-group/Quamba?style=social)](https://github.com/enyac-group/Quamba)
- [[ICML](https://openreview.net/forum?id=G6DmP9wxeB)] LRA-QViT: Integrating Low-Rank Approximation and Quantization for Robust and Efficient Vision Transformers
- [[ICML](https://arxiv.org/abs/2406.13474)] BoA: Attention-aware Post-training Quantization without Backpropagation
- [[ICML](https://arxiv.org/abs/2505.03804)] MoEQuant: Enhancing Quantization for Mixture-of-Experts Large Language Models via Expert-Balanced Sampling and Affinity Guidance [[code](https://github.com/chenzx921020/MoEQuant)] [![GitHub stars](https://img.shields.io/github/stars/chenzx921020/MoEQuant?style=social)](https://github.com/chenzx921020/MoEQuant)
- [[ICML](https://arxiv.org/abs/2502.09720)] NestQuant: nested lattice quantization for matrix products and LLMs
- [[ICML](https://arxiv.org/abs/2506.20251)] Q-resafe: Assessing Safety Risks and Quantization-aware Safety Patching for Quantized Large Language Models [[code](https://github.com/Thecommonirin/Qresafe)] [![GitHub stars](https://img.shields.io/github/stars/Thecommonirin/Qresafe?style=social)](https://github.com/Thecommonirin/Qresafe)
- [[ICML](https://arxiv.org/abs/2410.09615)] SLiM: One-shot Quantization and Sparsity with Low-rank Approximation for LLM Weight Compression [[code](https://github.com/Paramathic/slim)] [![GitHub stars](https://img.shields.io/github/stars/Paramathic/slim?style=social)](https://github.com/Paramathic/slim)
- [[ICML](https://arxiv.org/abs/2410.06020)] QT-DoG: Quantization-Aware Training for Domain Generalization [[code](https://github.com/saqibjaved1/QT-DoG)] [![GitHub stars](https://img.shields.io/github/stars/saqibjaved1/QT-DoG?style=social)](https://github.com/saqibjaved1/QT-DoG)
- [[ICML](https://arxiv.org/abs/2502.06786)] Matryoshka Quantization
- [[ICML](https://arxiv.org/abs/2505.23651)] Merge-Friendly Post-Training Quantization for Multi-Target Domain Adaptation [[code](https://github.com/ewsn1593/HDRQ)] [![GitHub stars](https://img.shields.io/github/stars/ewsn1593/HDRQ?style=social)](https://github.com/ewsn1593/HDRQ)
- [[ICML](https://arxiv.org/abs/2505.14371)] Layer-wise Quantization for Quantized Optimistic Dual Averaging
- [[ICML](https://openreview.net/forum?id=w5fONAEwra)] Outlier-Aware Post-Training Quantization for Discrete Graph Diffusion Models
- [[ICML](https://arxiv.org/abs/2501.01144)] BlockDialect: Block-wise Fine-grained Mixed Format Quantization for Energy-Efficient LLM Inference
- [[ICML](https://arxiv.org/abs/2504.02692)] GPTAQ: Efficient Finetuning-Free Quantization with Asymmetric Calibration [[code](https://github.com/Intelligent-Computing-Lab-Panda/GPTAQ)] [![GitHub stars](https://img.shields.io/github/stars/Intelligent-Computing-Lab-Panda/GPTAQ?style=social)](https://github.com/Intelligent-Computing-Lab-Panda/GPTAQ)
- [[ICML](https://arxiv.org/abs/2501.17116)] Optimizing Large Language Model Training Using FP4 Quantization
- [[ICML](https://arxiv.org/abs/2412.04180)] SKIM: Any-bit Quantization Pushing The Limits of Post-Training Quantization
- [[ICML](https://arxiv.org/abs/2411.10958)] SageAttention2: Efficient Attention with Thorough Outlier Smoothing and Per-thread INT4 Quantization [[code](https://github.com/thu-ml/SageAttention)] [![GitHub stars](https://img.shields.io/github/stars/thu-ml/SageAttention?style=social)](https://github.com/thu-ml/SageAttention)
- [[AAAI](https://arxiv.org/abs/2409.14330)] Thinking in Granularity: Dynamic Quantization for Image Super-Resolution by Intriguing Multi-Granularity Clues [[code](https://github.com/MmmingS/Granular-DQ)] [![GitHub stars](https://img.shields.io/github/stars/MmmingS/Granular-DQ?style=social)](https://github.com/MmmingS/Granular-DQ)
- [[AAAI](https://arxiv.org/abs/2501.08180)] D2-DPM: Dual Denoising for Quantized Diffusion Probabilistic Models [[code](https://github.com/TaylorJocelyn/D2-DPM)] [![GitHub stars](https://img.shields.io/github/stars/TaylorJocelyn/D2-DPM?style=social)](https://github.com/TaylorJocelyn/D2-DPM)
- [[CVPR](https://arxiv.org/abs/2411.13918)] Quantization without Tears
- [[CVPR](https://arxiv.org/abs/2504.02508)] APHQ-ViT: Post-Training Quantization with Average Perturbation Hessian Based Reconstruction for Vision Transformer [[code](https://github.com/GoatWu/APHQ-ViT)] [![GitHub stars](https://img.shields.io/github/stars/GoatWu/APHQ-ViT?style=social)](https://github.com/GoatWu/APHQ-ViT)
- [[ICLR](https://openreview.net/forum?id=2rnOgyFQgb)] SynQ: Accurate Zero-shot Quantization by Synthesis-aware Fine-tuning [[code](https://github.com/snudm-starlab/SynQ)] [![GitHub stars](https://img.shields.io/github/stars/snudm-starlab/SynQ?style=social)](https://github.com/snudm-starlab/SynQ)

### 2024

- [[ICML](https://openreview.net/forum?id=qOl2WWOqFg)] BiLLM: Pushing the Limit of Post-Training Quantization for LLMs [[code](https://github.com/Aaronhuang-778/BiLLM)] [![GitHub stars](https://img.shields.io/github/stars/Aaronhuang-778/BiLLM?style=social)](https://github.com/Aaronhuang-778/BiLLM)
- [[ICML](https://openreview.net/forum?id=sCGRhnuMUJ)] Compressing Large Language Models by Joint Sparsification and Quantization
- [[NeurIPS](https://nips.cc/virtual/2024/poster/93620)] BiDM: Pushing the Limit of Quantization for Diffusion Models
- [[ACL Findings](https://aclanthology.org/2024.findings-acl.516/)] DB-LLM: Accurate Dual-Binarization for Efficient LLMs
- [[NeurIPS](https://neurips.cc/virtual/2024/poster/93008)] Binarized Diffusion Model for Image Super-Resolution [[code](https://github.com/zhengchen1999/BI-DiffSR)] [![GitHub stars](https://img.shields.io/github/stars/zhengchen1999/BI-DiffSR?style=social)](https://github.com/zhengchen1999/BI-DiffSR)
- [[NeurIPS](https://openreview.net/forum?id=ADJASE9uQ2)] 2DQuant: Low-bit Post-Training Quantization for Image Super-Resolution [[code](https://github.com/Kai-Liu001/2DQuant)] [![GitHub stars](https://img.shields.io/github/stars/Kai-Liu001/2DQuant?style=social)](https://github.com/Kai-Liu001/2DQuant)
- [[ICML](https://proceedings.mlr.press/v235/qin24b.html)] Accurate LoRA-Finetuning Quantization of LLMs via Information Retention [[code](https://github.com/htqin/IR-QLoRA)] [![GitHub stars](https://img.shields.io/github/stars/htqin/IR-QLoRA?style=social)](https://github.com/htqin/IR-QLoRA)
- [[ICML](https://proceedings.mlr.press/v235/zhang24bb.html)] Flexible Residual Binarization for Image Super-Resolution
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/29860)] Agile-Quant: Activation-Guided Quantization for Faster Inference of LLMs on the Edge
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/29487)] AQ-DETR: Low-Bit Quantized Detection Transformer with Auxiliary Queries
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/28109)] Bi-ViT: Pushing the Limit of Vision Transformer Quantization
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/29908)] Exploring Post-training Quantization in LLMs from Comprehensive Study to Low Rank Compensation
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/29045)] Make RepVGG Greater Again: A Quantization-Aware Approach
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/29212)] MetaMix: Meta-State Precision Searcher for Mixed-Precision Activation Quantization
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/29815)] Norm Tweaking: High-Performance Low-Bit Quantization of Large Language Models
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/29237)] OWQ: Outlier-Aware Weight Quantization for Efficient Fine-Tuning and Inference of Large Language Models
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/29553)] PTMQ: Post-training Multi-Bit Quantization of Neural Networks
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/28972)] Robustness-Guided Image Synthesis for Data-Free Quantization
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/29765)] What Makes Quantization for Large Language Model Hard? An Empirical Study from the Lens of Perturbation
- [[ACL](https://aclanthology.org/2024.acl-long.612/)] Improving Conversational Abilities of Quantized Large Language Models via Direct Preference Alignment
- [[ACM MM](https://dl.acm.org/doi/abs/10.1145/3664647.3680838)] Advancing Multimodal Large Language Models with Quantization-Aware Scale Learning Based on Warmup
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2024/html/Fan_Data-Free_Quantization_via_Pseudo-label_Filtering_CVPR_2024_paper.html)] Data-Free Quantization via Pseudo-label Filtering
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2024/html/Shang_Enhancing_Post-training_Quantization_Calibration_through_Contrastive_Learning_CVPR_2024_paper.html)] Enhancing Post-training Quantization Calibration through Contrastive Learning
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2024/html/Moon_Instance-Aware_Group_Quantization_for_Vision_Transformers_CVPR_2024_paper.html)] Instance-Aware Group Quantization for Vision Transformers
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2024/html/Chen_Mixed-Precision_Quantization_for_Federated_Learning_on_Resource-Constrained_Heterogeneous_Devices_CVPR_2024_paper.html)] Mixed-Precision Quantization for Federated Learning on Resource-Constrained Heterogeneous Devices
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2024/html/Lv_PTQ4SAM_Post-Training_Quantization_for_Segment_Anything_CVPR_2024_paper.html)] PTQ4SAM: Post-Training Quantization for Segment Anything
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2024/html/Ding_Reg-PTQ_Regression-specialized_Post-training_Quantization_for_Fully_Quantized_Object_Detector_CVPR_2024_paper.html)] Reg-PTQ: Regression-specialized Post-training Quantization for Fully Quantized Object Detector
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2024/html/Tang_Retraining-Free_Model_Quantization_via_One-Shot_Weight-Coupling_Learning_CVPR_2024_paper.html)] Retraining-Free Model Quantization via One-Shot Weight-Coupling Learning
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2024/html/Huang_TFMQ-DM_Temporal_Feature_Maintenance_Quantization_for_Diffusion_Models_CVPR_2024_paper.html)] TFMQ-DM: Temporal Feature Maintenance Quantization for Diffusion Models
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2024/html/Wang_Towards_Accurate_Post-training_Quantization_for_Diffusion_Models_CVPR_2024_paper.html)] Towards Accurate Post-training Quantization for Diffusion Models
- [[ECCV](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/3969_ECCV_2024_paper.php)] AdaLog: Post-Training Quantization for Vision Transformers with Adaptive Logarithm Quantizer
- [[ECCV](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/8434_ECCV_2024_paper.php)] CLAMP-ViT: Contrastive Data-Free Learning for Adaptive Post-Training Quantization of ViTs
- [[ECCV](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/2494_ECCV_2024_paper.php)] Memory-Efficient Fine-Tuning for Quantized Diffusion Model
- [[ECCV](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/3914_ECCV_2024_paper.php)] MetaAug: Meta-Data Augmentation for Post-Training Quantization
- [[ECCV](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/2212_ECCV_2024_paper.php)] MixDQ: Memory-Efficient Few-Step Text-to-Image Diffusion Models with Metric-Decoupled Mixed Precision Quantization
- [[ECCV](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/2121_ECCV_2024_paper.php)] Overcoming Distribution Mismatch in Quantizing Image Super-Resolution Networks
- [[ECCV](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/7353_ECCV_2024_paper.php)] Post-training Quantization with Progressive Calibration and Activation Relaxing for Text-to-Image Diffusion Models
- [[ECCV](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/1627_ECCV_2024_paper.php)] PQ-SAM: Post-training Quantization for Segment Anything Model
- [[ECCV](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/8312_ECCV_2024_paper.php)] Timestep-Aware Correction for Quantized Diffusion Models
- [[ECCV](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/9567_ECCV_2024_paper.php)] Towards Robust Full Low-bit Quantization of Super Resolution Networks
- [[EMNLP](https://aclanthology.org/2024.emnlp-main.1168/)] ApiQ: Finetuning of 2-Bit Quantized Large Language Model
- [[EMNLP](https://aclanthology.org/2024.emnlp-main.134/)] Prefixing Attention Sinks can Mitigate Activation Outliers for Large Language Model Quantization
- [[EMNLP](https://aclanthology.org/2024.emnlp-main.467/)] VPTQ: Extreme Low-bit Vector Post-Training Quantization for Large Language Models
- [[ICLR](https://openreview.net/forum?id=of2rhALq8l)] AffineQuant: Affine Transformation Quantization for Large Language Models [[code](https://github.com/bytedance/AffineQuant)] [![GitHub stars](https://img.shields.io/github/stars/bytedance/AffineQuant?style=social)](https://github.com/bytedance/AffineQuant)
- [[ICLR](https://openreview.net/forum?id=UmMa3UNDAz)] EfficientDM: Efficient Quantization-Aware Fine-Tuning of Low-Bit Diffusion Models
- [[ICLR](https://openreview.net/forum?id=0d1gQI114C)] LiDAR-PTQ: Post-Training Quantization for Point Cloud 3D Object Detection
- [[ICLR](https://openreview.net/forum?id=LzPWWPAdY4)] LoftQ: LoRA-Fine-Tuning-aware Quantization for Large Language Models [[code](https://github.com/yxli2123/LoftQ)] [![GitHub stars](https://img.shields.io/github/stars/yxli2123/LoftQ?style=social)](https://github.com/yxli2123/LoftQ)
- [[ICLR](https://openreview.net/forum?id=gLARhFLE0F)] LUT-GEMM: Quantized Matrix Multiplication based on LUTs for Efficient Inference in Large-Scale Generative Language Models
- [[ICLR](https://openreview.net/forum?id=8Wuvhh0LYW)] OmniQuant: Omnidirectionally Calibrated Quantization for Large Language Models [[code](https://github.com/OpenGVLab/OmniQuant)] [![GitHub stars](https://img.shields.io/github/stars/OpenGVLab/OmniQuant?style=social)](https://github.com/OpenGVLab/OmniQuant)
- [[ICLR](https://openreview.net/forum?id=BifeBRhikU)] PB-LLM: Partially Binarized Large Language Models [[code](https://github.com/hahnyuan/PB-LLM)] [![GitHub stars](https://img.shields.io/github/stars/hahnyuan/PB-LLM?style=social)](https://github.com/hahnyuan/PB-LLM)
- [[ICLR](https://openreview.net/forum?id=WvFoJccpo8)] QA-LoRA: Quantization-Aware Low-Rank Adaptation of Large Language Models [[code](https://github.com/yuhuixu1993/qa-lora)] [![GitHub stars](https://img.shields.io/github/stars/yuhuixu1993/qa-lora?style=social)](https://github.com/yuhuixu1993/qa-lora)
- [[ICLR](https://openreview.net/forum?id=FIplmUWdm3)] QLLM: Accurate and Efficient Low-Bitwidth Quantization for Large Language Models
- [[ICLR](https://openreview.net/forum?id=JzG7kSpjJk)] Rethinking Channel Dimensions to Isolate Outliers for Low-bit Weight Quantization of Large Language Models
- [[ICLR](https://openreview.net/forum?id=Q1u25ahSuy)] SpQR: A Sparse-Quantized Representation for Near-Lossless LLM Weight Compression [[code](https://github.com/Vahe1994/SpQR)] [![GitHub stars](https://img.shields.io/github/stars/Vahe1994/SpQR?style=social)](https://github.com/Vahe1994/SpQR)
- [[ICML](https://openreview.net/forum?id=mbx2pLK5Eq)] A2Q+: Improving Accumulator-Aware Weight Quantization
- [[ICML](https://openreview.net/forum?id=DbyHDYslM7)] BiE: Bi-Exponent Block Floating-Point for Large Language Models Quantization
- [[ICML](https://openreview.net/forum?id=jKUWlgra9b)] ERQ: Error Reduction for Post-Training Quantization of Vision Transformers
- [[ICML](https://openreview.net/forum?id=DKKg5EFAFr)] Evaluating Quantized Large Language Models
- [[ICML](https://openreview.net/forum?id=5mCaITRTmO)] Extreme Compression of Large Language Models via Additive Quantization
- [[ICML](https://openreview.net/forum?id=xPypr0kufs)] FrameQuant: Flexible Low-Bit Quantization for Transformers
- [[ICML](https://openreview.net/forum?id=L057s2Rq8O)] KIVI: A Tuning-Free Asymmetric 2bit Quantization for KV Cache [[code](https://github.com/jy-yuan/KIVI)] [![GitHub stars](https://img.shields.io/github/stars/jy-yuan/KIVI?style=social)](https://github.com/jy-yuan/KIVI)
- [[ICML](https://openreview.net/forum?id=dh8k41g775)] LQER: Low-Rank Quantization Error Reconstruction for LLMs
- [[ICML](https://openreview.net/forum?id=Uh5XN9d2J4)] Outlier-aware Slicing for Post-Training Quantization in Vision Transformer
- [[ICML](https://openreview.net/forum?id=8mKXMnhnFW)] Sharpness-Aware Data Generation for Zero-shot Quantization
- [[ICML](https://openreview.net/forum?id=0jpbpFia8m)] SqueezeLLM: Dense-and-Sparse Quantization [[code](https://github.com/SqueezeAILab/SqueezeLLM)] [![GitHub stars](https://img.shields.io/github/stars/SqueezeAILab/SqueezeLLM?style=social)](https://github.com/SqueezeAILab/SqueezeLLM)
- [[MLSys](https://proceedings.mlsys.org/paper_files/paper/2024/hash/42a452cbafa9dd64e9ba4aa95cc1ef21-Abstract-Conference.html)] AWQ: Activation-aware Weight Quantization for On-Device LLM Compression and Acceleration [[code](https://github.com/mit-han-lab/llm-awq)] [![GitHub stars](https://img.shields.io/github/stars/mit-han-lab/llm-awq?style=social)](https://github.com/mit-han-lab/llm-awq)
- [[NeurIPS](https://nips.cc/virtual/2024/poster/96909)] BitsFusion: 1.99 bits Weight Quantization of Diffusion Model
- [[NeurIPS](https://nips.cc/virtual/2024/poster/93727)] DuQuant: Distributing Outliers via Dual Transformation Makes Stronger Quantized LLMs
- [[NeurIPS](https://nips.cc/virtual/2024/poster/93558)] KV Cache is 1 Bit Per Channel: Efficient Large Language Model Inference with Coupled Quantization
- [[NeurIPS](https://nips.cc/virtual/2024/poster/96936)] KVQuant: Towards 10 Million Context Length LLM Inference with KV Cache Quantization
- [[NeurIPS](https://nips.cc/virtual/2024/poster/95445)] PTQ4DiT: Post-training Quantization for Diffusion Transformers
- [[NeurIPS](https://nips.cc/virtual/2024/poster/94107)] Q-VLM: Post-training Quantization for Large Vision-Language Models
- [[NeurIPS](https://nips.cc/virtual/2024/poster/95634)] QBB: Quantization with Binary Bases for LLMs
- [[NeurIPS](https://nips.cc/virtual/2024/poster/96563)] ZipCache: Accurate and Efficient KV Cache Quantization with Salient Token Identification
- [[ACL Findings](https://aclanthology.org/2024.findings-acl.726/)] A Comprehensive Evaluation of Quantization Strategies for Large Language Models
- [[ACL Findings](https://aclanthology.org/2024.findings-acl.3/)] AFPQ: Asymmetric Floating Point Quantization for LLMs [[code](https://github.com/zhangsichengsjtu/AFPQ)] [![GitHub stars](https://img.shields.io/github/stars/zhangsichengsjtu/AFPQ?style=social)](https://github.com/zhangsichengsjtu/AFPQ)
- [[ACL Findings](https://aclanthology.org/2024.findings-acl.26/)] LLM-QAT: Data-Free Quantization Aware Training for Large Language Models
- [[EMNLP Findings](https://aclanthology.org/2024.findings-emnlp.1001/)] ATQ: Activation Transformation for Weight-Activation Quantization of LLMs
- [[EMNLP Findings](https://aclanthology.org/2024.findings-emnlp.444/)] Fine-tuning Rotated Outlier-free LLMs for Effective Weight-Activation Quantization
- [[EMNLP Findings](https://aclanthology.org/2024.findings-emnlp.935/)] How Does Quantization Affect Multilingual LLMs?
- [[EMNLP Findings](https://aclanthology.org/2024.findings-emnlp.570/)] MobileQuant: Mobile-friendly Quantization for On-device Language Models
- [[EMNLP Findings](https://aclanthology.org/2024.findings-emnlp.811/)] QEFT: Quantization for Efficient Fine-Tuning of LLMs
- [[EMNLP Industry](https://aclanthology.org/2024.emnlp-industry.12/)] LLMC: Benchmarking Large Language Model Quantization with a Versatile Compression Toolkit
- [[arXiv](https://arxiv.org/abs/2402.14866)] APTQ: Attention-aware Post-Training Mixed-Precision Quantization for Large Language Models
- [[arXiv](https://arxiv.org/abs/2403.02775)] EasyQuant: An Efficient Data-free Quantization Algorithm for LLMs
- [[arXiv](https://arxiv.org/abs/2402.10787)] EdgeQAT: Entropy and Distribution Guided Quantization-Aware Training for the Acceleration of Lightweight LLMs on the Edge [[code](https://github.com/shawnricecake/EdgeQAT)] [![GitHub stars](https://img.shields.io/github/stars/shawnricecake/EdgeQAT?style=social)](https://github.com/shawnricecake/EdgeQAT)
- [[arXiv](https://arxiv.org/abs/2402.17985)] FlattenQuant: Breaking Through the Inference Compute-bound for Large Language Models with Per-tensor Quantization
- [[arXiv](https://arxiv.org/abs/2402.15319)] GPTVQ: The Blessing of Dimensionality for LLM Quantization [[code](https://github.com/qualcomm-ai-research/gptvq)] [![GitHub stars](https://img.shields.io/github/stars/qualcomm-ai-research/gptvq?style=social)](https://github.com/qualcomm-ai-research/gptvq)
- [[arXiv](https://arxiv.org/abs/2403.01241)] IntactKV: Improving Large Language Model Quantization by Keeping Pivot Tokens Intact
- [[arXiv](https://arxiv.org/abs/2402.11295)] OneBit: Towards Extremely Low-bit Large Language Models
- [[arXiv](https://arxiv.org/abs/2404.00456)] QuaRot: Outlier-Free 4-Bit Inference in Rotated LLMs [[code](https://github.com/spcl/QuaRot)] [![GitHub stars](https://img.shields.io/github/stars/spcl/QuaRot?style=social)](https://github.com/spcl/QuaRot)
- [[arXiv](https://arxiv.org/abs/2402.05628)] RepQuant: Towards Accurate Post-Training Quantization of Large Transformer Models via Scale Reparameterization
- [[SIGMOD](https://dl.acm.org/doi/10.1145/3654970)] RaBitQ: Quantizing High-Dimensional Vectors with a Theoretical Error Bound for Approximate Nearest Neighbor Search [[code](https://github.com/gaoj0017/RaBitQ)] [![GitHub stars](https://img.shields.io/github/stars/gaoj0017/RaBitQ?style=social)](https://github.com/gaoj0017/RaBitQ)
- [[AAAI](https://arxiv.org/abs/2401.16760)] One-Step Forward and Backtrack: Overcoming Zig-Zagging in Loss-Aware Quantization Training
- [[ICML](https://arxiv.org/abs/2405.03103)] Learning from students: Applying t-distributions to explore accurate and efficient formats for llms [[code](https://github.com/cornell-zhang/llm-datatypes)] [![GitHub stars](https://img.shields.io/github/stars/cornell-zhang/llm-datatypes?style=social)](https://github.com/cornell-zhang/llm-datatypes)
- [[ICML](https://arxiv.org/abs/2403.12422)] Jetfire: Efficient and Accurate Transformer Pretraining with INT8 Data Flow and Per-Block Quantization
- [[ICML](https://openreview.net/forum?id=fM9xTkpAdu)] Reshape and Adapt for Output Quantization (RAOQ): Quantization-aware Training for In-memory Computing Systems
- [[ICML](https://arxiv.org/abs/2402.04396)] QuIP#: Even Better LLM Quantization with Hadamard Incoherence and Lattice Codebooks [[code](https://github.com/Cornell-RelaxML/quip-sharp)] [![GitHub stars](https://img.shields.io/github/stars/Cornell-RelaxML/quip-sharp?style=social)](https://github.com/Cornell-RelaxML/quip-sharp)
- [[NeurIPS](https://arxiv.org/abs/2402.08958)] Towards Next-Level Post-Training Quantization of Hyper-Scale Transformers [[code](https://github.com/SamsungLabs/aespa)] [![GitHub stars](https://img.shields.io/github/stars/SamsungLabs/aespa?style=social)](https://github.com/SamsungLabs/aespa)
- [[NeurIPS](https://arxiv.org/abs/2406.00800)] MagR: Weight Magnitude Reduction for Enhancing Post-Training Quantization [[code](https://github.com/aozhongzhang/magr)] [![GitHub stars](https://img.shields.io/github/stars/aozhongzhang/magr?style=social)](https://github.com/aozhongzhang/magr)
- [[NeurIPS](https://arxiv.org/abs/2405.18137)] Exploiting LLM Quantization
- [[NeurIPS](https://openreview.net/forum?id=HfpV6u0kbX)] Efficient Multi-task LLM Quantization and Serving for Multiple LoRA Adapters
- [[NeurIPS](https://arxiv.org/abs/2406.11235)] QTIP: Quantization with Trellises and Incoherence Processing [[code](https://github.com/Cornell-RelaxML/qtip)] [![GitHub stars](https://img.shields.io/github/stars/Cornell-RelaxML/qtip?style=social)](https://github.com/Cornell-RelaxML/qtip)
- [[NeurIPS](https://openreview.net/forum?id=dYIqAZXQNV)] Generalizing CNNs to graphs with learnable neighborhood quantization [[code](https://github.com/Grosenick-Lab-Cornell/QuantNets)] [![GitHub stars](https://img.shields.io/github/stars/Grosenick-Lab-Cornell/QuantNets?style=social)](https://github.com/Grosenick-Lab-Cornell/QuantNets)
- [[NeurIPS](https://arxiv.org/abs/2410.15526)] SDP4Bit: Toward 4-bit Communication Quantization in Sharded Data Parallelism for LLM Training [[code](https://github.com/ByteDance-Seed/SDP4Bit)] [![GitHub stars](https://img.shields.io/github/stars/ByteDance-Seed/SDP4Bit?style=social)](https://github.com/ByteDance-Seed/SDP4Bit)
- [[NeurIPS](https://papers.nips.cc/paper_files/paper/2024/file/ab6a2c6ee757afe43882121281f6065c-Paper-Conference.pdf)] Optimal and Approximate Adaptive Stochastic Quantization [[code](https://github.com/ranbenbasat/QUIVER)] [![GitHub stars](https://img.shields.io/github/stars/ranbenbasat/QUIVER?style=social)](https://github.com/ranbenbasat/QUIVER)
- [[NeurIPS](https://arxiv.org/abs/2404.02837)] Cherry on Top: Parameter Heterogeneity and Quantization in Large Language Models
- [[NeurIPS](https://openreview.net/forum?id=cEtExbAKYV)] StepbaQ: Stepping backward as Correction for Quantized Diffusion Models

### 2023

- [[ICML](https://proceedings.mlr.press/v202/qin23a.html)] BiBench: Benchmarking and Analyzing Network Binarization [[code](https://github.com/htqin/BiBench)] [![GitHub stars](https://img.shields.io/github/stars/htqin/BiBench?style=social)](https://github.com/htqin/BiBench)
- [[IJCV](https://arxiv.org/abs/2109.12338)] Distribution-sensitive Information Retention for Accurate Binary Neural Network
- [[NeurIPS](https://neurips.cc/virtual/2023/poster/71287)] BiMatting: Efficient Video Matting via Binarization [[code](https://github.com/htqin/BiMatting)] [![GitHub stars](https://img.shields.io/github/stars/htqin/BiMatting?style=social)](https://github.com/htqin/BiMatting)
- [[NeurIPS](https://neurips.cc/virtual/2023/poster/72890)] QuantSR: Accurate Low-bit Quantization for Efficient Image Super-Resolution [[code](https://github.com/htqin/QuantSR)] [![GitHub stars](https://img.shields.io/github/stars/htqin/QuantSR?style=social)](https://github.com/htqin/QuantSR)
- [[TPAMI](https://ieeexplore.ieee.org/document/10146917)] Diverse Sample Generation: Pushing the Limit of Generative Data-Free Quantization [[code](https://github.com/htqin/DSG)] [![GitHub stars](https://img.shields.io/github/stars/htqin/DSG?style=social)](https://github.com/htqin/DSG)
- [[TNNLS](https://ieeexplore.ieee.org/document/10049753)] BiFSMNv2: Pushing Binary Neural Networks for Keyword Spotting to Real-Network Performance [[code](https://github.com/htqin/BiFSMNv2)] [![GitHub stars](https://img.shields.io/github/stars/htqin/BiFSMNv2?style=social)](https://github.com/htqin/BiFSMNv2)
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/26268)] Fast and Accurate Binary Neural Networks Based on Depth-Width Reshaping
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/26084)] OMPQ: Orthogonal Mixed Precision Quantization
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/26354)] Quantized Feature Distillation for Network Quantization
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/26261)] Resilient Binary Neural Network
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/26136)] Rethinking Data-Free Quantization as a Zero-Sum Game
- [[ACL](https://aclanthology.org/2023.findings-acl.15/)] Boost Transformer-based Language Models with GPU-Friendly Sparsity and Quantization
- [[ACL](https://arxiv.org/abs/2306.00014)] PreQuant: A Task-agnostic Quantization Approach for Pre-trained Language Models
- [[CVPR](https://ipl.dgist.ac.kr/ABCD_cvpr23.pdf)] ABCD : Arbitrary Bitwise Coefficient for De-quantization
- [[CVPR](https://arxiv.org/abs/2303.06869)] Adaptive Data-Free Quantization
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Lin_Bit-Shrinking_Limiting_Instantaneous_Sharpness_for_Improving_Post-Training_Quantization_CVPR_2023_paper.pdf)] Bit-shrinking: Limiting Instantaneous Sharpness for Improving Post-training Quantization
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Yu_Boost_Vision_Transformer_With_GPU-Friendly_Sparsity_and_Quantization_CVPR_2023_paper.pdf)] Boost Vision Transformer with GPU-Friendly Sparsity and Quantization
- [[CVPR](https://arxiv.org/abs/2212.04780)] GENIE: Show Me the Data for Quantization [[code](https://github.com/SamsungLabs/Genie)] [![GitHub stars](https://img.shields.io/github/stars/SamsungLabs/Genie?style=social)](https://github.com/SamsungLabs/Genie)
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2023/html/Li_Hard_Sample_Matters_a_Lot_in_Zero-Shot_Quantization_CVPR_2023_paper.html)] Hard Sample Matters a Lot in Zero-Shot Quantization
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Shin_NIPQ_Noise_Proxy-Based_Integrated_Pseudo-Quantization_CVPR_2023_paper.pdf)] NIPQ: Noise proxy-based Integrated Pseudo-Quantization
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_NoisyQuant_Noisy_Bias-Enhanced_Post-Training_Activation_Quantization_for_Vision_Transformers_CVPR_2023_paper.pdf)] NoisyQuant: Noisy Bias-Enhanced Post-Training Activation Quantization for Vision Transformers
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Koryakovskiy_One-Shot_Model_for_Mixed-Precision_Quantization_CVPR_2023_paper.pdf)] One-Shot Model for Mixed-Precision Quantization
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2023/html/Liu_PD-Quant_Post-Training_Quantization_Based_on_Prediction_Difference_Metric_CVPR_2023_paper.html)] PD-Quant: Post-Training Quantization Based on Prediction Difference Metric [[code](https://github.com/hustvl/PD-Quant)] [![GitHub stars](https://img.shields.io/github/stars/hustvl/PD-Quant?style=social)](https://github.com/hustvl/PD-Quant)
- [[CVPR](http://openaccess.thecvf.com/content/CVPR2023/html/Shang_Post-Training_Quantization_on_Diffusion_Models_CVPR_2023_paper.html)] Post-training Quantization on Diffusion Models [[code](https://https//github.com/42Shawn/PTQ4DM)]
- [[CVPR](http://openaccess.thecvf.com/content/CVPR2023/html/Xu_Q-DETR_An_Efficient_Low-Bit_Quantized_Detection_Transformer_CVPR_2023_paper.html)] Q-DETR: An Efficient Low-Bit Quantized Detection Transformer [[code](https://github.com/SteveTsui/Q-DETR)] [![GitHub stars](https://img.shields.io/github/stars/SteveTsui/Q-DETR?style=social)](https://github.com/SteveTsui/Q-DETR)
- [[CVPR](https://arxiv.org/abs/2303.06424)] Regularized Vector Quantization for Tokenized Image Synthesis
- [[CVPR](https://arxiv.org/pdf/2303.11906.pdf)] Solving Oscillation Problem in Post-Training Quantization Through a Theoretical Perspective [[code](https://github.com/bytedance/mrecg)] [![GitHub stars](https://img.shields.io/github/stars/bytedance/mrecg?style=social)](https://github.com/bytedance/mrecg)
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Tu_Toward_Accurate_Post-Training_Quantization_for_Image_Super_Resolution_CVPR_2023_paper.pdf)] Toward Accurate Post-Training Quantization for Image Super Resolution
- [[EMNLP](https://arxiv.org/abs/2310.16836)] LLM-FP4: 4-Bit Floating-Point Quantized Transformers [[code](https://github.com/nbasyl/LLM-FP4)] [![GitHub stars](https://img.shields.io/github/stars/nbasyl/LLM-FP4?style=social)](https://github.com/nbasyl/LLM-FP4)
- [[EMNLP](https://arxiv.org/abs/2304.09145)] Outlier Suppression+: Accurate quantization of large language models by equivalent and optimal shifting and scaling
- [[EMNLP](https://arxiv.org/abs/2310.05079)] Revisiting Block-based Quantisation: What is Important for Sub-8-bit LLM Inference?
- [[EMNLP](https://arxiv.org/abs/2310.11237)] Watermarking LLMs with Weight Quantization [[code](https://github.com/Twilight92z/Quantize-Watermark)] [![GitHub stars](https://img.shields.io/github/stars/Twilight92z/Quantize-Watermark?style=social)](https://github.com/Twilight92z/Quantize-Watermark)
- [[EMNLP](https://arxiv.org/abs/2310.13315)] Zero-Shot Sharpness-Aware Quantization for Pre-trained Language Models
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Colbert_A2Q_Accumulator-Aware_Quantization_with_Guaranteed_Overflow_Avoidance_ICCV_2023_paper.pdf)] A2Q: Accumulator-Aware Quantization with Guaranteed Overflow Avoidance
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/He_BiViT_Extremely_Compressed_Binary_Vision_Transformers_ICCV_2023_paper.pdf)] BiViT: Extremely Compressed Binary Vision Transformers
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Shang_Causal-DFQ_Causality_Guided_Data-Free_Network_Quantization_ICCV_2023_paper.pdf)] Causal-DFQ: Causality Guided Data-Free Network Quantization [[code](https://github.com/42Shawn/Causal-DFQ)] [![GitHub stars](https://img.shields.io/github/stars/42Shawn/Causal-DFQ?style=social)](https://github.com/42Shawn/Causal-DFQ)
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_DenseShift_Towards_Accurate_and_Efficient_Low-Bit_Power-of-Two_Quantization_ICCV_2023_paper.pdf)] DenseShift: Towards Accurate and Efficient Low-Bit Power-of-Two Quantization
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Dong_EMQ_Evolving_Training-free_Proxies_for_Automated_Mixed_Precision_Quantization_ICCV_2023_paper.pdf)] EMQ: Evolving Training-free Proxies for Automated Mixed Precision Quantization
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_EQ-Net_Elastic_Quantization_Neural_Networks_ICCV_2023_paper.pdf)] EQ-Net: Elastic Quantization Neural Networks [[code](https://github.com/xuke225/EQ-Net)] [![GitHub stars](https://img.shields.io/github/stars/xuke225/EQ-Net?style=social)](https://github.com/xuke225/EQ-Net)
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2023/html/Wu_Estimator_Meets_Equilibrium_Perspective_A_Rectified_Straight_Through_Estimator_for_ICCV_2023_paper.html)] Estimator Meets Equilibrium Perspective: A Rectified Straight Through Estimator for Binary Neural Networks Training [[code](https://github.com/DravenALG/ReSTE)] [![GitHub stars](https://img.shields.io/github/stars/DravenALG/ReSTE?style=social)](https://github.com/DravenALG/ReSTE)
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_I-ViT_Integer-only_Quantization_for_Efficient_Vision_Transformer_Inference_ICCV_2023_paper.pdf)] I-ViT: Integer-only Quantization for Efficient Vision Transformer Inference [[code](https://github.com/zkkli/I-ViT)] [![GitHub stars](https://img.shields.io/github/stars/zkkli/I-ViT?style=social)](https://github.com/zkkli/I-ViT)
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Frumkin_Jumping_through_Local_Minima_Quantization_in_the_Loss_Landscape_of_ICCV_2023_paper.pdf)] Jumping through Local Minima: Quantization in the Loss Landscape of Vision Transformers
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_Overcoming_Forgetting_Catastrophe_in_Quantization-Aware_Training_ICCV_2023_paper.pdf)] Overcoming Forgetting Catastrophe in Quantization-Aware Training
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Q-Diffusion_Quantizing_Diffusion_Models_ICCV_2023_paper.pdf)] Q-diffusion: Quantizing Diffusion Models [[code](https://github.com/Xiuyu-Li/q-diffusion)] [![GitHub stars](https://img.shields.io/github/stars/Xiuyu-Li/q-diffusion?style=social)](https://github.com/Xiuyu-Li/q-diffusion)
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_QD-BEV__Quantization-aware_View-guided_Distillation_for_Multi-view_3D_Object_Detection_ICCV_2023_paper.pdf)] QD-BEV: Quantization-aware View-guided Distillation for Multi-view 3D Object Detection
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_RepQ-ViT_Scale_Reparameterization_for_Post-Training_Quantization_of_Vision_Transformers_ICCV_2023_paper.pdf)] RepQ-ViT: Scale Reparameterization for Post-Training Quantization of Vision Transformers [[code](https://github.com/zkkli/RepQ-ViT)] [![GitHub stars](https://img.shields.io/github/stars/zkkli/RepQ-ViT?style=social)](https://github.com/zkkli/RepQ-ViT)
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Bai_Unified_Data-Free_Compression_Pruning_and_Quantization_without_Fine-Tuning_ICCV_2023_paper.pdf)] Unified Data-Free Compression: Pruning and Quantization without Fine-Tuning
- [[ICLR](https://openreview.net/forum?id=3itjR9QxFw)] Analog Bits: Generating Discrete Data using Diffusion Models with Self-Conditioning
- [[ICLR](https://arxiv.org/abs/2210.17323)] GPTQ: Accurate Post-Training Quantization for Generative Pre-trained Transformers [[code](https://github.com/IST-DASLab/gptq)] [![GitHub stars](https://img.shields.io/github/stars/IST-DASLab/gptq?style=social)](https://github.com/IST-DASLab/gptq)
- [[ICML](https://openreview.net/forum?id=m2S96Qf2R3)] Few-bit Backward: Quantized Gradients of Activation Functions for Memory Footprint Reduction [[code](https://github.com/SkoltechAI/fewbit)] [![GitHub stars](https://img.shields.io/github/stars/SkoltechAI/fewbit?style=social)](https://github.com/SkoltechAI/fewbit)
- [[ICML](https://openreview.net/forum?id=EPnzNJTYsb)] FlexRound: Learnable Rounding based on Element-wise Division for Post-Training Quantization [[code](https://openreview.net/attachment?id=-tYCaP0phY_&name=supplementary_material)]
- [[ICML](https://icml.cc/virtual/2023/28295)] GPT-Zip: Deep Compression of Finetuned Large Language Models
- [[ICML](https://openreview.net/forum?id=DihXH24AdY)] Oscillation-free Quantization for Low-bit Vision Transformers [[code](https://github.com/nbasyl/OFQ)] [![GitHub stars](https://img.shields.io/github/stars/nbasyl/OFQ?style=social)](https://github.com/nbasyl/OFQ)
- [[ICML](https://arxiv.org/abs/2307.03738)] QIGen: Generating Efficient Kernels for Quantized Inference on Large Language Models [[code](https://github.com/IST-DASLab/QIGen)] [![GitHub stars](https://img.shields.io/github/stars/IST-DASLab/QIGen?style=social)](https://github.com/IST-DASLab/QIGen)
- [[ICML](https://openreview.net/forum?id=Nqp8A5IDzq)] Quantized Distributed Training of Large Models with Convergence Guarantees
- [[ICML](https://arxiv.org/abs/2211.10438)] SmoothQuant: Accurate and Efficient Post-Training Quantization for Large Language Models [[code](https://github.com/mit-han-lab/smoothquant)] [![GitHub stars](https://img.shields.io/github/stars/mit-han-lab/smoothquant?style=social)](https://github.com/mit-han-lab/smoothquant)
- [[ICML](https://openreview.net/forum?id=i8tGb1ab1j)] The case for 4-bit precision: k-bit Inference Scaling Laws
- [[ICML](https://openreview.net/forum?id=q1WGm3hItW)] Understanding Int4 Quantization for Language Models: Latency Speedup, Composability, and Failure Cases
- [[ICML](https://arxiv.org/abs/2301.12017)] Understanding INT4 Quantization for Transformer Models: Latency Speedup, Composability, and Failure Cases [[code](https://github.com/microsoft/DeepSpeed)] [![GitHub stars](https://img.shields.io/github/stars/microsoft/DeepSpeed?style=social)](https://github.com/microsoft/DeepSpeed)
- [[NeurIPS](https://arxiv.org/abs/2305.10299)] Binarized Spectral Compressive Imaging [[code](https://github.com/caiyuanhao1998/BiSCI)] [![GitHub stars](https://img.shields.io/github/stars/caiyuanhao1998/BiSCI?style=social)](https://github.com/caiyuanhao1998/BiSCI)
- [[NeurIPS](https://neurips.cc/virtual/2023/poster/72931)] Memory-Efficient Fine-Tuning of Compressed Large Language Models via sub-4-bit Integer Quantization
- [[NeurIPS](https://neurips.cc/virtual/2023/poster/71880)] PackQViT: Faster Sub-8-bit Vision Transformers via Full and Packed Quantization on the Mobile
- [[NeurIPS](https://neurips.cc/virtual/2023/poster/71314)] PTQD: Accurate Post-Training Quantization for Diffusion Models [[code](https://github.com/ziplab/PTQD)] [![GitHub stars](https://img.shields.io/github/stars/ziplab/PTQD?style=social)](https://github.com/ziplab/PTQD)
- [[NeurIPS](https://neurips.cc/virtual/2023/poster/70279)] Q-DM: An Efficient Low-bit Quantized Diffusion Model
- [[NeurIPS](https://neurips.cc/virtual/2023/poster/71815)] QLoRA: Efficient Finetuning of Quantized LLMs [[code](https://github.com/artidoro/qlora)] [![GitHub stars](https://img.shields.io/github/stars/artidoro/qlora?style=social)](https://github.com/artidoro/qlora)
- [[NeurIPS](https://neurips.cc/virtual/2023/poster/69982)] QuIP: 2-Bit Quantization of Large Language Models With Guarantees [[code](https://github.com/jerry-chee/QuIP)] [![GitHub stars](https://img.shields.io/github/stars/jerry-chee/QuIP?style=social)](https://github.com/jerry-chee/QuIP)
- [[NeurIPS](https://neurips.cc/virtual/2023/poster/72396)] Temporal Dynamic Quantization for Diffusion Models
- [[NeurIPS](https://neurips.cc/virtual/2023/poster/70325)] TexQ: Zero-shot Network Quantization with Texture Feature Distribution Calibration
- [[NeurIPS](https://neurips.cc/virtual/2023/poster/71526)] Understanding Neural Network Binarization with Forward and Backward Proximal Quantizers
- [[TIP](https://ieeexplore.ieee.org/abstract/document/10107717)] MBFQuant: A Multiplier-Bitwidth-Fixed, Mixed-Precision Quantization Method for Mobile CNN-Based Applications
- [[TPAMI](https://ieeexplore.ieee.org/abstract/document/9735379)] Optimization-Based Post-Training Quantization With Bit-Split and Stitching
- [[TPAMI](https://ieeexplore.ieee.org/abstract/document/10122994)] Single-path Bit Sharing for Automatic Loss-aware Model Compression
- [[arXiv](https://arxiv.org/abs/2310.19102)] Atom: Low-bit Quantization for Efficient and Accurate LLM Serving [[code](https://github.com/efeslab/Atom)] [![GitHub stars](https://img.shields.io/github/stars/efeslab/Atom?style=social)](https://github.com/efeslab/Atom)
- [[arXiv](https://arxiv.org/abs/2309.14592)] Efficient Post-training Quantization with FP8 Formats [[code](https://github.com/intel/neural-compressor)] [![GitHub stars](https://img.shields.io/github/stars/intel/neural-compressor?style=social)](https://github.com/intel/neural-compressor)
- [[arXiv](https://arxiv.org/abs/2310.07147)] QFT: Quantized Full-parameter Tuning of LLMs with Affordable Resources
- [[arXiv](https://arxiv.org/abs/2310.16795)] QMoE: Practical Sub-1-Bit Compression of Trillion-Parameter Models
- [[arXiv](https://arxiv.org/abs/2304.01089)] RPTQ: Reorder-based Post-training Quantization for Large Language Models [[code](https://github.com/hahnyuan/RPTQ4LLM)] [![GitHub stars](https://img.shields.io/github/stars/hahnyuan/RPTQ4LLM?style=social)](https://github.com/hahnyuan/RPTQ4LLM)
- [[arXiv](https://arxiv.org/abs/2310.17723)] ZeroQuant-HERO: Hardware-Enhanced Robust Optimized Post-Training Quantization Framework for W8A8 Transformers
- [[AAAI](https://arxiv.org/abs/2211.16187)] Quantization-Aware Interval Bound Propagation for Training Certifiably Robust Quantized Neural Networks [[code](https://github.com/mlech26l/quantization_aware_ibp)] [![GitHub stars](https://img.shields.io/github/stars/mlech26l/quantization_aware_ibp?style=social)](https://github.com/mlech26l/quantization_aware_ibp)
- [[ICLR](https://openreview.net/forum?id=s1KljJpAukm)] PowerQuant:Automorphism Search For Non-Uniform Quantization
- [[ICLR](https://openreview.net/forum?id=VWm4o4l3V9e)] Block and Subword-Scaling Floating-Point (BSFP) : An Efficient Non-Uniform Quantization For Low Precision Inference
- [[NeurIPS](https://arxiv.org/abs/2203.14645)] REx: Data-Free Residual Quantization Error Expansion
- [[NeurIPS](https://arxiv.org/abs/2305.19268)] Intriguing Properties of Quantization at Scale
- [[NeurIPS](https://arxiv.org/abs/2306.11987)] Training Transformers with 4-bit Integers [[code](https://github.com/xijiu9/Train_Transformers_with_INT4)] [![GitHub stars](https://img.shields.io/github/stars/xijiu9/Train_Transformers_with_INT4?style=social)](https://github.com/xijiu9/Train_Transformers_with_INT4)
- [[NeurIPS](https://papers.nips.cc/paper_files/paper/2023/file/400a2e6a82520b690810b97fd67fcc4e-Paper-Conference.pdf)] Towards Efficient and Accurate Winograd Convolution via Full Quantization
- [[NeurIPS](https://papers.nips.cc/paper_files/paper/2023/file/c48bc80aa5d3cbbdd712d1cc107b8319-Paper-Conference.pdf)] Pruning vs Quantization: Which is Better? [[code](https://github.com/Qualcomm-AI-research/pruning-vs-quantization)] [![GitHub stars](https://img.shields.io/github/stars/Qualcomm-AI-research/pruning-vs-quantization?style=social)](https://github.com/Qualcomm-AI-research/pruning-vs-quantization)
- [[ICLR](https://openreview.net/forum?id=7L2mgi0TNEP)] A^2Q: Aggregation-Aware Quantization for Graph Neural Networks

### 2022

- [[ICLR](https://openreview.net/forum?id=5xEgrl_5FAJ)] BiBERT: Accurate Fully Binarized BERT. [code](https://github.com/htqin/BiBERT)]
- [[IJCAI](https://arxiv.org/abs/2202.06483)] BiFSMN: Binary Neural Network for Keyword Spotting [[code](https://github.com/htqin/BiFSMN)] [![GitHub stars](https://img.shields.io/github/stars/htqin/BiFSMN?style=social)](https://github.com/htqin/BiFSMN)
- [[ACM MM](https://arxiv.org/abs/2303.14341)] Towards Accurate Post-Training Quantizationfor Vision Transformer
- [[ACL](https://aclanthology.org/2022.acl-long.331)] Compression of Generative Pre-trained Language Models via Quantization
- [[ACM Trans. Des. Autom. Electron. Syst.](https://web.archive.org/web/20220722092230id_/https://dl.acm.org/doi/pdf/10.1145/3549535)] Structured Dynamic Precision for Deep Neural Networks uantization
- [[ASE](https://dl.acm.org/doi/abs/10.1145/3551349.3556916)] QVIP: An ILP-based Formal Verification Approach for Quantized Neural Networks
- [[Applied Soft Computing](https://www.sciencedirect.com/science/article/pii/S1568494622005038)] A neural network compression method based on knowledge-distillation and parameter quantization for the bearing fault diagnosis
- [[CCF Transactions on High Performance Computing](https://link.springer.com/article/10.1007/s42514-022-00121-z)] An efficient segmented quantization for graph neural networks
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2022W/ECV/papers/Jiang_A_Low_Memory_Footprint_Quantized_Neural_Network_for_Depth_Completion_CVPRW_2022_paper.pdf)] A Low Memory Footprint Quantized Neural Network for Depth Completion of Very Sparse Time-of-Flight Depth Maps
- [[CVPR](https://ieeexplore.ieee.org/document/9879477/)] BppAttack: Stealthy and Efficient Trojan Attacks against Deep Neural Networks via Image Quantization and Contrastive Adversarial Learning [[code](https://github.com/RU-System-Software-and-Security/BppAttack)] [![GitHub stars](https://img.shields.io/github/stars/RU-System-Software-and-Security/BppAttack?style=social)](https://github.com/RU-System-Software-and-Security/BppAttack)
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Chikin_Data-Free_Network_Compression_via_Parametric_Non-Uniform_Mixed_Precision_Quantization_CVPR_2022_paper.pdf)] Data-Free Network Compression via Parametric Non-uniform Mixed Precision Quantization
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Instance-Aware_Dynamic_Neural_Network_Quantization_CVPR_2022_paper.pdf)] Instance-Aware Dynamic Neural Network Quantization
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2022/html/Zhong_IntraQ_Learning_Synthetic_Images_With_Intra-Class_Heterogeneity_for_Zero-Shot_Network_CVPR_2022_paper.html)] IntraQ: Learning Synthetic Images With Intra-Class Heterogeneity for Zero-Shot Network Quantization [[code](https://github.com/zysxmu/IntraQ)] [![GitHub stars](https://img.shields.io/github/stars/zysxmu/IntraQ?style=social)](https://github.com/zysxmu/IntraQ)
- [[CVPR](https://arxiv.org/abs/2203.17008)] It's All In the Teacher: Zero-Shot Quantization Brought Closer to the Teacher [[code](https://github.com/iamkanghyunchoi/ait)] [![GitHub stars](https://img.shields.io/github/stars/iamkanghyunchoi/ait?style=social)](https://github.com/iamkanghyunchoi/ait)
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Learnable_Lookup_Table_for_Neural_Network_Quantization_CVPR_2022_paper.pdf)] Learnable Lookup Table for Neural Network Quantization [[code](https://github.com/The-Learning-And-Vision-Atelier-LAVA/LLT)] [![GitHub stars](https://img.shields.io/github/stars/The-Learning-And-Vision-Atelier-LAVA/LLT?style=social)](https://github.com/The-Learning-And-Vision-Atelier-LAVA/LLT)
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Jeon_Mr.BiQ_Post-Training_Non-Uniform_Quantization_Based_on_Minimizing_the_Reconstruction_Error_CVPR_2022_paper.pdf)] Mr.BiQ: Post-Training Non-Uniform Quantization based on Minimizing the Reconstruction Error
- [[CVPR](https://arxiv.org/abs/2111.14826)] Nonuniform-to-Uniform Quantization: Towards Accurate Quantization via Generalized Straight-Through Estimation [[code](https://github.com/liuzechun/Nonuniform-to-Uniform-Quantization)] [![GitHub stars](https://img.shields.io/github/stars/liuzechun/Nonuniform-to-Uniform-Quantization?style=social)](https://github.com/liuzechun/Nonuniform-to-Uniform-Quantization)
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2022/html/Guo_RecDis-SNN_Rectifying_Membrane_Potential_Distribution_for_Directly_Training_Spiking_Neural_CVPR_2022_paper.html)] RecDis-SNN: Rectifying Membrane Potential Distribution for Directly Training Spiking Neural Networks
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2022W/ECV/papers/van_Baalen_Simulated_Quantization_Real_Power_Savings_CVPRW_2022_paper.pdf)] Simulated Quantization, Real Power Savings
- [[EANN](https://link.springer.com/chapter/10.1007/978-3-031-08223-8_35)] A Robust, Quantization-Aware Training Method for Photonic Neural Networks
- [[ECCV](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136720017.pdf)] BASQ: Branch-wise Activation-clipping Search Quantization for Sub-4-bit Neural Networks [[code](https://github.com/HanByulKim/BASQ)] [![GitHub stars](https://img.shields.io/github/stars/HanByulKim/BASQ?style=social)](https://github.com/HanByulKim/BASQ)
- [[ECCV](https://arxiv.org/abs/2203.08368)] Mixed-Precision Neural Network Quantization via Learned Layer-Wise Importance [[code](https://github.com/1hunters/LIMPQ)] [![GitHub stars](https://img.shields.io/github/stars/1hunters/LIMPQ?style=social)](https://github.com/1hunters/LIMPQ)
- [[ECCV](https://link.springer.com/chapter/10.1007/978-3-031-20071-7_37)] Neuromorphic Data Augmentation for Training Spiking Neural Networks. [[code]](https://github.com/Intelligent-Computing-Lab-Yale/NDA_SNN)
- [[ECCV](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136710657.pdf)] Non-Uniform Step Size Quantization for Accurate Post-Training Quantization
- [[ECCV](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136710154.pdf)] Patch Similarity Aware Data-Free Quantization for Vision Transformers [[code](https://github.com/zkkli/psaq-vit)] [![GitHub stars](https://img.shields.io/github/stars/zkkli/psaq-vit?style=social)](https://github.com/zkkli/psaq-vit)
- [[ECCV](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136720190.pdf)] PTQ4ViT: Post-Training Quantization for Vision Transformers with Twin Uniform Quantization [[code](https://github.com/hahnyuan/ptq4vit)] [![GitHub stars](https://img.shields.io/github/stars/hahnyuan/ptq4vit?style=social)](https://github.com/hahnyuan/ptq4vit)
- [[ECCV](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136720156.pdf)] RDO-Q: Extremely Fine-Grained Channel-Wise Quantization via Rate-Distortion Optimization
- [[ECCV](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136710207.pdf)] Symmetry Regularization and Saturating Nonlinearity for Robust Quantization
- [[ECCV](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136710726.pdf)] Towards Accurate Network Quantization with Equivalent Smooth Regularizer
- [[ECCV](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136710416.pdf)] Weight Fixing Networks. [[code]](https://github.com/subiawaud/Weight_Fix_Networks)
- [[ESE](https://link.springer.com/article/10.1007/s10664-022-10202-w)] DiverGet: a Search-Based Software Testing approach for Deep Neural Network Quantization assessment
- [[Electronics](https://www.mdpi.com/2079-9292/11/6/945)] A Survey on Efficient Convolutional Neural Networks and Hardware Acceleration
- [[FPGA](https://dl.acm.org/doi/abs/10.1145/3490422.3502364)] FILM-QNN: Efficient FPGA Acceleration of Deep Neural Networks with Intra-Layer, Mixed-Precision Quantization
- [[ICCRD](https://ieeexplore.ieee.org/abstract/document/9730411/authors)] Post Training Quantization after Neural Network
- [[ICLR](https://openreview.net/forum?id=shpkpVXzo3h)] 8-bit Optimizers via Block-wise Quantization [[code](https://github.com/facebookresearch/bitsandbytes)] [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/bitsandbytes?style=social)](https://github.com/facebookresearch/bitsandbytes)
- [[ICLR](https://openreview.net/forum?id=_CfpJazzXT2)] F8Net: Fixed-Point 8-bit Only Multiplication for Network Quantization
- [[ICLR](https://openreview.net/forum?id=kF9DZQQrU0w)] Information Bottleneck: Exact Analysis of (Quantized) Neural Networks [[code](https://github.com/StephanLorenzen/ExactIBAnalysisInQNNs)] [![GitHub stars](https://img.shields.io/github/stars/StephanLorenzen/ExactIBAnalysisInQNNs?style=social)](https://github.com/StephanLorenzen/ExactIBAnalysisInQNNs)
- [[ICLR](https://openreview.net/forum?id=ySQH0oDyp7)] Optimal ANN-SNN Conversion for High-accuracy and Ultra-low-latency Spiking Neural Networks
- [[ICLR](https://openreview.net/forum?id=ySQH0oDyp7)] QDrop: Randomly Dropping Quantization for Extremely Low-bit Post-Training Quantization [[code](https://github.com/wimh966/QDrop)] [![GitHub stars](https://img.shields.io/github/stars/wimh966/QDrop?style=social)](https://github.com/wimh966/QDrop)
- [[ICLR](https://openreview.net/forum?id=JXhROKNZzOc)] SQuant: On-the-Fly Data-Free Quantization via Diagonal Hessian Approximation. [code](https://github.com/clevercool/SQuant)]
- [[ICLR](https://openreview.net/forum?id=3HJOA-1hb0e)] Toward Efficient Low-Precision Training: Data Format Optimization and Hysteresis Quantization
- [[ICLR](https://openreview.net/forum?id=7udZAsEzd60)] VC dimension of partially quantized neural networks in the overparametrized regime
- [[ICML](https://proceedings.mlr.press/v162/dong22a.html)] Finding the Task-Optimal Low-Bit Sub-Distribution in Deep Neural Networks [[code](https://github.com/RunpeiDong/DGMS)] [![GitHub stars](https://img.shields.io/github/stars/RunpeiDong/DGMS?style=social)](https://github.com/RunpeiDong/DGMS)
- [[ICML](https://proceedings.mlr.press/v162/liu22v.html)] GACT: Activation Compressed Training for Generic Network Architectures [[code](https://github.com/LiuXiaoxuanPKU/GACT-ICML)] [![GitHub stars](https://img.shields.io/github/stars/LiuXiaoxuanPKU/GACT-ICML?style=social)](https://github.com/LiuXiaoxuanPKU/GACT-ICML)
- [[ICML](https://proceedings.mlr.press/v162/nagel22a/nagel22a.pdf)] Overcoming Oscillations in Quantization-Aware Training [[code](https://github.com/qualcomm-ai-research/oscillations-qat)] [![GitHub stars](https://img.shields.io/github/stars/qualcomm-ai-research/oscillations-qat?style=social)](https://github.com/qualcomm-ai-research/oscillations-qat)
- [[ICML](https://proceedings.mlr.press/v162/huang22h.html)] SDQ: Stochastic Differentiable Quantization with Mixed Precision
- [[ICPR](https://ieeexplore.ieee.org/abstract/document/9956237)] Layer-Wise Data-Free CNN Compression
- [[IEEE Internet of Things Journal](https://ieeexplore.ieee.org/abstract/document/9915794)] FedQNN: A Computation–Communication-Efficient Federated Learning Framework for IoT With Low-Bitwidth Neural Network Quantization
- [[IJCAI](https://arxiv.org/abs/2111.13824)] FQ-ViT: Post-Training Quantization for Fully Quantized Vision Transformer [[code](https://github.com/megvii-research/FQ-ViT)] [![GitHub stars](https://img.shields.io/github/stars/megvii-research/FQ-ViT?style=social)](https://github.com/megvii-research/FQ-ViT)
- [[IJCAI](https://www.ijcai.org/proceedings/2022/504)] MultiQuant: Training Once for Multi-bit Quantization of Neural Networks
- [[IJCAI](https://www.ijcai.org/proceedings/2022/219)] RAPQ: Rescuing Accuracy for Power-of-Two Low-bit Post-training Quantization [[code](https://github.com/billamihom/rapq)] [![GitHub stars](https://img.shields.io/github/stars/billamihom/rapq?style=social)](https://github.com/billamihom/rapq)
- [[IJCNN](https://ieeexplore.ieee.org/abstract/document/9892671)] Accuracy Evaluation of Transposed Convolution-Based Quantized Neural Networks
- [[IJCV](https://arxiv.org/abs/2109.12338)] Distribution-sensitive Information Retention for Accurate Binary Neural Network
- [[IJNS](https://arxiv.org/pdf/2209.15317.pdf)] Convolutional Neural Networks Quantization with Attention
- [[ITSM](https://ieeexplore.ieee.org/abstract/document/9827546)] Edge–Artificial Intelligence-Powered Parking Surveillance With Quantized Neural Networks
- [[Intelligent Automation & Soft Computing](https://web.p.ebscohost.com/abstract?direct=true&profile=ehost&scope=site&authtype=crawler&jrnl=10798587&AN=155230773&h=buFz%2f8gWWhfyGU%2btyHURhybWlmqZvGCIyITNuefG%2bIwBHoSqNwo4CVrCT7hsuZbtZ%2brDTVnLfGgNR6EX8e6%2fGg%3d%3d&crl=c&resultNs=AdminWebAuth&resultLocal=ErrCrlNotAuth&crlhashurl=login.aspx%3fdirect%3dtrue%26profile%3dehost%26scope%3dsite%26authtype%3dcrawler%26jrnl%3d10798587%26AN%3d155230773)] A Resource-Efficient Convolutional Neural Network Accelerator Using Fine-Grained Logarithmic Quantization
- [[LNAI](https://link.springer.com/chapter/10.1007/978-3-031-04083-2_14)] ECQ$^x$: Explainability-Driven Quantization for Low-Bit and Sparse DNNs
- [[MICRO](https://ieeexplore.ieee.org/abstract/document/9923832)] ANT: Exploiting Adaptive Numerical Data Type for Low-bit Deep Neural Network Quantization
- [[NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2022/hash/20f94998511f25bb6378cae0e098bc46-Abstract-Conference.html)] BiMLP: Compact Binary Architectures for Vision Multi-Layer Perceptrons [[code](https://gitee.com/mindspore/models/tree/master/research/cv/BiMLP)]
- [[NeurIPS](https://nips.cc/Conferences/2022/Schedule?showEvent=55032)] BiT: Robustly Binarized Multi-distilled Transformer [[code](https://github.com/facebookresearch/bit)] [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/bit?style=social)](https://github.com/facebookresearch/bit)
- [[NeurIPS](https://nips.cc/Conferences/2022/Schedule?showEvent=55162)] ClimbQ: Class Imbalanced Quantization Enabling Robustness on Efficient Inferences
- [[NeurIPS](https://nips.cc/Conferences/2022/Schedule?showEvent=54104)] Entropy-Driven Mixed-Precision Quantization for Deep Network Design
- [[NeurIPS](https://nips.cc/Conferences/2022/Schedule?showEvent=53073)] FP8 Quantization: The Power of the Exponent [[code](https://github.com/qualcomm-ai-research/fp8-quantization)] [![GitHub stars](https://img.shields.io/github/stars/qualcomm-ai-research/fp8-quantization?style=social)](https://github.com/qualcomm-ai-research/fp8-quantization)
- [[NeurIPS](https://nips.cc/Conferences/2022/Schedule?showEvent=54389)] Leveraging Inter-Layer Dependency for Post -Training Quantization
- [[NeurIPS](https://arxiv.org/abs/2208.07339)] LLM.int8(): 8-bit Matrix Multiplication for Transformers at Scale [[code](https://github.com/timdettmers/bitsandbytes)] [![GitHub stars](https://img.shields.io/github/stars/timdettmers/bitsandbytes?style=social)](https://github.com/timdettmers/bitsandbytes)
- [[NeurIPS](https://nips.cc/Conferences/2022/Schedule?showEvent=53412)] Optimal Brain Compression: A Framework for Accurate Post-Training Quantization and Pruning [[code](https://github.com/ist-daslab/obc)] [![GitHub stars](https://img.shields.io/github/stars/ist-daslab/obc?style=social)](https://github.com/ist-daslab/obc)
- [[NeurIPS](https://openreview.net/forum?id=fU-m9kQe0ke)] Q-ViT: Accurate and Fully Quantized Low-bit Vision Transformer [[code](https://github.com/yanjingli0202/q-vit)] [![GitHub stars](https://img.shields.io/github/stars/yanjingli0202/q-vit?style=social)](https://github.com/yanjingli0202/q-vit)
- [[NeurIPS](https://nips.cc/Conferences/2022/Schedule?showEvent=54812)] Redistribution of Weights and Activations for AdderNet Quantization
- [[NeurIPS](https://nips.cc/Conferences/2022/Schedule?showEvent=53476)] Theoretically Better and Numerically Faster Distributed Optimization with Smoothness-Aware Quantization Techniques
- [[NeurIPS](https://nips.cc/Conferences/2022/Schedule?showEvent=53407)] Towards Efficient Post-training Quantization of Pre-trained Language Models
- [[NeurIPS](https://nips.cc/Conferences/2022/Schedule?showEvent=54407)] ZeroQuant: Efficient and Affordable Post-Training Quantization for Large-Scale Transformers [[code](https://github.com/microsoft/DeepSpeed)] [![GitHub stars](https://img.shields.io/github/stars/microsoft/DeepSpeed?style=social)](https://github.com/microsoft/DeepSpeed)
- [[Neural Networks](https://www.sciencedirect.com/science/article/pii/S0893608022003598)] Quantization-aware training for low precision photonic neural networks
- [[Neurocomputing](https://www.sciencedirect.com/science/article/pii/S0925231222008293)] EPQuant: A Graph Neural Network compression approach based on product quantization
- [[Ocean Engineering](https://www.sciencedirect.com/science/article/pii/S0029801822017887)] Neural network based adaptive sliding mode tracking control of autonomous surface vehicles with input quantization and saturation
- [[PPoPP](https://dl.acm.org/doi/abs/10.1145/3503221.3508408)] QGTC: accelerating quantized graph neural networks via GPU tensor core
- [[TCCN](https://ieeexplore.ieee.org/abstract/document/9703679)] Low-Bitwidth Convolutional Neural Networks for Wireless Interference Identification
- [[TCSVT](https://ieeexplore.ieee.org/abstract/document/9849674)] An Efficient Implementation of Convolutional Neural Network With CLIP-Q Quantization on FPGA
- [[TGARS](https://ieeexplore.ieee.org/abstract/document/9362309)] Accelerating Convolutional Neural Network-Based Hyperspectral Image Classification by Step Activation Quantization
- [[TODAES](https://dl.acm.org/doi/10.1145/3498328)] Dynamic Quantization Range Control for Analog-in-Memory Neural Networks Acceleration
- [[arXiv](https://arxiv.org/pdf/2206.07741.pdf)] Edge Inference with Fully Differentiable Quantized Mixed Precision Neural Networks
- [[arXiv](https://arxiv.org/pdf/2201.08442)] Neural network quantization with ai model efficiency toolkit (aimet)
- [[arXiv](https://arxiv.org/pdf/2201.07703.pdf)] Q-ViT: Fully Differentiable Quantization for Vision Transformer
- [[arXiv](https://arxiv.org/pdf/2206.07527.pdf)] QONNX: Representing Arbitrary-Precision Quantized Neural Networks
- [[arXiv](https://arxiv.org/pdf/2202.05048.pdf)] Quantune: Post-training Quantization of Convolutional Neural Networks using Extreme Gradient Boosting for Fast Deployment
- [[arXiv](https://arxiv.org/pdf/2211.10438.pdf)] SmoothQuant: Accurate and Efficient Post-Training Quantization for Large Language Models [[code](https://github.com/mit-han-lab/smoothquant)] [![GitHub stars](https://img.shields.io/github/stars/mit-han-lab/smoothquant?style=social)](https://github.com/mit-han-lab/smoothquant)
- [[arXiv](http://arxiv.org/abs/2206.15408)] Sub-8-Bit Quantization Aware Training for 8-Bit Neural Network Accelerator with On-Device Speech Recognition
- [[tinyML Research Symposium](https://arxiv.org/pdf/2203.05025.pdf)] Power-of-Two Quantization for Low Bitwidth and Hardware Compliant Neural Networks
- [[ECCV](https://arxiv.org/abs/2207.10345)] CADyQ: Content-Aware Dynamic Quantization for Image Super-Resolution
- [[ECCV](https://arxiv.org/abs/2207.10188)] Bitwidth-Adaptive Quantization-Aware Neural Network Training: A Meta-Learning Approach [[code](https://github.com/jsjs0369/MEBQAT)] [![GitHub stars](https://img.shields.io/github/stars/jsjs0369/MEBQAT?style=social)](https://github.com/jsjs0369/MEBQAT)
- [[ECCV](https://arxiv.org/abs/2007.07743)] Fine-grained Data Distribution Alignment for Post-Training Quantization [[code](https://github.com/zysxmu/FDDA)] [![GitHub stars](https://img.shields.io/github/stars/zysxmu/FDDA?style=social)](https://github.com/zysxmu/FDDA)
- [[ICML](https://arxiv.org/abs/2206.06501)] Optimal Clipping and Magnitude-aware Differentiation for Improved Quantization-aware Training

### 2021

- [[CVPR](https://arxiv.org/abs/2103.01049)] Diversifying Sample Generation for Accurate Data-Free Quantization
- [[ICLR](https://openreview.net/forum?id=9QLRCVysdlO)] BiPointNet: Binary Neural Network for Point Clouds [[code](https://github.com/htqin/BiPointNet)] [![GitHub stars](https://img.shields.io/github/stars/htqin/BiPointNet?style=social)](https://github.com/htqin/BiPointNet)
- [[ICML](http://proceedings.mlr.press/v139/liu21t/liu21t.pdf)] How Do Adam and Training Strategies Help BNNs Optimization? [[code](https://github.com/liuzechun/AdamBNN)] [![GitHub stars](https://img.shields.io/github/stars/liuzechun/AdamBNN?style=social)](https://github.com/liuzechun/AdamBNN)
- [[AAAI](https://arxiv.org/pdf/2010.02778)] Compressing Deep Convolutional Neural Networks by Stacking Low-­Dimensional Binary Convolution Filters
- [[AAAI](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwj4-rjuq7nvAhUVPH0KHXlYCUQQFjAFegQIChAD&url=https%3A%2F%2Fwww.aaai.org%2FAAAI21Papers%2FAAAI-7144.ZhaoK.pdf&usg=AOvVaw3dnOXfzKkLIw_qWXj7p7Yc)] Distribution Adaptive INT8 Quantization for Training CNNs
- [[AAAI](https://www.semanticscholar.org/paper/FracBits%3A-Mixed-Precision-Quantization-via-Yang-Jin/cb219432863778fa173925d51fbf02af1d17ad98)] FracBits: Mixed Precision Quantization via Fractional Bit-Widths
- [[AAAI](https://arxiv.org/pdf/2010.02577)] Memory and Computation-Efficient Kernel SVM via Binary Embedding and Ternary Coefficients
- [[AAAI](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjD6aPrqbnvAhXeIDQIHWNdDCUQFjADegQIAxAD&url=https%3A%2F%2Fwww.aaai.org%2FAAAI21Papers%2FAAAI-1054.HuP.pdf&usg=AOvVaw2R_BcDlKyuuAPHMeO0Q-1c)] OPQ: Compressing Deep Neural Networks with One-shot Pruning-Quantization
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/16474/16281)] Optimizing Information Theory Based Bitwise Bottlenecks for Efficient Mixed-Precision Activation Quantization
- [[AAAI](https://arxiv.org/pdf/2002.09049)] Post-­‐training Quantization with Multiple Points: Mixed Precision without Mixed Precision
- [[AAAI](https://arxiv.org/pdf/2012.08185)] Scalable Verification of Quantized Neural Networks [[code](https://github.com/mlech26l/qnn_robustness_benchmarks)] [![GitHub stars](https://img.shields.io/github/stars/mlech26l/qnn_robustness_benchmarks?style=social)](https://github.com/mlech26l/qnn_robustness_benchmarks)
- [[AAAI](https://arxiv.org/abs/2009.14502)] Stochastic Precision Ensemble: Self‐Knowledge Distillation for Quantized Deep Neural Networks
- [[AAAI](https://www.aaai.org/AAAI21Papers/AAAI-4473.LiY.pdf)] TRQ: Ternary Neural Networks with Residual Quantization
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/17434/17241)] Uncertainty Quantification in CNN through the Bootstrap of Convex Neural Networks
- [[AAAI](https://arxiv.org/pdf/1907.05911)] Vector Quantized Bayesian Neural Network Inference for Data Streams
- [[ACL](https://aclanthology.org/2021.findings-acl.363)] On the Distribution, Sparsity, and Inference-time Quantization of Attention Values in Transformers
- [[ACM MM](https://arxiv.org/abs/2011.14265)] Fully Quantized Image Super-Resolution Networks [[code](https://github.com/billhhh/FQSR)] [![GitHub stars](https://img.shields.io/github/stars/billhhh/FQSR?style=social)](https://github.com/billhhh/FQSR)
- [[ACM MM](https://dl.acm.org/doi/10.1145/3474085.3475224)] VQMG: Hierarchical Vector Quantised and Multi-hops Graph Reasoning for Explicit Representation Learning
- [[CVPR](https://arxiv.org/abs/2012.15823)] Binary Graph Neural Networks [[code](https://github.com/mbahri/binary_gnn)] [![GitHub stars](https://img.shields.io/github/stars/mbahri/binary_gnn?style=social)](https://github.com/mbahri/binary_gnn)
- [[CVPR](https://arxiv.org/abs/2103.07156)] Learnable Companding Quantization for Accurate Low-bit Neural Networks
- [[CVPR](https://arxiv.org/abs/2104.00903)] Network Quantization with Element-wise Gradient Scaling [[code](https://github.com/cvlab-yonsei/EWGS)] [![GitHub stars](https://img.shields.io/github/stars/cvlab-yonsei/EWGS?style=social)](https://github.com/cvlab-yonsei/EWGS)
- [[CVPR](https://arxiv.org/abs/2010.15703)] Permute, Quantize, and Fine-tune: Efficient Compression of Neural Networks [[code](https://github.com/uber-research/permute-quantize-finetune)] [![GitHub stars](https://img.shields.io/github/stars/uber-research/permute-quantize-finetune?style=social)](https://github.com/uber-research/permute-quantize-finetune)
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_PokeBNN_A_Binary_Pursuit_of_Lightweight_Accuracy_CVPR_2022_paper.pdf)] PokeBNN: A Binary Pursuit of Lightweight Accuracy [[code](https://github.com/google/aqt)] [![GitHub stars](https://img.shields.io/github/stars/google/aqt?style=social)](https://github.com/google/aqt)
- [[CVPR](http://openaccess.thecvf.com/content/CVPR2021/html/Shen_S2-BNN_Bridging_the_Gap_Between_Self-Supervised_Real_and_1-Bit_Neural_CVPR_2021_paper.html)] S2-bnn: Bridging the gap between self-supervised real and 1-bit neural networks via guided distribution calibration [[code](https://github.com/szq0214/S2-BNN)] [![GitHub stars](https://img.shields.io/github/stars/szq0214/S2-BNN?style=social)](https://github.com/szq0214/S2-BNN)
- [[CVPR](https://arxiv.org/abs/2103.15263)] Zero-shot Adversarial Quantization [[code](https://github.com/FLHonker/ZAQ-code)] [![GitHub stars](https://img.shields.io/github/stars/FLHonker/ZAQ-code?style=social)](https://github.com/FLHonker/ZAQ-code)
- [[ECCV](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700562.pdf)] PAMS: Quantized Super-Resolution via Parameterized Max Scale [[code](https://github.com/colorjam/PAMS)] [![GitHub stars](https://img.shields.io/github/stars/colorjam/PAMS?style=social)](https://github.com/colorjam/PAMS)
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2021/html/Li_MixMix_All_You_Need_for_Data-Free_Compression_Are_Feature_and_ICCV_2021_paper.html)] MixMix: All You Need for Data-Free Compression Are Feature and Data Mixing
- [[ICLR](https://openreview.net/forum?id=POWv6hDd9XH)] BRECQ: Pushing the Limit of Post-Training Quantization by Block Reconstruction [[code](https://github.com/yhhhli/BRECQ)] [![GitHub stars](https://img.shields.io/github/stars/yhhhli/BRECQ?style=social)](https://github.com/yhhhli/BRECQ)
- [[ICLR](https://openreview.net/forum?id=TiXl51SCNw8)] BSQ: Exploring Bit-Level Sparsity for Mixed-Precision Neural Network Quantization [[code](https://github.com/yanghr/BSQ)] [![GitHub stars](https://img.shields.io/github/stars/yanghr/BSQ?style=social)](https://github.com/yanghr/BSQ)
- [[ICLR](https://openreview.net/forum?id=NSBrFgJAHg)] Degree-Quant: Quantization-Aware Training for Graph Neural Networks
- [[ICLR](https://openreview.net/forum?id=MxaY4FzOTa)] High-Capacity Expert Binary Networks [[code](https://github.com/1adrianb/expert-binary-networks)] [![GitHub stars](https://img.shields.io/github/stars/1adrianb/expert-binary-networks?style=social)](https://github.com/1adrianb/expert-binary-networks)
- [[ICLR](https://openreview.net/forum?id=3SV-ZePhnZM)] Incremental few-shot learning via vector quantization in deep embedded space
- [[ICLR](https://openreview.net/forum?id=U_mat0b9iv)] Multi-Prize Lottery Ticket Hypothesis: Finding Accurate Binary Neural Networks by Pruning A Randomly Weighted Network [[code](https://github.com/chrundle/biprop)] [![GitHub stars](https://img.shields.io/github/stars/chrundle/biprop?style=social)](https://github.com/chrundle/biprop)
- [[ICLR](https://openreview.net/forum?id=EoFNy62JGd)] Neural gradients are near-lognormal: improved quantized and sparse training
- [[ICLR](https://openreview.net/forum?id=sTeoJiB4uR)] Reducing the Computational Cost of Deep Generative Models with Binary Neural Networks
- [[ICLR](https://openreview.net/forum?id=Qr0aRliE_Hb)] Simple Augmentation Goes a Long Way: ADRL for DNN Quantization
- [[ICLR](https://openreview.net/forum?id=pBqLS-7KYAF)] Sparse Quantized Spectral Clustering
- [[ICLR](https://openreview.net/forum?id=dV19Yyi1fS3)] Training with Quantization Noise for Extreme Model Compression [[code](https://github.com/pytorch/fairseq/tree/master/examples/quant_noise)] [![GitHub stars](https://img.shields.io/github/stars/pytorch/fairseq?style=social)](https://github.com/pytorch/fairseq)
- [[ICLR](https://arxiv.org/pdf/2007.13242.pdf)] WrapNet: Neural Net Inference with Ultra-Low-Resolution Arithmetic
- [[ICML](https://proceedings.mlr.press/v139/chen21z.html)] ActNN: Reducing Training Memory Footprint via 2-Bit Activation Compressed Training [[code](https://github.com/ucbrise/actnn)] [![GitHub stars](https://img.shields.io/github/stars/ucbrise/actnn?style=social)](https://github.com/ucbrise/actnn)
- [[ICML](https://proceedings.mlr.press/v139/fu21d.html)] Auto-NBA: Efficient and Effective Search Over the Joint Space of Networks, Bitwidths, and Accelerators [[code](https://github.com/RICE-EIC/Auto-NBA)] [![GitHub stars](https://img.shields.io/github/stars/RICE-EIC/Auto-NBA?style=social)](https://github.com/RICE-EIC/Auto-NBA)
- [[ICML](https://proceedings.mlr.press/v139/zhang21r.html)] Differentiable Dynamic Quantization with Mixed Precision and Adaptive Resolution
- [[ICML](https://proceedings.mlr.press/v139/yao21a.html)] HAWQ-V3: Dyadic Neural Network Quantization [[code](https://github.com/Zhen-Dong/HAWQ)] [![GitHub stars](https://img.shields.io/github/stars/Zhen-Dong/HAWQ?style=social)](https://github.com/Zhen-Dong/HAWQ)
- [[ICML](https://proceedings.mlr.press/v139/kim21d.html)] I-BERT: Integer-only BERT Quantization [[code](https://github.com/kssteven418/I-BERT)] [![GitHub stars](https://img.shields.io/github/stars/kssteven418/I-BERT?style=social)](https://github.com/kssteven418/I-BERT)
- [[NeurIPS](https://openreview.net/forum?id=YygA0yppTR)] A Winning Hand: Compressing Deep Networks Can Improve Out-of-Distribution Robustness [[code](https://github.com/chrundle/biprop)] [![GitHub stars](https://img.shields.io/github/stars/chrundle/biprop?style=social)](https://github.com/chrundle/biprop)
- [[NeurIPS](https://openreview.net/forum?id=Z_J5bCb4Rra)] Divergence Frontiers for Generative Models: Sample Complexity, Quantization Effects, and Frontier Integrals
- [[NeurIPS](https://openreview.net/forum?id=9TX5OsKJvm)] Post-Training Quantization for Vision Transformer
- [[NeurIPS](https://openreview.net/forum?id=qe9z54E_cqE)] Post-Training Sparsity-Aware Quantization [[code](https://github.com/gilshm/sparq)] [![GitHub stars](https://img.shields.io/github/stars/gilshm/sparq?style=social)](https://github.com/gilshm/sparq)
- [[NeurIPS](https://openreview.net/forum?id=ejo1_Weiart)] Qimera: Data-free Quantization with Synthetic Boundary Supporting Samples [[code](https://github.com/iamkanghyunchoi/qimera)] [![GitHub stars](https://img.shields.io/github/stars/iamkanghyunchoi/qimera?style=social)](https://github.com/iamkanghyunchoi/qimera)
- [[NeurIPS](https://openreview.net/forum?id=0kCxbBQknN)] Qu-ANTI-zation: Exploiting Quantization Artifacts for Achieving Adversarial Outcomes 
- [[NeurIPS](https://openreview.net/forum?id=EO-CQzgcIxd)] VQ-GNN: A Universal Framework to Scale up Graph Neural Networks using Vector Quantization
- [[arXiv](http://arxiv.org/abs/2103.13630)] A Survey of Quantization Methods for Efficient Neural Network Inference
- [[arXiv](https://arxiv.org/pdf/2106.08295.pdf)] A White Paper on Neural Network Quantization
- [[arXiv](https://arxiv.org/abs/1911.07346)] Any-Precision Deep Neural Networks [[code](https://github.com/SHI-Labs/Any-Precision-DNNs)] [![GitHub stars](https://img.shields.io/github/stars/SHI-Labs/Any-Precision-DNNs?style=social)](https://github.com/SHI-Labs/Any-Precision-DNNs)
- [[arXiv](http://arxiv.org/abs/2103.12369)] ReCU: Reviving the Dead Weights in Binary Neural Networks [[code](https://github.com/z-hXu/ReCU)] [![GitHub stars](https://img.shields.io/github/stars/z-hXu/ReCU?style=social)](https://github.com/z-hXu/ReCU)
- [[AAAI](https://cdn.aaai.org/ojs/16263/16263-13-19757-1-2-20210518.pdf)] Training Binary Neural Network without Batch Normalization for Image Super-Resolution
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/16306)] SA-BNN: State-­Aware Binary Neural Network
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2021/papers/Oh_Automated_Log-Scale_Quantization_for_Low-Cost_Deep_Neural_Networks_CVPR_2021_paper.pdf)] Automated Log-Scale Quantization for Low-Cost Deep Neural Networks
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2021/papers/Kryzhanovskiy_QPP_Real-Time_Quantization_Parameter_Prediction_for_Deep_Neural_Networks_CVPR_2021_paper.pdf)] QPP: Real-Time Quantization Parameter Prediction for Deep Neural Networks
- [[ICLR](https://arxiv.org/abs/2006.10518)] Improving Post Training Neural Quantization: Layer-wise Calibration and Integer Programming [[code](https://github.com/itayhubara/CalibTIP)] [![GitHub stars](https://img.shields.io/github/stars/itayhubara/CalibTIP?style=social)](https://github.com/itayhubara/CalibTIP)
- [[ICML](https://proceedings.mlr.press/v139/hubara21a/hubara21a.pdf)] Accurate Post Training Quantization With Small Calibration Sets
- [[NeurIPS](https://arxiv.org/abs/2105.08952)] BatchQuant: Quantized-for-all Architecture Search with Robust Quantizer

### 2020

- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2020/papers/Qin_Forward_and_Backward_Information_Retention_for_Accurate_Binary_Neural_Networks_CVPR_2020_paper.pdf)] Forward and Backward Information Retention for Accurate Binary Neural Networks [[code](https://github.com/htqin/IR-Net)] [![GitHub stars](https://img.shields.io/github/stars/htqin/IR-Net?style=social)](https://github.com/htqin/IR-Net)
- [[PR](https://arxiv.org/abs/2004.03333)] Binary neural networks: A survey
- [[AAAI](https://aaai.org/ojs/index.php/AAAI/article/view/6035)] HLHLp: Quantized Neural Networks Traing for Reaching Flat Minima in Loss Sufrface
- [[AAAI](https://arxiv.org/abs/1909.05840)] Q-BERT: Hessian Based Ultra Low Precision Quantization of BERT
- [[AAAI](https://aaai.org/ojs/index.php/AAAI/article/view/6900)] Sparsity-Inducing Binarized Neural Networks
- [[AAAI](https://aaai.org/ojs/index.php/AAAI/article/view/6134)] Towards Accurate Low Bit-Width Quantization with Multiple Phase Adaptations
- [[ACL](https://www.aclweb.org/anthology/2020.sustainlp-1.4.pdf)] End to End Binarized Neural Networks for Text Classification
- [[COOL CHIPS](https://ieeexplore.ieee.org/document/9097642/)] A Novel In-DRAM Accelerator Architecture for Binary Neural Network
- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_APQ_Joint_Search_for_Network_Architecture_Pruning_and_Quantization_Policy_CVPR_2020_paper.pdf)] APQ: Joint Search for Network Architecture, Pruning and Quantization Policy [[code](https://github.com/mit-han-lab/apq)] [![GitHub stars](https://img.shields.io/github/stars/mit-han-lab/apq?style=social)](https://github.com/mit-han-lab/apq)
- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_BiDet_An_Efficient_Binarized_Object_Detector_CVPR_2020_paper.pdf)] BiDet: An Efficient Binarized Object Detector. [[code](https://github.com/ZiweiWangTHU/BiDet)] [![GitHub stars](https://img.shields.io/github/stars/ZiweiWangTHU/BiDet?style=social)](https://github.com/ZiweiWangTHU/BiDet)
- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_Fixed-Point_Back-Propagation_Training_CVPR_2020_paper.pdf)] Fixed-Point Back-Propagation Training
- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2020/papers/Han_GhostNet_More_Features_From_Cheap_Operations_CVPR_2020_paper.pdf)] GhostNet: More Features from Cheap Operations
- [[CVPR](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w40/Yu_Low-Bit_Quantization_Needs_Good_Distribution_CVPRW_2020_paper.pdf)] Low-Bit Quantization Needs Good Distribution
- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_Rotation_Consistent_Margin_Loss_for_Efficient_Low-Bit_Face_Recognition_CVPR_2020_paper.pdf)] Rotation Consistent Margin Loss for Efficient Low-Bit Face Recognition
- [[arXiv](https://arxiv.org/pdf/2002.10778.pdf)] Training Binary Neural Networks using the Bayesian Learning Rule
- [[DATE](https://ieeexplore.ieee.org/document/9116220)] BNNsplit: Binarized Neural Networks for embedded distributed FPGA-based computing systems
- [[DATE](https://ieeexplore.ieee.org/abstract/document/9116308)] OrthrusPE: Runtime Reconfigurable Processing Elements for Binary Neural Networks
- [[DATE](https://arxiv.org/abs/1912.04050)] PhoneBit: Efficient GPU-Accelerated Binary Neural Network Inference Engine for Mobile Phones
- [[ECCV](http://arxiv.org/abs/2003.01711)] BATS: Binary ArchitecTure Search
- [[ECCV](https://arxiv.org/abs/2007.10463)] Differentiable Joint Pruning and Quantization for Hardware Efficiency
- [[ECCV](https://arxiv.org/abs/2003.03603)] Generative Low-bitwidth Data Free Quantization [[code](https://github.com/xushoukai/GDFQ)] [![GitHub stars](https://img.shields.io/github/stars/xushoukai/GDFQ?style=social)](https://github.com/xushoukai/GDFQ)
- [[ECCV](https://arxiv.org/abs/2002.06963)] Learning Architectures for Binary Networks [[code](https://github.com/gistvision/bnas)] [![GitHub stars](https://img.shields.io/github/stars/gistvision/bnas?style=social)](https://github.com/gistvision/bnas)
- [[ECCV](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123510426.pdf)] PROFIT: A Novel Training Method for sub-4-bit MobileNet Models
- [[ECCV](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123480222.pdf)] ProxyBNN: Learning Binarized Neural Networks via Proxy Matrices
- [[ECCV](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590137.pdf)] ReActNet: Towards Precise Binary Neural Network with Generalized Activation Functions [[code](https://github.com/liuzechun/ReActNet)] [![GitHub stars](https://img.shields.io/github/stars/liuzechun/ReActNet?style=social)](https://github.com/liuzechun/ReActNet)
- [[EMNLP](https://arxiv.org/abs/1910.10485)] Fully Quantized Transformer for Machine Translation
- [[EMNLP](https://arxiv.org/abs/2009.12812)] TernaryBERT: Distillation-aware Ultra-low Bit BERT [[code](https://github.com/huawei-noah/Pretrained-Language-Model)] [![GitHub stars](https://img.shields.io/github/stars/huawei-noah/Pretrained-Language-Model?style=social)](https://github.com/huawei-noah/Pretrained-Language-Model)
- [[ICASSP](https://ieeexplore.ieee.org/document/9054599)] Balanced Binary Neural Networks with Gated Residual
- [[ICET](https://ieeexplore.ieee.org/document/9119704)] An Energy-Efficient Bagged Binary Neural Network Accelerator
- [[ICLR](https://arxiv.org/abs/2002.06517)] BinaryDuo: Reducing Gradient Mismatch in Binary Activation Network by Coupling Binary Activations [[code](https://github.com/Hyungjun-K1m/BinaryDuo)] [![GitHub stars](https://img.shields.io/github/stars/Hyungjun-K1m/BinaryDuo?style=social)](https://github.com/Hyungjun-K1m/BinaryDuo)
- [[ICLR](https://openreview.net/pdf?id=XKeyCSUWusK)] DMS: Differentiable Dimension Search for Binary Neural Networks
- [[ICLR](https://arxiv.org/abs/1902.08153)] Learned Step Size Quantization
- [[ICLR](https://openreview.net/forum?id=Hyx0slrFvH)] Mixed Precision DNNs: All You Need is a Good Parametrization [[code](https://github.com/sony/ai-research-code/tree/master/mixed-precision-dnns)] [![GitHub stars](https://img.shields.io/github/stars/sony/ai-research-code?style=social)](https://github.com/sony/ai-research-code)
- [[ICLR](https://openreview.net/pdf?id=BJg4NgBKvH)] Training Binary Neural Networks with Real-to-Binary Convolutions
- [[ICML](https://arxiv.org/abs/1908.10396)] Accelerating Large-Scale Inference with Anisotropic Vector Quantization
- [[ICML](https://arxiv.org/abs/2004.09576)] LSQ+: Improving low-bit quantization through learnable offsets and better initialization
- [[ICML](https://proceedings.icml.cc/static/paper_files/icml/2020/181-Paper.pdf)] Training Binary Neural Networks through Learning with Noisy Supervision
- [[ICML](https://arxiv.org/abs/2004.10568)] Up or Down? Adaptive Rounding for Post-Training Quantization
- [[IEEE Access](https://ieeexplore.ieee.org/document/9091590/)] An Energy-Efficient and High Throughput in-Memory Computing Bit-Cell With Excellent Robustness Under Process Variations for Binary Neural Network
- [[IEEE TCS.I](https://arxiv.org/pdf/2003.12558.pdf)] IMAC: In-Memory Multi-Bit Multiplication and ACcumulation in 6T SRAM Array
- [[IEEE TCS.II](https://ieeexplore.ieee.org/document/9144282/)] A Resource-Efficient Inference Accelerator for Binary Convolutional Neural Networks
- [[IEEE Trans. Electron Devices](https://ieeexplore.ieee.org/document/9112690)] Design of High Robustness BNN Inference Accelerator Based on Binary Memristors
- [[IEEE Trans. Magn](https://arxiv.org/abs/2003.05132)] SIMBA: A Skyrmionic In-Memory Binary Neural Network Accelerator
- [[IJCAI](https://arxiv.org/pdf/2005.00057.pdf)] CP-NAS: Child-Parent Neural Architecture Search for Binary Neural Networks
- [[IJCAI](https://www.ijcai.org/proceedings/2020/292)] Direct Quantization for Training Highly Accurate Low Bit-width Deep Neural Networks
- [[IJCAI](https://www.ijcai.org/proceedings/2020/288)] Fully Nested Neural Network for Adaptive Compression and Quantization
- [[IJCAI](https://www.ijcai.org/proceedings/2020/121)] Overflow Aware Quantization: Accelerating Neural Network Inference by Low-bit Multiply-Accumulate Operations
- [[IJCAI](https://www.ijcai.org/proceedings/2020/318)] Soft Threshold Ternary Networks
- [[IJCAI](https://www.ijcai.org/Proceedings/2020/0520.pdf)] Towards Fully 8-bit Integer Inference for the Transformer Model
- [[IJCV](https://arxiv.org/abs/2009.04247)] Binarized Neural Architecture Search for Efficient Object Recognition
- [[ISCAS](https://arxiv.org/pdf/2004.08914.pdf)] MuBiNN: Multi-Level Binarized Recurrent Neural Network for EEG Signal Classification
- [[ISQED](https://ieeexplore.ieee.org/document/9136977)] BNN Pruning: Pruning Binary Neural Network Guided by Weight Flipping Frequency [[code](https://github.com/PSCLab-ASU/BNNPruning)] [![GitHub stars](https://img.shields.io/github/stars/PSCLab-ASU/BNNPruning?style=social)](https://github.com/PSCLab-ASU/BNNPruning)
- [[MICRO](http://arxiv.org/abs/2005.03842)] GOBO: Quantizing Attention-Based NLP Models for Low Latency and Energy Efficient Inference
- [[MLST](https://arxiv.org/abs/2003.06308)] Compressing deep neural networks on FPGAs to binary and ternary precision with HLS4ML
- [[NN](https://www.sciencedirect.com/science/article/abs/pii/S0893608019304290?via%3Dihub)] Training high-performance and large-scale deep neural networks with full 8-bit integers
- [[NeurIPS](https://proceedings.neurips.cc/paper/2020/hash/20b5e1cf8694af7a3c1ba4a87f073021-Abstract.html)] Adaptive Gradient Quantization for Data-Parallel SGD [[code](https://github.com/tabrizian/learning-to-quantize)] [![GitHub stars](https://img.shields.io/github/stars/tabrizian/learning-to-quantize?style=social)](https://github.com/tabrizian/learning-to-quantize)
- [[NeurIPS](https://proceedings.neurips.cc/paper/2020/hash/3f13cf4ddf6fc50c0d39a1d5aeb57dd8-Abstract.html)] Bayesian Bits: Unifying Quantization and Pruning
- [[NeurIPS](https://proceedings.neurips.cc/paper/2020/hash/26ed695e9b7b9f6463ef4bc1fd74fc87-Abstract.html)] Closing the Dequantization Gap: PixelCNN as a Single-Layer Flow [[code](https://github.com/didriknielsen/pixelcnn_flow)] [![GitHub stars](https://img.shields.io/github/stars/didriknielsen/pixelcnn_flow?style=social)](https://github.com/didriknielsen/pixelcnn_flow)
- [[NeurIPS](https://proceedings.neurips.cc/paper/2020/hash/1385974ed5904a438616ff7bdb3f7439-Abstract.html)] Efficient Exact Verification of Binarized Neural Networks [[code](https://github.com/jia-kai/eevbnn)] [![GitHub stars](https://img.shields.io/github/stars/jia-kai/eevbnn?style=social)](https://github.com/jia-kai/eevbnn)
- [[NeurIPS](https://proceedings.neurips.cc/paper/2020/hash/0e230b1a582d76526b7ad7fc62ae937d-Abstract.html)] FleXOR: Trainable Fractional Quantization
- [[NeurIPS](https://proceedings.neurips.cc/paper/2020/hash/d77c703536718b95308130ff2e5cf9ee-Abstract.html)] HAWQ-V2: Hessian Aware trace-Weighted Quantization of Neural Networks
- [[NeurIPS](https://proceedings.neurips.cc/paper/2020/hash/96fca94df72984fc97ee5095410d4dec-Abstract.html)] Path Sample-Analytic Gradient Estimators for Stochastic Binary Networks [[code](https://github.com/shekhovt/PSA-Neurips2020)] [![GitHub stars](https://img.shields.io/github/stars/shekhovt/PSA-Neurips2020?style=social)](https://github.com/shekhovt/PSA-Neurips2020)
- [[NeurIPS](http://arxiv.org/abs/2005.11035)] Position-based Scaled Gradient for Model Quantization and Pruning [[code](https://github.com/Jangho-Kim/PSG-pytorch)] [![GitHub stars](https://img.shields.io/github/stars/Jangho-Kim/PSG-pytorch?style=social)](https://github.com/Jangho-Kim/PSG-pytorch)
- [[NeurIPS](https://proceedings.neurips.cc/paper/2020/hash/3948ead63a9f2944218de038d8934305-Abstract.html)] Robust Quantization: One Model to Rule Them All
- [[NeurIPS](https://papers.nips.cc/paper/2020/file/53c5b2affa12eed84dfec9bfd83550b1-Paper.pdf)] Rotated Binary Neural Network [[code](https://github.com/lmbxmu/RBNN)] [![GitHub stars](https://img.shields.io/github/stars/lmbxmu/RBNN?style=social)](https://github.com/lmbxmu/RBNN)
- [[NeurIPS](https://proceedings.neurips.cc/paper/2020/file/2a084e55c87b1ebcdaad1f62fdbbac8e-Paper.pdf)] Searching for Low-Bit Weights in Quantized Neural Networks [[code](https://github.com/zhaohui-yang/Binary-Neural-Networks/tree/main/SLB)] [![GitHub stars](https://img.shields.io/github/stars/zhaohui-yang/Binary-Neural-Networks?style=social)](https://github.com/zhaohui-yang/Binary-Neural-Networks)
- [[NeurIPS](https://proceedings.neurips.cc/paper/2020/hash/92049debbe566ca5782a3045cf300a3c-Abstract.html)] Universally Quantized Neural Compression
- [[Neurocomputing](https://www.sciencedirect.com/science/article/abs/pii/S0925231219314274)] Eye localization based on weight binarization cascade convolution neural network
- [[PR Letters](https://arxiv.org/abs/2008.01438)] Controlling information capacity of binary neural network
- [[SysML](https://ubicomplab.cs.washington.edu/pdfs/riptide.pdf)] Riptide: Fast End-to-End Binarized Neural Networks [[code](https://github.com/jwfromm/Riptide)] [![GitHub stars](https://img.shields.io/github/stars/jwfromm/Riptide?style=social)](https://github.com/jwfromm/Riptide)
- [[TPAMI](https://ieeexplore.ieee.org/document/8573867/)] Deep Neural Network Compression by In-Parallel Pruning-Quantization
- [[TPAMI](https://ieeexplore.ieee.org/document/8444745/)] Hierarchical Binary CNNs for Landmark Localization with Limited Resources [[code](https://www.adrianbulat.com/binary-cnn-landmarks)]
- [[TPAMI](https://ieeexplore.ieee.org/document/8674614/)] Towards Efficient U-Nets: A Coupled and Quantized Approach
- [[TVLSI](https://arxiv.org/pdf/2003.02628.pdf)] Phoenix: A Low-Precision Floating-Point Quantization Oriented Architecture for Convolutional Neural Networks
- [[WACV](https://openaccess.thecvf.com/content_WACV_2020/papers/Phan_MoBiNet_A_Mobile_Binary_Network_for_Image_Classification_WACV_2020_paper.pdf)] MoBiNet: A Mobile Binary Network for Image Classification
- [[arXiv](https://arxiv.org/abs/2006.16578)] Accelerating Binarized Neural Networks via Bit-Tensor-Cores in Turing GPUs [[code](https://github.com/pnnl/TCBNN)] [![GitHub stars](https://img.shields.io/github/stars/pnnl/TCBNN?style=social)](https://github.com/pnnl/TCBNN)
- [[arXiv](https://arxiv.org/pdf/2004.11147.pdf)] Binarized Graph Neural Network
- [[arXiv](https://arxiv.org/abs/2012.15701)] BinaryBERT: Pushing the Limit of BERT Quantization [[code](https://github.com/huawei-noah/Pretrained-Language-Model)] [![GitHub stars](https://img.shields.io/github/stars/huawei-noah/Pretrained-Language-Model?style=social)](https://github.com/huawei-noah/Pretrained-Language-Model)
- [[arXiv](https://arxiv.org/pdf/2007.05223.pdf)] Distillation Guided Residual Learning for Binary Convolutional Neural Networks
- [[arXiv](https://arxiv.org/pdf/1909.09139.pdf)] How Does Batch Normalization Help Binary Training?
- [[arXiv](https://arxiv.org/abs/2001.05936)] MeliusNet: Can Binary Neural Networks Achieve MobileNet-level Accuracy? [[code](https://github.com/hpi-xnor/BMXNet-v2)] [![GitHub stars](https://img.shields.io/github/stars/hpi-xnor/BMXNet-v2?style=social)](https://github.com/hpi-xnor/BMXNet-v2)
- [[arXiv](https://arxiv.org/pdf/2001.01091.pdf)] RPR: Random Partition Relaxation for Training; Binary and Ternary Weight Neural Networks
- [[arXiv](https://arxiv.org/abs/2004.07320)] Training with Quantization Noise for Extreme Model Compression [[code](https://github.com/pytorch/fairseq/tree/master/examples/quant_noise)] [![GitHub stars](https://img.shields.io/github/stars/pytorch/fairseq?style=social)](https://github.com/pytorch/fairseq)
- [[arXiv](https://arxiv.org/abs/2006.07522)] Understanding Learning Dynamics of Binary Neural Networks via Information Bottleneck
- [[paper](https://www.researchgate.net/publication/343568789_Towards_Lossless_Binary_Convolutional_Neural_Networks_Using_Piecewise_Approximation)] Towards Lossless Binary Convolutional Neural Networks Using Piecewise Approximation
- [[CVPR](https://arxiv.org/abs/2001.00281)] ZeroQ: A Novel Zero Shot Quantization Framework [[code](https://github.com/amirgholami/ZeroQ)] [![GitHub stars](https://img.shields.io/github/stars/amirgholami/ZeroQ?style=social)](https://github.com/amirgholami/ZeroQ)
- [[CVPR](https://arxiv.org/abs/1912.09666)] AdaBits: Neural Network Quantization With Adaptive Bit-Widths [[code](https://github.com/deJQK/AdaBits)] [![GitHub stars](https://img.shields.io/github/stars/deJQK/AdaBits?style=social)](https://github.com/deJQK/AdaBits)
- [[CVPR](https://arxiv.org/abs/1912.08883)] Adaptive Loss-aware Quantization for Multi-bit Networks [[code](https://github.com/zqu1992/ALQ)] [![GitHub stars](https://img.shields.io/github/stars/zqu1992/ALQ?style=social)](https://github.com/zqu1992/ALQ)
- [[ECCV](https://arxiv.org/abs/2007.09952)] HMQ: Hardware Friendly Mixed Precision Quantization Block for CNNs [[code](https://github.com/sony-si/ai-research)] [![GitHub stars](https://img.shields.io/github/stars/sony-si/ai-research?style=social)](https://github.com/sony-si/ai-research)

### 2019

- [[AAAI](https://www.aaai.org/ojs/index.php/AAAI/article/view/4273/4151)] Efficient Quantization for Neural Networks with Binary Weights and Low Bitwidth Activations
- [[AAAI](https://www.aaai.org/ojs/index.php/AAAI/article/view/4848/4721)] Projection Convolutional Neural Networks for 1-bit CNNs via Discrete Back Propagation
- [[APCCAS](https://ieeexplore.ieee.org/document/8953134/)] Using Neuroevolved Binary Neural Networks to solve reinforcement learning environments [[code](https://github.com/rval735/BiSUNA)] [![GitHub stars](https://img.shields.io/github/stars/rval735/BiSUNA?style=social)](https://github.com/rval735/BiSUNA)
- [[BMVC](https://arxiv.org/abs/1909.11366)] Accurate and Compact Convolutional Neural Networks with Trained Binarization
- [[BMVC](https://arxiv.org/abs/1909.13863)] XNOR-Net++: Improved Binary Neural Networks
- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Xu_A_MainSubsidiary_Network_Framework_for_Simplifying_Binary_Neural_Networks_CVPR_2019_paper.pdf)] A Main/Subsidiary Network Framework for Simplifying Binary Neural Network
- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhu_Binary_Ensemble_Neural_Network_More_Bits_per_Network_or_More_CVPR_2019_paper.pdf)] Binary Ensemble Neural Network: More Bits per Network or More Networks per Bit?
- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Circulant_Binary_Convolutional_Networks_Enhancing_the_Performance_of_1-Bit_DCNNs_CVPR_2019_paper.pdf)] Circulant Binary Convolutional Networks: Enhancing the Performance of 1-bit DCNNs with Circulant Back Propagation
- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Fully_Quantized_Network_for_Object_Detection_CVPR_2019_paper.pdf)] Fully Quantized Network for Object Detection
- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_HAQ_Hardware-Aware_Automated_Quantization_With_Mixed_Precision_CVPR_2019_paper.pdf)] HAQ: Hardware-Aware Automated Quantization with Mixed Precision [[code](https://github.com/mit-han-lab/haq)] [![GitHub stars](https://img.shields.io/github/stars/mit-han-lab/haq?style=social)](https://github.com/mit-han-lab/haq)
- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Learning_Channel-Wise_Interactions_for_Binary_Convolutional_Neural_Networks_CVPR_2019_paper.pdf)] Learning Channel-Wise Interactions for Binary Convolutional Neural Networks
- [[CVPR](https://arxiv.org/abs/1808.05779)] Learning to Quantize Deep Networks by Optimizing Quantization Intervals with Task Loss
- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yang_Quantization_Networks_CVPR_2019_paper.pdf)] Quantization Networks [[code](https://github.com/aliyun/alibabacloud-quantization-networks)] [![GitHub stars](https://img.shields.io/github/stars/aliyun/alibabacloud-quantization-networks?style=social)](https://github.com/aliyun/alibabacloud-quantization-networks)
- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Ding_Regularizing_Activation_Distribution_for_Training_Binarized_Deep_Networks_CVPR_2019_paper.pdf)] Regularizing Activation Distribution for Training Binarized Deep Networks
- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Cao_SeerNet_Predicting_Convolutional_Neural_Network_Feature-Map_Sparsity_Through_Low-Bit_Quantization_CVPR_2019_paper.pdf)] SeerNet: Predicting Convolutional Neural Network Feature-Map Sparsity Through Low-Bit Quantization
- [[CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhuang_Structured_Binary_Neural_Networks_for_Accurate_Image_Classification_and_Semantic_CVPR_2019_paper.pdf)] Structured Binary Neural Networks for Accurate Image Classification and Semantic Segmentation
- [[arXiv](https://arxiv.org/pdf/1906.08637.pdf)] Back to Simplicity: How to Train Accurate BNNs from Scratch? [[code](https://github.com/hpi-xnor/BMXNet-v2)] [![GitHub stars](https://img.shields.io/github/stars/hpi-xnor/BMXNet-v2?style=social)](https://github.com/hpi-xnor/BMXNet-v2)
- [[arXiv](https://arxiv.org/abs/1911.10862)] Binarized Neural Architecture Search
- [[arXiv](http://arxiv.org/abs/1904.05868)] Improved training of binary networks for human pose estimation and image recognition
- [[arXiv](https://arxiv.org/pdf/1904.07852.pdf)] Matrix and tensor decompositions for training binary neural networks
- [[arXiv](https://arxiv.org/abs/1908.07748)] RBCN: Rectified Binary Convolutional Networks for Enhancing the Performance of 1-bit DCNNs
- [[arXiv](https://arxiv.org/abs/1912.10103)] TentacleNet: A Pseudo-Ensemble Template for Accurate Binary Convolutional Neural Networks
- [[FPGA](https://arxiv.org/abs/1810.02068)] Towards Fast and Energy-Efficient Binarized Neural Network Inference on FPGA
- [[GLSVLSI](https://dl.acm.org/doi/pdf/10.1145/3299874.3318034)] Binarized Depthwise Separable Neural Network for Object Tracking in FPGA
- [[ICCV](https://arxiv.org/pdf/1908.06314.pdf)] Bayesian optimized 1-bit cnns
- [[ICCV](https://openaccess.thecvf.com/content_ICCV_2019/html/Nagel_Data-Free_Quantization_Through_Weight_Equalization_and_Bias_Correction_ICCV_2019_paper.html)] Data-Free Quantization Through Weight Equalization and Bias Correction [[code](https://github.com/jakc4103/DFQ)] [![GitHub stars](https://img.shields.io/github/stars/jakc4103/DFQ?style=social)](https://github.com/jakc4103/DFQ)
- [[ICCV](https://arxiv.org/abs/1908.05033)] Differentiable Soft Quantization: Bridging Full-Precision and Low-Bit Neural Networks
- [[ICCV](https://arxiv.org/abs/1901.01928)] DSConv: Efficient Convolution Operator
- [[ICCV](https://openaccess.thecvf.com/content_ICCV_2019/html/Dong_HAWQ_Hessian_AWare_Quantization_of_Neural_Networks_With_Mixed-Precision_ICCV_2019_paper.html)] HAWQ: Hessian AWare Quantization of Neural Networks With Mixed-Precision
- [[ICCV](https://openaccess.thecvf.com/content_ICCVW_2019/papers/NeurArch/Shen_Searching_for_Accurate_Binary_Neural_Architectures_ICCVW_2019_paper.pdf)] Searching for Accurate Binary Neural Architectures
- [[ICIP](https://ieeexplore.ieee.org/document/8802610)] Training Accurate Binary Neural Networks from Scratch [[code](https://github.com/hpi-xnor/BMXNet-v2)] [![GitHub stars](https://img.shields.io/github/stars/hpi-xnor/BMXNet-v2?style=social)](https://github.com/hpi-xnor/BMXNet-v2)
- [[ICLR](https://openreview.net/pdf?id=rJfUCoR5KX)] An Empirical study of Binary Neural Networks' Optimisation
- [[ICLR](https://openreview.net/pdf?id=HyzMyhCcK7)] ProxQuant: Quantized Neural Networks via Proximal Operators [[code](https://github.com/allenbai01/ProxQuant)] [![GitHub stars](https://img.shields.io/github/stars/allenbai01/ProxQuant?style=social)](https://github.com/allenbai01/ProxQuant)
- [[ICML](https://arxiv.org/abs/1906.00532v2)] Efficient 8-Bit Quantization of Transformer Neural Machine Language Translation Model
- [[ICUS](https://ieeexplore.ieee.org/document/8996039/)] Balanced Circulant Binary Convolutional Networks
- [[IEEE J. Emerg. Sel. Topics Circuits Syst.](https://ieeexplore.ieee.org/document/8668446/)] Hyperdrive: A Multi-Chip Systolically Scalable Binary-Weight CNN Inference Engine
- [[IEEE J. Solid-State Circuits](https://ieeexplore.ieee.org/document/8581485)] An Energy-Efficient Reconfigurable Processor for Binary-and Ternary-Weight Neural Networks With Flexible Data Bit Width
- [[IEEE JETC](https://arxiv.org/pdf/1807.07928.pdf)] Eyeriss v2: A Flexible Accelerator for Emerging Deep Neural Networks on Mobile Devices
- [[IEEE TCS.I](https://ieeexplore.ieee.org/abstract/document/8643565)] Recursive Binary Neural Network Training Model for Efficient Usage of On-Chip Memory
- [[IEEE TCS.I](https://arxiv.org/pdf/1807.00343.pdf)] Xcel-RAM: Accelerating Binary Neural Networks in High-Throughput SRAM Compute Arrays
- [[IJCAI](https://www.ijcai.org/Proceedings/2019/0667.pdf)] Binarized Collaborative Filtering with Distilling Graph Convolutional Network
- [[IJCAI](https://see.xidian.edu.cn/faculty/chdeng/Welcome%20to%20Cheng%20Deng's%20Homepage_files/Papers/Conference/IJCAI2019_Feng.pdf)] Binarized Neural Networks for Resource-Efficient Hashing with Minimizing Quantization Loss
- [[ISOCC](https://ieeexplore.ieee.org/document/9027649)] Dual Path Binary Neural Network
- [[MDPI Electronics](https://doi.org/10.3390/electronics8060661)] A Review of Binarized Neural Networks
- [[NeurIPS](https://www.emc2-ai.org/assets/docs/neurips-19/emc2-neurips19-paper-36.pdf)] Fully Quantized Transformer for Improved Translation
- [[NeurIPS](https://papers.nips.cc/paper/2019/file/9ca8c9b0996bbf05ae7753d34667a6fd-Paper.pdf)] Latent Weights Do Not Exist: Rethinking Binarized Neural Network Optimization [[code](https://github.com/plumerai/rethinking-bnn-optimization)] [![GitHub stars](https://img.shields.io/github/stars/plumerai/rethinking-bnn-optimization?style=social)](https://github.com/plumerai/rethinking-bnn-optimization)
- [[NeurIPS](https://csyhhu.github.io/data/MetaQuant.pdf)] MetaQuant: Learning to Quantize by Learning to Penetrate Non-differentiable Quantization [[code](https://github.com/csyhhu/MetaQuant)] [![GitHub stars](https://img.shields.io/github/stars/csyhhu/MetaQuant?style=social)](https://github.com/csyhhu/MetaQuant)
- [[NeurIPS](https://arxiv.org/abs/1902.03538)] Model Compression with Adversarial Robustness: A Unified Optimization Framework
- [[NeurIPS](https://openreview.net/pdf?id=rJgB34rx8r)] Normalization Helps Training of Quantized LSTM
- [[NeurIPS](https://www.emc2-ai.org/assets/docs/neurips-19/emc2-neurips19-paper-31.pdf)] Q8BERT: Quantized 8Bit BERT
- [[NeurIPS](http://arxiv.org/abs/1812.11800)] Regularized Binary Network Training
- [[RoEduNet](https://ieeexplore.ieee.org/document/8909493/)] PXNOR: Perturbative Binary Neural Network [[code](https://github.com/Apfelin/PXNOR)] [![GitHub stars](https://img.shields.io/github/stars/Apfelin/PXNOR?style=social)](https://github.com/Apfelin/PXNOR)
- [[SiPS](https://arxiv.org/abs/1909.01688)] Knowledge distillation for optimization of quantized deep neural networks
- [[TMM](https://arxiv.org/pdf/1712.02956.pdf)] Compact Hash Code Learning With Binary Deep Neural Network
- [[TMM](https://arxiv.org/abs/1708.05127)] Deep Binary Reconstruction for Cross-Modal Hashing
- [[VLSI-SoC](https://ieeexplore.ieee.org/document/8920343/)] A Product Engine for Energy-Efficient Execution of Binary Neural Networks Using Resistive Memories
- [[arXiv](http://arxiv.org/abs/1908.05858)] daBNN: A Super Fast Inference Framework for Binary Neural Networks on ARM devices [[code](https://github.com/JDAI-CV/dabnn)] [![GitHub stars](https://img.shields.io/github/stars/JDAI-CV/dabnn?style=social)](https://github.com/JDAI-CV/dabnn)
- [[arXiv](https://arxiv.org/abs/1812.00090)] Mixed Precision Quantization of ConvNets via Differentiable Neural Architecture Search
- [[arXiv](https://arxiv.org/abs/1911.12491)] QKD: Quantization-aware Knowledge Distillation
- [[arXiv](http://arxiv.org/abs/1902.00730)] Self-Binarizing Networks
- [[arXiv](https://arxiv.org/abs/1912.12607)] Towards Unified INT8 Training for Convolutional Neural Network
- [[paper](https://openreview.net/pdf?id=SJfHg2A5tQ)] BNN+: Improved Binary Network Training

### 2018

- [[AAAI](https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPDFInterstitial/16767/16728)] Extremely Low Bit Neural Network: Squeeze the Last Bit Out with ADMM [[code](https://web.stanford.edu/~boyd/admm.html)]
- [[AAAI](https://arxiv.org/abs/1802.02733)] From Hashing to CNNs: Training BinaryWeight Networks via Hashing
- [[CAAI](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8603080)] Fast object detection based on binary deep convolution neural networks
- [[CVPR](https://arxiv.org/abs/1908.04680)] Effective Training of Convolutional Neural Networks with Low-bitwidth Weights and Activations
- [[CVPR](https://openaccess.thecvf.com/content_cvpr_2018/html/Zhou_Explicit_Loss-Error-Aware_Quantization_CVPR_2018_paper.html)] Explicit loss-error-aware quantization for low-bit deep neural networks
- [[CVPR](https://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Modulated_Convolutional_Networks_CVPR_2018_paper.pdf)] Modulated convolutional networks
- [[CVPR](https://openaccess.thecvf.com/content_cvpr_2018/papers/Jacob_Quantization_and_Training_CVPR_2018_paper.pdf)] Quantization and Training of Neural Networks for Efficient Integer-Arithmetic-Only Inference
- [[CVPR](https://openaccess.thecvf.com/content_cvpr_2018/papers/Faraone_SYQ_Learning_Symmetric_CVPR_2018_paper.pdf)] SYQ: Learning Symmetric Quantization For Efficient Deep Neural Networks [[code](https://www.github.com/julianfaraone/SYQ)]
- [[CVPR](https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhuang_Towards_Effective_Low-Bitwidth_CVPR_2018_paper.pdf)] Towards Effective Low-bitwidth Convolutional Neural Networks
- [[CVPR](https://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Two-Step_Quantization_for_CVPR_2018_paper.pdf)] Two-Step Quantization for Low-bit Neural Networks
- [[arXiv](https://arxiv.org/pdf/1801.06313.pdf)] BinaryRelax: A Relaxation Approach For Training Deep Neural Networks With Quantized Weights
- [[arXiv](https://arxiv.org/abs/1802.02178)] LightNN: Filling the Gap between Conventional Deep Neural Networks and Binarized Networks
- [[ECCV](https://openaccess.thecvf.com/content_ECCV_2018/papers/zechun_liu_Bi-Real_Net_Enhancing_ECCV_2018_paper.pdf)] Bi-Real Net: Enhancing the Performance of 1-bit CNNs With Improved Representational Capability and Advanced Training Algorithm [[code](https://github.com/liuzechun/Bi-Real-net)] [![GitHub stars](https://img.shields.io/github/stars/liuzechun/Bi-Real-net?style=social)](https://github.com/liuzechun/Bi-Real-net)
- [[ECCV](https://openaccess.thecvf.com/content_ECCV_2018/papers/Dongqing_Zhang_Optimized_Quantization_for_ECCV_2018_paper.pdf)] LQ-Nets: Learned Quantization for Highly Accurate and Compact Deep Neural Networks [[code](https://github.com/microsoft/LQ-Nets)] [![GitHub stars](https://img.shields.io/github/stars/microsoft/LQ-Nets?style=social)](https://github.com/microsoft/LQ-Nets)
- [[ECCV](https://yan-junjie.github.io/publication/dblp-confeccv-wei-pqoy-18/dblp-confeccv-wei-pqoy-18.pdf)] Quantization Mimic: Towards Very Tiny CNN for Object Detection
- [[ECCV](https://openaccess.thecvf.com/content_ECCV_2018/papers/Diwen_Wan_TBN_Convolutional_Neural_ECCV_2018_paper.pdf)] TBN: Convolutional Neural Network with Ternary Inputs and Binary Weights [[code](https://github.com/dnvtmf/TBN)] [![GitHub stars](https://img.shields.io/github/stars/dnvtmf/TBN?style=social)](https://github.com/dnvtmf/TBN)
- [[ECCV](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Qinghao_Hu_Training_Binary_Weight_ECCV_2018_paper.pdf)] Training Binary Weight Networks via Semi-Binary Decomposition
- [[FCCM](http://aceslab.org/sites/default/files/FCCM_2018_resbinnet.pdf)] ReBNet: Residual Binarized Neural Network [[code](https://github.com/mohaghasemzadeh/ReBNet)] [![GitHub stars](https://img.shields.io/github/stars/mohaghasemzadeh/ReBNet?style=social)](https://github.com/mohaghasemzadeh/ReBNet)
- [[FPL](https://ieeexplore.ieee.org/document/8532584/)] FBNA: A Fully Binarized Neural Network Accelerator
- [[ICLR](https://openreview.net/pdf?id=ryM_IoAqYX)] Analysis of Quantized Models
- [[ICLR](https://openreview.net/pdf?id=B1ae1lZRb)] Apprentice: Using Knowledge Distillation Techniques To Improve Low-Precision Network Accuracy
- [[ICLR](https://arxiv.org/abs/1802.08635)] Loss-aware Weight Quantization of Deep Networks [[code](https://github.com/houlu369/Loss-aware-weight-quantization)] [![GitHub stars](https://img.shields.io/github/stars/houlu369/Loss-aware-weight-quantization?style=social)](https://github.com/houlu369/Loss-aware-weight-quantization)
- [[ICLR](https://research-explorer.app.ist.ac.at/download/7812/7894/2018_ICLR_Polino.pdf)] Model compression via distillation and quantization [[code](https://github.com/antspy/quantized_distillation)] [![GitHub stars](https://img.shields.io/github/stars/antspy/quantized_distillation?style=social)](https://github.com/antspy/quantized_distillation)
- [[ICLR](https://openreview.net/pdf?id=By5ugjyCb)] PACT: Parameterized Clipping Activation for Quantized Neural Networks
- [[ICLR](https://openreview.net/pdf?id=B1ZvaaeAZ)] WRPN: Wide Reduced-Precision Networks
- [[IEEE J. Solid-State Circuits](http://ieeexplore.ieee.org/document/8226999/)] BRein Memory: A Single-Chip Binary/Ternary Reconfigurable in-Memory Deep Neural Network Accelerator Achieving 1.4 TOPS at 0.6 W
- [[IJCAI](https://www.ijcai.org/Proceedings/2018/0380.pdf)] Deterministic Binary Filters for Convolutional Neural Networks
- [[IJCAI](https://www.ijcai.org/Proceedings/2018/0669.pdf)] Planning in Factored State and Action Spaces with Learned Binarized Neural Network Transition Models
- [[IJCNN](https://ieeexplore.ieee.org/document/8489259)] Analysis and Implementation of Simple Dynamic Binary Neural Networks
- [[IPDPS](https://ieeexplore.ieee.org/document/8425178)] BitFlow: Exploiting Vector Parallelism for Binary Neural Networks on CPU
- [[MM](https://dl.acm.org/doi/10.1145/3240508.3240673)] BitStream: Efficient Computing Architecture for Real-Time Low-Power Inference of Binary Neural Networks on CPUs
- [[NCA](https://arxiv.org/pdf/1712.08934.pdf)] A survey of FPGA-based accelerators for convolutional neural networks
- [[NeurIPS](https://papers.nips.cc/paper/2018/file/e82c4b19b8151ddc25d4d93baf7b908f-Paper.pdf)] Scalable methods for 8-bit training of neural networks [[code](https://github.com/eladhoffer/quantized.pytorch)] [![GitHub stars](https://img.shields.io/github/stars/eladhoffer/quantized.pytorch?style=social)](https://github.com/eladhoffer/quantized.pytorch)
- [[NeurIPS](https://papers.nips.cc/paper/2018/file/335d3d1cd7ef05ec77714a215134914c-Paper.pdf)] Training Deep Neural Networks with 8-bit Floating Point Numbers
- [[Res Math Sci](https://arxiv.org/abs/1808.05240)] Blended coarse gradient descent for full quantization of deep neural networks
- [[TCAD](https://ieeexplore.ieee.org/document/8412533/)] XNOR Neural Engine: A Hardware Accelerator IP for 21.6-fJ/op Binary Neural Network Inference
- [[TRETS](http://arxiv.org/abs/1809.04570)] FINN-R: An End-to-End Deep-Learning Framework for Fast Exploration of Quantized Neural Networks
- [[TVLSI](http://ieeexplore.ieee.org/document/8103902/)] An Energy-Efficient Architecture for Binary Weight Convolutional Neural Networks
- [[arXiv](https://arxiv.org/abs/1811.09426)] Joint Neural Architecture Search and Quantization [[code](https://github.com/yukang2017/NAS-quantization)] [![GitHub stars](https://img.shields.io/github/stars/yukang2017/NAS-quantization?style=social)](https://github.com/yukang2017/NAS-quantization)
- [[arXiv](https://arxiv.org/abs/1812.01965)] Training Competitive Binary Neural Networks from Scratch [[code](https://github.com/hpi-xnor/BMXNet-v2)] [![GitHub stars](https://img.shields.io/github/stars/hpi-xnor/BMXNet-v2?style=social)](https://github.com/hpi-xnor/BMXNet-v2)

### 2017

- [[CVPR](https://openaccess.thecvf.com/content_cvpr_2017/papers/Cai_Deep_Learning_With_CVPR_2017_paper.pdf)] Deep Learning with Low Precision by Half-wave Gaussian Quantization [[code](https://github.com/zhaoweicai/hwgq)] [![GitHub stars](https://img.shields.io/github/stars/zhaoweicai/hwgq?style=social)](https://github.com/zhaoweicai/hwgq)
- [[CVPR](https://openaccess.thecvf.com/content_cvpr_2017/papers/Juefei-Xu_Local_Binary_Convolutional_CVPR_2017_paper.pdf)] Local Binary Convolutional Neural Networks [[code](https://github.com/juefeix/lbcnn.torch)] [![GitHub stars](https://img.shields.io/github/stars/juefeix/lbcnn.torch?style=social)](https://github.com/juefeix/lbcnn.torch)
- [[arXiv](https://arxiv.org/pdf/1705.09864.pdf)] BMXNet: An Open-Source Binary Neural Network Implementation Based on MXNet [[code](https://github.com/hpi-xnor)]
- [[FPGA](https://arxiv.org/abs/1612.07119)] FINN: A Framework for Fast, Scalable Binarized Neural Network Inference
- [[ICASSP](https://arxiv.org/abs/1702.08171)] Fixed-point optimization of deep neural networks with adaptive step size retraining
- [[ICCV](https://openaccess.thecvf.com/content_ICCV_2017/papers/Bulat_Binarized_Convolutional_Landmark_ICCV_2017_paper.pdf)] Binarized Convolutional Landmark Localizers for Human Pose Estimation and Face Alignment with Limited Resources [[code](https://www.adrianbulat.com/binary-cnn-landmarks)]
- [[ICCV](https://openaccess.thecvf.com/content_ICCV_2017/papers/Li_Performance_Guaranteed_Network_ICCV_2017_paper.pdf)] Performance Guaranteed Network Acceleration via High-Order Residual Quantization
- [[ICLR](https://openreview.net/pdf?id=HyQJ-mclg)] Incremental Network Quantization: Towards Lossless CNNs with Low-Precision Weights [[code](https://github.com/Mxbonn/INQ-pytorch)] [![GitHub stars](https://img.shields.io/github/stars/Mxbonn/INQ-pytorch?style=social)](https://github.com/Mxbonn/INQ-pytorch)
- [[ICLR](https://openreview.net/pdf?id=S1oWlN9ll)] Loss-aware Binarization of Deep Networks [[code](https://github.com/houlu369/Loss-aware-Binarization)] [![GitHub stars](https://img.shields.io/github/stars/houlu369/Loss-aware-Binarization?style=social)](https://github.com/houlu369/Loss-aware-Binarization)
- [[ICLR](https://openreview.net/pdf?id=HJGwcKclx)] Soft Weight-Sharing for Neural Network Compression
- [[ICLR](https://openreview.net/pdf?id=S1_pAu9xl)] Trained Ternary Quantization [[code](https://github.com/TropComplique/trained-ternary-quantization)] [![GitHub stars](https://img.shields.io/github/stars/TropComplique/trained-ternary-quantization?style=social)](https://github.com/TropComplique/trained-ternary-quantization)
- [[IPDPSW](https://ieeexplore.ieee.org/document/7965031)] On-Chip Memory Based Binarized Convolutional Deep Neural Network Applying Batch Normalization Free Technique on an FPGA
- [[InterSpeech](https://www.isca-speech.org/archive/Interspeech_2017/pdfs/1343.PDF)] Binary Deep Neural Networks for Speech Recognition
- [[JETC](https://arxiv.org/abs/1702.06392)] A GPU-Outperforming FPGA Accelerator Architecture for Binary Convolutional Neural Networks
- [[MWSCAS](http://ieeexplore.ieee.org/document/8052915/)] Deep learning binary neural network on an FPGA
- [[NeurIPS](https://arxiv.org/abs/1711.11294)] Towards Accurate Binary Convolutional Neural Network [[code](https://github.com/layog/Accurate-Binary-Convolution-Network)] [![GitHub stars](https://img.shields.io/github/stars/layog/Accurate-Binary-Convolution-Network?style=social)](https://github.com/layog/Accurate-Binary-Convolution-Network)
- [[Neurocomputing](http://www.doc.ic.ac.uk/~wl/papers/17/neuro17sl0.pdf)] FP-BNN: Binarized neural network on FPGA
- [[arXiv](https://arxiv.org/abs/1706.02393)] ShiftCNN: Generalized Low-Precision Architecture for Inference of Convolutional Neural Networks [[code](https://github.com/gudovskiy/ShiftCNN)] [![GitHub stars](https://img.shields.io/github/stars/gudovskiy/ShiftCNN?style=social)](https://github.com/gudovskiy/ShiftCNN)
- [[arXiv](https://arxiv.org/pdf/1705.01462.pdf)] Ternary Neural Networks with Fine-Grained Quantization

### 2016

- [[CVPR](https://openaccess.thecvf.com/content_cvpr_2016/html/Wu_Quantized_Convolutional_Neural_CVPR_2016_paper.html)] Quantized convolutional neural networks for mobile devices. [code](https://github.com/jiaxiang-wu/quantized-cnn)
- [[arXiv](http://arxiv.org/abs/1606.06160)] DoReFa-Net: Training Low Bitwidth Convolutional Neural Networks with Low Bitwidth Gradients [[code](https://github.com/tensorpack/tensorpack/tree/master/examples/DoReFa-Net)] [![GitHub stars](https://img.shields.io/github/stars/tensorpack/tensorpack?style=social)](https://github.com/tensorpack/tensorpack)
- [[ECCV](https://arxiv.org/abs/1603.05279)] XNOR-Net: ImageNet Classification Using Binary Convolutional Neural Networks [[code](https://github.com/allenai/XNOR-Net)] [![GitHub stars](https://img.shields.io/github/stars/allenai/XNOR-Net?style=social)](https://github.com/allenai/XNOR-Net)
- [[ICASSP](https://arxiv.org/abs/1512.01322)] Fixed-point Performance Analysis of Recurrent Neural Networks
- [[NeurIPS](https://arxiv.org/pdf/1602.02830)] Binarized Neural Networks: Training Deep Neural Networks with Weights and Activations Constrained to +1 or -1 [[code](https://github.com/itayhubara/BinaryNet)] [![GitHub stars](https://img.shields.io/github/stars/itayhubara/BinaryNet?style=social)](https://github.com/itayhubara/BinaryNet)
- [[NeurIPS](https://arxiv.org/pdf/1605.04711.pdf)] Ternary weight networks [[code](https://github.com/fengfu-chris/caffe-twns)] [![GitHub stars](https://img.shields.io/github/stars/fengfu-chris/caffe-twns?style=social)](https://github.com/fengfu-chris/caffe-twns)

### 2015

- [[ICML](https://arxiv.org/abs/1601.06071)] Bitwise Neural Networks
- [[NeurIPS](https://arxiv.org/abs/1511.00363)] BinaryConnect: Training Deep Neural Networks with binary weights during propagations [[code](https://github.com/MatthieuCourbariaux/BinaryConnect)] [![GitHub stars](https://img.shields.io/github/stars/MatthieuCourbariaux/BinaryConnect?style=social)](https://github.com/MatthieuCourbariaux/BinaryConnect)
- [[arXiv](https://arxiv.org/abs/1511.06488)] Resiliency of Deep Neural Networks under quantizations

## Books

- [Quantization and Fast Inference: A practitioner’s guide to efficient AI](https://www.manning.com/books/quantization-and-fast-inference)

## Related Repositories

- [Awesome Efficient LLM & Diffusion](https://github.com/efficient-ml/awesome-efficient-llm-diffusion)
- [Awesome Quantization Papers](https://github.com/Zhen-Dong/Awesome-Quantization-Papers)

## Star History

<a href="https://www.star-history.com/?repos=Efficient-ML%2FAwesome-Model-Quantization&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=Efficient-ML/Awesome-Model-Quantization&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=Efficient-ML/Awesome-Model-Quantization&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=Efficient-ML/Awesome-Model-Quantization&type=date&legend=top-left" />
 </picture>
</a>

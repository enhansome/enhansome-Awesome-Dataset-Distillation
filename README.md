# Awesome Dataset Distillation with stars

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 497,652 | 🐛 102 | 📅 2026-08-18 <img src="https://img.shields.io/badge/Contributions-Welcome-278ea5" alt="Contrib"/> <img src="https://img.shields.io/badge/Number%20of%20Items-352-FF6F00" alt="PaperNum"/> ![Stars](https://img.shields.io/github/stars/Guang000/Awesome-Dataset-Distillation?color=yellow\&label=Stars) ![Forks](https://img.shields.io/github/forks/Guang000/Awesome-Dataset-Distillation?color=green\&label=Forks)

**Awesome Dataset Distillation** provides the most comprehensive and detailed information on the Dataset Distillation field.

**Dataset distillation** is the task of synthesizing a small dataset such that models trained on it achieve high performance on the original large dataset. A dataset distillation algorithm takes as **input** a large real dataset to be distilled (training set), and **outputs** a small synthetic distilled dataset, which is evaluated via testing models trained on this distilled dataset on a separate real dataset (validation/test set). A good small distilled dataset is not only useful in dataset understanding, but has various applications (e.g., continual learning, privacy, neural architecture search, etc.). This task was first introduced in the paper [*Dataset Distillation* \[Tongzhou Wang et al., '18\]](https://www.tongzhouwang.info/dataset_distillation/), along with a proposed algorithm using backpropagation through optimization steps. Then the task was first extended to the real-world datasets in the paper [*Medical Dataset Distillation* \[Guang Li et al., '19\]](https://arxiv.org/abs/2104.02857), which also explored the privacy preservation possibilities of dataset distillation. In the paper [*Dataset Condensation* \[Bo Zhao et al., '20\]](https://arxiv.org/abs/2006.05929), gradient matching was first introduced and greatly promoted the development of the dataset distillation field.

In recent years (2022-now), dataset distillation has gained increasing attention in the research community, across many institutes and labs. More papers are now being published each year. These wonderful researches have been constantly improving dataset distillation and exploring its various variants and applications.

**This project is curated and maintained by [Guang Li](https://guang000.github.io/), [Bo Zhao](https://www.bozhao.me/), and [Tongzhou Wang](https://www.tongzhouwang.info/).**

<img src="./images/logo.jpg" width="20%"/>

#### [How to submit a pull request?](./CONTRIBUTING.md)

* :globe\_with\_meridians: Project Page
* :octocat: Code
* :book: `bibtex`

## Latest Updates

* \[2026/07/07] [Hard Labels In! Rethinking the Role of Hard Labels in Mitigating Local Semantic Drift](https://arxiv.org/abs/2512.15647) (Jiacheng Cui et al., ICML 2026) [:octocat:](https://github.com/Jiacheng8/HALD) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-05-01 [:book:](./citations/cui2026hard.txt)
* \[2026/07/08] [Distill Once, Adapt Life-Long: Exploring Dataset Distillation for Continual Test-Time Adaptation](https://arxiv.org/abs/2606.20196) (Hyun-Kurl Jang & Jihun Kim & Hyeokjun Kweon et al., ECCV 2026) [:octocat:](https://github.com/blue-531/DOALL) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2026-06-24 [:book:](./citations/jang2026doall.txt)
* \[2026/07/08] [FD2: A Dedicated Framework for Fine-Grained Dataset Distillation](https://arxiv.org/abs/2603.25144) (Hongxu Ma & Guang Li et al., ECCV 2026) [:globe\_with\_meridians:](https://guang000.github.io/FD2-Webpage/) [:octocat:](https://github.com/Guang000/FD2) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2026-07-23 [:book:](./citations/ma2026fd2.txt)
* \[2026/07/08] [Condensing Large-Scale Datasets Directly with Minimal Information Loss](https://arxiv.org/abs/2607.00916) (Xinyi Shang & Peng Sun & Bei Shi et al., ECCV 2026) [:octocat:](https://github.com/LINs-lab/CIM) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2026-06-29 [:book:](./citations/shang2026cim.txt)
* \[2026/07/07] [One Batch Is Enough: A Unified Dataset Condensation Framework for General Time Series Analysis](https://openreview.net/forum?id=i8FO7f2OYJ) (Wei Shao et al., ICML 2026) [:octocat:](https://github.com/ZJU-DAILY/UniTSC) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-05-17 [:book:](./citations/shao2026unitsc.txt)
* \[2026/07/07] [Set-Coupled Guidance: Set-Level Coordination in Diffusion-Based Dataset Distillation](https://openreview.net/forum?id=onosLtwoiK) (Ziang Gan et al., ICML 2026) [:octocat:](https://github.com/tade1s/SCG) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-07-27 [:book:](./citations/gan2026scg.txt)
* \[2026/07/08] [Rank-Aware Hyperbolic Alignment for Vision-Language Dataset Distillation](https://arxiv.org/abs/2606.29464) (Jongoh Jeong et al., ECCV 2026) [:globe\_with\_meridians:](https://andyj1.github.io/raha/) [:octocat:](https://github.com/andyj1/raha) ⭐ 0 | 🐛 0 | 📅 2026-08-09 [:book:](./citations/jeong2026raha.txt)
* \[2026/07/07] [Efficient Multi-modal Dataset Distillation via Analytic Parameter Matching](https://openreview.net/forum?id=Yh4dMR5mJ0) (Deyu Bo et al., ICML 2026) [:octocat:](https://github.com/bdy9527/MMDD) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2025-12-09 [:book:](./citations/bo2026apm.txt)
* \[2026/07/08] [Adaptive Latent Trajectory Anchoring for Action Segmentation Dataset Condensation](https://arxiv.org/abs/2607.09081) (Arthème Gauthier-Villars & Guodong Ding et al., ECCV 2026) [:book:](./citations/gauthier2026adaptive.txt)
* \[2026/07/08] [Structural Assessment for Understanding and Guiding Dataset Distillation in Discrete Token Space](https://arxiv.org/abs/2606.21705) (Yue Cao et al., ECCV 2026) [:book:](./citations/cao2026structural.txt)
* \[2026/07/07] [ProtoVAR: Efficient Dataset Distillation via Prototype-Guided Visual Autoregressive Modeling](https://openreview.net/forum?id=5YvTHX0QS9) (Mingyu Wang et al., ICML 2026) [:book:](./citations/protovar2026.txt)
* \[2026/07/07] [Utility Boundary of Dataset Distillation: Scaling and Configuration-Coverage Laws](https://openreview.net/forum?id=wbXPNPw5jW) (Zhengquan Luo et al., ICML 2026) [:book:](./citations/luo2026utility.txt)
* \[2026/07/07] [Attention Hijacking: Backdooring Text Dataset Distillation via Semantic Anchors](https://openreview.net/forum?id=g4BWfkULIo) (Hang Ren et al., ICML 2026) [:book:](./citations/ren2026attention.txt)

## Contents

* [Main](#main)
  * [Early Work](#early-work)
  * [Gradient/Trajectory Matching Surrogate Objective](#gradient-objective)
  * [Distribution/Feature Matching Surrogate Objective](#feature-objective)
  * [Kernel-Based Distillation](#kernel)
  * [Distilled Dataset Parametrization](#parametrization)
  * [Generative Distillation](#generative)
  * [Better Optimization](#optimization)
  * [Better Understanding](#understanding)
  * [Label Distillation](#label)
  * [Dataset Quantization](#quant)
  * [Decoupled Distillation](#decouple)
  * [Multimodal Distillation](#multi)
  * [Self-Supervised Distillation](#self)
  * [Benchmark](#benchmark)
  * [Survey](#survey)
  * [Ph.D. Thesis](#thesis)
  * [Workshop](#workshop)
  * [Challenge](#challenge)
* [Applications](#applications)
  * [Continual Learning](#continual)
  * [Privacy](#privacy)
  * [Medical](#medical)
  * [Federated Learning](#fed)
  * [Graph Neural Network](#gnn)
  * [Neural Architecture Search](#nas)
  * [Fashion, Art, and Design](#fashion)
  * [Recommender Systems](#rec)
  * [Blackbox Optimization](#blackbox)
  * [Robustness](#robustness)
  * [Fairness](#fairness)
  * [Text](#text)
  * [Video](#video)
  * [Tabular](#tabular)
  * [Retrieval](#retrieval)
  * [Domain Adaptation](#domain)
  * [Super Resolution](#super)
  * [Time Series](#time)
  * [Speech](#speech)
  * [Machine Unlearning](#unlearning)
  * [Reinforcement Learning](#rl)
  * [Long-Tail](#long)
  * [Learning with Noisy Labels](#noisy)
  * [Object Detection](#detection)
  * [Point Cloud](#point)
  * [Universal Distillation](#uni)
  * [Spiking Neural Network](#snn)
  * [EEG](#eeg)
  * [Finance](#finance)
  * [Music](#music)
  * [Remote Sensing](#rs)
  * [Deraining](#dr)
  * [Fine-Grained](#fine)
  * [Test-Time Adaptation](#tta)
  * [Semantic Segmentation](#segmentation)
    <a name="main" />

## Main

* [Dataset Distillation](https://arxiv.org/abs/1811.10959) (Tongzhou Wang et al., 2018) [:globe\_with\_meridians:](https://ssnl.github.io/dataset_distillation/) [:octocat:](https://github.com/SsnL/dataset-distillation) ⭐ 829 | 🐛 11 | 🌐 Python | 📅 2025-06-17 [:book:](./citations/wang2018datasetdistillation.txt)

<a name="early-work" />

### Early Work

* [Gradient-Based Hyperparameter Optimization Through Reversible Learning](https://arxiv.org/abs/1502.03492) (Dougal Maclaurin et al., ICML 2015) [:octocat:](https://github.com/HIPS/hypergrad) ⭐ 297 | 🐛 5 | 🌐 Python | 📅 2016-01-15 [:book:](./citations/maclaurin2015gradient.txt)

<a name="gradient-objective" />

### Gradient/Trajectory Matching Surrogate Objective

* [Dataset Condensation with Gradient Matching](https://arxiv.org/abs/2006.05929) (Bo Zhao et al., ICLR 2021) [:octocat:](https://github.com/VICO-UoE/DatasetCondensation) ⭐ 541 | 🐛 4 | 🌐 Python | 📅 2023-11-27 [:book:](./citations/zhao2021datasetcondensation.txt)
* [Dataset Condensation with Differentiable Siamese Augmentation](https://arxiv.org/abs/2102.08259) (Bo Zhao et al., ICML 2021) [:octocat:](https://github.com/VICO-UoE/DatasetCondensation) ⭐ 541 | 🐛 4 | 🌐 Python | 📅 2023-11-27 [:book:](./citations/zhao2021differentiatble.txt)
* [Dataset Distillation by Matching Training Trajectories](https://arxiv.org/abs/2203.11932) (George Cazenavette et al., CVPR 2022) [:globe\_with\_meridians:](https://georgecazenavette.github.io/mtt-distillation/) [:octocat:](https://github.com/georgecazenavette/mtt-distillation) ⭐ 439 | 🐛 9 | 🌐 Python | 📅 2024-07-16 [:book:](./citations/cazenavette2022dataset.txt)
* [Minimizing the Accumulated Trajectory Error to Improve Dataset Distillation](https://arxiv.org/abs/2211.11004) (Jiawei Du & Yidi Jiang et al., CVPR 2023) [:octocat:](https://github.com/AngusDujw/FTD-distillation) ⭐ 40 | 🐛 3 | 🌐 Python | 📅 2023-03-25 [:book:](./citations/du2023minimizing.txt)
* [Scaling Up Dataset Distillation to ImageNet-1K with Constant Memory](https://arxiv.org/abs/2211.10586) (Justin Cui et al., ICML 2023) [:octocat:](https://github.com/justincui03/tesla) ⭐ 30 | 🐛 4 | 🌐 Python | 📅 2024-04-12 [:book:](./citations/cui2022scaling.txt)
* [Emphasizing Discriminative Features for Dataset Distillation in Complex Scenarios](https://arxiv.org/abs/2410.17193) (Kai Wang & Zekai Li et al., CVPR 2025) [:octocat:](https://github.com/NUS-HPC-AI-Lab/EDF) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2024-11-16 [:book:](./citations/wang2025edf.txt)
* [Dataset Condensation with Contrastive Signals](https://arxiv.org/abs/2202.02916) (Saehyung Lee et al., ICML 2022) [:octocat:](https://github.com/saehyung-lee/dcc) ⭐ 22 | 🐛 1 | 🌐 Python | 📅 2022-06-08 [:book:](./citations/lee2022dataset.txt)
* [Loss-Curvature Matching for Dataset Selection and Condensation](https://arxiv.org/abs/2303.04449) (Seungjae Shin & Heesun Bae et al., AISTATS 2023) [:octocat:](https://github.com/SJShin-AI/LCMat) ⭐ 22 | 🐛 2 | 🌐 Python | 📅 2023-03-14 [:book:](./citations/shin2023lcmat.txt)
* [Prioritize Alignment in Dataset Distillation](https://arxiv.org/abs/2408.03360) (Zekai Li & Ziyao Guo et al., 2024) [:octocat:](https://github.com/NUS-HPC-AI-Lab/PAD) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2024-12-03 [:book:](./citations/li2024pad.txt)
* [SelMatch: Effectively Scaling Up Dataset Distillation via Selection-Based Initialization and Partial Updates by Trajectory Matching](https://arxiv.org/abs/2406.18561) (Yongmin Lee et al., ICML 2024) [:octocat:](https://github.com/Yongalls/SelMatch) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2024-05-28 [:book:](./citations/lee2024selmatch.txt)
* [Dataset Distillation by Automatic Training Trajectories](https://arxiv.org/abs/2407.14245) (Dai Liu et al., ECCV 2024) [:octocat:](https://github.com/NiaLiu/ATT) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2024-10-21 [:book:](./citations/liu2024att.txt)
* [Towards Stable and Storage-efficient Dataset Distillation: Matching Convexified Trajectory](https://arxiv.org/abs/2406.19827) (Wenliang Zhong et al., CVPR 2025) [:octocat:](https://github.com/Zhong0x29a/MCT) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-04-07 [:book:](./citations/zhong2025mct.txt)
* [Sequential Subset Matching for Dataset Distillation](https://arxiv.org/abs/2311.01570) (Jiawei Du et al., NeurIPS 2023) [:octocat:](https://github.com/shqii1j/seqmatch) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2023-12-28 [:book:](./citations/du2023seqmatch.txt)
* [Towards Lossless Dataset Distillation via Difficulty-Aligned Trajectory Matching](https://arxiv.org/abs/2310.05773) (Ziyao Guo & Kai Wang et al., ICLR 2024) [:globe\_with\_meridians:](https://gzyaftermath.github.io/DATM/) [:octocat:](https://github.com/GzyAftermath/DATM) ⭐ 0 | 🐛 0 | 📅 2024-04-09 [:book:](./citations/guo2024datm.txt)
* [Neural Spectral Decomposition for Dataset Distillation](https://arxiv.org/abs/2408.16236) (Shaolei Yang et al., ECCV 2024) [:octocat:](https://github.com/slyang2021/NSD) ⭐ 0 | 🐛 1 | 📅 2024-07-09 [:book:](./citations/yang2024nsd.txt)

<a name="feature-objective" />

### Distribution/Feature Matching Surrogate Objective

* [Dataset Condensation with Distribution Matching](https://arxiv.org/abs/2110.04181) (Bo Zhao et al., WACV 2023) [:octocat:](https://github.com/VICO-UoE/DatasetCondensation) ⭐ 541 | 🐛 4 | 🌐 Python | 📅 2023-11-27 [:book:](./citations/zhao2023distribution.txt)
* [Dataset Distillation with Neural Characteristic Function: A Minmax Perspective](https://arxiv.org/abs/2502.20653) (Shaobo Wang et al., CVPR 2025) [:octocat:](https://github.com/gszfwsb/NCFM) ⭐ 413 | 🐛 2 | 🌐 Python | 📅 2026-06-03 [:book:](./citations/wang2025ncfm.txt)
* [CAFE: Learning to Condense Dataset by Aligning Features](https://arxiv.org/abs/2203.01531) (Kai Wang & Bo Zhao et al., CVPR 2022) [:octocat:](https://github.com/kaiwang960112/cafe) ⭐ 73 | 🐛 1 | 🌐 Python | 📅 2023-12-12 [:book:](./citations/wang2022cafe.txt)
* [Dataset Distillation via the Wasserstein Metric](https://arxiv.org/abs/2311.18531) (Haoyang Liu et al., ICCV 2025) [:globe\_with\_meridians:](https://liu-hy.github.io/WMDD/) [:octocat:](https://github.com/Liu-Hy/WMDD) ⭐ 58 | 🐛 0 | 🌐 Python | 📅 2026-03-08 [:book:](./citations/liu2025wasserstein.txt)
* [DataDAM: Efficient Dataset Distillation with Attention Matching](https://arxiv.org/abs/2310.00093) (Ahmad Sajedi & Samir Khaki et al., ICCV 2023) [:globe\_with\_meridians:](https://datadistillation.github.io/DataDAM/) [:octocat:](https://github.com/DataDistillation/DataDAM) ⭐ 34 | 🐛 1 | 🌐 Python | 📅 2024-06-20 [:book:](./citations/sajedi2023datadam.txt)
* [Improved Distribution Matching for Dataset Condensation](https://arxiv.org/abs/2307.09742) (Ganlong Zhao et al., CVPR 2023) [:octocat:](https://github.com/uitrbn/IDM) ⭐ 28 | 🐛 4 | 🌐 Python | 📅 2023-06-12 [:book:](./citations/zhao2023idm.txt)
* [M3D: Dataset Condensation by Minimizing Maximum Mean Discrepancy](https://arxiv.org/abs/2312.15927) (Hansong Zhang & Shikun Li et al., AAAI 2024)  [:octocat:](https://github.com/Hansong-Zhang/M3D) ⭐ 26 | 🐛 3 | 🌐 Python | 📅 2024-03-02 [:book:](./citations/zhang2024m3d.txt)
* [Hyperbolic Dataset Distillation](https://arxiv.org/abs/2505.24623) (Wenyuan Li & Guang Li et al., NeurIPS 2025) [:globe\_with\_meridians:](https://guang000.github.io/HDD-Webpage/) [:octocat:](https://github.com/Guang000/HDD) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2026-03-20 [:book:](./citations/li2025hdd.txt)
* [Exploiting Inter-sample and Inter-feature Relations in Dataset Distillation](https://arxiv.org/abs/2404.00563) (Wenxiao Deng et al., CVPR 2024) [:octocat:](https://github.com/VincenDen/IID) ⭐ 10 | 🐛 2 | 🌐 Python | 📅 2024-06-16 [:book:](./citations/deng2024iid.txt)
* [DANCE: Dual-View Distribution Alignment for Dataset Condensation](https://arxiv.org/abs/2406.01063) (Hansong Zhang et al., IJCAI 2024) [:octocat:](https://github.com/Hansong-Zhang/DANCE) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2024-08-26 [:book:](./citations/zhang2024dance.txt)
* [Diversified Semantic Distribution Matching for Dataset Distillation](https://dl.acm.org/doi/10.1145/3664647.3680900) (Hongcheng Li et al., MM 2024) [:octocat:](https://github.com/Li-Hongcheng/DSDM) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-08-10 [:book:](./citations/li2024dsdm.txt)
* [TGDD: Trajectory Guided Dataset Distillation with Balanced Distribution](https://arxiv.org/abs/2512.02469) (Fengli Ran et al., AAAI 2026) [:octocat:](https://github.com/FlyFinley/TGDD) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-05-09 [:book:](./citations/ran2026tgdd.txt)
* [Dataset Condensation with Latent Quantile Matching](https://openaccess.thecvf.com/content/CVPR2024W/DDCV/html/Wei_Dataset_Condensation_with_Latent_Quantile_Matching_CVPRW_2024_paper.html) (Wei Wei et al., CVPR 2024 Workshop) [:book:](./citations/wei2024lqm.txt)
* [OPTICAL: Leveraging Optimal Transport for Contribution Allocation in Dataset Distillation](https://openaccess.thecvf.com/content/CVPR2025/html/Cui_OPTICAL_Leveraging_Optimal_Transport_for_Contribution_Allocation_in_Dataset_Distillation_CVPR_2025_paper.html) (Xiao Cui et al., CVPR 2025) [:book:](./citations/cui2025optical.txt)
* [Diversity-Enhanced Distribution Alignment for Dataset Distillation](https://openaccess.thecvf.com/content/ICCV2025/html/Li_Diversity-Enhanced_Distribution_Alignment_for_Dataset_Distillation_ICCV_2025_paper.html) (Hongcheng Li et al., ICCV 2025) [:book:](./citations/li2025deda.txt)
* [GeoDM: Geometry-aware Distribution Matching for Dataset Distillation](https://arxiv.org/abs/2512.08317) (Xuhui Li et al., ICML 2026) [:book:](./citations/li2026geodm.txt)

<a name="kernel" />

### Kernel-Based Distillation

* [Dataset Meta-Learning from Kernel Ridge-Regression](https://arxiv.org/abs/2011.00050) (Timothy Nguyen et al., ICLR 2021) [:octocat:](https://github.com/google/neural-tangents) ⚠️ Archived [:book:](./citations/nguyen2021kip.txt)
* [Dataset Distillation with Infinitely Wide Convolutional Networks](https://arxiv.org/abs/2107.13034) (Timothy Nguyen et al., NeurIPS 2021) [:octocat:](https://github.com/google/neural-tangents) ⚠️ Archived [:book:](./citations/nguyen2021kipimprovedresults.txt)
* [Efficient Dataset Distillation using Random Feature Approximation](https://arxiv.org/abs/2210.12067) (Noel Loo et al., NeurIPS 2022) [:octocat:](https://github.com/yolky/RFAD) ⭐ 37 | 🐛 2 | 🌐 Python | 📅 2023-02-24 [:book:](./citations/loo2022efficient.txt)
* [Dataset Distillation with Convexified Implicit Gradients](https://arxiv.org/abs/2302.06755) (Noel Loo et al., ICML 2023) [:octocat:](https://github.com/yolky/RCIG) ⭐ 15 | 🐛 3 | 🌐 Python | 📅 2023-04-25 [:book:](./citations/loo2023dataset.txt)
* [Dataset Distillation using Neural Feature Regression](https://arxiv.org/abs/2206.00719) (Yongchao Zhou et al., NeurIPS 2022) [:globe\_with\_meridians:](https://sites.google.com/view/frepo) [:octocat:](https://github.com/yongchao97/FRePo) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-09-01 [:book:](./citations/zhou2022dataset.txt)
* [Provable and Efficient Dataset Distillation for Kernel Ridge Regression](https://openreview.net/forum?id=WI2VpcBdnd) (Yilan Chen et al., NeurIPS 2024) [:book:](./citations/chen2024krr.txt)

<a name="parametrization" />

### Distilled Dataset Parametrization

* [Dataset Condensation via Efficient Synthetic-Data Parameterization](https://arxiv.org/abs/2205.14959) (Jang-Hyun Kim et al., ICML 2022) [:octocat:](https://github.com/snu-mllab/efficient-dataset-condensation) ⭐ 115 | 🐛 0 | 🌐 Python | 📅 2023-10-18 [:book:](./citations/kim2022dataset.txt)
* [Dataset Distillation via Factorization](https://arxiv.org/abs/2210.16774) (Songhua Liu et al., NeurIPS 2022) [:octocat:](https://github.com/Huage001/DatasetFactorization) ⭐ 67 | 🐛 3 | 🌐 Python | 📅 2022-11-28 [:book:](./citations/liu2022dataset.txt)
* [FYI: Flip Your Images for Dataset Distillation](https://arxiv.org/abs/2407.08113) (Byunggwan Son et al., ECCV 2024) [:globe\_with\_meridians:](https://cvlab.yonsei.ac.kr/projects/FYI/) [:octocat:](https://github.com/cvlab-yonsei/FYI) ⭐ 60 | 🐛 0 | 🌐 Python | 📅 2024-12-23 [:book:](./citations/son2024fyi.txt)
* [Remember the Past: Distilling Datasets into Addressable Memories for Neural Networks](https://arxiv.org/abs/2206.02916) (Zhiwei Deng et al., NeurIPS 2022) [:octocat:](https://github.com/princetonvisualai/RememberThePast-DatasetDistillation) ⭐ 41 | 🐛 2 | 🌐 Python | 📅 2022-11-19 [:book:](./citations/deng2022remember.txt)
* [Frequency Domain-based Dataset Distillation](https://arxiv.org/abs/2311.08819) (Donghyeok Shin & Seungjae Shin et al., NeurIPS 2023) [:octocat:](https://github.com/sdh0818/FreD) ⭐ 31 | 🐛 1 | 🌐 Python | 📅 2024-05-07 [:book:](./citations/shin2023fred.txt)
* [PRANC: Pseudo RAndom Networks for Compacting Deep Models](https://arxiv.org/abs/2206.08464) (Parsa Nooralinejad et al., 2022) [:octocat:](https://github.com/UCDvision/PRANC) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2023-01-24 [:book:](./citations/nooralinejad2022pranc.txt)
* [Sparse Parameterization for Epitomic Dataset Distillation](https://openreview.net/forum?id=ZIfhYAE2xg) (Xing Wei & Anjia Cao et al., NeurIPS 2023) [:octocat:](https://github.com/MIV-XJTU/SPEED) ⭐ 20 | 🐛 3 | 🌐 Python | 📅 2024-06-28 [:book:](./citations/wei2023sparse.txt)
* [Distilling Dataset into Neural Field](https://arxiv.org/abs/2503.04835) (Donghyeok Shin et al., ICLR 2025) [:octocat:](https://github.com/aailab-kaist/DDiF) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2025-03-20 [:book:](./citations/shin2025ddif.txt)
* [On Divergence Measures for Bayesian Pseudocoresets](https://arxiv.org/abs/2210.06205) (Balhae Kim et al., NeurIPS 2022) [:octocat:](https://github.com/balhaekim/bpc-divergences) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2022-10-04 [:book:](./citations/kim2022divergence.txt)
* [Color-Oriented Redundancy Reduction in Dataset Distillation](https://arxiv.org/abs/2411.11329) (Bowen Yuan et al., NeurIPS 2024) [:octocat:](https://github.com/KeViNYuAn0314/AutoPalette) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2025-01-27 [:book:](./citations/yuan2024color.txt)
* [Beyond Pixels: Efficient Dataset Distillation via Sparse Gaussian Representation](https://arxiv.org/abs/2509.26219) (Chenyang Jiang et al., 2025) [:octocat:](https://github.com/j-cyoung/GSDatasetDistillation) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2026-03-18 [:book:](./citations/jiang2025gsdd.txt)
* [Dataset Distillation as Data Compression: A Rate-Utility Perspective](https://arxiv.org/abs/2507.17221) (Youneng Bao & Yiping Liu et al., ICCV 2025) [:globe\_with\_meridians:](https://nouise.github.io/DD-RUO/) [:octocat:](https://github.com/nouise/DD-RUO) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-06-28 [:book:](./citations/bao2025ruo.txt)
* [Dataset Condensation with Latent Space Knowledge Factorization and Sharing](https://arxiv.org/abs/2208.10494) (Hae Beom Lee & Dong Bok Lee et al., 2022) [:book:](./citations/lee2022kfs.txt)
* [Slimmable Dataset Condensation](https://openaccess.thecvf.com/content/CVPR2023/html/Liu_Slimmable_Dataset_Condensation_CVPR_2023_paper.html) (Songhua Liu et al., CVPR 2023) [:book:](./citations/liu2023slimmable.txt)
* [Few-Shot Dataset Distillation via Translative Pre-Training](https://openaccess.thecvf.com/content/ICCV2023/html/Liu_Few-Shot_Dataset_Distillation_via_Translative_Pre-Training_ICCV_2023_paper.html) (Songhua Liu et al., ICCV 2023) [:book:](./citations/liu2023fewshot.txt)
* [MGDD: A Meta Generator for Fast Dataset Distillation](https://openreview.net/forum?id=D9CMRR5Lof) (Songhua Liu et al., NeurIPS 2023) [:book:](./citations/liu2023mgdd.txt)
* [Leveraging Hierarchical Feature Sharing for Efficient Dataset Condensation](https://arxiv.org/abs/2310.07506) (Haizhong Zheng et al., ECCV 2024) [:book:](./citations/zheng2024hmn.txt)
* [Post Training Quantization for Efficient Dataset Condensation](https://arxiv.org/abs/2603.13346) (Linh-Tam Tran et al., AAAI 2026) [:book:](./citations/tran2026ptqdc.txt)

<a name="generative" />

### Generative Distillation

#### GAN

* [Generalizing Dataset Distillation via Deep Generative Prior](https://arxiv.org/abs/2305.01649) (George Cazenavette et al., CVPR 2023) [:globe\_with\_meridians:](https://georgecazenavette.github.io/glad/) [:octocat:](https://github.com/georgecazenavette/glad) ⭐ 114 | 🐛 8 | 🌐 Python | 📅 2023-05-22 [:book:](./citations/cazenavette2023glad.txt)
* [DiM: Distilling Dataset into Generative Model](https://arxiv.org/abs/2303.04707) (Kai Wang & Jianyang Gu et al., 2023) [:octocat:](https://github.com/vimar-gu/DiM) ⭐ 54 | 🐛 0 | 🌐 Python | 📅 2023-03-15 [:book:](./citations/wang2023dim.txt)
* [Synthesizing Informative Training Samples with GAN](https://arxiv.org/abs/2204.07513) (Bo Zhao et al., NeurIPS 2022 Workshop) [:octocat:](https://github.com/vico-uoe/it-gan) ⭐ 24 | 🐛 3 | 🌐 Python | 📅 2023-10-31 [:book:](./citations/zhao2022synthesizing.txt)
* [Hierarchical Features Matter: A Deep Exploration of GAN Priors for Improved Dataset Distillation](https://arxiv.org/abs/2406.05704) (Xinhao Zhong & Hao Fang et al., CVPR 2025) [:octocat:](https://github.com/ndhg1213/H-GLaD) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2025-02-28 [:book:](./citations/zhong2025hglad.txt)
* [Dataset Condensation via Generative Model](https://arxiv.org/abs/2309.07698) (Junhao Zhang et al., 2023) [:book:](./citations/zhang2023dc.txt)
* [Generative Dataset Distillation: Balancing Global Structure and Local Details](https://arxiv.org/abs/2404.17732) (Longzhen Li & Guang Li et al., CVPR 2024 Workshop) [:book:](./citations/li2024generative.txt)
* [Data-to-Model Distillation: Data-Efficient Learning Framework](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/6020_ECCV_2024_paper.php) (Ahmad Sajedi & Samir Khaki et al., ECCV 2024) [:book:](./citations/sajedi2024data.txt)
* [Generative Dataset Distillation Based on Self-knowledge Distillation](https://arxiv.org/abs/2501.04202) (Longzhen Li & Guang Li et al., ICASSP 2025) [:book:](./citations/li2025generative.txt)

#### Diffusion

* [Efficient Dataset Distillation via Minimax Diffusion](https://arxiv.org/abs/2311.15529) (Jianyang Gu et al., CVPR 2024) [:octocat:](https://github.com/vimar-gu/MinimaxDiffusion) ⭐ 105 | 🐛 8 | 🌐 Python | 📅 2024-03-22 [:book:](./citations/gu2024efficient.txt)
* [D4M: Dataset Distillation via Disentangled Diffusion Model](https://arxiv.org/abs/2407.15138) (Duo Su & Junjie Hou et al., CVPR 2024) [:globe\_with\_meridians:](https://junjie31.github.io/D4M/) [:octocat:](https://github.com/suduo94/D4M) ⭐ 42 | 🐛 6 | 🌐 Python | 📅 2024-09-06 [:book:](./citations/su2024d4m.txt)
* [MGD3: Mode-Guided Dataset Distillation using Diffusion Models](https://arxiv.org/abs/2505.18963) (Jeffrey A. Chan-Santiago et al., ICML 2025) [:globe\_with\_meridians:](https://jachansantiago.com/mode-guided-distillation/) [:octocat:](https://github.com/jachansantiago/mode_guidance/) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2025-12-06 [:book:](./citations/chan-santiago2025mgd3.txt)
* [Dataset Distillation via Vision-Language Category Prototype](https://arxiv.org/abs/2506.23580) (Yawen Zou & Guang Li et al., ICCV 2025) [:globe\_with\_meridians:](https://zou-yawen.github.io/DD_via_vision-language)  [:octocat:](https://github.com/zou-yawen/Dataset-Distillation-via-Vision-Language-Category-Prototype/) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2026-03-20 [:book:](./citations/zou2025vlcp.txt)
* [Taming Diffusion for Dataset Distillation with High Representativeness](https://arxiv.org/abs/2505.18399) (Lin Zhao et al., ICML 2025) [:octocat:](https://github.com/lin-zhao-resoLve/D3HR) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2025-08-24 [:book:](./citations/zhao2025d3hr.txt)
* [Influence-Guided Diffusion for Dataset Distillation](https://openreview.net/forum?id=0whx8MhysK) (Mingyang Chen et al., ICLR 2025) [:octocat:](https://github.com/mchen725/DD_IGD) ⭐ 15 | 🐛 4 | 🌐 Python | 📅 2025-02-12 [:book:](./citations/chen2025igd.txt)
* [Generative Dataset Distillation Based on Diffusion Model](https://arxiv.org/abs/2408.08610) (Duo Su & Junjie Hou & Guang Li et al., ECCV 2024 Workshop) [:octocat:](https://github.com/Guang000/Generative-Dataset-Distillation-Based-on-Diffusion-Model) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2024-10-11 [:book:](./citations/su2024diffusion.txt)
* [CaO2: Rectifying Inconsistencies in Diffusion-Based Dataset Distillation](https://arxiv.org/abs/2506.22637) (Haoxuan Wang et al., ICCV 2025) [:octocat:](https://github.com/hatchetProject/CaO2) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2026-01-15 [:book:](./citations/wang2025cao2.txt)
* [Unlocking Dataset Distillation with Diffusion Models](https://arxiv.org/abs/2403.03881) (Brian B. Moser & Federico Raue et al., NeurIPS 2025) [:octocat:](https://github.com/Brian-Moser/prune_and_distill) ⭐ 9 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-01-05 [:book:](./citations/moser2025ld3m.txt)
* [EVLF: Early Vision-Language Fusion for Generative Dataset Distillation](https://arxiv.org/abs/2603.07476) (Wenqi Cai et al., CVPR 2026) [:globe\_with\_meridians:](https://wenqi-cai297.github.io/earlyfusion-HP/) [:octocat:](https://github.com/wenqi-cai297/earlyfusion-for-dd/) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-03-23 [:book:](./citations/cai2026evlf.txt)
* [Geometry-Aware Dataset Condensation for Diffusion Model Training](https://arxiv.org/abs/2606.05883) (Xiao Cui et al., ICML 2026) [:octocat:](https://github.com/2018cx/GADC) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-06-08 [:book:](./citations/cui2026gadc.txt)
* [Dataset Condensation with Color Compensation](https://arxiv.org/abs/2508.01139) (Huyu Wu et al., TMLR 2025) [:globe\_with\_meridians:](https://528why.github.io/DC3-Page/) [:octocat:](https://github.com/528why/Dataset-Condensation-with-Color-Compensation) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2025-10-23 [:book:](./citations/wu2025dc3.txt)
* [CoDA: From Text-to-Image Diffusion Models to Training-Free Dataset Distillation](https://arxiv.org/abs/2512.03844) (Letian Zhou et al., ICLR 2026) [:octocat:](https://github.com/zzzlt422/CoDA) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-01-27 [:book:](./citations/zhou2026coda.txt)
* [ManifoldGD: Training-Free Hierarchical Manifold Guidance for Diffusion-Based Dataset Distillation](https://arxiv.org/abs/2602.23295) (Ayush Roy et al., CVPR 2026) [:octocat:](https://github.com/AyushRoy2001/ManifoldGD) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-06-27 [:book:](./citations/roy2026manifold.txt)
* [Task-Specific Generative Dataset Distillation with Difficulty-Guided Sampling](https://arxiv.org/abs/2507.03331) (Mingzhuo Li & Guang Li et al., ICCV 2025 Workshop) [:octocat:](https://github.com/SumomoTaku/DiffGuideSamp) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-09-09 [:book:](./citations/li2025diff.txt)
* [DIVER: Diving Deeper into Distilled Data via Expressive Semantic Recovery](https://arxiv.org/abs/2605.12649) (Qianxin Xia et al., ICML 2026) [:octocat:](https://github.com/einsteinxia/DIVER) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2026-08-05 [:book:](./citations/xia2026diver.txt)
* [Set-Coupled Guidance: Set-Level Coordination in Diffusion-Based Dataset Distillation](https://openreview.net/forum?id=onosLtwoiK) (Ziang Gan et al., ICML 2026) [:octocat:](https://github.com/tade1s/SCG) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-07-27 [:book:](./citations/gan2026scg.txt)
* [Enhancing Diffusion-based Dataset Distillation via Adversary-Guided Curriculum Sampling](https://arxiv.org/abs/2508.01264) (Lexiao Zou et al., ICME 2025) [:book:](./citations/zou2025acs.txt)
* [Optimizing Distributional Geometry Alignment with Optimal Transport for Generative Dataset Distillation](https://arxiv.org/abs/2512.00308) (Xiao Cui et al., NeurIPS 2025) [:book:](./citations/cui2025ot.txt)
* [Diffusion Models as Dataset Distillation Priors](https://arxiv.org/abs/2510.17421) (Duo Su et al., ICLR 2026) [:book:](./citations/su2026dap.txt)
* [IMS3: Breaking Distributional Aggregation in Diffusion-Based Dataset Distillation](https://arxiv.org/abs/2603.13960) (Chenru Wang & Yunyi Chen et al., CVPR 2026) [:book:](./citations/wang2026ims3.txt)
* [Learnability-Guided Diffusion for Dataset Distillation](https://arxiv.org/abs/2604.00519) (Jeffrey A. Chan-Santiago et al., CVPR 2026) [:globe\_with\_meridians:](https://jachansantiago.com/learnability-guided-distillation/) [:book:](./citations/chansantiago2026learnability.txt)
* [DMGD: Train-Free Dataset Distillation with Semantic-Distribution Matching in Diffusion Models](https://arxiv.org/abs/2605.03877) (Qichao Wang et al., CVPR 2026) [:book:](./citations/wang2026dmgd.txt)
* [Mitigating the Distribution Shift of Diffusion-based Dataset Distillation](https://openaccess.thecvf.com/content/CVPR2026/html/Xu_Mitigating_The_Distribution_Shift_of_Diffusion-based_Dataset_Distillation_CVPR_2026_paper.html) (Yue Xu et al., CVPR 2026) [:book:](./citations/xu2026distribution.txt)

#### VAR

* [HIERAMP: Coarse-to-Fine Autoregressive Amplification for Generative Dataset Distillation](https://arxiv.org/abs/2603.06932) (Lin Zhao & Xinru Jiang et al., CVPR 2026) [:octocat:](https://github.com/Oshikaka/HIERAMP) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-08-07 [:book:](./citations/zhao2026hieramp.txt)
* [ProtoVAR: Efficient Dataset Distillation via Prototype-Guided Visual Autoregressive Modeling](https://openreview.net/forum?id=5YvTHX0QS9) (Mingyu Wang et al., ICML 2026) [:book:](./citations/protovar2026.txt)

#### Flow

* [Path-Guided Flow Matching for Dataset Distillation](https://arxiv.org/abs/2602.05616) (Xuhui Li et al., 2026) [:book:](./citations/li2026flow.txt)

<a name="optimization" />

### Better Optimization

* [DREAM: Efficient Dataset Distillation by Representative Matching](https://arxiv.org/abs/2302.14416) (Yanqing Liu & Jianyang Gu & Kai Wang et al., ICCV 2023) [:octocat:](https://github.com/lyq312318224/DREAM) ⭐ 114 | 🐛 7 | 🌐 Python | 📅 2024-02-28 [:book:](./citations/liu2023dream.txt)
* [DREAM+: Efficient Dataset Distillation by Bidirectional Representative Matching](https://arxiv.org/abs/2310.15052) (Yanqing Liu & Jianyang Gu & Kai Wang et al., 2023) [:octocat:](https://github.com/lyq312318224/DREAM) ⭐ 114 | 🐛 7 | 🌐 Python | 📅 2024-02-28 [:book:](./citations/liu2023dream+.txt)
* [Distill Gold from Massive Ores: Bi-level Data Pruning towards Efficient Dataset Distillation](https://arxiv.org/abs/2305.18381) (Yue Xu et al., ECCV 2024) [:octocat:](https://github.com/silicx/GoldFromOres) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2024-07-06 [:book:](./citations/xu2024distill.txt)
* [You Only Condense Once: Two Rules for Pruning Condensed Datasets](https://arxiv.org/abs/2310.14019) (Yang He et al., NeurIPS 2023) [:octocat:](https://github.com/he-y/you-only-condense-once) ⭐ 17 | 🐛 2 | 🌐 Python | 📅 2026-07-30 [:book:](./citations/he2023yoco.txt)
* [Multisize Dataset Condensation](https://arxiv.org/abs/2403.06075) (Yang He et al., ICLR 2024) [:octocat:](https://github.com/he-y/Multisize-Dataset-Condensation) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2024-04-18 [:book:](./citations/he2024mdc.txt)
* [Can Pre-Trained Models Assist in Dataset Distillation?](https://arxiv.org/abs/2310.03295) (Yao Lu et al., 2023) [:octocat:](https://github.com/yaolu-zjut/DDInterpreter) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2024-05-28 [:book:](./citations/lu2023pre.txt)
* [Data Distillation Can Be Like Vodka: Distilling More Times For Better Quality](https://arxiv.org/abs/2310.06982) (Xuxi Chen & Yu Yang et al., ICLR 2024) [:octocat:](https://github.com/VITA-Group/ProgressiveDD) ⭐ 15 | 🐛 2 | 🌐 Python | 📅 2024-05-18 [:book:](./citations/chen2024vodka.txt)
* [Accelerating Dataset Distillation via Model Augmentation](https://arxiv.org/abs/2212.06152) (Lei Zhang & Jie Zhang et al., CVPR 2023) [:octocat:](https://github.com/ncsu-dk-lab/Acc-DD) ⭐ 14 | 🐛 3 | 🌐 Python | 📅 2023-04-21 [:book:](./citations/zhang2023accelerating.txt)
* [Embarassingly Simple Dataset Distillation](https://arxiv.org/abs/2311.07025) (Yunzhen Feng et al., ICLR 2024) [:octocat:](https://github.com/fengyzpku/Simple_Dataset_Distillation) ⭐ 14 | 🐛 3 | 🌐 Python | 📅 2024-04-21 [:book:](./citations/yunzhen2024embarassingly.txt)
* [Towards Model-Agnostic Dataset Condensation by Heterogeneous Models](https://arxiv.org/abs/2409.14538) (Jun-Yeong Moon et al., ECCV 2024) [:octocat:](https://github.com/khu-agi/hmdc) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2024-12-15 [:book:](./citations/moon2024hmdc.txt)
* [Curriculum Coarse-to-Fine Selection for High-IPC Dataset Distillation](https://arxiv.org/abs/2503.18872) (Yanda Chen & Gongwei Chen et al., CVPR 2025) [:octocat:](https://github.com/CYDaaa30/CCFS) ⭐ 9 | 🐛 2 | 🌐 Python | 📅 2025-03-27 [:book:](./citations/chen2025ccfs.txt)
* [BACON: Bayesian Optimal Condensation Framework for Dataset Distillation](https://arxiv.org/abs/2406.01112) (Zheng Zhou et al., 2024) [:octocat:](https://github.com/zhouzhengqd/BACON) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-05-14 [:book:](./citations/zhou2024bacon.txt)
* [Large Scale Dataset Distillation with Domain Shift](https://openreview.net/forum?id=0FWPKHMCSc) (Noel Loo & Alaa Maalouf et al., ICML 2024) [:octocat:](https://github.com/yolky/d3s_distillation) ⭐ 1 | 🐛 2 | 📅 2024-06-03 [:book:](./citations/loo2024d3s.txt)
* [Going Beyond Feature Similarity: Effective Dataset Distillation based on Class-aware Conditional Mutual Information](https://arxiv.org/abs/2412.09945) (Xinhao Zhong et al., ICLR 2025) [:octocat:](https://github.com/ndhg1213/CMIDD) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-02-21 [:book:](./citations/zhong2025cmi.txt)
* [Dataset Distillation by Influence Matching](https://arxiv.org/abs/2607.16859) (Haoru Tan & Wang Wang et al., CVPR 2026) [:octocat:](https://github.com/hrtan/infmatch) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-07-18 [:book:](./citations/tan2026infmatch.txt)
* [MIM4DD: Mutual Information Maximization for Dataset Distillation](https://arxiv.org/abs/2312.16627) (Yuzhang Shang et al., NeurIPS 2023) [:book:](./citations/shang2023mim4dd.txt)
* [Dataset Distillation in Latent Space](https://arxiv.org/abs/2311.15547) (Yuxuan Duan et al., 2023) [:book:](./citations/duan2023latent.txt)
* [Teddy: Efficient Large-Scale Dataset Distillation via Taylor-Approximated Matching](https://arxiv.org/abs/2410.07579) (Ruonan Yu et al., ECCV 2024) [:book:](./citations/yu2024teddy.txt)
* [Not All Samples Should Be Utilized Equally: Towards Understanding and Improving Dataset Distillation](https://arxiv.org/abs/2408.12483) (Shaobo Wang et al., CVPR 2025 Workshop) [:book:](./citations/wang2025samples.txt)
* [Beyond Random: Automatic Inner-loop Optimization in Dataset Distillation](https://arxiv.org/abs/2510.04838) (Muquan Li et al., NeurIPS 2025) [:book:](./citations/li2025bptt.txt)
* [Dataset Distillation as Pushforward Optimal Quantization](https://arxiv.org/abs/2501.07681) (Hongye Tan et al., ICLR 2026) [:book:](./citations/tan2026optimal.txt)

<a name="understanding" />

### Better Understanding

* [Optimizing Millions of Hyperparameters by Implicit Differentiation](https://arxiv.org/abs/1911.02590) (Jonathan Lorraine et al., AISTATS 2020) [:octocat:](https://github.com/MaximeVandegar/Papers-in-100-Lines-of-Code/tree/main/Optimizing_Millions_of_Hyperparameters_by_Implicit_Differentiation) ⭐ 2,859 | 🐛 0 | 🌐 Python | 📅 2026-08-17 [:book:](./citations/lorraine2020optimizing.txt)
* [Flowing Datasets with Wasserstein over Wasserstein Gradient Flows](https://arxiv.org/abs/2506.07534) (Clément Bonet & Christophe Vauthier et al., ICML 2025) [:octocat:](https://github.com/clbonet/Flowing_Datasets_with_WoW_Gradient_Flows) ⭐ 21 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-05-21 [:book:](./citations/bonet2025flowing.txt)
* [What is Dataset Distillation Learning?](https://arxiv.org/abs/2406.04284) (William Yang et al., ICML 2024) [:octocat:](https://github.com/princetonvisualai/What-is-Dataset-Distillation-Learning) ⭐ 18 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-06-14 [:book:](./citations/yang2024learning.txt)
* [On Implicit Bias in Overparameterized Bilevel Optimization](https://proceedings.mlr.press/v162/vicol22a.html) (Paul Vicol et al., ICML 2022) [:book:](./citations/vicol2022implicit.txt)
* [On the Size and Approximation Error of Distilled Sets](https://arxiv.org/abs/2305.14113) (Alaa Maalouf & Murad Tukan et al., NeurIPS 2023) [:book:](./citations/maalouf2023size.txt)
* [A Theoretical Study of Dataset Distillation](https://openreview.net/forum?id=dq5QGXGxoJ) (Zachary Izzo et al., NeurIPS 2023 Workshop) [:book:](./citations/izzo2023theo.txt)
* [Mitigating Bias in Dataset Distillation](https://arxiv.org/abs/2406.06609) (Justin Cui et al., ICML 2024) [:book:](./citations/cui2024bias.txt)
* [Dataset Distillation from First Principles: Integrating Core Information Extraction and Purposeful Learning](https://arxiv.org/abs/2409.01410) (Vyacheslav Kungurtsev et al., 2024) [:book:](./citations/kungurtsev2024first.txt)
* [Information-Guided Diffusion Sampling for Dataset Distillation](https://arxiv.org/abs/2507.04619) (Linfeng Ye et al., NeurIPS 2025 Workshop) [:book:](./citations/ye2025igds.txt)
* [A Discrepancy-Based Perspective on Dataset Condensation](https://arxiv.org/abs/2509.10367) (Tong Chen et al., 2025) [:book:](./citations/chen2025discrepancy.txt)
* [Understanding Dataset Distillation via Spectral Filtering](https://arxiv.org/abs/2503.01212) (Deyu Bo et al., ICLR 2026) [:book:](./citations/bo2026unidd.txt)
* [Dataset Distillation for Memorized Data: Soft Labels can Leak Held-Out Teacher Knowledge](https://arxiv.org/abs/2506.14457) (Freya Behrens et al., ICLR 2026) [:book:](./citations/behrens2026soft.txt)
* [Rethinking Dataset Distillation: Hard Truths about Soft Labels](https://arxiv.org/abs/2604.18811) (Priyam Dey & Aditya Sahdev et al., CVPR 2026) [:book:](./citations/dey2026hardtruths.txt)
* [Dataset Distillation Efficiently Encodes Low-Dimensional Representations from Gradient-Based Learning of Non-Linear Tasks](https://arxiv.org/abs/2603.14830) (Yuri Kinoshita et al., ICML 2026) [:book:](./citations/kinoshita2026lowdim.txt)
* [Utility Boundary of Dataset Distillation: Scaling and Configuration-Coverage Laws](https://openreview.net/forum?id=wbXPNPw5jW) (Zhengquan Luo et al., ICML 2026) [:book:](./citations/luo2026utility.txt)
* [Structural Assessment for Understanding and Guiding Dataset Distillation in Discrete Token Space](https://arxiv.org/abs/2606.21705) (Yue Cao et al., ECCV 2026) [:book:](./citations/cao2026structural.txt)
* [Rethinking Dataset Distillation for Classification: Do Distilled Sets Outperform Coresets?](https://arxiv.org/abs/2606.18209) (Trisha Mittal & Akshay Mehra et al., 2026) [:book:](./citations/mittal2026rethinking.txt)

<a name="label" />

### Label Distillation

* [Soft-Label Dataset Distillation and Text Dataset Distillation](https://arxiv.org/abs/1910.02551) (Ilia Sucholutsky et al., IJCNN 2021) [:octocat:](https://github.com/ilia10000/dataset-distillation) ⭐ 74 | 🐛 6 | 🌐 Python | 📅 2022-11-17 [:book:](./citations/sucholutsky2021soft.txt)
* [Flexible Dataset Distillation: Learn Labels Instead of Images](https://arxiv.org/abs/2006.08572) (Ondrej Bohdal et al., NeurIPS 2020 Workshop) [:octocat:](https://github.com/ondrejbohdal/label-distillation) ⭐ 41 | 🐛 0 | 🌐 Python | 📅 2020-10-21 [:book:](./citations/bohdal2020flexible.txt)
* [A Label is Worth a Thousand Images in Dataset Distillation](https://arxiv.org/abs/2406.10485) (Tian Qin et al., NeurIPS 2024) [:octocat:](https://github.com/sunnytqin/no-distillation) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2025-02-24 [:book:](./citations/qin2024label.txt)
* [Are Large-scale Soft Labels Necessary for Large-scale Dataset Distillation?](https://arxiv.org/abs/2410.15919) (Lingao Xiao et al., NeurIPS 2024) [:octocat:](https://github.com/he-y/soft-label-pruning-for-dataset-distillation) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2024-11-13 [:book:](./citations/xiao2024soft.txt)
* [GIFT: Unlocking Full Potential of Labels in Distilled Dataset at Near-zero Cost](https://arxiv.org/abs/2405.14736) (Xinyi Shang & Peng Sun et al., ICLR 2025) [:octocat:](https://github.com/LINs-lab/GIFT) ⭐ 10 | 🐛 2 | 🌐 Python | 📅 2025-12-26 [:book:](./citations/shang2025gift.txt)
* [Soft Label Pruning and Quantization for Large-Scale Dataset Distillation](https://arxiv.org/abs/2604.18135) (Lingao Xiao et al., TPAMI 2026) [:octocat:](https://github.com/he-y/soft-label-pruning-quantization-for-dataset-distillation) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2026-04-18 [:book:](./citations/lingao2026lpqld.txt)
* [DRUPI: Dataset Reduction Using Privileged Information](https://arxiv.org/abs/2410.01611) (Shaobo Wang et al., 2024) [:book:](./citations/wang2024drupi.txt)
* [Label-Augmented Dataset Distillation](https://arxiv.org/abs/2409.16239) (Seoungyoon Kang & Youngsun Lim et al., WACV 2025) [:book:](./citations/kang2024label.txt)
* [Heavy Labels Out! Dataset Distillation with Label Space Lightening](https://arxiv.org/abs/2408.08201) (Ruonan Yu et al., ICCV 2025) [:book:](./citations/yu2025helio.txt)

<a name="quant" />

### Dataset Quantization

* [Dataset Quantization](https://arxiv.org/abs/2308.10524) (Daquan Zhou & Kai Wang & Jianyang Gu et al., ICCV 2023) [:octocat:](https://github.com/magic-research/Dataset_Quantization) ⚠️ Archived [:book:](./citations/zhou2023dataset.txt)
* [Dataset Quantization with Active Learning based Adaptive Sampling](https://arxiv.org/abs/2407.07268) (Zhenghao Zhao et al., ECCV 2024) [:octocat:](https://github.com/ichbill/DQAS) ⭐ 9 | 🐛 3 | 📅 2024-07-09 [:book:](./citations/zhao2024dqas.txt)
* [Adaptive Dataset Quantization](https://www.arxiv.org/abs/2412.16895) (Muquan Li et al., AAAI 2025) [:book:](./citations/li2025adq.txt)
* [Dataset Color Quantization: A Training-Oriented Framework for Dataset-Level Compression](https://arxiv.org/abs/2602.20650) (Chenyue Yu et al., ICLR 2026) [:book:](./citations/yu2026dcq.txt)

<a name="decouple" />

### Decoupled Distillation

* [Squeeze, Recover and Relabel: Dataset Condensation at ImageNet Scale From A New Perspective](https://arxiv.org/abs/2306.13092) (Zeyuan Yin & Zhiqiang Shen et al., NeurIPS 2023) [:globe\_with\_meridians:](https://zeyuanyin.github.io/projects/SRe2L/) [:octocat:](https://github.com/VILA-Lab/SRe2L/tree/main/SRe2L) ⭐ 141 | 🐛 1 | 🌐 Python | 📅 2024-11-15 [:book:](./citations/yin2023sre2l.txt)
* [Dataset Distillation via Curriculum Data Synthesis in Large Data Era](https://arxiv.org/abs/2311.18838) (Zeyuan Yin et al., TMLR 2024) [:octocat:](https://github.com/VILA-Lab/SRe2L/tree/main/CDA) ⭐ 141 | 🐛 1 | 🌐 Python | 📅 2024-11-15 [:book:](./citations/yin2024cda.txt)
* [On the Diversity and Realism of Distilled Dataset: An Efficient Dataset Distillation Paradigm](https://arxiv.org/abs/2312.03526) (Peng Sun et al., CVPR 2024) [:octocat:](https://github.com/LINs-lab/RDED) ⭐ 85 | 🐛 5 | 🌐 Python | 📅 2025-02-24 [:book:](./citations/sun2024rded.txt)
* [DELT: A Simple Diversity-driven EarlyLate Training for Dataset Distillation](https://arxiv.org/abs/2411.19946) (Zhiqiang Shen & Ammar Sherif et al., CVPR 2025) [:octocat:](https://github.com/VILA-Lab/DELT) ⭐ 28 | 🐛 1 | 🌐 Python | 📅 2025-08-23 [:book:](./citations/shen2025delt.txt)
* [Generalized Large-Scale Data Condensation via Various Backbone and Statistical Matching](https://arxiv.org/abs/2311.17950) (Shitong Shao et al., CVPR 2024) [:octocat:](https://github.com/shaoshitong/G_VBSM_Dataset_Condensation) ⭐ 27 | 🐛 1 | 🌐 Python | 📅 2024-10-09 [:book:](./citations/shao2024gvbsm.txt)
* [Elucidating the Design Space of Dataset Condensation](https://arxiv.org/abs/2404.13733) (Shitong Shao et al., NeurIPS 2024) [:octocat:](https://github.com/shaoshitong/EDC) ⭐ 20 | 🐛 4 | 🌐 Python | 📅 2024-10-05 [:book:](./citations/shao2024edc.txt)
* [Dataset Distillation via Committee Voting](https://arxiv.org/abs/2501.07575) (Jiacheng Cui et al., 2025) [:octocat:](https://github.com/Jiacheng8/CV-DD) ⭐ 16 | 🐛 1 | 🌐 Shell | 📅 2025-07-28 [:book:](./citations/cui2025cvdd.txt)
* [FADRM: Fast and Accurate Data Residual Matching for Dataset Distillation](https://arxiv.org/abs/2506.24125) (Jiacheng Cui & Xinyue Bi et al., NeurIPS 2025) [:octocat:](https://github.com/Jiacheng8/FADRM) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-03-22 [:book:](./citations/cui2025fadrm.txt)
* [Diversity-Driven Synthesis: Enhancing Dataset Distillation through Directed Weight Adjustment](https://arxiv.org/abs/2409.17612) (Jiawei Du et al., NeurIPS 2024) [:octocat:](https://github.com/AngusDujw/Diversity-Driven-Synthesis) ⭐ 8 | 🐛 2 | 🌐 Python | 📅 2025-03-01 [:book:](./citations/du2024diversity.txt)
* [Breaking Class Barriers: Efficient Dataset Distillation via Inter-Class Feature Compensator](https://arxiv.org/abs/2408.06927) (Xin Zhang et al., ICLR 2025) [:octocat:](https://github.com/zhangxin-xd/UFC) ⭐ 8 | 🐛 2 | 🌐 Python | 📅 2025-04-06 [:book:](./citations/zhang2025infer.txt)
* [Curriculum Dataset Distillation](https://arxiv.org/abs/2405.09150) (Zhiheng Ma & Anjia Cao et al., TIP 2025) [:octocat:](https://github.com/MIV-XJTU/CUDD) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2025-07-08 [:book:](./citations/ma2025cudd.txt)
* [Balanced Dataset Distillation via Modeling Multiple Visual Pattern Distribution](https://openaccess.thecvf.com/content/CVPR2026/html/Shi_Balanced_Dataset_Distillation_via_Modeling_Multiple_Visual_Pattern_Distribution_CVPR_2026_paper.html) (Guanghui Shi et al., CVPR 2026) [:octocat:](https://github.com/BeCarefulOfYournaoke/BPS) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-06-05 [:book:](./citations/shi2026bps.txt)
* [Condensing Large-Scale Datasets Directly with Minimal Information Loss](https://arxiv.org/abs/2607.00916) (Xinyi Shang & Peng Sun & Bei Shi et al., ECCV 2026) [:octocat:](https://github.com/LINs-lab/CIM) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2026-06-29 [:book:](./citations/shang2026cim.txt)
  [Hard Labels In! Rethinking the Role of Hard Labels in Mitigating Local Semantic Drift](https://arxiv.org/abs/2512.15647) (Jiacheng Cui et al., ICML 2026) [:octocat:](https://github.com/Jiacheng8/HALD) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-05-01 [:book:](./citations/cui2026hard.txt)
* [PRISM: Diversifying Dataset Distillation by Decoupling Architectural Priors](https://arxiv.org/abs/2511.09905) (Brian B. Moser et al., TMLR 2026) [:octocat:](https://github.com/Brian-Moser/prism) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-01-05 [:book:](./citations/moser2026prism.txt)
* [DiRe: Diversity-promoting Regularization for Dataset Condensation](https://arxiv.org/abs/2512.13083) (Saumyaranjan Mohanty et al., WACV 2026) [:octocat:](https://github.com/DIL-IITH/DiRe) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-12-09 [:book:](./citations/mohanty2026dire.txt)
* [Enhancing Dataset Distillation via Non-Critical Region Refinement](https://arxiv.org/abs/2503.18267) (Minh-Tuan Tran et al., CVPR 2025) [:octocat:](https://github.com/tmtuan1307/NRR-DD) ⭐ 0 | 🐛 3 | 📅 2025-03-24 [:book:](./citations/tran2025nrrdd.txt)
* [Information Compensation: A Fix for Any-scale Dataset Distillation](https://openreview.net/forum?id=2SnmKd1JK4) (Peng Sun et al., ICLR 2024 Workshop) [:book:](./citations/sun2024lic.txt)
* [FocusDD: Real-World Scene Infusion for Robust Dataset Distillation](https://arxiv.org/abs/2501.06405) (Youbin Hu et al., 2025) [:book:](./citations/hu2025focusdd.txt)
* [Grounding and Enhancing Informativeness and Utility in Dataset Distillation](https://arxiv.org/abs/2601.21296) (Shaobo Wang et al., ICLR 2026) [:book:](./citations/wang2026infoutil.txt)
* [Fixed Anchors Are Not Enough: Dynamic Retrieval and Persistent Homology for Dataset Distillation](https://arxiv.org/abs/2602.24144) (Muquan Li et al., CVPR 2026) [:book:](./citations/li2026reta.txt)
* [Beyond Soft Label: Dataset Distillation via Orthogonal Gradient Matching](https://openaccess.thecvf.com/content/CVPR2026/html/Bo_Beyond_Soft_Label_Dataset_Distillation_via_Orthogonal_Gradient_Matching_CVPR_2026_paper.html) (Deyu Bo et al., CVPR 2026) [:book:](./citations/bo2026ogm.txt)

<a name="multi" />

### Multimodal Distillation

* [Vision-Language Dataset Distillation](https://arxiv.org/abs/2308.07545) (Xindi Wu et al., TMLR 2024) [:globe\_with\_meridians:](https://princetonvisualai.github.io/multimodal_dataset_distillation/) [:octocat:](https://github.com/princetonvisualai/multimodal_dataset_distillation) ⭐ 65 | 🐛 6 | 🌐 Python | 📅 2024-12-30 [:book:](./citations/wu2024multi.txt)
* [Low-Rank Similarity Mining for Multimodal Dataset Distillation](https://arxiv.org/abs/2406.03793) (Yue Xu et al., ICML 2024) [:octocat:](https://github.com/silicx/LoRS_Distill) ⭐ 44 | 🐛 1 | 🌐 Python | 📅 2024-10-11 [:book:](./citations/xu2024lors.txt)
* [Efficient Multimodal Dataset Distillation via Generative Models](https://arxiv.org/abs/2509.15472) (Zhenghao Zhao et al., NeurIPS 2025) [:octocat:](https://github.com/ichbill/EDGE) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2025-12-17 [:book:](./citations/zhao2025edge.txt)
* [Audio-Visual Dataset Distillation](https://openreview.net/forum?id=IJlbuSrXmk) (Saksham Singh Kushwaha et al., TMLR 2024) [:octocat:](https://github.com/sakshamsingh1/AVDD) ⭐ 8 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2025-04-14 [:book:](./citations/kush2024avdd.txt)
* [Multimodal Dataset Distillation Made Simple by Prototype-Guided Data Synthesis](https://arxiv.org/abs/2602.19756) (Junhyeok Choi et al., ICLR 2026) [:octocat:](https://github.com/junhyeok9712/PDS) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2026-02-12 [:book:](./citations/choi2026multi.txt)
* [CovMatch: Cross-Covariance Guided Multimodal Dataset Distillation with Trainable Text Encoder](https://arxiv.org/abs/2510.18583) (Yongmin Lee et al., NeurIPS 2025) [:octocat:](https://github.com/Yongalls/CovMatch) ⭐ 6 | 🐛 2 | 🌐 Python | 📅 2025-10-21 [:book:](./citations/lee2025covmatch.txt)
* [Multimodal Dataset Distillation via Phased Teacher Models](https://arxiv.org/abs/2603.25388) (Shengbin Guo & Hang Zhao et al., ICLR 2026) [:octocat:](https://github.com/Previsior/PTM-ST) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2026-04-01 [:book:](./citations/guo2026ptmst.txt)
* [Multimodal Distribution Matching for Vision-Language Dataset Distillation](https://arxiv.org/abs/2605.23482) (Jongoh Jeong & Hoyong Kwon & Minseok Kim et al., CVPR 2026) [:octocat:](https://github.com/andyj1/mdm) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-08-15 [:book:](./citations/jeong2026mdm.txt)
* [Efficient Multi-modal Dataset Distillation via Analytic Parameter Matching](https://openreview.net/forum?id=Yh4dMR5mJ0) (Deyu Bo et al., ICML 2026) [:octocat:](https://github.com/bdy9527/MMDD) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2025-12-09 [:book:](./citations/bo2026apm.txt)
* [Rank-Aware Hyperbolic Alignment for Vision-Language Dataset Distillation](https://arxiv.org/abs/2606.29464) (Jongoh Jeong et al., ECCV 2026) [:globe\_with\_meridians:](https://andyj1.github.io/raha/) [:octocat:](https://github.com/andyj1/raha) ⭐ 0 | 🐛 0 | 📅 2026-08-09 [:book:](./citations/jeong2026raha.txt)
* [Beyond Modality Collapse: Representations Blending for Multimodal Dataset Distillation](https://arxiv.org/abs/2505.14705) (Xin Zhang et al., NeurIPS 2025) [:book:](./citations/zhang2025mdd.txt)
* [Decoupled Audio-Visual Dataset Distillation](https://arxiv.org/abs/2511.17890) (Wenyuan Li & Guang Li et al., 2025) [:book:](./citations/li2025davdd.txt)
* [ImageBindDC: Compressing Multi-modal Data with ImageBind-based Condensation](https://arxiv.org/abs/2511.08263) (Yue Min & Shaobo Wang et al., AAAI 2026) [:book:](./citations/min2026imagebinddc.txt)
* [Asynchronous Matching with Dynamic Sampling for Multimodal Dataset Distillation](https://openreview.net/forum?id=7SgSMKM2KF) (Ding Qi et al., ICLR 2026) [:book:](./citations/qi2026amd.txt)

<a name="self" />

### Self-Supervised Distillation

* [Self-supervised Dataset Distillation: A Good Compression Is All You Need](https://arxiv.org/abs/2404.07976) (Muxin Zhou et al., 2024) [:octocat:](https://github.com/VILA-Lab/SRe2L/tree/main/SCDD/) ⭐ 141 | 🐛 1 | 🌐 Python | 📅 2024-11-15 [:book:](./citations/zhou2024self.txt)
* [Dataset Distillation for Pre-Trained Self-Supervised Vision Models](https://arxiv.org/abs/2511.16674) (George Cazenavette et al., NeurIPS 2025) [:globe\_with\_meridians:](https://linear-gradient-matching.github.io/) [:octocat:](https://github.com/GeorgeCazenavette/linear-gradient-matching) ⭐ 53 | 🐛 0 | 🌐 Python | 📅 2026-03-31 [:book:](./citations/cazenavette2025dataset.txt)
* [Self-Supervised Dataset Distillation for Transfer Learning](https://arxiv.org/abs/2310.06511) (Dong Bok Lee & Seanie Lee et al., ICLR 2024) [:octocat:](https://github.com/db-Lee/selfsup_dd) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2024-04-10 [:book:](./citations/lee2024self.txt)
* [Efficiency for Free: Ideal Data Are Transportable Representations](https://arxiv.org/abs/2405.14669) (Peng Sun et al., NeurIPS 2024) [:octocat:](https://github.com/LINs-lab/ReLA) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2025-01-19 [:book:](./citations/sun2024rela.txt)
* [Dataset Distillation via Knowledge Distillation: Towards Efficient Self-Supervised Pre-Training of Deep Networks](https://arxiv.org/abs/2410.02116) (Siddharth Joshi et al., ICLR 2025) [:octocat:](https://github.com/jiayini1119/MKDT) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-01-25 [:book:](./citations/joshi2025kd.txt)
* [Boost Self-Supervised Dataset Distillation via Parameterization, Predefined Augmentation, and Approximation](https://arxiv.org/abs/2507.21455) (Sheng-Feng Yu et al., ICLR 2025) [:book:](./citations/yu2025self.txt)
* [Closed-Form Linear-Probe Dataset Distillation for Pre-trained Vision Models](https://arxiv.org/abs/2605.07194) (Bincheng Peng & Guang Li et al., 2026) [:book:](./citations/peng2026clpdd.txt)

<a name="benchmark" />

### Benchmark

* [DC-BENCH: Dataset Condensation Benchmark](https://arxiv.org/abs/2207.09639) (Justin Cui et al., NeurIPS 2022) [:globe\_with\_meridians:](https://dc-bench.github.io/) [:octocat:](https://github.com/justincui03/dc_benchmark) ⭐ 91 | 🐛 7 | 🌐 Python | 📅 2023-01-22 [:book:](./citations/cui2022dc.txt)
* [DD-Ranking: Rethinking the Evaluation of Dataset Distillation](https://arxiv.org/abs/2505.13300) (Zekai Li & Xinhao Zhong et al., 2025) [:globe\_with\_meridians:](https://nus-hpc-ai-lab.github.io/DD-Ranking/) [:octocat:](https://github.com/NUS-HPC-AI-Lab/DD-Ranking) ⭐ 73 | 🐛 0 | 🌐 HTML | 📅 2025-06-13 [:book:](./citations/li2025ranking.txt)
* [DD-RobustBench: An Adversarial Robustness Benchmark for Dataset Distillation](https://arxiv.org/abs/2403.13322) (Yifan Wu et al., TIP 2025) [:octocat:](https://github.com/FredWU-HUST/DD-RobustBench) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2025-12-28 [:book:](./citations/wu2025robust.txt)
* [BEARD: Benchmarking the Adversarial Robustness for Dataset Distillation](https://arxiv.org/abs/2411.09265) (Zheng Zhou et al., 2024) [:globe\_with\_meridians:](https://beard-leaderboard.github.io/) [:octocat:](https://github.com/zhouzhengqd/BEARD/) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-02-11 [:book:](./citations/zhou2024beard.txt)
* [A Comprehensive Study on Dataset Distillation: Performance, Privacy, Robustness and Fairness](https://arxiv.org/abs/2305.03355) (Zongxiong Chen & Jiahui Geng et al., 2023) [:book:](./citations/chen2023study.txt)
* [Rectified Decoupled Dataset Distillation: A Closer Look for Fair and Comprehensive Evaluation](https://arxiv.org/abs/2509.19743) (Xinhao Zhong et al., ICLR 2026) [:book:](./citations/zhong2026rd3.txt)

<a name="survey" />

### Survey

* [A Survey on Dataset Distillation: Approaches, Applications and Future Directions](https://arxiv.org/abs/2305.01975) (Jiahui Geng & Zongxiong Chen et al., IJCAI 2023) [:octocat:](https://github.com/Guang000/Awesome-Dataset-Distillation) ⭐ 1,967 | 🐛 1 | 🌐 HTML | 📅 2026-08-15 [:book:](./citations/geng2023survey.txt)
* [A Comprehensive Survey to Dataset Distillation](https://arxiv.org/abs/2301.05603) (Shiye Lei et al., TPAMI 2023) [:octocat:](https://github.com/Guang000/Awesome-Dataset-Distillation) ⭐ 1,967 | 🐛 1 | 🌐 HTML | 📅 2026-08-15 [:book:](./citations/lei2023survey.txt)
* [Dataset Distillation: A Comprehensive Review](https://arxiv.org/abs/2301.07014) (Ruonan Yu & Songhua Liu et al., TPAMI 2023) [:octocat:](https://github.com/Guang000/Awesome-Dataset-Distillation) ⭐ 1,967 | 🐛 1 | 🌐 HTML | 📅 2026-08-15 [:book:](./citations/yu2023review.txt)
* [Data Distillation: A Survey](https://arxiv.org/abs/2301.04272) (Noveen Sachdeva et al., TMLR 2023) [:book:](./citations/sachdeva2023survey.txt)
* [The Evolution of Dataset Distillation: Toward Scalable and Generalizable Solutions](https://arxiv.org/abs/2502.05673) (Ping Liu et al., 2025) [:book:](./citations/liu2025survey.txt)

<a name="thesis" />

### Ph.D. Thesis

* [Data-efficient Neural Network Training with Dataset Condensation](https://era.ed.ac.uk/handle/1842/39756) (Bo Zhao, The University of Edinburgh 2023) [:book:](./citations/zhao2023thesis.txt)

<a name="workshop" />

### Workshop

* 1st CVPR Workshop on Dataset Distillation (Saeed Vahidian et al., CVPR 2024) [:globe\_with\_meridians:](https://sites.google.com/view/dd-cvpr2024/home)

<a name="challenge" />

### Challenge

* The First Dataset Distillation Challenge (Kai Wang & Ahmad Sajedi et al., ECCV 2024) [:globe\_with\_meridians:](https://www.dd-challenge.com/) [:octocat:](https://github.com/DataDistillation/ECCV2024-Dataset-Distillation-Challenge) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2024-07-16

## Applications

<a name="continual" />

### Continual Learning

* [Summarizing Stream Data for Memory-Restricted Online Continual Learning](https://arxiv.org/abs/2305.16645) (Jianyang Gu et al., AAAI 2024) [:octocat:](https://github.com/vimar-gu/SSD) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2024-04-30 [:book:](./citations/gu2024ssd.txt)
* [Distilled Replay: Overcoming Forgetting through Synthetic Samples](https://arxiv.org/abs/2103.15851) (Andrea Rosasco et al., IJCAI 2021 Workshop) [:octocat:](https://github.com/andrearosasco/DistilledReplay) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2021-04-01 [:book:](./citations/rosasco2021distilled.txt)
* [An Efficient Dataset Condensation Plugin and Its Application to Continual Learning](https://openreview.net/forum?id=Murj6wcjRw) (Enneng Yang et al., NeurIPS 2023) [:octocat:](https://github.com/EnnengYang/An-Efficient-Dataset-Condensation-Plugin) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2023-11-29 [:book:](./citations/yang2023efficient.txt)
* [Condensed Composite Memory Continual Learning](https://arxiv.org/abs/2102.09890) (Felix Wiewel et al., IJCNN 2021) [:octocat:](https://github.com/FelixWiewel/CCMCL) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2021-09-29 [:book:](./citations/wiewel2021soft.txt)
* [Sample Condensation in Online Continual Learning](https://arxiv.org/abs/2206.11849) (Mattia Sangermano et al., IJCNN 2022) [:octocat:](https://github.com/MattiaSangermano/OLCGM) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2022-06-22 [:book:](./citations/sangermano2022sample.txt)
* [Asymmetric Synthetic Data Update for Domain Incremental Dataset Distillation](https://openreview.net/forum?id=XcsaCHaoJh) (Minyoung Oh et al., ICLR 2026) [:octocat:](https://github.com/myoh97/DIDD-ASU) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-03-27 [:book:](./citations/oh2026asu.txt)
* [Reducing Catastrophic Forgetting with Learning on Synthetic Data](https://arxiv.org/abs/2004.14046) (Wojciech Masarczyk et al., CVPR 2020 Workshop) [:book:](./citations/masarczyk2020reducing.txt)
* [CD2: Constrained Dataset Distillation for Few-Shot Class-Incremental Learning](https://arxiv.org/abs/2601.08519) (Kexin Bao et al., IJCAI 2025) [:book:](./citations/bao2025cd2.txt)

<a name="privacy" />

### Privacy

* [Backdoor Attacks Against Dataset Distillation](https://arxiv.org/abs/2301.01197) (Yugeng Liu et al., NDSS 2023) [:octocat:](https://github.com/liuyugeng/baadd) ⭐ 37 | 🐛 4 | 🌐 Python | 📅 2023-04-19 [:book:](./citations/liu2023backdoor.txt)
* [Private Set Generation with Discriminative Information](https://arxiv.org/abs/2211.04446) (Dingfan Chen et al., NeurIPS 2022) [:octocat:](https://github.com/DingfanChen/Private-Set) ⭐ 18 | 🐛 3 | 🌐 Python | 📅 2023-08-14 [:book:](./citations/chen2022privacy.txt)
* [Differentially Private Kernel Inducing Points (DP-KIP) for Privacy-preserving Data Distillation](https://arxiv.org/abs/2301.13389) (Margarita Vinaroz et al., 2023) [:octocat:](https://github.com/dpclip/dpclip) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2023-05-24 [:book:](./citations/vinaroz2023dpkip.txt)
* [Improving Noise Efficiency in Privacy-preserving Dataset Distillation](https://arxiv.org/abs/2508.01749) (Runkai Zheng et al., ICCV 2025) [:octocat:](https://github.com/humansensinglab/Dosser) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-07-31 [:book:](./citations/zheng2025dosser.txt)
* [Privacy for Free: How does Dataset Condensation Help Privacy?](https://arxiv.org/abs/2206.00240) (Tian Dong et al., ICML 2022) [:book:](./citations/dong2022privacy.txt)
* [No Free Lunch in "Privacy for Free: How does Dataset Condensation Help Privacy"](https://arxiv.org/abs/2209.14987) (Nicholas Carlini et al., 2022) [:book:](./citations/carlini2022no.txt)
* [Understanding Reconstruction Attacks with the Neural Tangent Kernel and Dataset Distillation](https://arxiv.org/abs/2302.01428) (Noel Loo et al., ICLR 2024) [:book:](./citations/loo2024attack.txt)
* [Rethinking Backdoor Attacks on Dataset Distillation: A Kernel Method Perspective](https://arxiv.org/abs/2311.16646) (Ming-Yu Chung et al., ICLR 2024) [:book:](./citations/chung2024backdoor.txt)
* [Differentially Private Dataset Condensation](https://www.ndss-symposium.org/ndss-paper/auto-draft-542/) (Zheng et al., NDSS 2024 Workshop) [:book:](./citations/zheng2024differentially.txt)
* [Adaptive Backdoor Attacks Against Dataset Distillation for Federated Learning](https://ieeexplore.ieee.org/abstract/document/10622462?casa_token=tHyZ-Pz7DpUAAAAA:vmCYI4cUcKzMluUsASHhIhr0CvBkjzBR-0N7REVj7aFN5hT5TinQTpSEsE0Bo3Fl8auh52Fipm_v) (Ze Chai et al., ICC 2024) [:book:](./citations/chai2024backdoor.txt)
* [SNEAKDOOR: Stealthy Backdoor Attacks against Distribution Matching-based Dataset Condensation](https://arxiv.org/abs/2603.28824) (He Yang & Dongyi Lv et al., NeurIPS 2025) [:book:](./citations/yang2025sneakdoor.txt)
* [Poisoned Distillation: Injecting Backdoors into Distilled Datasets Without Raw Data Access](https://arxiv.org/abs/2502.04229) (Ziyuan Yang et al., AAAI 2026) [:book:](./citations/yang2026pd.txt)
* [DP-GENG: Differentially Private Dataset Distillation Guided by DP-Generated Data](https://arxiv.org/abs/2511.09876) (Shuo Shi et al., AAAI 2026) [:book:](./citations/shi2026dpgeng.txt)
* [Attention Hijacking: Backdooring Text Dataset Distillation via Semantic Anchors](https://openreview.net/forum?id=g4BWfkULIo) (Hang Ren et al., ICML 2026) [:book:](./citations/ren2026attention.txt)

<a name="medical" />

### Medical

* [Multi-modal Vision Pre-training for Medical Image Analysis](https://arxiv.org/abs/2410.10604) (Shaohao Rui & Lingzhi Chen et al., CVPR 2025) [:octocat:](https://github.com/openmedlab/BrainMVP) ⭐ 87 | 🐛 1 | 🌐 Python | 📅 2025-06-18 [:book:](./citations/rui2025brain.txt)
* [FedWSIDD: Federated Whole Slide Image Classification via Dataset Distillation](https://arxiv.org/abs/2506.15365) (Haolong Jin et al., MICCAI 2025) [:octocat:](https://github.com/f1oNae/FedWSIDD) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2025-09-17 [:book:](./citations/jin2025fedwsidd.txt)
* [Image Distillation for Safe Data Sharing in Histopathology](https://arxiv.org/abs/2406.13536) (Zhe Li et al., MICCAI 2024) [:octocat:](https://github.com/ZheLi2020/InfoDist) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2025-06-18 [:book:](./citations/li2024infodist.txt)
* [High-Order Progressive Trajectory Matching for Medical Image Dataset Distillation](https://arxiv.org/abs/2509.24177) (Le Dong et al., MICCAI 2025) [:octocat:](https://github.com/Bian-jh/HoP-TM) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-09-29 [:book:](./citations/dong2025hop.txt)
* [Dataset Distillation for Medical Dataset Sharing](https://r2hcai.github.io/AAAI-23/pages/accepted-papers.html) (Guang Li et al., AAAI 2023 Workshop) [:octocat:](https://github.com/Guang000/mtt-distillation) ⭐ 1 | 🐛 0 | 📅 2022-05-26 [:book:](./citations/li2023sharing.txt)
* [Soft-Label Anonymous Gastric X-ray Image Distillation](https://arxiv.org/abs/2104.02857) (Guang Li et al., ICIP 2020) [:octocat:](https://github.com/Guang000/dataset-distillation) ⭐ 0 | 🐛 0 | 📅 2019-10-09 [:book:](./citations/li2020soft.txt)
* [Compressed Gastric Image Generation Based on Soft-Label Dataset Distillation for Medical Data Sharing](https://arxiv.org/abs/2209.14635) (Guang Li et al., CMPB 2022) [:octocat:](https://github.com/Guang000/dataset-distillation) ⭐ 0 | 🐛 0 | 📅 2019-10-09 [:book:](./citations/li2022compressed.txt)
* [Communication-Efficient Federated Skin Lesion Classification with Generalizable Dataset Distillation](https://link.springer.com/chapter/10.1007/978-3-031-47401-9_2) (Yuchen Tian & Jiacheng Wang et al., MICCAI 2023 Workshop) [:book:](./citations/tian2023gdd.txt)
* [Importance-Aware Adaptive Dataset Distillation](https://arxiv.org/abs/2401.15863) (Guang Li et al., NN 2024) [:book:](./citations/li2024iadd.txt)
* [MedSynth: Leveraging Generative Model for Healthcare Data Sharing](https://link.springer.com/chapter/10.1007/978-3-031-72390-2_61) (Renuga Kanagavelu et al., MICCAI 2024) [:book:](./citations/kanagavelu2024medsynth.txt)
* [Progressive Trajectory Matching for Medical Dataset Distillation](https://arxiv.org/abs/2403.13469) (Zhen Yu et al., 2024) [:book:](./citations/yu2024progressive.txt)
* [Dataset Distillation in Medical Imaging: A Feasibility Study](https://arxiv.org/abs/2407.14429) (Muyang Li et al., 2024) [:book:](./citations/li2024medical.txt)
* [Dataset Distillation for Histopathology Image Classification](https://arxiv.org/abs/2408.09709) (Cong Cong et al., 2024) [:book:](./citations/cong2024dataset.txt)
* [Low-Level Dataset Distillation for Medical Image Enhancemen](https://arxiv.org/abs/2511.13106) (Fengzhi Xu et al., 2025) [:book:](./citations/xu2025low.txt)
* [Towards Data Quality-Aware Dataset Distillation in Bioimaging](https://www.scitepress.org/publishedPapers/2026/143417) (Bárbara Capelo et al., Bioimaging 2026) [:book:](./citations/capelo2026bioimaging.txt)

<a name="fed" />

### Federated Learning

* [DYNAFED: Tackling Client Data Heterogeneity with Global Dynamics](https://arxiv.org/abs/2211.10878) (Renjie Pi et al., CVPR 2023) [:octocat:](https://github.com/pipilurj/dynafed) ⭐ 50 | 🐛 2 | 🌐 Python | 📅 2023-04-01 [:book:](./citations/pi2023dynafed.txt)
* [DENSE: Data-Free One-Shot Federated Learning](https://arxiv.org/abs/2112.12371) (Jie Zhang & Chen Chen et al., NeurIPS 2022) [:octocat:](https://github.com/zj-jayzhang/DENSE) ⭐ 35 | 🐛 4 | 🌐 Python | 📅 2022-12-11 [:book:](./citations/zhang2022dense.txt)
* [Federated Learning via Decentralized Dataset Distillation in Resource-Constrained Edge Environments](https://arxiv.org/abs/2208.11311) (Rui Song et al., IJCNN 2023) [:octocat:](https://github.com/rruisong/fedd3) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2023-04-08 [:book:](./citations/song2023federated.txt)
* [FedVCK: Non-IID Robust and Communication-Efficient Federated Learning via Valuable Condensed Knowledge for Medical Image Analysis](https://arxiv.org/abs/2412.18557) (Guochen Yan et al., AAAI 2025) [:octocat:](https://github.com/Youth-49/FedVCK_2024) ⭐ 21 | 🐛 1 | 🌐 Python | 📅 2025-02-19 [:book:](./citations/yan2025fedvck.txt)
* [FedDM: Iterative Distribution Matching for Communication-Efficient Federated Learning](https://arxiv.org/abs/2207.09653) (Yuanhao Xiong & Ruochen Wang et al., CVPR 2023) [:octocat:](https://github.com/anonymifish/fed-distribution-matching) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2024-01-04 [:book:](./citations/xiong2023feddm.txt)
* [Overcoming Data and Model Heterogeneities in Decentralized Federated Learning via Synthetic Anchors](https://arxiv.org/abs/2405.11525) (Chun-Yin Huang et al., ICML 2024) [:octocat:](https://github.com/ubc-tea/DESA) ⭐ 16 | 🐛 3 | 🌐 Python | 📅 2024-06-14 [:book:](./citations/huang2024desa.txt)
* [FedLAP-DP: Federated Learning by Sharing Differentially Private Loss Approximations](https://arxiv.org/abs/2302.01068) (Hui-Po Wang et al., 2023) [:octocat:](https://github.com/a514514772/fedlap-dp) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2024-07-03 [:book:](./citations/wang2023fed.txt)
* [Unlocking the Potential of Federated Learning: The Symphony of Dataset Distillation via Deep Generative Latents](https://arxiv.org/abs/2312.01537) (Yuqi Jia & Saeed Vahidian et al., ECCV 2024) [:octocat:](https://github.com/FedDG23/FedDG-main) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2023-11-21 [:book:](./citations/jia2024feddg.txt)
* [Federated Learning on Virtual Heterogeneous Data with Local-global Distillation](https://arxiv.org/abs/2303.02278) (Chun-Yin Huang et al., TMLR 2024) [:octocat:](https://github.com/ubc-tea/FedLGD) ⭐ 4 | 🐛 2 | 🌐 Python | 📅 2025-02-03 [:book:](./citations/huang2024federated.txt)
* [One-Shot Collaborative Data Distillation](https://arxiv.org/abs/2408.02266) (William Holland et al., ECAI 2024) [:octocat:](https://github.com/rayneholland/CollabDM) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2024-08-02 [:book:](./citations/holland2024one.txt)
* [DCFL: Non-IID Awareness Dataset Condensation Aided Federated Learning](https://ieeexplore.ieee.org/document/10650791) (Xingwang Wang et al., IJCNN 2024) [:octocat:](https://github.com/JLUssh/DCFL) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-05-22 [:book:](./citations/wang2024dcfl.txt)
* [Federated Learning via Synthetic Data](https://arxiv.org/abs/2008.04489) (Jack Goetz et al., 2020) [:book:](./citations/goetz2020federated.txt)
* [Distilled One-Shot Federated Learning](https://arxiv.org/abs/2009.07999) (Yanlin Zhou et al., 2020) [:book:](./citations/zhou2020distilled.txt)
* [FedSynth: Gradient Compression via Synthetic Data in Federated Learning](https://arxiv.org/abs/2204.01273) (Shengyuan Hu et al., 2022) [:book:](./citations/hu2022fedsynth.txt)
* [Meta Knowledge Condensation for Federated Learning](https://arxiv.org/abs/2209.14851) (Ping Liu et al., ICLR 2023) [:book:](./citations/liu2023meta.txt)
* [An Aggregation-Free Federated Learning for Tackling Data Heterogeneity](https://arxiv.org/abs/2404.18962) (Yuan Wang et al., CVPR 2024) [:book:](./citations/wang2024fed.txt)

<a name="gnn" />

### Graph Neural Network

* [Graph Condensation for Graph Neural Networks](https://arxiv.org/abs/2110.07580) (Wei Jin et al., ICLR 2022) [:octocat:](https://github.com/chandlerbang/gcond) ⭐ 144 | 🐛 11 | 🌐 Python | 📅 2025-10-10 [:book:](./citations/jin2022graph.txt)
* [Structure-free Graph Condensation: From Large-scale Graphs to Condensed Graph-free Data](https://arxiv.org/abs/2306.02664) (Xin Zheng et al., NeurIPS 2023) [:octocat:](https://github.com/amanda-zheng/sfgc) ⭐ 38 | 🐛 1 | 🌐 Python | 📅 2023-10-06 [:book:](./citations/zheng2023sfgc.txt)
* [Does Graph Distillation See Like Vision Dataset Counterpart?](https://arxiv.org/abs/2310.09192) (Beining Yang & Kai Wang et al., NeurIPS 2023) [:octocat:](https://github.com/RingBDStack/SGDD) ⭐ 26 | 🐛 7 | 🌐 Python | 📅 2023-10-19 [:book:](./citations/yang2023sgdd.txt)
* [Navigating Complexity: Toward Lossless Graph Condensation via Expanding Window Matching](https://arxiv.org/abs/2402.05011) (Yuchen Zhang & Tianle Zhang & Kai Wang et al., ICML 2024) [:octocat:](https://github.com/nus-hpc-ai-lab/geom) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2024-06-23 [:book:](./citations/zhang2024geom.txt)
* [Condensing Graphs via One-Step Gradient Matching](https://arxiv.org/abs/2206.07746) (Wei Jin et al., KDD 2022) [:octocat:](https://github.com/amazon-research/DosCond) ⭐ 19 | 🐛 4 | 🌐 Python | 📅 2023-07-10 [:book:](./citations/jin2022condensing.txt)
* [Graph Distillation with Eigenbasis Matching](https://arxiv.org/abs/2310.09202) (Yang Liu & Deyu Bo et al., ICML 2024) [:octocat:](https://github.com/liuyang-tian/GDEM) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2024-07-02 [:book:](./citations/liu2024gdem.txt)
* [CaT: Balanced Continual Graph Learning with Graph Condensation](https://arxiv.org/abs/2309.09455) (Yilun Liu et al., ICDM 2023) [:octocat:](https://github.com/superallen13/CaT-CGL) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2023-12-21 [:book:](./citations/liu2023cat.txt)
* [Graph Data Condensation via Self-expressive Graph Structure Reconstruction](https://arxiv.org/abs/2403.07294) (Zhanyu Liu & Chaolv Zeng et al., KDD 2024) [:octocat:](https://github.com/zclzcl0223/GCSR) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2024-11-20 [:book:](./citations/liu2024gcsr.txt)
* [Kernel Ridge Regression-Based Graph Dataset Distillation](https://dl.acm.org/doi/10.1145/3580305.3599398) (Zhe Xu et al., KDD 2023) [:octocat:](https://github.com/pricexu/KIDD) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2023-09-10 [:book:](./citations/xu2023kidd.txt)
* [Two Trades is not Baffled: Condensing Graph via Crafting Rational Gradient Matching](https://arxiv.org/abs/2402.04924) (Tianle Zhang & Yuchen Zhang & Kai Wang et al., 2024) [:octocat:](https://github.com/nus-hpc-ai-lab/ctrl) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2024-02-09 [:book:](./citations/zhang2024ctrl.txt)
* [Mirage: Model-Agnostic Graph Distillation for Graph Classification](https://arxiv.org/abs/2310.09486) (Mridul Gupta & Sahil Manchanda et al., ICLR 2024) [:octocat:](https://github.com/frigategnn/Mirage) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2024-04-03 [:book:](./citations/gupta2024mirage.txt)
* [Graph Condensation via Receptive Field Distribution Matching](https://arxiv.org/abs/2206.13697) (Mengyang Liu et al., 2022) [:book:](./citations/liu2022graph.txt)

#### Survey

* [A Comprehensive Survey on Graph Reduction: Sparsification, Coarsening, and Condensation](https://arxiv.org/abs/2402.03358) (Mohammad Hashemi et al., IJCAI 2024) [:octocat:](https://github.com/Emory-Melody/awesome-graph-reduction) ⭐ 188 | 🐛 0 | 📅 2026-02-25 [:book:](./citations/hashemi2024awesome.txt)
* [Graph Condensation: A Survey](https://arxiv.org/abs/2401.11720) (Xinyi Gao et al., TKDE 2025) [:octocat:](https://github.com/xygaog/graph-condensation-papers) ⭐ 51 | 🐛 0 | 📅 2025-07-01 [:book:](./citations/gao2025graph.txt)
* [A Survey on Graph Condensation](https://arxiv.org/abs/2402.02000) (Hongjia Xu et al., 2024) [:octocat:](https://github.com/Frostland12138/Awesome-Graph-Condensation) ⭐ 21 | 🐛 0 | 📅 2025-04-10 [:book:](./citations/xu2024survey.txt)

#### Benchmark

* [GC-Bench: A Benchmark Framework for Graph Condensation with New Insights](https://arxiv.org/abs/2406.16715) (Shengbo Gong & Juntong Ni et al., 2024) [:octocat:](https://github.com/Emory-Melody/GraphSlim) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2026-07-23 [:book:](./citations/gong2024graphslim.txt)
* [GC-Bench: An Open and Unified Benchmark for Graph Condensation](https://arxiv.org/abs/2407.00615) (Qingyun Sun & Ziying Chen et al., NeurIPS 2024) [:octocat:](https://github.com/RingBDStack/GC-Bench) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2024-08-15 [:book:](./citations/sun2024gcbench.txt)
* [GCondenser: Benchmarking Graph Condensation](https://arxiv.org/abs/2405.14246) (Yilun Liu et al., 2024) [:octocat:](https://github.com/superallen13/GCondenser) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2025-06-18 [:book:](./citations/liu2024gcondenser.txt)

#### No further updates will be made regarding graph distillation topics as sufficient papers and summary projects are already available on the subject

<a name="nas" />

### Neural Architecture Search

* [Generative Teaching Networks: Accelerating Neural Architecture Search by Learning to Generate Synthetic Training Data](https://arxiv.org/abs/1912.07768) (Felipe Petroski Such et al., ICML 2020) [:octocat:](https://github.com/uber-research/GTN) ⭐ 78 | 🐛 3 | 🌐 Python | 📅 2020-04-20 [:book:](./citations/such2020generative.txt)
* [Learning to Generate Synthetic Training Data using Gradient Matching and Implicit Differentiation](https://arxiv.org/abs/2203.08559) (Dmitry Medvedev et al., AIST 2021) [:octocat:](https://github.com/dm-medvedev/efficientdistillation) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2022-04-19 [:book:](./citations/medvedev2021tabular.txt)
* [Calibrated Dataset Condensation for Faster Hyperparameter Search](https://arxiv.org/abs/2405.17535) (Mucong Ding et al., 2024) [:book:](./citations/ding2024hcdc.txt)

<a name="fashion" />

### Fashion, Art, and Design

* [Wearable ImageNet: Synthesizing Tileable Textures via Dataset Distillation](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/html/Cazenavette_Wearable_ImageNet_Synthesizing_Tileable_Textures_via_Dataset_Distillation_CVPRW_2022_paper.html) (George Cazenavette et al., CVPR 2022 Workshop) [:globe\_with\_meridians:](https://georgecazenavette.github.io/mtt-distillation/) [:octocat:](https://github.com/georgecazenavette/mtt-distillation) ⭐ 439 | 🐛 9 | 🌐 Python | 📅 2024-07-16 [:book:](./citations/cazenavette2022textures.txt)
* [Galaxy Dataset Distillation with Self-Adaptive Trajectory Matching](https://arxiv.org/abs/2311.17967) (Haowen Guan et al., NeurIPS 2023 Workshop) [:octocat:](https://github.com/HaowenGuan/Galaxy-Dataset-Distillation) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2024-03-13 [:book:](./citations/guan2023galaxy.txt)
* [Learning from Designers: Fashion Compatibility Analysis Via Dataset Distillation](https://ieeexplore.ieee.org/document/9897234) (Yulan Chen et al., ICIP 2022) [:book:](./citations/chen2022fashion.txt)

<a name="rec" />

### Recommender Systems

* [Infinite Recommendation Networks: A Data-Centric Approach](https://arxiv.org/abs/2206.02626) (Noveen Sachdeva et al., NeurIPS 2022) [:octocat:](https://github.com/noveens/distill_cf) ⭐ 24 | 🐛 1 | 🌐 Python | 📅 2023-06-08 [:book:](./citations/sachdeva2022data.txt)
* [TD3: Tucker Decomposition Based Dataset Distillation Method for Sequential Recommendation](https://arxiv.org/abs/2502.02854) (Jiaqing Zhang et al., WWW 2025) [:octocat:](https://github.com/USTC-StarTeam/TD3) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2024-10-23 [:book:](./citations/zhang2025td3.txt)
* [Gradient Matching for Categorical Data Distillation in CTR Prediction](https://dl.acm.org/doi/10.1145/3604915.3608769) (Chen Wang et al., RecSys 2023) [:book:](./citations/wang2023cgm.txt)
* [DIET: Learning to Distill Dataset Continually for Recommender Systems](https://arxiv.org/abs/2603.24958) (Jiaqing Zhang et al., 2026) [:book:](./citations/zhang2026diet.txt)
* [FOSTER: First-order Dataset Distillation for Text-based Sequential Recommendation](https://arxiv.org/abs/2605.30772) (Hung Vinh Tran et al., arXiv 2026) [:book:](./citations/tran2026foster.txt)

<a name="blackbox" />

### Blackbox Optimization

* [Bidirectional Learning for Offline Infinite-width Model-based Optimization](https://arxiv.org/abs/2209.07507) (Can Chen et al., NeurIPS 2022) [:octocat:](https://github.com/ggchen1997/bdi) ⭐ 14 | 🐛 2 | 🌐 Python | 📅 2023-01-19 [:book:](./citations/chen2022bidirectional.txt)
* [Bidirectional Learning for Offline Model-based Biological Sequence Design](https://arxiv.org/abs/2301.02931) (Can Chen et al., ICML 2023) [:octocat:](https://github.com/GGchen1997/BIB-ICML2023-Submission) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2023-01-22 [:book:](./citations/chen2023bidirectional.txt)

<a name="robustness" />

### Robustness

* [Towards Trustworthy Dataset Distillation](https://arxiv.org/abs/2307.09165) (Shijie Ma et al., PR 2024) [:octocat:](https://github.com/mashijie1028/TrustDD/) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2024-12-08  [:book:](./citations/ma2024trustworthy.txt)
* [Group Distributionally Robust Dataset Distillation with Risk Minimization](https://arxiv.org/abs/2402.04676) (Saeed Vahidian & Mingyu Wang & Jianyang Gu et al., ICLR 2025) [:octocat:](https://github.com/Mming11/RobustDatasetDistillation) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2025-03-21 [:book:](./citations/vahidian2025group.txt)
* [Towards Adversarially Robust Dataset Distillation by Curvature Regularization](https://arxiv.org/abs/2403.10045) (Eric Xue et al., AAAI 2025) [:globe\_with\_meridians:](https://yumozi.github.io/GUARD/) [:octocat:](https://github.com/yumozi/GUARD) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2025-10-21 [:book:](./citations/xue2025robust.txt)
* [ROME is Forged in Adversity: Robust Distilled Datasets via Information Bottleneck](https://openreview.net/forum?id=agtwOsnLUB) (Zheng Zhou et al., ICML 2025) [:globe\_with\_meridians:](https://zhouzhengqd.github.io/rome.page/) [:octocat:](https://github.com/zhouzhengqd/ROME) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-07-01 [:book:](./citations/zhou2025rome.txt)
* [Can We Achieve Robustness from Data Alone?](https://arxiv.org/abs/2207.11727) (Nikolaos Tsilivis et al., ICML 2022 Workshop) [:book:](./citations/tsilivis2022robust.txt)
* [Towards Robust Dataset Learning](https://arxiv.org/abs/2211.10752) (Yihan Wu et al., 2022) [:book:](./citations/wu2022towards.txt)
* [Rethinking Data Distillation: Do Not Overlook Calibration](https://arxiv.org/abs/2307.12463) (Dongyao Zhu et al., ICCV 2023) [:book:](./citations/zhu2023calibration.txt)
* [Mind Your Margin and Boundary: Are Your Distilled Datasets Truly Robust?](https://arxiv.org/abs/2605.20606) (Muquan Li et al., ICML 2026) [:book:](./citations/li2026c2r.txt)

<a name="fairness" />

### Fairness

* [FairDD: Fair Dataset Distillation](https://arxiv.org/abs/2411.19623) (Qihang Zhou et al., NeurIPS 2025) [:octocat:](https://github.com/zqhang/FairDD) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2025-10-26 [:book:](./citations/zhou2025fair.txt)
* [Fair Dataset Distillation via Cross-Group Barycenter Alignment](https://arxiv.org/abs/2605.00185) (Mohammad Hossein Moslemi et al., ICML 2026) [:octocat:](https://github.com/mhmoslemi/COBRA) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-05-08 [:book:](./citations/moslemi2026fairdd.txt)
* [Fair Graph Distillation](https://openreview.net/forum?id=xW0ayZxPWs) (Qizhang Feng et al., NeurIPS 2023) [:book:](./citations/feng2023fair.txt)

<a name="text" />

### Text

* [DiLM: Distilling Dataset into Language Model for Text-level Dataset Distillation](https://arxiv.org/abs/2404.00264) (Aru Maekawa et al., NAACL 2024) [:octocat:](https://github.com/arumaekawa/DiLM) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2025-02-10 [:book:](./citations/maekawa2024dilm.txt)
* [Dataset Distillation with Attention Labels for Fine-tuning BERT](https://aclanthology.org/2023.acl-short.12/) (Aru Maekawa et al., ACL 2023) [:octocat:](https://github.com/arumaekawa/dataset-distillation-with-attention-labels) ⭐ 23 | 🐛 1 | 🌐 Python | 📅 2024-01-08 [:book:](./citations/maekawa2023text.txt)
* [Synthetic Text Generation for Training Large Language Models via Gradient Matching](https://arxiv.org/abs/2502.17607) (Dang Nguyen & Zeman Li et al., ICML 2025) [:octocat:](https://github.com/BigML-CS-UCLA/GRADMM) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2025-06-18 [:book:](./citations/nguyen2025llm.txt)
* [UniDetox: Universal Detoxification of Large Language Models via Dataset Distillation](https://arxiv.org/abs/2504.20500) (Huimin Lu et al., ICLR 2025) [:octocat:](https://github.com/EminLU/UniDetox) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-04-14 [:book:](./citations/lu2025llm.txt)
* [CondenseLM: LLMs-driven Text Dataset Condensation via Reward Matching](https://aclanthology.org/2025.emnlp-main.65/) (Cheng Shen et al., EMNLP 2025) [:octocat:](https://github.com/cs6331/CondenseLM/) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-04-24 [:book:](./citations/shen2025llm.txt)
* [Data Distillation for Text Classification](https://arxiv.org/abs/2104.08448) (Yongqi Li et al., 2021) [:book:](./citations/li2021text.txt)
* [Textual Dataset Distillation via Language Model Embedding](https://aclanthology.org/2024.findings-emnlp.733/) (Yefan Tao et al., EMNLP 2024) [:book:](./citations/tao2024textual.txt)
* [Knowledge Hierarchy Guided Biological-Medical Dataset Distillation for Domain LLM Training](https://arxiv.org/abs/2501.15108) (Xunxin Cai & Chengrui Wang & Qingqing Long et al., DASFAA 2025) [:book:](./citations/cai2025llm.txt)

<a name="video" />

### Video

* [Dancing with Still Images: Video Distillation via Static-Dynamic Disentanglement](https://arxiv.org/abs/2312.00362) (Ziyu Wang & Yue Xu et al., CVPR 2024) [:octocat:](https://github.com/yuz1wan/video_distillation) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2025-12-21 [:book:](./citations/wang2023dancing.txt)
* [A Large-Scale Study on Video Action Dataset Condensation](https://arxiv.org/abs/2412.21197) (Yang Chen et al., 2024) [:octocat:](https://github.com/MCG-NJU/Video-DC) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2025-07-30 [:book:](./citations/chen2024video.txt)
* [Latent Video Dataset Distillation](https://arxiv.org/abs/2504.17132) (Ning Li et al., CVPR 2025 Workshop) [:octocat:](https://github.com/liningresearch/Latent_Video_Dataset_Distillation) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2025-07-31 [:book:](./citations/li2025latent.txt)
* [Video Set Distillation: Information Diversification and Temporal Densifica](https://arxiv.org/abs/2412.00111) (Yinjie Zhao et al., 2024) [:book:](./citations/zhao2024video.txt)
* [Condensing Action Segmentation Datasets via Generative Network Inversion](https://arxiv.org/abs/2503.14112) (Guodong Ding et al., CVPR 2025) [:book:](./citations/ding2025video.txt)
* [Distill Video Datasets into Images](https://arxiv.org/abs/2512.14621) (Zhenghao Zhao et al., 2025) [:book:](./citations/zhao2025video.txt)
* [PRISM: Video Dataset Condensation with Progressive Refinement and Insertion for Sparse Motion](https://arxiv.org/abs/2505.22564) (Jaehyun Choi et al., CVPR 2026) [:book:](./citations/choi2026prism.txt)
* [Adaptive Latent Trajectory Anchoring for Action Segmentation Dataset Condensation](https://arxiv.org/abs/2607.09081) (Arthème Gauthier-Villars & Guodong Ding et al., ECCV 2026) [:book:](./citations/gauthier2026adaptive.txt)

<a name="tabular" />

### Tabular

* [New Properties of the Data Distillation Method When Working With Tabular Data](https://arxiv.org/abs/2010.09839) (Dmitry Medvedev et al., AIST 2020) [:octocat:](https://github.com/dm-medvedev/dataset-distillation) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2020-10-02 [:book:](./citations/medvedev2020tabular.txt)

<a name="retrieval" />

### Retrieval

* [Towards Efficient Deep Hashing Retrieval: Condensing Your Data via Feature-Embedding Matching](https://arxiv.org/abs/2305.18076) (Tao Feng & Jie Zhang et al., 2023) [:book:](./citations/feng2023hash.txt)

<a name="domain" />

### Domain Adaptation

* [Multi-Source Domain Adaptation Meets Dataset Distillation through Dataset Dictionary Learning](https://arxiv.org/abs/2309.07666) (Eduardo Montesuma et al., ICASSP 2024) [:book:](./citations/montesuma2024multi.txt)

<a name="super" />

### Super Resolution

* [GSDD: Generative Space Dataset Distillation for Image Super-resolution](https://ojs.aaai.org/index.php/AAAI/article/view/28534) (Haiyu Zhang et al., AAAI 2024) [:book:](./citations/zhang2024super.txt)

<a name="time" />

### Time Series

* [CondTSF: One-line Plugin of Dataset Condensation for Time Series Forecasting](https://arxiv.org/abs/2406.02131) (Jianrong Ding & Zhanyu Liu et al., NeurIPS 2024) [:octocat:](https://github.com/RafaDD/CondTSF) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-06-05 [:book:](./citations/ding2024time.txt)
* [Effective Dataset Distillation for Spatio-Temporal Forecasting with Bi-dimensional Compression](https://arxiv.org/abs/2603.10410) (Taehyung Kwon & Yeonje Choi et al., ICDE 2026) [:octocat:](https://github.com/kbrother/STemDist) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2026-04-08 [:book:](./citations/kwon2026effective.txt)
* [Dataset Condensation for Time Series Classification via Dual Domain Matching](https://arxiv.org/abs/2403.07245) (Zhanyu Liu et al., KDD 2024) [:octocat:](https://github.com/zhyliu00/TimeSeriesCond) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2024-05-17 [:book:](./citations/liu2024time.txt)
* [ShapeCond: Fast Shapelet-Guided Dataset Condensation for Time Series Classification](https://arxiv.org/abs/2602.09008) (Sijia Peng et al., 2026) [:octocat:](https://github.com/lunaaa95/ShapeCond) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-02-18 [:book:](./citations/peng2026shapecond.txt)
* [Less is More: Efficient Time Series Dataset Condensation via Two-fold Modal Matching](https://arxiv.org/abs/2410.20905) (Hao Miao et al., VLDB 2025) [:octocat:](https://github.com/uestc-liuzq/STdistillation) ⭐ 9 | 🐛 3 | 🌐 Python | 📅 2025-03-26 [:book:](./citations/miao2025timedc.txt)
* [Distilling Time Series Foundation Models for Efficient Forecasting](https://arxiv.org/abs/2601.12785) (Yuqi Li & Kuiye Ding et al., ICASSP 2026) [:octocat:](https://github.com/itsnotacie/DistilTS-ICASSP2026) ⭐ 9 | 🐛 3 | 🌐 Python | 📅 2025-09-17 [:book:](./citations/li2026distilts.txt)
* [One Batch Is Enough: A Unified Dataset Condensation Framework for General Time Series Analysis](https://openreview.net/forum?id=i8FO7f2OYJ) (Wei Shao et al., ICML 2026) [:octocat:](https://github.com/ZJU-DAILY/UniTSC) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-05-17 [:book:](./citations/shao2026unitsc.txt)
* [DDTime: Dataset Distillation with Spectral Alignment and Information Bottleneck for Time-Series Forecasting](https://arxiv.org/abs/2511.16715) (Yuqi Li & Kuiye Ding et al., 2025) [:book:](./citations/li2025time.txt)
* [Harmonic Dataset Distillation for Time Series Forecasting](https://arxiv.org/abs/2603.03760) (Seungha Hong et al., AAAI 2026) [:book:](./citations/hong2026hdt.txt)

<a name="speech" />

### Speech

* [Dataset-Distillation Generative Model for Speech Emotion Recognition](https://arxiv.org/abs/2406.02963) (Fabian Ritter-Gutierrez et al., Interspeech 2024) [:book:](./citations/fabian2024speech.txt)

<a name="unlearning" />

### Machine Unlearning

* [Distilled Datamodel with Reverse Gradient Matching](https://arxiv.org/abs/2404.14006) (Jingwen Ye et al., CVPR 2024) [:book:](./citations/ye2024datamodel.txt)
* [Dataset Condensation Driven Machine Unlearning](https://arxiv.org/abs/2402.00195) (Junaid Iqbal Khan, 2024) [:octocat:](https://github.com/algebraicdianuj/DC_U) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-07-13 [:book:](./citations/khan2024unlearning.txt)

<a name="rl" />

### Reinforcement Learning

* [Dataset Distillation for Offline Reinforcement Learning](https://arxiv.org/abs/2407.20299) (Jonathan Light & Yuanzhe Liu et al., ICML 2024 Workshop) [:globe\_with\_meridians:](https://datasetdistillation4rl.github.io/) [:octocat:](https://github.com/ggflow123/DDRL) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2024-08-02 [:book:](./citations/light2024rl.txt)
* [Offline Behavior Distillation](https://arxiv.org/abs/2410.22728) (Shiye Lei et al., NeurIPS 2024) [:octocat:](https://github.com/LeavesLei/OBD) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2024-10-31 [:book:](./citations/lei2024obl.txt)
* [Behaviour Distillation](https://arxiv.org/abs/2406.15042) (Andrei Lupu et al., ICLR 2024) [:octocat:](https://github.com/flairox/behaviour-distillation) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2024-06-21 [:book:](./citations/lupu2024bd.txt)
* [Distilling Reinforcement Learning into Single-Batch Datasets](https://arxiv.org/abs/2508.09283) (Connor Wilhelm et al., ECAI 2025) [:book:](./citations/wilhelm2025rl.txt)
* [Algorithmic Guarantees for Distilling Supervised and Offline RL Datasets](https://arxiv.org/abs/2512.00536) (Aaryan Gupta et al., ICLR 2026) [:book:](./citations/gupta2026rl.txt)

<a name="long" />

### Long-Tail

* [Distilling Long-tailed Datasets](https://arxiv.org/abs/2408.14506) (Zhenghao Zhao & Haoxuan Wang et al., CVPR 2025) [:octocat:](https://github.com/ichbill/LTDD) ⭐ 25 | 🐛 1 | 🌐 Python | 📅 2025-08-13 [:book:](./citations/zhao2025long.txt)
* [Rectifying Soft-Label Entangled Bias in Long-Tailed Dataset Distillation](https://arxiv.org/abs/2511.17914) (Chenyang Jiang et al., NeurIPS 2025) [:octocat:](https://github.com/j-cyoung/ADSA_DD) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-10-27 [:book:](./citations/jiang2025long.txt)
* [Rethinking Long-tailed Dataset Distillation: A Uni-Level Framework with Unbiased Recovery and Relabeling](https://arxiv.org/abs/2511.18858) (Xiao Cui et al., AAAI 2026) [:book:](./citations/cui2026long.txt)

<a name="noisy" />

### Learning with Noisy Labels

* [Robust Dataset Condensation using Supervised Contrastive Learning](https://openaccess.thecvf.com/content/ICCV2025/html/Kim_Robust_Dataset_Condensation_using_Supervised_Contrastive_Learning_ICCV_2025_paper.html) (Nicole Hee-Yeon Kim et al., ICCV 2025) [:octocat:](https://github.com/DISL-Lab/RDC-ICCV2025) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2025-11-07 [:book:](./citations/kim2025rdc.txt)
* [Dataset Distillers Are Good Label Denoisers In the Wild](https://arxiv.org/abs/2411.11924) (Lechao Cheng et al., 2024) [:octocat:](https://github.com/Kciiiman/DD_LNL) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-01-12 [:book:](./citations/cheng2024noisy.txt)

<a name="detection" />

### Object Detection

* [Fetch and Forge: Efficient Dataset Condensation for Object Detection](https://openreview.net/forum?id=m8MElyzuwp) (Ding Qi et al., NeurIPS 2024) [:book:](./citations/qi2024dcod.txt)
* [OD3: Optimization-free Dataset Distillation for Object Detection](https://arxiv.org/abs/2506.01942) (Salwa K. Al Khatib & Ahmed ElHagry & Shitong Shao et al., ICLR 2026) [:octocat:](https://github.com/VILA-Lab/OD3) ⭐ 31 | 🐛 1 | 🌐 Python | 📅 2026-01-26 [:book:](./citations/khatib2026od3.txt)

<a name="point" />

### Point Cloud

* [Dataset Distillation of 3D Point Clouds via Distribution Matching](https://arxiv.org/abs/2503.22154) (Jae-Young Yim & Dongwook Kim et al., NeurIPS 2025) [:octocat:](https://github.com/donguk071/SADM) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2026-05-13 [:book:](./citations/yim2025point.txt)
* [Parameterization-Based Dataset Distillation of 3D Point Clouds through Learnable Shape Morphing](https://openreview.net/forum?id=Qe7dKZOtWM) (Dongwook Kim & Jae-Young Yim et al., ICLR 2026) [:octocat:](https://github.com/donguk071/3DDP) ⭐ 3 | 🐛 0 | 📅 2026-05-11 [:book:](./citations/kim2026pointmorph.txt)
* [Point Cloud Dataset Distillation](https://openreview.net/forum?id=Us8v5tDOFd) (Deyu Bo et al., ICML 2025) [:book:](./citations/bo2025point.txt)

<a name="uni" />

### Universal Distillation

* [Towards Universal Dataset Distillation via Task-Driven Diffusion](https://openaccess.thecvf.com/content/CVPR2025/html/Qi_Towards_Universal_Dataset_Distillation_via_Task-Driven_Diffusion_CVPR_2025_paper.html) (Ding Qi et al., CVPR 2025) [:book:](./citations/qi2025unidd.txt)

<a name="snn" />

### Spiking Neural Network

* [Learning from Dense Events: Towards Fast Spiking Neural Networks Training via Event Dataset Distillation](https://arxiv.org/abs/2511.12095) (Shuhan Ye et al., 2025) [:book:](./citations/ye2025snn.txt)

<a name="eeg" />

### EEG

* [EEG-DLite: Dataset Distillation for Efficient Large EEG Model Training](https://arxiv.org/abs/2512.12210) (Yuting Tang et al., AAAI 2026) [:octocat:](https://github.com/t170815518/EEG-DLite) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2025-12-16 [:book:](./citations/tang2026eeg.txt)

<a name="finance" />

### Finance

* [Secure and Explainable Fraud Detection in Finance via Hierarchical Multi-source Dataset Distillation](https://arxiv.org/abs/2512.21866) (Yiming Qian et al., ICAIFW 2025) [:book:](./citations/qian2025finance.txt)

<a name="music" />

### Music

* [ConceptCaps: a Distilled Concept Dataset for Interpretability in Music Models](https://arxiv.org/abs/2601.14157) (Bruno Sienkiewicz et al., 2026) [:book:](./citations/sienkiewicz2026music.txt)

<a name="rs" />

### Remote Sensing

* [Towards Realistic Remote Sensing Dataset Distillation with Discriminative Prototype-guided Diffusion](https://arxiv.org/abs/2601.15829) (Yonghao Xu et al., 2026) [:book:](./citations/xu2026rs.txt)

<a name="dr" />

### Deraining

* [UniRain: Unified Image Deraining with RAG-based Dataset Distillation and Multi-objective Reweighted Optimization](https://arxiv.org/abs/2603.03967) (Qianfeng Yang et al., CVPR 2026) [:octocat:](https://github.com/QianfengY/UniRain) ⭐ 26 | 🐛 2 | 🌐 Python | 📅 2026-05-25 [:book:](./citations/yang2026unirain.txt)

<a name="fine" />

### Fine-grained

* [FD2: A Dedicated Framework for Fine-Grained Dataset Distillation](https://arxiv.org/abs/2603.25144) (Hongxu Ma & Guang Li et al., ECCV 2026) [:book:](./citations/ma2026fd2.txt)

<a name="segmentation" />

### Test-Time Adaptation

* [Distill Once, Adapt Life-Long: Exploring Dataset Distillation for Continual Test-Time Adaptation](https://arxiv.org/abs/2606.20196) (Hyun-Kurl Jang & Jihun Kim & Hyeokjun Kweon et al., ECCV 2026) [:octocat:](https://github.com/blue-531/DOALL) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2026-06-24 [:book:](./citations/jang2026doall.txt)

### Semantic Segmentation

* [D3S2: Diffusion-Guided Dataset Distillation for Semantic Segmentation](https://arxiv.org/abs/2605.25022) (Wenjie Zheng et al., arXiv 2026) [:book:](./citations/zheng2026d3s2.txt)

<a name="tta" />

## Media Coverage

* [Beginning of Awesome Dataset Distillation](https://twitter.com/TongzhouWang/status/1560043815204970497?cxt=HHwWgoCz9bPlsaYrAAAA)
* [Most Popular AI Research Aug 2022](https://www.libhunt.com/posts/874974-d-most-popular-ai-research-aug-2022-ranked-based-on-github-stars)
* [一个项目帮你了解数据集蒸馏Dataset Distillation](https://www.jiqizhixin.com/articles/2022-10-11-22)
* [浓缩就是精华：用大一统视角看待数据集蒸馏](https://mp.weixin.qq.com/s/__IjS0_FMpu35X9cNhNhPg)

## Citing Awesome Dataset Distillation

If you find this project useful for your research, please use the following BibTeX entry.

```
@misc{li2022awesome,
  author={Li, Guang and Zhao, Bo and Wang, Tongzhou},
  title={Awesome Dataset Distillation},
  howpublished={\url{https://github.com/Guang000/Awesome-Dataset-Distillation}},
  year={2022}
}
```

## Acknowledgments

We would like to express our heartfelt thanks to [Nikolaos Tsilivis](https://github.com/Tsili42), [Wei Jin](https://github.com/ChandlerBang), [Yongchao Zhou](https://github.com/yongchao97), [Noveen Sachdeva](https://github.com/noveens), [Can Chen](https://github.com/GGchen1997), [Guangxiang Zhao](https://github.com/zhaoguangxiang), [Shiye Lei](https://github.com/LeavesLei), [Xinchao Wang](https://sites.google.com/site/sitexinchaowang/), [Dmitry Medvedev](https://github.com/dm-medvedev), [Seungjae Shin](https://github.com/SJShin-AI), [Jiawei Du](https://github.com/AngusDujw), [Yidi Jiang](https://github.com/Jiang-Yidi), [Xindi Wu](https://github.com/XindiWu), [Guangyi Liu](https://github.com/lgy0404), [Yilun Liu](https://github.com/superallen13), [Kai Wang](https://github.com/kaiwang960112), [Yue Xu](https://github.com/silicx), [Anjia Cao](https://github.com/CAOANJIA), [Jianyang Gu](https://github.com/vimar-gu), [Yuanzhen Feng](https://github.com/fengyzpku), [Peng Sun](https://github.com/sp12138), [Ahmad Sajedi](https://github.com/AhmadSajedii), [Zhihao Sui](https://github.com/suizhihao), [Ziyu Wang](https://github.com/yuz1wan), [Haoyang Liu](https://github.com/Liu-Hy), [Eduardo Montesuma](https://github.com/eddardd), [Shengbo Gong](https://github.com/rockcor), [Zheng Zhou](https://github.com/zhouzhengqd), [Zhenghao Zhao](https://github.com/ichbill), [Duo Su](https://github.com/suduo94), [Tianhang Zheng](https://github.com/tianzheng4), [Shijie Ma](https://github.com/mashijie1028), [Wei Wei](https://github.com/WeiWeic6222848), [Yantai Yang](https://github.com/Hiter-Q), [Shaobo Wang](https://github.com/gszfwsb), [Xinhao Zhong](https://github.com/ndhg1213), [Zhiqiang Shen](https://github.com/szq0214), [Cong Cong](https://github.com/thomascong121), [Chun-Yin Huang](https://github.com/chunyinhuang), [Dai Liu](https://github.com/NiaLiu), [Ruonan Yu](https://github.com/Lexie-YU), [William Holland](https://github.com/rayneholland), [Saksham Singh Kushwaha](https://github.com/sakshamsingh1), [Ping Liu](https://github.com/pinglmlcv), [Wenliang Zhong](https://github.com/Zhong0x29a), [Ning Li](https://github.com/Ning9319), [Guochen Yan](https://github.com/Youth-49), [Saumyaranjan Mohanty](https://github.com/arareddy), [Taehyung Kwon](https://github.com/kbrother), [Dongwook Kim](https://github.com/donguk071), [Bárbara Capelo](https://github.com/BarbaraCapelo), [Guanghui Shi](https://github.com/BeCarefulOfYournaoke), [Jongoh Jeong](https://github.com/andyj1), [Akshay Mehra](https://github.com/akshaymehra24), [Hyun-Kurl Jang](https://github.com/blue-531), and [Jiacheng Cui](https://github.com/Jiacheng8) for their valuable suggestions and contributions.

The [Homepage](https://guang000.github.io/Awesome-Dataset-Distillation/) of Awesome Dataset Distillation was designed by [Longzhen Li](https://github.com/LOVELESSG) and maintained by [Mingzhuo Li](https://github.com/SumomoTaku).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._

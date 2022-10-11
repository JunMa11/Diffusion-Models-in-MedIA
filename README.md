# Diffusion Models in Medical Image Analysis

This is a curated list of diffusion models in medical image analysis. 

Welcome to add papers by pulling request or raising issues. 

## Overview
- [Image Synthesis](#image-synthesis)
- [Image Reconstruction](#image-reconstruction)
- [Image Translation](#image-translation)
- [Detection](#detection)
- [Segmentation](#segmentation)
- [Miscellaneous](#miscellaneous)

## Image Synthesis

| Date    | First & Last Author                    | Title                                                        | Paper & Code                                                 |
| ------- | -------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2022.10 | Pierre Chambon & Akshay Chaudhari  | Adapting Pretrained Vision-Language Foundational Models to Medical Imaging Domains | [arxiv](https://arxiv.org/abs/2210.04133) |
| 2022.09 | Virginia Fernandez & M. Jorge Cardoso  | Can Segmentation Models Be Trained with Fully Synthetically Generated Data? | [MICCAI22-SASHIMI](https://link.springer.com/chapter/10.1007/978-3-031-16980-9_8) |
| 2022.09 | Walter H. L. Pinaya & M. Jorge Cardoso | Brain Imaging Generation with Latent Diffusion Models        | [MICCAI22 DGM](https://link.springer.com/chapter/10.1007/978-3-031-18576-2_12) |
| 2022.07 | Boah Kim & Jong Chul Ye                | Diffusion Deformable Model for 4D Temporal Medical Image Generation | [MICCAI2022](https://link.springer.com/chapter/10.1007/978-3-031-16431-6_51), [code](https://github.com/torchddm/ddm) |



## Image Reconstruction

### MR 

| Date    | First & Last Author           | Title                                                        | Paper & Code                                                 |
| ------- | ----------------------------- | ------------------------------------------------------------ | -----------------------------------------------------------|
| 2022.09 | Zhuo-Xu Cui & Dong Liang      | Self-Score: Self-Supervised Learning on Score-Based Models for MRI Reconstruction | [arxiv](https://arxiv.org/abs/2209.00835), [code-TBA](https://github.com/ZhuoxuCui/Self-Score) |
| 2022.08 | Chentao Cao & Yanjie Zhu      | High-Frequency Space Diffusion Models for Accelerated MRI    | [arxiv](https://arxiv.org/abs/2208.05481)                    |
| 2022.07 | Salman UH Dar & Tolga Çukur   | Adaptive Diffusion Priors for Accelerated MRI Reconstruction | [arxiv](https://arxiv.org/abs/2207.05876)                    |
| 2022.07 | Xiangxi Meng & Dinggang Shen  | A Novel Unified Conditional Score-based Generative Framework for Multi-modal Medical Image Completion | [arxiv](https://arxiv.org/abs/2207.03430)                    |
| 2022.03 | Cheng Peng & Rama Chellappa   | Towards performant and reliable undersampled MR reconstruction via diffusion model sampling | [MICCAI22](https://link.springer.com/chapter/10.1007/978-3-031-16446-0_59), [code](https://github.com/cpeng93/diffuserecon) |
| 2022.03 | Yutong Xie & Quanzheng Li     | Measurement-conditioned Denoising Diffusion Probabilistic Model for Under-sampled Medical Image Reconstruction | [MICCAI22](https://link.springer.com/chapter/10.1007/978-3-031-16446-0_62), [code](https://github.com/Theodore-PKU/MC-DDPM) |
| 2022.02 | Guanxiong Luo & Martin Uecker | MRI Reconstruction via Data Driven Markov Chain with Joint Uncertainty Estimation | [arxiv](https://arxiv.org/abs/2202.01479), [code](https://github.com/mrirecon/spreco) |
| 2021.12 | Hyungjin Chung & Jong Chul Ye | Come-Closer-Diffuse-Faster: Accelerating Conditional Diffusion Models for Inverse Problems through Stochastic Contraction | [CVPR21](https://openaccess.thecvf.com/content/CVPR2022/papers/Chung_Come-Closer-Diffuse-Faster_Accelerating_Conditional_Diffusion_Models_for_Inverse_Problems_Through_Stochastic_CVPR_2022_paper.pdf) |
| 2021.10 | Hyungjin Chung & Jong Chul Ye | Score-based diffusion models for accelerated MRI             | [MedIA](https://www.sciencedirect.com/science/article/pii/S1361841522001268), [code](https://github.com/HJ-harry/score-MRI) |

### CT, OCT

| Date    | First & Last Author           | Title                                                        | Paper & Code                                                 |
| ------- | ----------------------------- | ------------------------------------------------------------ | -----------------------------------------------------------|
| 2022.09 | Wenjun Xia & Ge Wang          | Low-Dose CT Using Denoising Diffusion Probabilistic Model for 20× Speedup | [arxiv](https://arxiv.org/abs/2209.15136)                    |
| 2022.06 | Hyungjin Chung & Jong Chul Ye | Improving Diffusion Models for Inverse Problems using Manifold Constraints | [NeurIPS22](https://arxiv.org/abs/2206.00941), [code](https://github.com/HJ-harry/MCG_diffusion) |
| 2022.01 | Dewei Hu & Ipek Oguz          | Unsupervised Denoising of Retinal OCT with Diffusion Probabilistic Model | [SPIE MI22](https://doi.org/10.1117/12.2612235), [code](https://github.com/DeweiHu/OCT_DDPM) |
| 2021.11 | Yang Song & Stefano Ermon     | Solving Inverse Problems in Medical Imaging with Score-Based Generative Models | [ICLR22](https://openreview.net/forum?id=vaRCHVj0uGI), [code](https://github.com/yang-song/score_inverse_problems) |

### PET

| Date    | First & Last Author           | Title                                                        | Paper & Code                                                 |
| ------- | ----------------------------- | ------------------------------------------------------------ | -----------------------------------------------------------|
| 2022.09 | Kuang Gong & Tinsu Pan        | PET image denoising based on denoising diffusion probabilistic models | [arxiv](https://arxiv.org/abs/2209.06167)                    |

## Image Translation

| Date    | First & Last Author                      | Title                                                        | Paper & Code                                                 |
| ------- | ---------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2022.09 | Qing Lyu & Ge Wang                       | Conversion Between CT and MRI Images Using Diffusion and Score-Matching Models | [arxiv](https://arxiv.org/abs/2209.12104)                    |
| 2022.07 | Muzaffer Özbey & Tolga Çukur             | Unsupervised Medical Image Translation with Adversarial Diffusion Models | [arxiv](https://arxiv.org/abs/2207.08208), [code](https://github.com/icon-lab/SynDiff) |
| 2022.04 | Julia Wolleb & Philippe C. Cattin        | The Swiss Army Knife for Image-to-Image Translation: Multi-Task Diffusion Models | [arxiv](https://arxiv.org/abs/2204.02641)                    |



## Detection

| Date    | First & Last Author                     | Title                                                        | Paper & Code                                                 |
| ------- | --------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2022.07 | Pedro Sanchez and Sotirios A. Tsaftaris | What is Healthy? Generative Counterfactual Diffusion for Lesion Localization | [MICCAI22-DGM](https://link.springer.com/chapter/10.1007/978-3-031-18576-2_4), [code](https://github.com/vios-s/Diff-SCM) |
| 2022.06 | Walter H. L. Pinaya & M. Jorge Cardos   | Fast Unsupervised Brain Anomaly Detection and Segmentation with Diffusion Models | [arxiv](https://arxiv.org/abs/2206.03461)                    |
| 2022.06 | Julian Wyatt & Chris G. Willcocks       | AnoDDPM: Anomaly Detection with Denoising Diffusion Probabilistic Models using Simplex Noise | [CVPR22 Workshop](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/html/Wyatt_AnoDDPM_Anomaly_Detection_With_Denoising_Diffusion_Probabilistic_Models_Using_Simplex_CVPRW_2022_paper.html), [code](https://github.com/Julian-Wyatt/AnoDDPM) |
| 2022.03 | Julia Wolleb & Philippe C. Cattin       | Diffusion Models for Medical Anomaly Detection               | [MICCAI22](https://link.springer.com/chapter/10.1007/978-3-031-16452-1_4), [code](https://github.com/JuliaWolleb/diffusion-anomaly) |




## Segmentation

| Date    | First & Last Author               | Title                                                        | Paper & Code                                                 |
| ------- | --------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2022.09 | Boah Kim & Jong Chul Ye           | Diffusion Adversarial Representation Learning for Self-supervised Vessel Segmentation | [arxiv](https://arxiv.org/abs/2209.14566)                    |
| 2021.06 | Julia Wolleb & Philippe C. Cattin | Diffusion Models for Implicit Image Segmentation Ensembles   | [MILD22](https://openreview.net/forum?id=QNLR05X6uW), [code](https://github.com/JuliaWolleb/Diffusion-based-Segmentation) |


## Miscellaneous
- [Awesome Diffusion Models](https://github.com/heejkoo/Awesome-Diffusion-Models)







# Awesome Dynamic NeRF with stars

Verified: Papers listed with \[+] have been verfied by myself or colleagues. The code is runnable. Please leave an issue if you need help on setting up.

# 1. Datasets

## Custom Data Preparation

* [Neural Scene Flow Fields](https://github.com/zhengqili/Neural-Scene-Flow-Fields/tree/main) ⭐ 740 | 🐛 23 | 🌐 Python | 📅 2022-07-15
  Instructions for custom data.
* [Robust Dynamic Radiance Fields](https://github.com/facebookresearch/robust-dynrf) ⚠️ Archived
  Estimate monocular depth, Predict optical flows, Obtain motion mask.
* [Monocular Dynamic View Synthesis: A Reality Check](https://github.com/KAIR-BAIR/dycheck/blob/main/docs/RECORD3D_CAPTURE.md) ⭐ 219 | 🐛 6 | 🌐 Python | 📅 2024-12-21
* [Process a video into a Nerfie dataset](https://colab.research.google.com/github/google/nerfies/blob/main/notebooks/Nerfies_Capture_Processing.ipynb)

### Synthetic

* [D-Nerf Dataset](https://www.albertpumarola.com/research/D-NeRF/index.html)

### Real

* [Nerfies Dataset](https://github.com/google/nerfies/releases/download/0.1/nerfies-vrig-dataset-v0.1.zip) ⚠️ Archived
* [Hypernerf Dataset](https://github.com/google/hypernerf/releases/tag/v0.1) ⚠️ Archived
* [Plenoptic Dataset](https://github.com/facebookresearch/Neural_3D_Video/releases/tag/v1.0) ⚠️ Archived
* [Dynamic NeRF](https://github.com/gaochen315/DynamicNeRF) ⭐ 251 | 🐛 8 | 🌐 Python | 📅 2022-04-22
  Balloon1, Balloon2, Jumping, Playground, Skating, Truck, Umbrella

# 2. My Notebooks

* Robust Dynamic Radiance Fields, Liu et. al., CVPR, 2023. \[[Kaggle](https://www.kaggle.com/code/declanide/robust-nerf)]

# 3. Papers

## 2026

* 4C4D: 4 Camera 4D Gaussian Splatting, CVPR 2026. [Code](https://github.com/yangzf-1023/4C4D) ⭐ 147 | 🐛 4 | 🌐 Python | 📅 2026-04-07
* Splannequin: Freezing monocular mannequin-challenge footage with dual-detection splatting, WACV 2026 [Page](https://chien90190.github.io/splannequin/), [Code](https://github.com/chien90190/splannequin-gs) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-01-02
* ClipGStream: Clip-Stream Gaussian Splatting for Any Length and Any Motion Multi-View Dynamic Scene Reconstruction, CVPR 2026. [Project](https://liangjie1999.github.io/ClipGStreamWeb/)

## 2025

* FreeTimeGS: Free Gaussian Primitives at Anytime Anywhere for Dynamic Scene Reconstruction, CVPR 2025. [Code](https://github.com/OpsiClear/FreeTimeGsVanilla) ⭐ 181 | 🐛 2 | 🌐 Python | 📅 2026-01-23

* Hybrid 3D-4D Gaussian Splatting for Fast Dynamic Scene Representation, 2025. [Code](https://github.com/ohsngjun/3D-4DGS) ⭐ 163 | 🐛 9 | 🌐 Python | 📅 2025-06-05

* 4dslomo: 4d reconstruction for high speed scene with asynchronous capture, Siggraph Asia 2025. [Code](https://github.com/OpenImagingLab/4DSloMo) ⭐ 140 | 🐛 6 | 🌐 Python | 📅 2025-10-27

* Adaptive and Temporally Consistent Gaussian Surfels for Multi-view Dynamic Reconstruction, WACV 2025. [Code](https://github.com/fraunhoferhhi/AT-GS) ⭐ 89 | 🐛 0 | 🌐 Python | 📅 2025-06-11

* DASH: 4D Hash Encoding with Self-Supervised Decomposition for Real-Time Dynamic Scene Rendering, ICCV 2025. [Code](https://github.com/chenj02/DASH) ⭐ 28 | 🐛 5 | 🌐 Python | 📅 2026-04-13

* 4K4DGen: Panoramic 4D Generation at 4K Resolution, ICLR 2025. [Code](https://github.com/ShadowIterator/4K4DGen) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2025-11-19

* 1000+ FPS 4D Gaussian Splatting for Dynamic Scene Rendering, 2025

## 2024

* Dynamic 3D Gaussians: Tracking by Persistent Dynamic View Synthesis, Luiten et. al., International Conference on 3D Vision (3DV), 2024. \[[Paper](https://dynamic3dgaussians.github.io/paper.pdf) | [Project Page](https://dynamic3dgaussians.github.io/) | [Code](https://github.com/JonathonLuiten/Dynamic3DGaussians) ⭐ 2,292 | 🐛 32 | 🌐 Python | 📅 2023-12-22 | [Explanation Video](https://www.youtube.com/live/hDuy1TgD8I4?si=6oGN0IYnPRxOibpg)]

* Shape of Motion: 4D Reconstruction from a Single Video, 2024. \[[Project](https://shape-of-motion.github.io/) | [Code](https://github.com/vye16/shape-of-motion/) ⭐ 1,302 | 🐛 58 | 🌐 Python | 📅 2025-08-02]

* \[+] Spacetime Gaussian Feature Splatting for Real-Time Dynamic View Synthesis, CVPR 2024. [Code](https://github.com/oppo-us-research/SpacetimeGaussians) ⭐ 831 | 🐛 53 | 🌐 Python | 📅 2025-03-30

* SC-GS: Sparse-Controlled Gaussian Splatting for Editable Dynamic Scenes. \[[Code](https://github.com/yihua7/SC-GS) ⭐ 648 | 🐛 32 | 🌐 Python | 📅 2025-06-27]

* Endo-4DGS: Endoscopic Monocular Scene Reconstruction with 4D Gaussian Splatting, \[[Paper](https://arxiv.org/abs/2401.16416) | [Code](https://github.com/lastbasket/Endo-4DGS) ⭐ 107 | 🐛 9 | 🌐 Python | 📅 2025-08-30]

* Sync-NeRF : Generalizing Dynamic NeRFs to Unsynchronized Videos, AAAI 2024. \[[Paper](https://arxiv.org/abs/2310.13356), [Code](https://github.com/seoha-kim/Sync-NeRF) ⭐ 60 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-11-29]

* Sync-NeRF: Generalizing Dynamic NeRFs to Unsynchronized Videos, AAAI2024. \[[Code](https://github.com/seoha-kim/Sync-NeRF) ⭐ 60 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-11-29]

* Evdnerf: Reconstructing event data with dynamic neural radiance fields, WACV 2024. [Code](https://github.com/anish-bhattacharya/EvDNeRF) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2024-08-08

* CTNeRF: Cross-time Transformer for dynamic neural radiance field from monocular video, Pattern Recognition, 2024. [Code](https://github.com/xingy038/ctnerf) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2024-07-16

* DynamicSurf: Dynamic Neural RGB-D Surface Reconstruction with an Optimizable Feature Grid, International Conference on 3D Vision (3DV) 2024. [Code](https://github.com/Mirgahney/dynsurf) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2023-11-27

* DaReNeRF: Direction-aware Representation for Dynamic Scenes, CVPR 2024

* InstantSplat: Unbounded Sparse-view Pose-free Gaussian Splatting in 40 Seconds, [Project](https://instantsplat.github.io/)

* GaussianFlow: Splatting Gaussian Dynamics for 4D Content Creation

* Entity-NeRF: Detecting and Removing Moving Entities in Urban Scenes, CVPR 2024. [Project](https://otonari726.github.io/entitynerf/)

* Ced-NeRF: A Compact and Efficient Method for Dynamic Neural Radiance Fields, AAAI 2024. [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28138)

* MoSca: Dynamic Gaussian Fusion from Casual Videos via 4D Motion Scaffolds, 2024. [Project](https://www.cis.upenn.edu/~leijh/projects/mosca/)

* Dynamic Gaussian Marbles for Novel View Synthesis of Casual Monocular Videos, 2024

* Dynamic Gaussian Mesh: Consistent Mesh Reconstruction from Monocular Videos, 2024. [Project](https://www.liuisabella.com/DG-Mesh/)

* DyNeRFactor: Temporally consistent intrinsic scene decomposition for dynamic NeRFs, 2024. [Paper](https://www.sciencedirect.com/science/article/pii/S0097849324001195?dgcid=rss_sd_all)

* DynVideo-E: Harnessing Dynamic NeRF for Large-Scale Motion- and View-Change Human-Centric Video Editing, CVPR 2024. [Project](https://showlab.github.io/DynVideo-E/)

* Point-DynRF: Point-Based Dynamic Radiance Fields From a Monocular Video, WACV 2024. [Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Park_Point-DynRF_Point-Based_Dynamic_Radiance_Fields_From_a_Monocular_Video_WACV_2024_paper.pdf)

* FPO++: efficient encoding and rendering of dynamic neural radiance fields by analyzing and enhancing Fourier PlenOctrees, The Visual Computer, 2024.

## 2023

* Deformable 3D Gaussians for High-Fidelity Monocular Dynamic Scene Reconstruction, Yang et. al., ACM Transactions on Graphics, 2023. \[[Paper](https://arxiv.org/pdf/2309.13101.pdf) | [Project Page](https://ingra14m.github.io/Deformable-Gaussians/) | [Code](https://github.com/ingra14m/Deformable-3D-Gaussians) ⭐ 1,255 | 🐛 64 | 🌐 Python | 📅 2024-06-25]
* HyperReel: High-Fidelity 6-DoF Video with Ray-Conditioned Sampling, CVPR 2023 (Highlight). [Code](https://github.com/facebookresearch/hyperreel) ⭐ 481 | 🐛 11 | 🌐 Python | 📅 2025-02-12
* HexPlane: A Fast Representation for Dynamic Scenes, Cao et. al., CVPR, 2023. \[[Paper](https://caoang327.github.io/HexPlane/HexPlane.pdf) | [Project Page](https://caoang327.github.io/HexPlane/) | [Code](https://github.com/Caoang327/HexPlane) ⭐ 312 | 🐛 7 | 🌐 Python | 📅 2024-02-06]
* Robust Dynamic Radiance Fields, Liu et. al., CVPR, 2023. \[[Code](https://github.com/facebookresearch/robust-dynrf) ⚠️ Archived | [Kaggle](https://www.kaggle.com/code/declanide/robust-nerf)]
* Tensor4D : Efficient Neural 4D Decomposition for High-fidelity Dynamic Reconstruction and Rendering, Shao et. al., CVPR, 2023. \[[Paper](https://arxiv.org/abs/2211.11610) | [Code](https://github.com/DSaurus/Tensor4D) ⭐ 231 | 🐛 12 | 🌐 Python | 📅 2023-06-03]
* Dynamic Mesh-Aware Radiance Fields, ICCV, 2023. \[[Project Page](https://mesh-aware-rf.github.io/) | [Code](https://github.com/YilingQiao/DMRF) ⭐ 179 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2024-02-28]
* MixVoxels: Mixed Neural Voxels for Fast Multi-view Video Synthesis, ICCV2023 Oral. [Code](https://github.com/fengres/mixvoxels) ⭐ 175 | 🐛 7 | 🌐 Python | 📅 2023-08-16
* NeRFPlayer: A Streamable Dynamic Scene Representation with Decomposed Neural Radiance Fields, IEEE Transactions on Visualization and Computer Graphics, vol 29(5), 2023. \[[Code](https://github.com/lsongx/nerfplayer-nerfstudio) ⭐ 53 | 🐛 5 | 🌐 Python | 📅 2024-11-03]
* V4D: Voxel for 4D Novel View Synthesis, Gan et. al., IEEE Transactions on Visualization and Computer Graphics, 2023. \[[Paper](https://arxiv.org/abs/2205.14332) | [Code](https://github.com/GANWANSHUI/V4D) ⭐ 33 | 🐛 0 | 🌐 Python | 📅 2023-10-11] (instructions for custom data)
* V4d: Voxel for 4d novel view synthesis, Gan et. al., IEEE Transactions on Visualization and Computer Graphics, 2023. \[[Code](https://github.com/GANWANSHUI/V4D) ⭐ 33 | 🐛 0 | 🌐 Python | 📅 2023-10-11]
* DynIBaR: Neural Dynamic Image-Based Rendering, CVPR, 2023 \[[Project Page](https://dynibar.github.io/)]
* DynPoint: Dynamic Neural Point For View Synthesis, NeurIPS 2023.

## 2022

* TiNeuVox: Fast Dynamic Radiance Fields with Time-Aware Neural Voxels, Fang et. al., ACM SIGGRAPH Asia 2022. \[[Project Page](https://jaminfong.cn/tineuvox/) | [Code](https://github.com/hustvl/TiNeuVox) ⭐ 351 | 🐛 6 | 🌐 Python | 📅 2023-05-11]
* D2NeRF: Self-Supervised Decoupling of Dynamic and Static Objects from a Monocular Video, NeurIPS, 2022. \[[Project Page](https://d2nerf.github.io/) | [Code](https://github.com/ChikaYan/d2nerf) ⭐ 192 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2023-08-12]
* Fourier PlenOctrees for Dynamic Radiance Field Rendering in Real-time, CVPR 2022 \[[Project Page](https://aoliao12138.github.io/FPO/)]
* Monocular Dynamic View Synthesis: A Reality Check, Gao et. al., Neurips 2022. \[[Project Page](https://hangg7.com/dycheck/)]
* Fourier PlenOctrees for Dynamic Radiance Field Rendering in Real-time, CVPR 2022. [Project](https://aoliao12138.github.io/FPO/)

## 2021

* Nerfies: Deformable Neural Radiance Fields, ICCV, 2021. \[[Code](https://github.com/google/nerfies) ⚠️ Archived] (instructions for **custom data**, this is the one everyone refering to)
* HyperNeRF: A Higher-Dimensional Representation for Topologically Varying Neural Radiance Fields, ACM Trans. Graph, 2021. \[[Code](https://github.com/google/hyperNeRF) ⚠️ Archived | [Project Page](https://hypernerf.github.io/) | [Colab](./colabs/HyperNerf.ipynb)] (instructions for custom data)
* BARF: Bundle-Adjusting Neural Radiance Fields, Lin et. al., ICCV 2021 (Oral). \[[Code](https://github.com/chenhsuanlin/bundle-adjusting-NeRF) ⭐ 823 | 🐛 16 | 🌐 Python | 📅 2023-04-28]
* Dynamic View Synthesis from Dynamic Monocular Video, ICCV, 2021. \[[Code](https://github.com/gaochen315/DynamicNeRF) ⭐ 251 | 🐛 8 | 🌐 Python | 📅 2022-04-22]

## 2020

* D-NeRF: Neural Radiance Fields for Dynamic Scenes, Pumarola et. al, CVPR 2020. \[[Project Page](https://www.albertpumarola.com/research/D-NeRF/index.html) | [Code](https://github.com/albertpumarola/D-NeRF) ⭐ 592 | 🐛 15 | 🌐 Jupyter Notebook | 📅 2024-01-26]

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-30._

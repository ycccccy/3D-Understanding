<div align="center">
    <h1 style="display: inline-flex; align-items: center;">
        Awesome LLMs for 3D Scene Understanding
    </h1>
</div>
This document summarizes cutting-edge research on 3D scene understanding and foundation models, covering innovative frameworks, datasets, and benchmarks for enhanced spatial reasoning. This document will be continuously updated.


## 📖 News
**[2026/01/04]** Release 3D Scene understanding and 3D foundation model methods.

## 🌟 Overview

- [📖 3D Scene Understanding](#3d-scene-understanding)
- [🌟 3D Foundation Model](#-3D-Foundation-Model)


## 🌟 3D Scene Understanding
| Method (Pub.) | Paper | Input | Framework | Data | Project |
|---------------|-------|-------|-----------|------|---------|
| **S²-MLLM (2025-12)** | [S²-MLLM: Boosting Spatial Reasoning Capability of MLLMs for 3D Visual Grounding with Structural Guidance](https://arxiv.org/pdf/2512.01223) | Multi-view RGB / Text Depth / Point map/ Ray| — | ScanRefer / Nr3D / Sr3D / Multiscan / ArkiScenes | |
| **SpaceDrive (2025-12)** | [SpaceDrive: Infusing Spatial Awareness into VLM-based Autonomous Driving](https://arxiv.org/abs/2512.10719v1) | Multi-view RGB / Depth / 3D position / Text | — | nuScenes / Bench2Drive | https://zhenghao2519.github.io/SpaceDrive_Page/ |
| **DSR (2025-12)** | [Learning to Reason in 4D: Dynamic Spatial Reasoning for Vision-Language Models](https://arxiv.org/abs/2512.20557) | RGB video / Text /Poses / Masks / Agent| — | DSR-Bench| https://github.com/TencentARC/DSR_Suite |
| **VLM² (2025-11)** | [Vision-Language Model with Memory for Spatial Reasoning in 3D Found](https://arxiv.org/abs/2511.20644) | RGB video / Text | — | VSI-Bench / VSTI-Bench / ScanQA / SQA3D | https://vlm2-memory.github.io |
| **SpaceMind (2025-11)** | [SpaceMind: Camera-Guided Modality Fusion for Spatial Reasoning in Vision-Language Models](https://arxiv.org/abs/2511.23075) |-- | — | VSI-Bench / SQA3D / SPBench | https://spacemind.github.io |
| **3DThinker (2025-10)** | [Think with 3D: Geometric Imagination Grounded Spatial Reasoning from Limited Views](https://arxiv.org/abs/2510.18632) | RGB Images / Text /3D Features| — | MindCube-Tiny / Ego3D-Bench / VSI-Bench / SPBench / CV-Bench / SPAR-Bench / ViewSpatialBench / MMSI-Bench | https://3dthinker.github.io |
| **SpaceVista-7B (2025-10)** | [SPACEVISTA: CALL-SCALE VISUAL SPATIAL REASONING FROM mm TO km](https://arxiv.org/abs/2510.09606) | RGB video / Text | — | SpaceVista | https://spacevista.github.io |
| **SR-3D (2025-09)** | [SR-3D: Spatial Region 3D Aware Vision-Language Model](https://arxiv.org/abs/2509.13317) |  | — | Scan2Cap / ScanQA / SQA3D / BLINK / COCO2017 / SR-3D-Bench / VSI-Bench | https://sr-3d.github.io |
| **SD-VLM (2025-09)** | [SD-VLM: Spatial Measuring and Understanding with Depth-Encoded Vision-Language Models](https://arxiv.org/abs/2509.17664) | RGB / Depth / Text | — | MSMU-Bench / Q-Spatial++ / SpatialRGPT-Bench / Whatsup / GQA / TextVQA / VQA-v2 / Vizwiz | https://github.com/cpystan/SD-VLM |
| **RynnEC (2025-08)** | [RynnEC: Bringing MLLMs into Embodied World](https://arxiv.org/abs/2508.14160) | Video / Text / Masks| — | RynnEC-Bench | https://github.com/alibaba-damo-academy/RynnEC |
| **3D-R1 (2025-07)** | [3D-R1: Enhancing Reasoning in 3D VLMs for Unified Scene Understanding](https://arxiv.org/abs/2507.23478) | RGB-D / Text / Point map | — | ScanRefer / Nr3D / ScanQA / Cap3D / 3D-LLM / SQA3D | https://3d-r1.github.io |
| **RoboRefer (2025-06)** | [RoboRefer: Towards Spatial Referring with Reasoning in Vision-Language Models for Robotics](https://arxiv.org/pdf/2506.04308) | RGB-D / Text | — | CV-Bench / BLINK / RoboSpatial / SAT / EmbSpatial / RoboRefIt / Where2Place  / RoboSpatial / RefCOCO  / RefCOCO+  / RefCOCOg / NVILA-2B  / RoboRefer | https://roborefer.github.io |
| **3DRS (2025-06)** | [MLLMs Need 3D-Aware Representation Supervision for Scene Understanding](https://arxiv.org/abs/2506.01946) | Images / Text / 3D Features | — | Multi3DRef / ScanRefer3D / Scan2Cap / ScanQA / SQA3D | https://visual-ai.github.io/3drs |
| **Scene-R1 (2025-06)** | [Scene-R1: VIDEO-GROUNDED LARGE LANGUAGE MODELS FOR 3D SCENE REASONING WITHOUT 3D ANNOTATIONS](https://arxiv.org/abs/2506.17545) |  | — | ScanRefer / VSI-Bench | https://scene-r1.github.io |
| **SpatialLM (2025-06)** | [SpatialLM: Training Large Language Models for Structured Indoor Modeling](https://arxiv.org/abs/2506.07491) |  | — | ScanNet \ Layout Estimation \ 3D Object Detection | https://spatiallm.github.io |
| **SSR (2025-05)** | [SSR: Enhancing Depth Perception in Vision-Language Models via Rational-e-Guided Spatial Reasoning](https://arxiv.org/abs/2505.12448) | RGB / Depth /Text | — | SpatialBench / SSRBENCH / CV-Bench / VQA  | https://yliu-cs.github.io/SSR |
| **Spatial-MLLM (2025-05)** | [Spatial-MLLM: Boosting MLLM Capabilities in Visual-based Spatial Intelligence from Pure 2D Observations](https://arxiv.org/abs/2505.23747) | RGB (images or video) / Text | — | Spatial-MLLM-120k / VSI-Bench / SQA3D / SPBench / Q-Spatial | https://spatial-mllm.github.io |
| **SAMA (2025-05)** | [SAMA: Towards Multi-Turn Referential Grounded Video Chat with Large Language Models](https://arxiv.org/abs/2505.18812) | video / Text / Masks | — | SAMA-Bench / RefCOCO / RefCOCO+ / RefCOCOg / GCG  / MeViS / Ref-DAVIS17 / Ref-YTVOS / ReVOS / MME / MMBench  / SEED-Benc / AI2D  / MMStar / SQA / Video-MME | https://sama-benchmark.github.io |
| **ViewSpatial-Bench (2025-05)** | [ViewSpatial-Bench: Evaluating Multi-perspective Spatial Localization in Vision-Language Models](https://arxiv.org/abs/2505.21500) |  | — | ViewSpatial-Bench / VSI-Bench / VSI-App | https://viewspatial-bench.github.io 


## 🌙 3D Foundation Model
| Method (Pub.) | Paper | Framework | Data | Project |
|---------------|-------|-----------|------|---------|
| **Depth Anything 3 (2025-11)** | [Depth Anything 3: Recovering the Visual Space from Any Views](https://arxiv.org/abs/2511.10647) | — | HiRoom / ETH3D / DTU / 7Scenes / ScanNet++ | https://depth-anything-3.github.io |
| **STream3R (2025-08)** | [STream3R: Scalable Sequential 3D Reconstruction with Causal Transformer](https://arxiv.org/abs/2508.10893) | — | Sintel  / Bonn / KITTI / NYU-v2 / TUM-dynamics  / ScanNet | https://stream3r.github.io |
| **Uni3R (2025-08)** | [Uni3R: Unposed 3D Reconstruction and Semantic Understanding via Gaussian Splatting](https://arxiv.org/abs/2508.03643) | — | ScanNet | https://uni3r.github.io |
| **VGGT-Long (2025-07)** | [VGGT-Long: Pushing VGGT’s Limits on Kilometer-scale RGB Sequences](https://arxiv.org/abs/2507.16443) | — | KITTI / Waymo / Virtual KITTI | https://github.com/DengKaiCQ/VGGT-Long |
| **StreamVGGT (2025-07)** | [Streaming 4D Visual Geometry Transformer](https://arxiv.org/abs/2507.11539) | — | 7-Scenes / NRGBD / KITTI / Sintel / Bonn / NYU-v2 / Sintel| https://github.com/wzzheng/StreamVGGT |
| **Dens3R (2025-07)** | [Dens3R: A Foundation Model for 3D Geometry Prediction](https://arxiv.org/abs/2507.16290) | — | NYUv2  / ScanNet / IBims-1  / Sintel / DIODE-outdoor / ZEB | https://dens3r.github.io |
| **VGGT (2025-03)** | [VGGT: Visual Geometry Grounded Transformer](https://arxiv.org/abs/2503.11651) | — | Re10K / CO3Dv2 / RealEstate10K / DTU / ETH3D / ScanNet-1500  / GSO / TAP-Vid | https://vggt.github.io |
| **Fast3R (2025-01)** | [Fast3R: Towards 3D Reconstruction of 1000+ Images in One Forward Pass](https://arxiv.org/abs/2501.13928) | — | CO3D-v2 / RealEstate10K / 7 Scenes / Mip-NeRF 360 | https://fast3r.github.io |
| **CUT3R (2025-01)** | [CUT3R: Continuous Updating Transformer for 3D Reconstruction](https://arxiv.org/abs/2501.12387) | — | Sintel  / Bonn / KITTI / NYU-v2 / TUM-dynamics  / ScanNet / 7 scenes / NRGBD | https://cut3r.github.io |
| **DUSt3R (2023-12)** | [DUSt3R: Geometric 3D Vision Made Easy](https://arxiv.org/abs/2312.14132) | — | 7Scenes / Cambridge  / KITTI / ScanNet / ETH3D / DTU / T&T | https://dust3r.github.io |

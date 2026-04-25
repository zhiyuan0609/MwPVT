<img width="430" height="70" alt="image" src="https://github.com/user-attachments/assets/e5714072-c328-49ac-a273-273b7a5a2816" /># 📌 MwPVT：Multi-window Parallel Voxel Transformer with Center Optimization Strategy for 3D Object Detection
![](https://github.com/zhiyuan0609/MwPVT/blob/main/figures/2.png)
MwPVT processes point clouds by first extracting group sampling features through a Group Sampling Strategy, then employs GSF modules for local geometry extraction and the GLF Block with PVA/GLA attention for multi-scale feature enhancement. This approach effectively expands the receptive field while capturing comprehensive geometric structure information.💥
# 👉 NOTE
This repo is implementation for MwPVT in pytorch. Our paper is accepted at Artificial Life and Robotics.🔥
# 🌀 Introduction
MwPVT is a novel multi‑window parallel voxel transformer with a center optimization strategy for 3D point cloud detection. It addresses the loss of local details and multi‑scale limitations in single‑sampling methods by using a multi‑scale cross‑attention module with parallel self‑attention and multi‑window sampling, enhanced by positional encoding. A center optimization strategy generates multiple candidate centers from high‑confidence keypoints and refines them via confidence‑weighted averaging, improving localization accuracy in sparse or occluded scenes.🚀

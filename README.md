# 📸 panorama-Equirectangular-3DGS-benchmark

提供全景图像数据及其 全景的COLMAP 稀疏模型，同时包含切分后的 pinhole 图像及其稀疏模型，便于 3DGS 研究者快速上手实验与评估。

---

## 🎯 目的

本仓库的主要目标是：

- 📦 提供本人采集的全部全景图像数据  
- 🛠️ 基于 [vismap] 处理好的全景 SfM（Structure from Motion）结果  
- 🔍 同时提供将全景图切分为 pinhole 模型图像的工具和对应的稀疏模型  
- 🤝 方便 3DGS（Gaussian Splatting 等）社区研究人员快速开展实验与对比分析  

---

## 📁 数据内容

- 🌐 全景图像（equirectangular 格式）  
- 🗺️ COLMAP 稀疏模型（全景图对应）  
- 🖼️ 切分后的 pinhole 图像（来自全景）  
- 🧠 对应的 COLMAP 稀疏模型（pinhole 模型）  

---

## 🚀 使用方式

1. 下载对应数据集
2. 可直接用于 3DGS、NeRF、Splatting 等方法训练与评估

---

## 🤗 欢迎贡献

如果你也有类似的数据并愿意共享，欢迎提 PR 或联系我一起完善这个 benchmark！

---


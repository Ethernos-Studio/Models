# AE-RVC-008

AE-SVS-008包含TogawaSakiko-Special RVC模型的一个版本和变体：
- R2-TS-S-F (e100, e200, e250, e300, Best)

包含TogawaSakiko-Special RVC模型的索引文件:
- added_IVF329_Flat_nprobe_1_R2-TS-S-F_v2

训练模型所使用的声源均来自提供者版权所有，所涉及的声源均为其各自所有者的资产，仅供识别。

## 基本信息

声源获取：PRTS Wiki
训练软件平台：RVC
算力平台: AutoDL

## 设备：
- CPU: `16 vCPU Intel(R) Xeon(R) Platinum 8358P CPU @ 2.60GHz`
- GPU:
  - 0: `NVIDIA GeForce RTX 4090 GPU (24GB)`
- OS: `Ubuntu 22.04`

## 模型详情:
1. R2-TS-S-F:
   - 采样率:40k
   - 模型是否输入音高引导:1
   - 版本:v2

## 训练端镜像信息:
 - RVC-Project/Retrieval-based-Voice-Conversion-WebUI/RVC20231226
 - 镜像版本: v12
 - 框架:PyTorch: 2.4
 - 芯片: NVIDIA
 - CPU架构: x86_64
 - CUDA:12.1

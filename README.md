# 我的主页: https://stupid-boy-me.github.io/
# Huang Yiguo Portfolio

自动驾驶感知方向｜车道线感知｜量化部署｜训练验证

## 代表项目

### 1. 车道线感知算法开发与稳定性优化
![预览](assets/gifs/lane_demo.gif)

- 解决问题：抖动、跳变、遮挡、弯道不稳定
- 关键方法：几何后处理 + 多帧滤波 + 卡尔曼 + 异常剔除
- [查看项目详情](docs/lane_detail.md)

### 2. 基于 ONNX 的 INT8 量化与部署优化
![预览](assets/images/quant_pipeline.png)

- 解决问题：量化掉点、敏感层、加速不明显
- 关键方法：PPQ PTQ + calibration + layerwise/graphwise 分析
- [查看项目详情](docs/quant_detail.md)

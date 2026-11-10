# Dataset B: UAV Aerial Person Detection Dataset for Generalization Validation（数据集B：无人机航拍人体检测泛化性验证数据集）

## Overview | 简介

**EN**: Dataset B is a self-constructed UAV aerial dataset for validating the cross-sample generalization ability of detection models. It contains 100 UAV aerial images at 800×800 resolution with 414 person annotations (single class: person). Flight altitudes, scenes, and disturbance types are consistent with Dataset A. It shares no samples with Dataset A and was collected in different environments.

**中文**：数据集B为自研无人机航拍数据集，用于验证模型的跨样本泛化能力。数据集包含100张800×800分辨率的航拍图像，共414个人体目标标注（单类：person）。飞行高度、场景、干扰类型与数据集A保持一致，与数据集A无重复样本且为不同环境下采集。

## Statistics | 数据统计

- Total images | 图像总数: 100 (800×800)
- Person annotations | 人体目标标注: 414 (single class: person | 单类：person)
- Purpose | 用途: cross-sample generalization validation | 跨样本泛化性验证

## Collection | 数据采集

**EN**: Images were captured by a DJI Flip UAV and extracted from aerial video, with flight altitudes consistent with Dataset A (65–80 m and 100–120 m). Scenes, and disturbance types (rain, fog, strong light, low light, Gaussian noise) are also consistent with Dataset A.

**中文**：图像由大疆 Flip 无人机拍摄视频抽帧获取，飞行高度与数据集A一致（65–80米、100–120米），场景与干扰类型（雨、雾、强光、暗光、高斯噪声）亦与数据集A保持一致。

## Annotation Format | 标注格式

**EN**: Annotations follow the YOLO format: one `.txt` file per image, single class `person` (class_id = 0). Note: this repository releases **images only**; annotations are available upon reasonable request (contact: [待填]).

**中文**：标注采用 YOLO 格式，每张图像对应一个 `.txt` 标签文件，单类 `person`（class_id = 0）。注意：本仓库仅发布图像，标注可通过合理申请联系作者获取（联系方式：[待填]）。

## Dataset Structure | 目录结构

```
images/
└── B1.jpg – B100.jpg
```

## Intended Use | 用途说明

**EN**: This dataset is released for academic research only.

**中文**：本数据集仅用于学术研究。

## License | 许可证

**EN**: This dataset is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) (Attribution-NonCommercial 4.0 International). You are free to use, share, and adapt this dataset for non-commercial purposes, provided that appropriate attribution is given. See the [LICENSE](LICENSE) file for the full license text.

**中文**：本数据集采用 [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)（署名-非商业性使用 4.0 国际）许可协议发布。任何人可在非商业目的下自由使用、共享和修改本数据集，但须注明来源与作者。完整许可文本见 [LICENSE](LICENSE) 文件。

## Citation | 引用

[待论文录用后填写 BibTeX]

## Authors & Contact | 作者与联系方式

[待填]

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=CHAOZHAO-1.HUSTmotor-multi-modal-dataset)

We released an open-source multimodal motor failure dataset.
我们发布了一个开源的多模态电机故障数据集。

We hope this dataset can benefit your research.
希望该数据集能对您的研究有所帮助。

Data of Google Drive / Google Drive 数据: https://drive.google.com/drive/folders/1XmahwIQ4o66FC3dpOaeTV-gqz2dd0XBw?usp=sharing

Data of Quark Netdisk / 夸克网盘数据: https://pan.quark.cn/s/5366b229f134

## Update 2026-10-29 / 更新（2026-10-29）

Files for the same fault class at 5, 10, 20, and 30 Hz come from the same motor.
同一故障类别在 5、10、20、30 Hz 下的文件来自同一台电机。

Each "class × speed" combination is an independent acquisition. The time blocks within a file are part of the result of a single acquisition.
每个"类别×转速"组合都是一次独立采集。文件内的各时间块属于同一次采集的结果。

The speed in the file name is the motor's set value.
文件名中的转速为电机的设定值。

**The following is a brief introduction to the dataset. For more detailed information, please refer to the dataset description file.**
**以下为数据集的简要介绍，更详细的信息请参阅数据集说明文件。**

## Dataset overview / 数据集概述

This dataset comprises vibration signals and acoustic signals from motors in **6** different health states under **4** distinct operating conditions.
本数据集包含电机在 **4** 种不同工况下、**6** 种健康状态的振动信号和声信号。

These datasets are publicly available, and anyone can use them to validate diagnosis algorithms.
这些数据集已公开，任何人均可使用它们来验证诊断算法。

Publications making use of the HUSTmotor multimodal datasets are requested to cite the following paper.
使用 HUSTmotor 多模态数据集发表成果的研究者，请引用以下论文：

**Chao Zhao, Weiming Shen, Enrico Zio, Hui Ma, Multimodal unified generalization and translation network for intelligent fault diagnosis under dynamic environments. Engineering Applications of Artificial Intelligence, Volume 162, Part C, 2025, 112559.**

![image](https://github.com/CHAOZHAO-1/HUSTmotor-multi-modal-dataset/blob/main/IMG/F4.png)

Fig. 1. (a) Test rig of HUSTmotor Multimodal dataset.
图 1. (a) HUSTmotor 多模态数据集的试验台。

## Brief introduction to experiments / 实验简介

### Motor testbed / 电机试验台

The Motor fault tests were conducted using a Spectra-Quest Mechanical Fault Simulator, as depicted in Fig. 1.
电机故障试验在 Spectra-Quest 机械故障模拟器上进行，如图 1 所示。

The motors in six health states include:
电机的六种健康状态包括：

(1) healthy / 健康 ---- H  
(2) bearing fault / 轴承故障 ---- BF  
(3) bowed rotor / 转子弯曲 ---- BOW  
(4) broken rotor bars / 转子断条 ---- BROKEN  
(5) rotor misalignment / 转子不对中 ---- MISAL  
(6) voltage unbalance / 电压不平衡 ---- UNBAL  

It's important to note that all faults are artificially preset.
需要说明的是，所有故障均为人工预置。

### Operating Condition / 工况

A total of 4 different operating conditions were set in experiments. The operating conditions include:
实验共设置了 4 种不同工况，包括：

1) 5 Hz  
2) 10 Hz  
3) 20 Hz  
4) 30 Hz  

### Sampling setting / 采样设置

The sampling frequency is set to 25.6 kHz. A total of 163840 data points (i.e. 6.4 s) are recorded for each sampling.
采样频率设为 25.6 kHz，每次采样共记录 163840 个数据点（即 6.4 s）。

## Dataset details / 数据集详情

The raw data file comprises 24 files (6 health states × 4 working conditions), each in txt format.
原始数据共包含 24 个文件（6 种健康状态 × 4 种工况），均为 txt 格式。

For instance, the filename "H_5HZ" indicates a healthy motor under the 5 Hz working condition.
例如，文件名"H_5HZ"表示 5 Hz 工况下的健康电机。

The health states are represented by the following codes:
健康状态的代码如下：

H: healthy / 健康  
BF: bearing fault / 轴承故障  
BOW: bowed rotor / 转子弯曲  
BROKEN: broken rotor bars / 转子断条  
MISAL: rotor misalignment / 转子不对中  
UNBAL: voltage unbalance / 电压不平衡  

## Contact / 联系方式

If you have any questions or suggestions, do not hesitate to contact:
如有任何问题或建议，请随时联系：

Mr. Chao Zhao / 赵超, zhaochao0612@gmail.com

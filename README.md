We released an open-source multimodal motor failure dataset. 

We hope this dataset can benefit your research.

Data of Google Drive: https://drive.google.com/drive/folders/1XmahwIQ4o66FC3dpOaeTV-gqz2dd0XBw?usp=sharing

Data of Quark Netdisk:  https://pan.quark.cn/s/61c75de606e8




**The following is a brief introduction to the dataset. For more detailed information, please refer to the dataset description file.**



## Dataset overview


This dataset comprises vibration signals and acoustic signals from motors in **6** different health states under **4** distinct operating conditions.   

These datasets are publicly available, and anyone can use them to validate diagnosis algorithms.   

Publications making use of the HUSTmotor multimodal datasets are requested to cite the following paper.  



**Chao Zhao, Weiming Shen, Enrico Zio, Hui Ma, Multimodal unified generalization and translation network for intelligent fault diagnosis under dynamic environments. Engineering Applications of Artificial Intelligence, Volume 162, Part C, 2025, 112559.**



![image](https://github.com/CHAOZHAO-1/HUSTmotor-multi-modal-dataset/blob/main/IMG/F4.png)


Fig. 1. (a) Test rig of HUSTmotor Multimodal dataset.

## Brief introduction to experiments

###	Motor testbed

The Motor fault tests were conducted using a Spectra-Quest Mechanical Fault Simulator, as depicted in Fig. 1

The motors in six health states includes:

(1) healthy----H   
(2) bearing fault----BF  
(3) bowed rotor----BOW  
(4) broken rotor bars----BROKEN  
(5) rotor misalignment----MISAL  
(6) voltage unbalance----UNBAL  

It's important to note that all faults are artificially preset.

### Operating Condition

A total of 4 different operating conditions were set in experiments. The operating conditions include:

1) 5 Hz  
2) 10 Hz  
3) 20 Hz  
4) 30 Hz  


### Sampling setting
   
The sampling frequency is set to 25.6 kHz. A total of 163840 data points (i.e. 6.4s) are recorded for each sampling.
 

## Dataset details

The raw data file comprises 24 files (6 health states multiplied by 4 working conditions), each in txt format.

For instance, the filename "H_5HZ" indicates a healthy motor under the 5 Hz working condition.

The health states are represented by the following codes:

H: healthy

BF: bearing fault

BOW: bowed rotor

BROKEN: broken rotor bars

MISAL: rotor misalignment

UNBAL: voltage unbalance


## Contact

If you have any questions or suggestions, do not hesitate to contact: 

Mr. Chao Zhao, zhaochao0612@gmail.com


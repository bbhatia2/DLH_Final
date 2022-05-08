# adversarial_seizure_detection
## Title: Adversarial representation learning for robust patient-independent epileptic seizure detection 
Bahaar B & Akarsh B
Group 28
Paper ID 302

Link to paper: https://arxiv.org/pdf/1909.10868.pdf
Original github code: https://github.com/xiangzhang1015/adversarial_seizure_detection/blob/master/main.py
Our Google Colab Link: https://colab.research.google.com/drive/11oV2X34BYDPcpVYbxPJUmhOczPhyeFJp?usp=sharing

PDF File contains our results and outputs (last two cells outputs). A screenshot is provided here below for convenience as well.
<img width="937" alt="image" src="https://user-images.githubusercontent.com/43009733/167318688-4c57b8f2-976c-411e-8d09-9e8b97213f60.png">
Accuracies at 50, 70, and 80 iterations

## Citiation

    @article{zhang2020adversarial,
      title={Adversarial representation learning for robust patient-independent epileptic seizure detection},
      author={Zhang, Xiang and Yao, Lina and Dong, Manqing and Liu, Zhe and Zhang, Yu and Li, Yong},
      journal={IEEE journal of biomedical and health informatics},
      volume={24},
      number={10},
      pages={2852--2859},
      year={2020},
      publisher={IEEE}
    }

## Changes to code & Dependencies
We used Google Colab to reproduce the paper. The github repo is generated from that. 

The following changes were made to the code:
1. We added Tensorflow 1.x to the first cell where libraries are imported for version control. 
2. Session was disabled to match tensorflow version control in the last cell where tf.v1.compact.placeholder is used.
3. We changed the number of steps (variable) in the last cell for training model due to limitations in computational feasibility. Now we use 81 epochs.

## Dataset
The cleaned dataset can be found by emailing the author. The author has mentioned to clean the data ourselves and paper does not mention specifics of how to clean data. Upon emailing author, he sent us the cleaned dataset (https://drive.google.com/file/d/14TqgvWHvWuxQU2egEcgSR3_AsvQNgVYr/view); however, the original dataset is Temple University Hospital Database (EEG corpus)

## Steps to run code & Data Download Instructions
1. Download dataset to Drive on Google Colab
2. Put path to drive in root dir
3. Change factory run time to GPU (Runtime > change runtime type > GPU)
4. Run cells to run preprocessing, training, and evaluation code
5. Last cell has our results



**Authors: Bahaar B, Akarsh B**


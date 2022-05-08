# DLH_Final

Link to paper: https://arxiv.org/pdf/1909.10868.pdf
Original github code: https://github.com/xiangzhang1015/adversarial_seizure_detection/blob/master/main.py

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

We used Google Colab to reproduce the paper. The github repo is generated from that. 

The following changes were made to the code:
1. We added Tensorflow 1.x to the first cell where libraries are imported for version control. 
2. Session was disabled to match tensorflow version control in the last cell where tf.v1.compact.placeholder is used.
3. We changed the number of steps (variable) in the last cell for training model due to limitations in computational feasibility. Previously, it was 51. Now we use 7 - 3 of which are for training.


The cleaned dataset can be found by emailing the author. The author has mentioned to clean the data ourselves and paper does not mention specifics of how to clean data. Upon emailing author, he sent us the cleaned dataset; however, the original dataset is Temple University Hospital Database (EEG corpus)

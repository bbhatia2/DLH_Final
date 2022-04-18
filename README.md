# DLH_Final

Link to paper: https://arxiv.org/pdf/1909.10868.pdf
Original github code: https://github.com/xiangzhang1015/adversarial_seizure_detection/blob/master/main.py

We used Google Colab to reproduce the paper. The github repo is generated from that. 

The following changes were made to the code:
1. We added Tensorflow 1.x to the first cell where libraries are imported for version control. 
2. Session was disabled to match tensorflow version control in the last cell where tf.v1.compact.placeholder is used.
3. We changed the number of steps (variable) in the last cell for training model due to limitations in computational feasibility. Previously, it was 51. Now we use 7 - 3 of which are for training.

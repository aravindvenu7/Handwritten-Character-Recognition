# Handwritten-Character-Recognition

The aim of this project is to develop an end to end Neural Network for both detecting and recognizing handwritten characters in natural images.The first approach that was proposed was to build a text detection module .The architecture of this module was proposed to be based on the Connectionist Text Proposal Network :
https://arxiv.org/abs/1609.03605

![download 2](https://user-images.githubusercontent.com/28951885/52520220-2f794b80-2c8d-11e9-82e4-90d47c482924.png)

CURRENT WORK

The proposed network uses a Faster RCNN inside the CTPN.Currently,the Faster RCNN has been implemented in code.The work in progress involves the implementation fo the Text Connector LSTM part of the network.Once this is complete,the CTPN can be trained.


FURTHER WORK

Further work will be to train the model using reinforcement learning as proposed by the following paper titled “Deep Reinforcement Learning of Region Proposal Networks for Object Detection” :
http://openaccess.thecvf.com/content_cvpr_2018/papers/Pirinen_Deep_Reinforcement_Learning_CVPR_2018_paper.pdf

The paper proposes a  drl-RPN, a deep reinforcement learning based visual recognition model consisting of a sequential region proposal network (RPN) and an object detector. This is achieved by replacing the greedy RoI selection process with a sequential attention mechanism which is trained via deep reinforcement learning (RL)

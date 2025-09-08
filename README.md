# [MultiNet: Multistaking Visual perception for Autonomous Driving](https://www.sciencedirect.com/science/article/pii/S0957417424001143)
An Encoder-Decoder network to learn multi-perception tasks (object detection, drivable area segmentation, and lane line identification) simultaneously

---

## Abstract
Abstract
Visual perception plays a vital role in autonomous driving systems, demanding high accuracy and real-time inference speed to ensure safety. In this paper, we propose a multi-task framework that simultaneously performs object detection, drivable area segmentation, and lane line identification, addressing the requirements of accurate and efficient visual perception. Our approach utilizes a shared-encoder architecture with three separate decoders, targeting each specific task. We investigate three configurations for the shared encoder: a Convolutional Neural Network (CNN), a Polyp Vision Transformer (PVT), and a hybrid CNN+PVT model. Through extensive experimentation and comparative analysis on the challenging BD100K dataset, we evaluate the performance of these shared-encoder models and provide valuable insights into their strengths and weaknesses. Our research contributes to the advancement of multi-task visual perception for autonomous driving systems by achieving competitive results in terms of accuracy and efficiency. 

## Model Training
To train the model:
```bash
python tools/train.py
```


## Citation
Usman, Muhammad, Muhammad Zaka-Ud-Din, and Qiang Ling. "Enhanced encoder–decoder architecture for visual perception multitasking of autonomous driving." Expert Systems with Applications 246 (2024): 123249.[https://www.sciencedirect.com/science/article/pii/S0957417424001143](https://www.sciencedirect.com/science/article/pii/S0957417424001143)

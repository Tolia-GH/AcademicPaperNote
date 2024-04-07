# The Smart Image Recognition Mechanism forCrop Harvesting System in Intelligent Agriculture

[source file](./CNNObjectDetectionInSmartAgriculture.-2020.03.pdf)

### Journal 期刊
**SCI II**: IEEE SENSORS JOURNAL
### KeyWords 关键词
- Internet of Things (IoT) 物联网
- multiaxial robotic arm control 多轴机械臂控制
- deep learning 深度学习
- object detection in smart agriculture 智能农业中的物体检测

### Algorithm 算法
- DeepLearning 深度学习
- Deep Neural Network 深度神经网络
- Convolutional Neural Network 卷积神经网络

### Innovation 创新点
- 基于物联网技术和智能图像识别的收割系统。
- 通过训练神经网络模组的物体检测来确定作物的成熟度
  
### Value 价值

- 图像进行农作物检测。经验表明，所提出的模型训练的平均精确度（mAP）为 84%，高于其他模型。
- 减轻农民在农产品收割中的体力劳动

### Abstract 摘要

This study proposed a harvesting system based on the Internet of Things technology and smart image recognition. Farming decisions require extensive experience;with the proposed system, crop maturity can be determined through object detection by training neural network models, and mature crops can then be harvested using robotic arms. Keras was used to construct a multilayer perceptron machine learning model and to predict multiaxial robotic arm movements and position. Following the execution of object detection on images, the pixel coordinates of the central point of the target crop in the image were used as neural network input, whereas the robotic arms were regarded as the output side. A MobileNet version 2 convolutional neural network was then used as the image feature extraction model, which was combined with a single shot multibox detector model as the posterior layer to form an object detection model. The model then performed crop detection by collecting and tagging images. Empirical evidence shows that the proposed model training had a mean average precision (mAP) of 84%, which was higher than that of other models; a mAP of 89% was observed from the arm picking results.
本研究提出了一种基于物联网技术和智能图像识别的收割系统。耕作决策需要丰富的经验；利用所提出的系统，可以通过训练神经网络模型进行物体检测来确定作物的成熟度，然后使用机械臂收割成熟的作物。使用 Keras 构建了一个多层感知器机器学习模型，并预测多轴机械臂的运动和位置。在对图像执行物体检测后，图像中目标作物中心点的像素坐标被用作神经网络的输入端，而机械臂则被视为输出端。
方。然后使用 MobileNet 第 2 版卷积神经网络作为图像特征提取模型，并将其与作为后层的单次多箱检测器模型相结合，形成物体检测模型。然后，该模型通过收集和标记图像来进行作物检测。经验证据表明，所提出的模型训练的平均精度（mAP）为 84%，高于其他模型；从手臂采摘结果中观察到的平均精度（mAP）为 89%。
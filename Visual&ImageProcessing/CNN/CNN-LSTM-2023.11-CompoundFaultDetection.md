# A hybrid 3DSE-CNN-2DLSTM model for compound fault detection of wind turbines

[source file](./CNN-LSTM-2023.11-CompoundFaultDetection.pdf)

### Journal 期刊

Expert Systems With Applications 

### KeyWords 关键词

- Wind turbine  
  风力涡轮机
- Compound fault detection  
  复合故障检测
- Spatial–temporal correlation  
  时空相关性
- SE attention  
  SE关注
- CNN-LSTM

### Algorithm 算法

3DSE-CNN-2DLSTM模型
- three-dimensional squeeze-excitation convolutional neural network (3DSE-CNN)
  三维挤压激励卷积神经网络（3DSE-CNN）
- two-dimensional long and short-term memory network (2DLSTM)
  二维长短期记忆网络（2DLSTM）

### Innovation 创新点

- 结合了三维挤压激励卷积神经网络（3DSE-CNN）和二维长短期记忆网络（2DLSTM）构建模型：首先，通过滑动窗口方法将一维数据转换为二维图像。 然后，在提出的3DSE-CNN模型中，应用SE注意模块来增强卷积通道信息并提取空间特征。 所提出的 2DLSTM 模型提取时空融合特征。 最后通过argmax函数得到故障类别的标签。 
- 实现了风力发电领域的复合故障检测

### Value 价值

- 实现了特定的复合故障检测并提高了检测精度

### Abstract 摘要

In recent years, intelligent fault detection methods have achieved dramatic results for wind power generation. However, a majority of the available intelligent detected methods can only detect single faults. The supervisory control and data acquisition (SCADA) system is widely applied in wind turbines (WTs). SCADA data is a time-stream of variable data. Considering spatial correlation and temporal correlation among SCADA data, this study proposes a WT compound fault detection model combining a three-dimensional squeeze-excitation convolutional neural network (3DSE-CNN), and a two-dimensional long and short-term memory network (2DLSTM). The proposed 3DSE-CNN-2DLSTM model consists of three parts: data preprocessing, spatiotemporal feature extrac-tion, and fault detection. First, one-dimensional data is converted into a 2D image by a sliding window method. Then, in the proposed 3DSE-CNN model, the SE attention module is applied to enhance the convolutional channel information and extract spatial features. The proposed 2DLSTM model extracts spatiotemporal fusion features. Finally, the label of the fault category is obtained by argmax function. To validate 3DSE-CNN-2DLSTM, a 3 MW WT SCADA dataset from the south coast of Ireland is applied in the experiment. The proposed 3DSE-CNN-2DLSTM model achieves specific compound fault detection and improves detection accuracy.  
近年来，智能故障检测方法在风力发电领域取得了显着的成果。 然而，大多数现有的智能检测方法只能检测单一故障。 监控和数据采集（SCADA）系统广泛应用于风力涡轮机（WT）。 SCADA 数据是可变数据的时间流。 考虑到SCADA数据之间的空间相关性和时间相关性，本文提出了一种结合三维挤压激励卷积神经网络（3DSE-CNN）和二维长短期记忆网络（2DLSTM）的WT复合故障检测模型）。 所提出的3DSE-CNN-2DLSTM模型由三部分组成：数据预处理、时空特征提取和故障检测。 首先，通过滑动窗口方法将一维数据转换为二维图像。 然后，在提出的3DSE-CNN模型中，应用SE注意模块来增强卷积通道信息并提取空间特征。 所提出的 2DLSTM 模型提取时空融合特征。 最后通过argmax函数得到故障类别的标签。 为了验证 3DSE-CNN-2DLSTM，实验中应用了来自爱尔兰南海岸的 3 MW WT SCADA 数据集。 所提出的3DSE-CNN-2DLSTM模型实现了特定的复合故障检测并提高了检测精度。
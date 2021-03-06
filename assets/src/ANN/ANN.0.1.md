### Deeplearning Algorithms tutorial
谷歌的人工智能位于全球前列，在图像识别、语音识别、无人驾驶等技术上都已经落地。而百度实质意义上扛起了国内的人工智能的大旗，覆盖无人驾驶、智能助手、图像识别等许多层面。苹果业已开始全面拥抱机器学习，新产品进军家庭智能音箱并打造工作站级别Mac。另外，腾讯的深度学习平台Mariana已支持了微信语音识别的语音输入法、语音开放平台、长按语音消息转文本等产品，在微信图像识别中开始应用。全球前十大科技公司全部发力人工智能理论研究和应用的实现，虽然入门艰难，但是一旦入门，高手也就在你的不远处！

机器学习主要有三种方式：监督学习，无监督学习与半监督学习。

（1）监督学习：从给定的训练数据集中学习出一个函数，当新的数据输入时，可以根据函数预测相应的结果。监督学习的训练集要求是包括输入和输出，也就是特征和目标。训练集中的目标是有标注的。如今机器学习已固有的监督学习算法有可以进行分类的，例如贝叶斯分类，SVM，ID3，C4.5以及分类决策树，以及现在最火热的人工神经网络，例如BP神经网络，RBF神经网络，Hopfield神经网络、深度信念网络和卷积神经网络等。人工神经网络是模拟人大脑的思考方式来进行分析，在人工神经网络中有显层，隐层以及输出层，而每一层都会有神经元，神经元的状态或开启或关闭，这取决于大数据。同样监督机器学习算法也可以作回归，最常用便是逻辑回归。

（2）无监督学习：与有监督学习相比，无监督学习的训练集的类标号是未知的，并且要学习的类的个数或集合可能事先不知道。常见的无监督学习算法包括聚类和关联，例如K均值法、Apriori算法。

（3）半监督学习：介于监督学习和无监督学习之间,例如EM算法。

如今的机器学习领域主要的研究工作在三个方面进行：1）面向任务的研究，研究和分析改进一组预定任务的执行性能的学习系统；2）认知模型，研究人类学习过程并进行计算模拟；3）理论的分析，从理论的层面探索可能的算法和独立的应用领域算法。

#### 人工神经网络(Artificial Neural Network)

人工神经网络 （Artificial Neural Network，ANN）简称神经网络(NN)，是基于生物学中神经网络的基本原理，在理解和抽象了人脑结构和外界刺激响应机制后，以网络拓扑知识为理论基础，模拟人脑的神经系统对复杂信息的处理机制的一种数学模型，根植于神经科学、数学、思维科学、人工智能、统计学、物理学、计算机科学以及工程科学的一门技术，通常用于解决分类和回归问题。具有并行分布的处理能力、高容错性、智能化和自学习等能力的特征，本质上是一个有大量简单元件相互连接而成的复杂网络，具有高度的非线性，能够进行复杂的逻辑操作和非线性关系实现的系统。

神经网络由大量的节点（或称神经元）之间相互联接构成，每个节点代表一种特定的输出函数，称为激活函数（activation function）；每两个节点间的连接都代表一个对于通过该连接信号的加权值，称之为权重（weight），神经网络就是通过这种方式来模拟人类的记忆。网络的输出则取决于网络的结构、网络的连接方式、权重和激活函数。而网络自身通常都是对自然界某种算法或者函数的逼近，也可能是对一种逻辑策略的表达，是对传统逻辑学演算的进一步延伸。

<p align="center">
<img width="300" align="center" src="../../images/1.jpg" />
</p>


人工神经网络中，神经元处理单元可表示不同的对象，例如特征、字母、概念，或者一些有意义的抽象模式。网络中处理单元的类型分为三类：输入单元、输出单元和隐单元。输入单元接受外部世界的信号与数据；输出单元实现系统处理结果的输出；隐单元是处在输入和输出单元之间，不能由系统外部观察的单元。神经元间的连接权值反映了单元间的连接强度，信息的表示和处理体现在网络处理单元的连接关系中。

应用领域：神经网络克服了传统人工智能方法对于直觉的缺陷，因而在神经专家系统、模式识别、智能控制、组合优化、预测等领域有成功的应用。

人工神经网络(Artificial Neural Network)算法应用： 
 * 自动编码器(Autoencoder) 
 * 反向传播(Backpropagation)
 * 递归神经网络(Recurrent Neural Network)
 * 多层感知器(Multilayer Perceptron)
 * 玻尔兹曼机(Boltzmann Machine)
 * 卷积神经网络(Convolutional Neural Network)
 * Hopfield网络(Hopfield Network)]() 
 * 径向基函数网络(Radial Basis Function Network)
 * 受限玻尔兹曼机(Restricted Boltzmann Machine)
 * 自组织映射(Self-Organizing Map)
 * 尖峰神经网络(Spiking Neural Network)

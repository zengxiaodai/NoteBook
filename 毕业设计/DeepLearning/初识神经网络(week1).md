## 深度学习名词解释

**1.神经网络**

* CNN（convolutional neural networks）
* RNN（recurrent neural networks）---*无序数据*---[（例如音频随着时间播放的，所以很自然的表现为一维时间序列）(例如语言是一个单词一个单词的出现)]

---

**2.Scale drives deep learning progress**

图1-1如下：

![提高迭代速度](E:\MySoftware\LearningRelated\Markdown\TheDocument\MyNotes\毕业设计\DeepLearning\image\MoreFast.PNG)

【解释】：推动深度学习进程：

* 改进算法提高计算速度
  * 例如（上图1-1）左边我们可以通过将sigmoid函数转化成Relu函数来提高梯度下降的速度（箭头标记处Sigmoid函数斜率趋近于0梯度下降慢）。

* 计算速度提高-->迭代速度提高
  * 例如（图1-1）右边我们可以看到在实际开发过程中迭代速度的提高开发者就可以尝试更多的想法并且更快的找到适合的应用神经网络。


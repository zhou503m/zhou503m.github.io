##### Face Attribute Prediction with classification CNN（2016）

总结性的：

中间层可以很好地预测可描述的面部属性很有效（比最后的层有效 )
可以为面部识别和属性预测构建单个深层网络 
实验结果显示中间层有较好的描述性  

----

#####Deep Learning Face Attributes in the Wild（2015）
提出一个新的深度学习框架：集成2个CNN、ANet、LNet   
LNet是通过大量的一般对象类别进行面部定位预训练的，而ANet是通过大量面部身份预先训练的属性预测   

---
#####Attribute and simile classifiers for face verification. In ICCV, pages 365–372, 2009.

1.属性分类器，很多个二分类   

2.相似性分类器（simile classifiers）去掉属性分类的标签，被训练来计算两张脸的相似性 how？   
######方法
- 第一步:Extract Low-level Features 
- 第二步：Compute Visual Traits
- 第三步：Perform Verification   


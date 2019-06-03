## 每日一题之mybatis面试题：xml常见标签

chenyx 



#### 1、mysql Xml文件中，除了常见的select|insert|updae|delete标签之外，还有哪些标签？

答：xml文件中有很多其他的标签如下所示：

<resultMap>、<parameterMap>、<sql>、<include>、<selectKey>

其中<sql>为sql片段标签，通过<include>标签引入sql片段，<selectKey>为不支持自增的主键生成策略标签。

还有动态sql的9个标签，trim|where|set|foreach|if|choose|when|otherwise|bind等
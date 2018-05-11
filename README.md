### 1、vue数据绑定简单实现：
* 数据劫持(defineProperty)；
* 发布订阅模式；
* 监听函数/订阅消息；
* 模板编译(createDocumentFragment优化+正则匹配)；
* 数据代理(defineProperty)。

### 2、fork：canfoo/self-vue (v3)
* 并解决了 /canfoo/self-vue/issues/3 描述的问题。
* 参考文章：剖析Vue原理&实现双向绑定MVVM - 前端足迹 - SegmentFault 思否

### 3、实现双向绑定：Proxy比defineproperty对比
可以参考issues#1的一些简单例子


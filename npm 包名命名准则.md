# npm 包名命名规范
因工作需要，最近在找 npm 包名的命名规范，但一直都没有找到，npm 官网文档中没有详细的说明，只是在包名准则 中提到几点：
1. 唯一的（独特的）；
2. 描述性的；
3. 符合 npm 政策准则。如：请勿给您的包裹起冒犯性的名称，也不要使用他人的商标名称或违反npm商标政策；
4. 不能和别人的包名有混淆的情况（查重规则会去掉符号，全转换为小写后进行查重）

另外从下面这篇类似译文的文章中可以得到 2019-04-18 左右的规则是：
1. 有小写英文字母加 标点符号、破折号和下划线“.”、“-”、“_”等组成；
2. 不支持大写字母，这是因为 jsonstream 和 JSONstream 容易被当成一个包来看待。
3. 可以使用@定义的作用域来区分名称相同的包，比如： react-native 和 @timwk/react-native 是两个不同的包。
转至：https://my.oschina.net/hongdaorong/blog/3038824
因 github blog 需要翻墙，目前现有的科学上网工具不太好用，还没找到原始出处。
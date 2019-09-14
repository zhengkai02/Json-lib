JSON in Java [package org.json]
===============================

[![Maven Central](https://img.shields.io/maven-central/v/org.json/json.svg)](https://mvnrepository.com/artifact/org.json/json)

**[Click here if you just want the latest release jar file.](https://repo1.maven.org/maven2/org/json/json/20190722/json-20190722.jar)**

json是一种轻量级、独立于语言的数据交换格式。
见 http://www.JSON.org/

java:jsonobject可以解析字符串或jsontokener中的文本来生成类似于映射的对象。对象提供了用于操作其内容和生成符合json的对象序列化的方法。

java:jsonarray可以解析字符串或jsontokener中的文本，从而生成类似向量的对象。该对象提供用于操作其内容和生成符合json的数组序列化的方法。

java:jsontokener将文本分解成一系列单独的标记。它可以由字符串、读取器或inputstream构造。

jsonexception.java：jsonexception是这个包抛出的标准异常类型。

json pointer.java:json指针的实现（rfc 6901）。支持字符串表示和uri片段表示形式的json指针。

JSONPropertyIgnore.java：可以在JavaBean吸收器方法上使用的注释类。当用于通常序列化为jsonobject的bean方法时，它将重写getter-to-key-name逻辑，并强制从生成的jsonobject中排除该属性。

JSONPropertyName.java：可以在JavaBean吸收器方法上使用的注释类。当用于通常序列化为jsonobject的bean方法时，它会重写getter-to-key-name逻辑并使用注释的值。bean处理器将查看类层次结构。这意味着您可以在基类或接口上使用注释，并且即使getter在子类中被重写，也将使用注释的值。

jsonstring.java:jsonstring接口需要一个tojsonstring方法，允许对象提供自己的序列化。

jsonstringer.java:jsonstringer为构建json字符串提供了方便的工具。

java:json writer为通过writer构建json文本提供了一个方便的工具。

java:cdl支持json和逗号分隔列表之间的转换。

java:cookie支持json和cookies之间的转换。

java:cookielist支持json和cookie列表之间的转换。

http.java:http支持在json和http头之间进行转换。

httptokener.java:httptokener扩展jsontokener以解析http头。

xml.java:xml支持json和xml之间的转换。

jsonml.java:jsonml支持jsonml和xml之间的转换。

java:xmltokener扩展了jsontokener来解析xml文本。

单元测试用这个项目中的代码测试JSON-Java拉取请求:
https://github.com/stleary/JSON-Java-unit-test

JSON Java发布可以通过在Maven存储库中搜索GyPID“Org .JSON”和AutoForTID“JSON”来找到。例如:
https://search.maven.org/search?q=g:org.json%20AND%20a:json&core=gav

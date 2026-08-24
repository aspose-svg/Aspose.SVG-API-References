---
title: "Document.CreateElement"
second_title: "Aspose.SVG for .NET API 参考"
description: "Document CreateElement 方法。创建由 localName 指定的 HTML 元素，如果未识别 localName，则返回 HTMLUnknownElement"
type: docs
weight: 850
url: /zh/net/aspose.svg.dom/document/createelement/
---
## Document.CreateElement method

创建由 localName 指定的 HTML 元素，如果未识别 localName，则返回 HTMLUnknownElement。

```csharp
public Element CreateElement(string localName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | String | 一个指定要创建的元素类型的字符串。创建的元素的 nodeName 使用 localName 的值进行初始化。不要在此方法中使用限定名称（如 \"html:a\"）。在 HTML 文档上调用时，createElement() 会在创建元素之前将 localName 转换为小写。 |

### 返回值

新的 [`Element`](../../element/)。

### 另请参阅

* class [Element](../../element/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

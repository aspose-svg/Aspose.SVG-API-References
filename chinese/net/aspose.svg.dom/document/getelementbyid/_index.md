---
title: "Document.GetElementById"
second_title: "Aspose.SVG for .NET API 参考"
description: "Document GetElementById 方法。此方法返回一个 Element 对象，表示其 id 属性与指定字符串匹配的元素。由于元素 ID 必须唯一（如果指定），它们是快速访问特定元素的有用方式。"
type: docs
weight: 960
url: /zh/net/aspose.svg.dom/document/getelementbyid/
---
## Document.GetElementById method

此方法返回一个 [`Element`](../../element/) 对象，表示其 id 属性与指定字符串匹配的元素。由于元素 ID 必须唯一（如果指定），它们是快速访问特定元素的有用方式。

如果需要访问没有 ID 的元素，可以使用 [`QuerySelector`](../queryselector/) 通过任意选择器查找该元素。

```csharp
public Element GetElementById(string elementId)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| elementId | String | 要定位的元素的 ID。ID 是区分大小写的字符串，在文档中唯一；任意给定的 ID 只能对应一个元素。 |

### 返回值

一个描述与指定 ID 匹配的 DOM 元素的 [`Element`](../../element/) 对象，如果在文档中未找到匹配的元素，则为 null。

## 备注

请参阅官方 [spec](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid)。

### 另请参阅

* class [Element](../../element/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

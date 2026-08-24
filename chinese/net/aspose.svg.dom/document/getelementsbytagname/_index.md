---
title: "Document.GetElementsByTagName"
second_title: "Aspose.SVG for .NET API 参考"
description: "Document GetElementsByTagName 方法。此方法返回具有给定标签名的元素的 HTMLCollection。"
type: docs
weight: 980
url: /zh/net/aspose.svg.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

此方法返回一个包含给定标签名元素的 [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/)。

完整文档会被搜索，包括根节点。返回的[`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/)是实时的，这意味着它会自动更新自身，以保持与 DOM 树同步，而无需再次调用此方法。

```csharp
public HTMLCollection GetElementsByTagName(string tagname)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 标签名 | String | 一个表示元素名称的字符串。特殊字符串 "*" 代表所有元素。 |

### 返回值

一个实时的[`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) ，其中包含按在树中出现顺序找到的元素。

## 备注

请参阅官方[规范](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname)。

### 另请参阅

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

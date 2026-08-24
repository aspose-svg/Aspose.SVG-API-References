---
title: "Document.GetElementsByTagNameNS"
second_title: "Aspose.SVG for .NET API 参考"
description: "Document GetElementsByTagNameNS 方法。返回属于给定命名空间且具有指定标签名的元素列表。搜索整个文档，包括根节点"
type: docs
weight: 990
url: /zh/net/aspose.svg.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

返回具有给定标签名且属于指定命名空间的元素列表。会搜索整个文档，包括根节点。

```csharp
public HTMLCollection GetElementsByTagNameNS(string namespaceURI, string localName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| namespaceURI | String | 要查找的元素的命名空间 URI。 |
| localName | String | 要查找的元素的本地名称，或特殊值 *，匹配所有元素。 |

### 返回值

一个实时的[`NodeList`](../../../aspose.svg.collections/nodelist/) ，按它们在树中出现的顺序列出找到的元素。

## 备注

请参阅官方[spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens)。

### 另请参阅

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

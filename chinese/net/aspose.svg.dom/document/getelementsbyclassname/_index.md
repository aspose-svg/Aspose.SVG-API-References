---
title: "Document.GetElementsByClassName"
second_title: "Aspose.SVG for .NET API 参考"
description: "Document GetElementsByClassName 方法。此方法返回一个类似数组的对象，包含所有具有给定类名的子元素。"
type: docs
weight: 970
url: /zh/net/aspose.svg.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

此方法返回一个类似数组的对象，包含所有具有给定类名的子元素。

在文档对象上调用时，会搜索完整文档，包括根节点。您也可以在任何元素上调用此方法；它将仅返回具有给定类名的、指定根元素的后代元素。

```csharp
public HTMLCollection GetElementsByClassName(string classNames)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| classNames | String | 包含一组无序唯一的以空格分隔的标记，表示类（类名）的字符串。 |

### 返回值

一个实时的[`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/)，包含找到的元素。

## 备注

请参阅官方[规范](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname)。

### 另请参阅

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

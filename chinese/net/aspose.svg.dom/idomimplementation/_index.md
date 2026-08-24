---
title: "IDOMImplementation 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.IDOMImplementation 接口。DOMImplementation 接口提供多种方法，用于执行与特定文档对象模型实例无关的操作。"
type: docs
weight: 3040
url: /zh/net/aspose.svg.dom/idomimplementation/
---
## IDOMImplementation interface

DOMImplementation 接口提供了多种方法，用于执行独立于任何特定文档对象模型实例的操作。

```csharp
public interface IDOMImplementation
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateDocument](../../aspose.svg.dom/idomimplementation/createdocument/)(*string, string, [DocumentType](../documenttype/)*) | 创建具有指定类型及其文档元素的 DOM Document 对象。 |
| [CreateDocumentType](../../aspose.svg.dom/idomimplementation/createdocumenttype/)(*string, string, string*) | 创建一个空的 DocumentType 节点。实体声明和符号未提供。不会进行实体引用展开和默认属性添加。 |
| [CreateHTMLDocument](../../aspose.svg.dom/idomimplementation/createhtmldocument/)(*string*) | 返回一个文档，已构建基本树并包含 title 元素，除非省略 title 参数。 |
| [HasFeature](../../aspose.svg.dom/idomimplementation/hasfeature/)() | 测试 DOM 实现是否实现了特定特性和版本，如 DOM Features 中所指定。 |

### 另请参阅

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

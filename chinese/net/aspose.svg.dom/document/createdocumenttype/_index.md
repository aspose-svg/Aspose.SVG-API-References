---
title: "Document.CreateDocumentType"
second_title: "Aspose.SVG for .NET API 参考"
description: "Document CreateDocumentType 方法。该方法返回一个 DocumentType 对象，可在文档创建时与 CreateDocument 一起使用，或通过 InsertBefore 或 ReplaceChild 等方法放入文档中。"
type: docs
weight: 840
url: /zh/net/aspose.svg.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

该方法返回一个 [`DocumentType`](../../documenttype/) 对象，该对象可以在文档创建时与 [`CreateDocument`](../../idomimplementation/createdocument/) 一起使用，或通过诸如 [`InsertBefore`](../../node/insertbefore/) 或 [`ReplaceChild`](../../node/replacechild/) 等方法放入文档中。

```csharp
public DocumentType CreateDocumentType(string name, string publicId, string systemId, 
    string internalSubset)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 是一个包含限定名称的 DOMString，例如 svg:svg。 |
| publicId | String | 是一个包含 PUBLIC 标识符的 DOMString。 |
| systemId | String | 是一个包含 SYSTEM 标识符的 DOMString。 |
| internalSubset | String | 内部子集。 |

### 返回值

该 [`DocumentType`](../../documenttype/)。

### 另请参阅

* class [DocumentType](../../documenttype/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

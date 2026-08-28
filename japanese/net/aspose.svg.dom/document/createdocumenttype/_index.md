---
title: "Document.CreateDocumentType"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Document CreateDocumentType メソッド。 このメソッドは DocumentType オブジェクトを返します。このオブジェクトはドキュメント作成時に CreateDocument と共に使用することも、InsertBefore や ReplaceChild などのメソッドを使ってドキュメントに挿入することもできます。"
type: docs
weight: 840
url: /ja/net/aspose.svg.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

このメソッドは [`DocumentType`](../../documenttype/) オブジェクトを返します。このオブジェクトはドキュメント作成時に [`CreateDocument`](../../idomimplementation/createdocument/) と共に使用することも、[`InsertBefore`](../../node/insertbefore/) や [`ReplaceChild`](../../node/replacechild/) などのメソッドを使ってドキュメントに挿入することもできます。

```csharp
public DocumentType CreateDocumentType(string name, string publicId, string systemId, 
    string internalSubset)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | String | 修飾名（例: svg:svg）を含む DOMString です。 |
| publicId | String | PUBLIC 識別子を含む DOMString です。 |
| systemId | String | SYSTEM 識別子を含む DOMString です。 |
| internalSubset | String | 内部サブセットです。 |

### 戻り値

[`DocumentType`](../../documenttype/)です。

### 参照

* class [DocumentType](../../documenttype/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

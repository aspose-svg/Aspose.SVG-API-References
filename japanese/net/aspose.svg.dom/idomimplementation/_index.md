---
title: "IDOMImplementation インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.IDOMImplementation インターフェイス。DOMImplementation インターフェイスは、特定のドキュメントオブジェクトモデルインスタンスに依存しない操作を実行するための多数のメソッドを提供します。"
type: docs
weight: 3040
url: /ja/net/aspose.svg.dom/idomimplementation/
---
## IDOMImplementation interface

DOMImplementation インターフェイスは、特定の Document Object Model インスタンスに依存しない操作を実行するための多数のメソッドを提供します。

```csharp
public interface IDOMImplementation
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreateDocument](../../aspose.svg.dom/idomimplementation/createdocument/)(*string, string, [DocumentType](../documenttype/)*) | 指定されたタイプの DOM Document オブジェクトを、そのドキュメント要素とともに作成します。 |
| [CreateDocumentType](../../aspose.svg.dom/idomimplementation/createdocumenttype/)(*string, string, string*) | 空の DocumentType ノードを作成します。エンティティ宣言や表記は利用できません。エンティティ参照の展開やデフォルト属性の追加は行われません。 |
| [CreateHTMLDocument](../../aspose.svg.dom/idomimplementation/createhtmldocument/)(*string*) | title 引数が省略されていない限り、title 要素を含む基本的なツリーがすでに構築されたドキュメントを返します。 |
| [HasFeature](../../aspose.svg.dom/idomimplementation/hasfeature/)() | DOM Features に指定されている特定の機能とバージョンが DOM 実装でサポートされているかテストします。 |

### 参照

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

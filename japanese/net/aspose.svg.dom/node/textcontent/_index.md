---
title: "Node.TextContent"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Node TextContent プロパティ。ノードとその子孫のテキスト内容を表します"
type: docs
weight: 160
url: /ja/net/aspose.svg.dom/node/textcontent/
---
## Node.TextContent property

ノードおよびその子孫のテキストコンテンツを表します。

```csharp
public virtual string TextContent { get; set; }
```

### Property Value

文字列または null。値は状況に依存します：

ノードがドキュメントまたはドキュメントタイプの場合、`TextContent` は null を返します。注: ドキュメント全体のテキストと CDATA データを取得するには、使用してください

```csharp
document.DocumentElement.TextContent
```

.ノードが CDATA セクション、コメント、処理命令、またはテキストノードの場合、`TextContent` はノード内のテキストを返すか、設定します。すなわち、[`NodeValue`](../nodevalue/)です。他のノードタイプの場合、`TextContent` はコメントと処理命令を除くすべての子ノードの `TextContent` を連結したものを返します。

## 備考

参照:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-textcontent).

### 参照

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---
title: "ITraversal インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Traversal.ITraversal インターフェイス。イテレータは、NodeList のノード集合や特定の Node が支配するドキュメントサブツリー、クエリ結果、その他任意のノード集合など、ノードの集合を順に処理するために使用されます。イテレートされるノード集合は NodeIterator の実装によって決定されます。DOM Level 2 は、ドキュメントサブツリーの文書順走査のための単一の NodeIterator 実装を規定しています。これらのイテレータのインスタンスは、DocumentTraversal .createNodeIterator を呼び出すことで作成されます。"
type: docs
weight: 3260
url: /ja/net/aspose.svg.dom.traversal/itraversal/
---
## ITraversal interface

イテレータはノードの集合を順に処理するために使用されます。例えば NodeList のノード集合、特定の Node が管理する文書サブツリー、クエリの結果、またはその他の任意のノード集合です。イテレートされるノード集合は NodeIterator の実装によって決定されます。DOM Level 2 は文書順走査用の単一の NodeIterator 実装を規定しています。これらのイテレータのインスタンスは DocumentTraversal .createNodeIterator() を呼び出すことで作成されます。

また、[Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113) も参照してください。@since DOM Level 2

```csharp
public interface ITraversal : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Filter](../../aspose.svg.dom.traversal/itraversal/filter/) { get; } | ノードをフィルタリングするために使用される NodeFilter。 |
| [Root](../../aspose.svg.dom.traversal/itraversal/root/) { get; } | 作成時に指定された NodeIterator のルートノード。 |
| [WhatToShow](../../aspose.svg.dom.traversal/itraversal/whattoshow/) { get; } | この属性は、イテレータを通じて提示されるノードタイプを決定します。利用可能な定数の集合は NodeFilter インターフェイスで定義されています。whatToShow で受け入れられないノードはスキップされますが、その子ノードは引き続き考慮される場合があります。なお、このスキップはフィルタ（存在する場合）よりも優先されます。 |

### 参照

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)

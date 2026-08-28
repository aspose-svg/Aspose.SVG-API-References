---
title: "NodeList クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Collections.NodeList クラス。NodeList は、コレクションがどのように実装されるかを定義または制約せずに、ノードの順序付けられたコレクションの抽象化を提供します。"
type: docs
weight: 2030
url: /ja/net/aspose.svg.collections/nodelist/
---
## NodeList class

NodeList は、ノードの順序付けられたコレクションの抽象化を提供し、このコレクションがどのように実装されるかは定義または制約しません。

```csharp
public abstract class NodeList : DOMObject, IEnumerable<Node>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/nodelist/item/) { get; } | メソッドはコレクション内の index 番目の項目を返します。index がリスト内のノード数以上の場合、null を返します。 |
| abstract [Length](../../aspose.svg.collections/nodelist/length/) { get; } | リスト内のノード数。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/nodelist/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| override [GetPlatformType](../../aspose.svg.collections/nodelist/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |

### 参照

* class [DOMObject](../../aspose.svg.dom/domobject/)
* class [Node](../../aspose.svg.dom/node/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)

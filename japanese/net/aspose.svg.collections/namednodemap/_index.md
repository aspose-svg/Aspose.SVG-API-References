---
title: "NamedNodeMap クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Collections.NamedNodeMap クラス。名前でアクセスできる属性のコレクションを表します。"
type: docs
weight: 2020
url: /ja/net/aspose.svg.collections/namednodemap/
---
## NamedNodeMap class

名前でアクセスできる属性のコレクションを表します。

```csharp
public class NamedNodeMap : DOMObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Item](../../aspose.svg.collections/namednodemap/item/) { get; } | マップ内のインデックス番目の項目を返します。インデックスがこのマップのノード数以上の場合は null を返します。（インデクサーが 2 つ） |
| [Length](../../aspose.svg.collections/namednodemap/length/) { get; } | このマップのノード数です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetNamedItem](../../aspose.svg.collections/namednodemap/getnameditem/)(*string*) | 名前で指定されたノードを取得します。 |
| [GetNamedItemNS](../../aspose.svg.collections/namednodemap/getnameditemns/)(*string, string*) | ローカル名と名前空間 URI で指定されたノードを取得します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [RemoveNamedItem](../../aspose.svg.collections/namednodemap/removenameditem/)(*string*) | 名前で指定されたノードを削除します。 |
| [RemoveNamedItemNS](../../aspose.svg.collections/namednodemap/removenameditemns/)(*string, string*) | ローカル名と名前空間 URI で指定されたノードを削除します。 |
| [SetNamedItem](../../aspose.svg.collections/namednodemap/setnameditem/)(*[Attr](../../aspose.svg.dom/attr/)*) | nodeName 属性を使用してノードを追加します。その名前のノードが既にこのマップに存在する場合、新しいノードで置き換えられます。自分自身のノードを置き換えても効果はありません。 |
| [SetNamedItemNS](../../aspose.svg.collections/namednodemap/setnameditemns/)(*[Attr](../../aspose.svg.dom/attr/)*) | namespaceURI と localName を使用してノードを追加します。その名前空間 URI とローカル名のノードが既にこのマップに存在する場合、新しいノードで置き換えられます。自分自身のノードを置き換えても効果はありません。 |

### 参照

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)

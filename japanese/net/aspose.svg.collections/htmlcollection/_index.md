---
title: "HTMLCollection クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Collections.HTMLCollection クラス。HTMLCollection は Element の汎用コレクションを表します。"
type: docs
weight: 2010
url: /ja/net/aspose.svg.collections/htmlcollection/
---
## HTMLCollection class

`HTMLCollection` は [`Element`](../../aspose.svg.dom/element/) の汎用コレクションを表します。

```csharp
public abstract class HTMLCollection : DOMObject, IEnumerable<Element>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/htmlcollection/item/) { get; } | コレクション内の index 番目の項目を返します。index がリスト内のノード数以上の場合、null を返します。 |
| abstract [Length](../../aspose.svg.collections/htmlcollection/length/) { get; } | リスト内のノード数。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/htmlcollection/getenumerator/)() | 列挙子を取得します。 |
| override [GetPlatformType](../../aspose.svg.collections/htmlcollection/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [NamedItem](../../aspose.svg.collections/htmlcollection/nameditem/)(*string*) | 指定された名前に一致するコレクション内の項目を返します。 |

### 参照

* class [DOMObject](../../aspose.svg.dom/domobject/)
* class [Element](../../aspose.svg.dom/element/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)

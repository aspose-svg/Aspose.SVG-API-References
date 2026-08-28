---
title: "SVGListBaseT クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Collections.SVGListBase1T クラス。このインターフェイスはすべての SVG リストの基本リストを定義します。"
type: docs
weight: 2040
url: /ja/net/aspose.svg.collections/svglistbase-1/
---
## SVGListBase<T> class

このインターフェイスは、すべての SVG リストの基本リストを定義します。

```csharp
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| パラメータ | 説明 |
| --- | --- |
| T | リストに格納される項目の型。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Item](../../aspose.svg.collections/svglistbase-1/item/) { get; set; } | リスト内の index 番目の項目を返します。 |
| [Length](../../aspose.svg.collections/svglistbase-1/length/) { get; } | リスト内の項目数。 |
| [NumberOfItems](../../aspose.svg.collections/svglistbase-1/numberofitems/) { get; } | リスト内の項目数。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AppendItem](../../aspose.svg.collections/svglistbase-1/appenditem/)(*T*) | リストの末尾に新しい項目を挿入します。 |
| [Clear](../../aspose.svg.collections/svglistbase-1/clear/)() | リストから既存のすべての項目をクリアし、結果として空のリストになります。 |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | アンマネージドリソースと、オプションでマネージドリソースを解放します。 |
| [GetEnumerator](../../aspose.svg.collections/svglistbase-1/getenumerator/)() | 列挙子を取得します。 |
| [GetItem](../../aspose.svg.collections/svglistbase-1/getitem/)(*ulong*) | リストから指定された項目を返します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [Initialize](../../aspose.svg.collections/svglistbase-1/initialize/)(*T*) | リストから既存のすべての項目をクリアし、パラメータで指定された単一の項目を保持するようにリストを再初期化します。 |
| [InsertItemBefore](../../aspose.svg.collections/svglistbase-1/insertitembefore/)(*T, ulong*) | 指定された位置に新しい項目をリストに挿入します。最初の項目は番号 0 です。 |
| [RemoveItem](../../aspose.svg.collections/svglistbase-1/removeitem/)(*ulong*) | リストから既存の項目を削除します。 |
| [ReplaceItem](../../aspose.svg.collections/svglistbase-1/replaceitem/)(*T, ulong*) | リスト内の既存の項目を新しい項目と置き換えます。 |

### 参照

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)

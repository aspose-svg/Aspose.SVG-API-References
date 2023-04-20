---
title: Class SVGListBaseT
second_title: Aspose.SVG for .NET API リファレンス
description: Aspose.Svg.Collections.SVGListBase1T クラス. このインターフェイスはすべての SVG リストの基本リストを定義します
type: docs
weight: 50
url: /ja/net/aspose.svg.collections/svglistbase-1/
---
## SVGListBase&lt;T&gt; class

このインターフェイスは、すべての SVG リストの基本リストを定義します。

```csharp
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| パラメータ | 説明 |
| --- | --- |
| T | リストに格納されるアイテムのタイプ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Item](../../aspose.svg.collections/svglistbase-1/item/) { get; set; } | リストのインデックス番目の項目を返します。 |
| [Length](../../aspose.svg.collections/svglistbase-1/length/) { get; } | リスト内の項目数。 |
| [NumberOfItems](../../aspose.svg.collections/svglistbase-1/numberofitems/) { get; } | リスト内の項目数。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AppendItem](../../aspose.svg.collections/svglistbase-1/appenditem/)(T) | リストの最後に新しい項目を挿入します。 |
| [Clear](../../aspose.svg.collections/svglistbase-1/clear/)() | リストから既存の現在の項目をすべてクリアし、結果は空のリストになります。 |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | 管理されていないリソースと、オプションで管理されているリソースを解放します。 |
| [GetEnumerator](../../aspose.svg.collections/svglistbase-1/getenumerator/)() | 列挙子を取得します。 |
| [GetItem](../../aspose.svg.collections/svglistbase-1/getitem/)(ulong) | リストから指定された項目を返します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType . |
| [Initialize](../../aspose.svg.collections/svglistbase-1/initialize/)(T) | リストから既存の現在のアイテムをすべてクリアし、リストを再初期化して、パラメーターで指定された単一のアイテムを保持します。 |
| [InsertItemBefore](../../aspose.svg.collections/svglistbase-1/insertitembefore/)(T, ulong) | リストの指定された位置に新しい項目を挿入します。最初の項目は番号 0. です。 |
| [RemoveItem](../../aspose.svg.collections/svglistbase-1/removeitem/)(ulong) | リストから既存の項目を削除します。 |
| [ReplaceItem](../../aspose.svg.collections/svglistbase-1/replaceitem/)(T, ulong) | リスト内の既存のアイテムを新しいアイテムに置き換えます。 |

### 関連項目

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype/)
* 名前空間 [Aspose.Svg.Collections](../../aspose.svg.collections/)
* 組み立て [Aspose.SVG](../../)



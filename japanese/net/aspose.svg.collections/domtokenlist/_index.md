---
title: "DOMTokenList クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Collections.DOMTokenList クラス。DOMTokenList クラスはスペースで区切られたトークンの集合を表します。JavaScript の配列オブジェクトと同様に、0 からインデックス付けされます。DOMTokenList は常に大文字小文字を区別します"
type: docs
weight: 2000
url: /ja/net/aspose.svg.collections/domtokenlist/
---
## DOMTokenList class

DOMTokenList クラスは、スペースで区切られたトークンの集合を表します。インデックスは JavaScript Array オブジェクトと同様に 0 から始まります。DOMTokenList は常に大文字と小文字を区別します。

```csharp
public class DOMTokenList : DOMObject, IEnumerable<string>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Item](../../aspose.svg.collections/domtokenlist/item/) { get; } | インデックスでリスト内の項目を返します。インデックスがリストの長さ以上の場合は null を返します。 |
| [Length](../../aspose.svg.collections/domtokenlist/length/) { get; } | このリストに格納されているトークン数を表す ulong を返します。 |
| [Value](../../aspose.svg.collections/domtokenlist/value/) { get; set; } | 対応する属性の値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.svg.collections/domtokenlist/add/)(*params string[]*) | 指定されたトークンをリストに追加します。 |
| [Contains](../../aspose.svg.collections/domtokenlist/contains/)(*string*) | リストに指定されたトークンが含まれている場合は true、そうでなければ false を返します。 |
| [GetEnumerator](../../aspose.svg.collections/domtokenlist/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [Remove](../../aspose.svg.collections/domtokenlist/remove/)(*params string[]*) | 指定されたトークンをリストから削除します。 |
| [Replace](../../aspose.svg.collections/domtokenlist/replace/)(*string, string*) | 既存のトークンを新しいトークンに置き換えます。最初のトークンが存在しない場合は何もしません。 |
| [Supports](../../aspose.svg.collections/domtokenlist/supports/)(*string*) | 指定されたトークンが関連属性のサポートされているトークンに含まれている場合は true を返します。 |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle/#toggle)(*string*) | トークンがリストに存在すれば削除し、存在しなければリストに追加します。 |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle/#toggle_1)(*string, bool*) | トークンがリストに存在すれば削除し、存在しなければリストに追加します。 |

### 参照

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)

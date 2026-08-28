---
title: "ICSSStyleDeclaration インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Css.ICSSStyleDeclaration インターフェイス。CSSStyleDeclaration インターフェイスは単一の CSS 宣言ブロックを表します。このインターフェイスは、ブロック内で現在設定されているスタイルプロパティを確認したり、ブロック内でスタイルプロパティを明示的に設定したりするために使用できます。"
type: docs
weight: 2640
url: /ja/net/aspose.svg.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

CSSStyleDeclaration インターフェイスは単一の CSS 宣言ブロックを表します。このインターフェイスはブロック内で現在設定されているスタイルプロパティを確認したり、ブロック内でスタイルプロパティを明示的に設定したりするために使用できます。

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssstyledeclaration/csstext/) { get; set; } | 宣言ブロックの解析可能なテキスト表現（周囲の波括弧は除く）です。この属性を設定すると、新しい値の解析が行われ、宣言ブロック内のすべてのプロパティがリセットされ、プロパティの削除や追加も行われます。 |
| [Item](../../aspose.svg.dom.css/icssstyledeclaration/item/) { get; } | この宣言ブロックで明示的に設定されたプロパティを取得するために使用されます。このメソッドで取得されるプロパティの順序は、設定された順序と一致する必要はありません。このメソッドは、この宣言ブロック内のすべてのプロパティを反復処理するために使用できます。 |
| [Length](../../aspose.svg.dom.css/icssstyledeclaration/length/) { get; } | この宣言ブロックで明示的に設定されたプロパティの数です。有効なインデックスの範囲は 0 から length-1（含む）です。 |
| [ParentRule](../../aspose.svg.dom.css/icssstyledeclaration/parentrule/) { get; } | この宣言ブロックを含む CSS ルール、またはこの CSSStyleDeclaration が CSSRule に添付されていない場合は null です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertycssvalue/)(*string*) | この宣言ブロック内で明示的に設定された CSS プロパティの値のオブジェクト表現を取得するために使用されます。プロパティがショートハンドプロパティの場合、このメソッドは null を返します。ショートハンドプロパティの値は、getPropertyValue および setProperty メソッドを使用して文字列としてのみアクセスおよび変更できます。 |
| [GetPropertyPriority](../../aspose.svg.dom.css/icssstyledeclaration/getpropertypriority/)(*string*) | この宣言ブロックでプロパティが明示的に設定されている場合、CSS プロパティの優先度（例: \"important\" 修飾子）を取得するために使用します。 |
| [GetPropertyValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertyvalue/)(*string*) | この宣言ブロック内でプロパティが明示的に設定されている場合、CSS プロパティの値を取得するために使用します。 |
| [RemoveProperty](../../aspose.svg.dom.css/icssstyledeclaration/removeproperty/)(*string*) | この宣言ブロック内でプロパティが明示的に設定されている場合、CSS プロパティを削除するために使用します。 |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty)(*string, string*) | この宣言ブロック内でデフォルトの優先度でプロパティ値を設定するために使用します。デフォルトの優先度は \"important\" ではなく、つまり String.Empty です。 |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(*string, string, string*) | この宣言ブロック内でプロパティ値と優先度を設定するために使用します。 |

### 参照

* interface [ICSS2Properties](../icss2properties/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)

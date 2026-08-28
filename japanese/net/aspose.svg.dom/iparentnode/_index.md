---
title: "IParentNode インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.IParentNode インターフェイス。任意の可能な親が実装する IParentNode インターフェイスを定義します。"
type: docs
weight: 3080
url: /ja/net/aspose.svg.dom/iparentnode/
---
## IParentNode interface

`IParentNode` インターフェイスを定義します。任意の可能な親が実装します。

```csharp
public interface IParentNode : IElementTraversal
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ChildElementCount](../../aspose.svg.dom/iparentnode/childelementcount/) { get; } | childElementCount 属性は、コンテキストオブジェクトの子要素である要素の数を返す必要があります。 |
| [Children](../../aspose.svg.dom/iparentnode/children/) { get; } | 子要素を返します。 |
| [FirstElementChild](../../aspose.svg.dom/iparentnode/firstelementchild/) { get; } | 要素である最初の子を返し、そうでない場合は null を返します。 |
| [LastElementChild](../../aspose.svg.dom/iparentnode/lastelementchild/) { get; } | 要素である最後の子を返し、そうでない場合は null を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [QuerySelector](../../aspose.svg.dom/iparentnode/queryselector/)(*string*) | セレクターに一致する node の子孫である最初の要素を返します。 |
| [QuerySelectorAll](../../aspose.svg.dom/iparentnode/queryselectorall/)(*string*) | セレクターに一致する node のすべての要素子孫を返します。 |

### 参照

* interface [IElementTraversal](../../aspose.svg.dom.traversal/ielementtraversal/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

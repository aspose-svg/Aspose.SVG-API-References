---
title: "SVGElementBuilderT クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGElementBuilder1T クラス。T 型の SVG 要素を構築するための基底クラスを表します。"
type: docs
weight: 1160
url: /ja/net/aspose.svg.builder/svgelementbuilder-1/
---
## SVGElementBuilder<T> class

*T* 型の SVG 要素を構築するための基底クラスを表します。

```csharp
public abstract class SVGElementBuilder<T> : ISVGElementBuilder
    where T : SVGElement
```

| パラメータ | 説明 |
| --- | --- |
| T | このビルダーが作成する SVG 要素の型です。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } | SVG 要素に適用される構成のリストを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) | SVG 要素に属性構成を追加します。 |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | SVG 要素を構築し、すべての構成を適用します。 |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build_1)(*T*) | 既存の SVG 要素に構成を適用します。 |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | SVG 要素を汎用的な SVGElement として構築します。 |

### 参照

* interface [ISVGElementBuilder](../isvgelementbuilder/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

---
title: "ISVGElementBuilder インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.ISVGElementBuilder インターフェイス。SVG スケーラブルベクターグラフィックス要素を構築するためのインターフェイス。このインターフェイスは、プログラムで SVG 要素を構築するために必要な基本的なメソッドとプロパティを定義します。属性設定機能を含めるために IAttributeSetter インターフェイスを拡張しています。"
type: docs
weight: 680
url: /ja/net/aspose.svg.builder/isvgelementbuilder/
---
## ISVGElementBuilder interface

SVG（Scalable Vector Graphics）要素を構築するためのインターフェイス。このインターフェイスは、SVG要素をプログラムで構築するために必要な基本的なメソッドとプロパティを定義します。属性設定機能を含むように IAttributeSetter インターフェイスを拡張しています。

```csharp
public interface ISVGElementBuilder : IAttributeSetter
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/isvgelementbuilder/configurations/) { get; } | ビルドプロセス中に SVGElement に適用されるアクションまたは構成のリストです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [BuildElement](../../aspose.svg.builder/isvgelementbuilder/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | ビルダーの現在の構成に基づいて SVGElement インスタンスを構築し、返します。 |

### 参照

* interface [IAttributeSetter](../iattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

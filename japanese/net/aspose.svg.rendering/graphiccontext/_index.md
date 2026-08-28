---
title: "GraphicContext クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Rendering.GraphicContext クラス。現在のグラフィック制御パラメータを保持します。これらのパラメータは、グラフィック演算子が実行されるグローバルフレームワークを定義します。"
type: docs
weight: 4880
url: /ja/net/aspose.svg.rendering/graphiccontext/
---
## GraphicContext class

現在のグラフィック制御パラメータを保持します。これらのパラメータは、グラフィック演算子が実行されるグローバルフレームワークを定義します。

```csharp
public class GraphicContext : ICloneable
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [GraphicContext](graphiccontext/)() | `GraphicContext` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.svg.rendering/graphiccontext/characterspacing/) { get; set; } | Sets or gets character spacing. |
| [CurrentElement](../../aspose.svg.rendering/graphiccontext/currentelement/) { get; } | Gets current processed element. |
| virtual [FillBrush](../../aspose.svg.rendering/graphiccontext/fillbrush/) { get; set; } | Sets or gets the brush object that is used to fill the interiors of paths. |
| virtual [Font](../../aspose.svg.rendering/graphiccontext/font/) { get; set; } | Sets or gets the true type font object that is used for rendering text. |
| virtual [FontSize](../../aspose.svg.rendering/graphiccontext/fontsize/) { get; set; } | テキストのフォントサイズを設定または取得します。 |
| virtual [FontStyle](../../aspose.svg.rendering/graphiccontext/fontstyle/) { get; set; } | テキストのフォントスタイルを設定または取得します。 |
| virtual [LineCap](../../aspose.svg.rendering/graphiccontext/linecap/) { get; set; } | ストロークされた任意の開いたパスのエンドポイントの形状を指定するコードを設定または取得します。 |
| virtual [LineDashOffset](../../aspose.svg.rendering/graphiccontext/linedashoffset/) { get; set; } | 現在の線の破線パターンの位相オフセットを設定または取得します。 |
| virtual [LineDashPattern](../../aspose.svg.rendering/graphiccontext/linedashpattern/) { get; set; } | パスがストロークされる際に使用される破線パターンの説明を設定または取得します。null または空の配列に設定すると無効化できます。 |
| virtual [LineJoin](../../aspose.svg.rendering/graphiccontext/linejoin/) { get; set; } | ストロークされたパスの接続されたセグメント間のジョイントの形状を指定するコードを設定または取得します。 |
| virtual [LineWidth](../../aspose.svg.rendering/graphiccontext/linewidth/) { get; set; } | ストロークされるパスの太さを設定または取得します。 |
| virtual [MiterLimit](../../aspose.svg.rendering/graphiccontext/miterlimit/) { get; set; } | ストロークされたパスのマイタージョインの最大長さを設定または取得します。このパラメータは、線分が鋭角で結合したときに生成される\"スパイク\"の長さを制限します。 |
| virtual [StrokeBrush](../../aspose.svg.rendering/graphiccontext/strokebrush/) { get; set; } | ストロークされたパスに使用されるブラシオブジェクトを設定または取得します。 |
| virtual [TextInfo](../../aspose.svg.rendering/graphiccontext/textinfo/) { get; } | [`TextInfo`](../textinfo/) オブジェクトを取得します。このオブジェクトはレンダリングされたテキストに関する情報を含みます。 |
| virtual [TransformationMatrix](../../aspose.svg.rendering/graphiccontext/transformationmatrix/) { get; set; } | 変換行列を設定または取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [Clone](../../aspose.svg.rendering/graphiccontext/clone/)() | 既存のインスタンスと同じプロパティ値を持つ GraphicContext クラスの新しいインスタンスを作成します。 |
| virtual [Transform](../../aspose.svg.rendering/graphiccontext/transform/)(*[IMatrix](../../aspose.svg.drawing/imatrix/)*) | 指定された行列を掛け算して現在の変換行列を変更します。 |

### 参照

* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)

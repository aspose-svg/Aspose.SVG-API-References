---
title: "IDevice インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Rendering.IDevice インターフェイス。パス、テキスト、画像などのグラフィック要素のカスタムレンダリングをサポートするメソッドとプロパティを定義します。"
type: docs
weight: 4890
url: /ja/net/aspose.svg.rendering/idevice/
---
## IDevice interface

パス、テキスト、画像などのグラフィック要素のカスタムレンダリングをサポートするメソッドとプロパティを定義します。

```csharp
public interface IDevice : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/idevice/graphiccontext/) { get; } | グラフィック コンテキストを取得します。 |
| [Options](../../aspose.svg.rendering/idevice/options/) { get; } | レンダリング オプションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddRect](../../aspose.svg.rendering/idevice/addrect/)(*RectangleF*) | 現在のパスに矩形を完全なサブパスとして追加します。 |
| [BeginDocument](../../aspose.svg.rendering/idevice/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | ドキュメントのレンダリングを開始します。 |
| [BeginElement](../../aspose.svg.rendering/idevice/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | 要素のレンダリングを開始します。 |
| [BeginPage](../../aspose.svg.rendering/idevice/beginpage/)(*SizeF*) | 新しいページのレンダリングを開始します。 |
| [Clip](../../aspose.svg.rendering/idevice/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | FillRule を使用して塗りつぶす領域を決定し、現在のパスと交差させて現在のクリッピングパスを変更します。このメソッドは現在のパスを終了します。 |
| [ClosePath](../../aspose.svg.rendering/idevice/closepath/)() | 現在の点からサブパスの開始点まで直線セグメントを追加して現在のサブパスを閉じます。現在のサブパスがすでに閉じている場合、"ClosePath" は何もしません。この演算子は現在のサブパスを終了します。現在のパスに別のセグメントを追加すると、新しいサブパスが開始されます。たとえ新しいセグメントが "ClosePath" メソッドで到達した終点から始まっても同様です。 |
| [CubicBezierTo](../../aspose.svg.rendering/idevice/cubicbezierto/)(*PointF, PointF, PointF*) | 現在のパスに3次ベジェ曲線を追加します。曲線は現在の点から点 pt3 まで伸び、pt1 と pt2 をベジェ制御点として使用します。新しい現在の点は pt3 です。 |
| [DrawImage](../../aspose.svg.rendering/idevice/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | 指定された画像を描画します。 |
| [EndDocument](../../aspose.svg.rendering/idevice/enddocument/)() | ドキュメントのレンダリングを終了します。 |
| [EndElement](../../aspose.svg.rendering/idevice/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | 要素のレンダリングを終了します。 |
| [EndPage](../../aspose.svg.rendering/idevice/endpage/)() | 現在のページのレンダリングを終了します。 |
| [Fill](../../aspose.svg.rendering/idevice/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | 現在のパスで囲まれた領域全体を塗りつぶします。パスが複数の切り離されたサブパスで構成されている場合、すべてのサブパスの内部をまとめて塗りつぶします。このメソッドは現在のパスを終了します。 |
| [FillText](../../aspose.svg.rendering/idevice/filltext/)(*string, PointF*) | 指定された位置に指定されたテキスト文字列を塗りつぶします。 |
| [Flush](../../aspose.svg.rendering/idevice/flush/)() | すべてのデータを出力ストリームにフラッシュします。 |
| [LineTo](../../aspose.svg.rendering/idevice/lineto/)(*PointF*) | 現在の点から点 (pt) まで直線セグメントを追加します。新しい現在の点は pt です。 |
| [MoveTo](../../aspose.svg.rendering/idevice/moveto/)(*PointF*) | パラメータ pt の座標に現在の点を移動させ、接続線セグメントを省略することで新しいサブパスを開始します。現在のパスで前のパス構築メソッドが "MoveTo" でも、新しい "MoveTo" がそれを上書きします。パス内に前の "MoveTo" 操作の痕跡は残りません。 |
| [RestoreGraphicContext](../../aspose.svg.rendering/idevice/restoregraphiccontext/)() | スタックからポップして、グラフィック コンテキスト全体を元の値に復元します。 |
| [SaveGraphicContext](../../aspose.svg.rendering/idevice/savegraphiccontext/)() | グラフィック コンテキスト全体のコピーをスタックにプッシュします。 |
| [Stroke](../../aspose.svg.rendering/idevice/stroke/)() | 現在のパスに沿って線を描画します。描画された線はパス内の各直線または曲線セグメントに沿い、セグメントの中心に位置し、側面はそれに平行です。パスの各サブパスは個別に処理されます。このメソッドは現在のパスを終了します。 |
| [StrokeAndFill](../../aspose.svg.rendering/idevice/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | 現在のパスを描画し塗りつぶします。このメソッドは現在のパスを終了します。 |
| [StrokeText](../../aspose.svg.rendering/idevice/stroketext/)(*string, PointF*) | 指定された位置に指定されたテキスト文字列を描画します。 |

### 参照

* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)

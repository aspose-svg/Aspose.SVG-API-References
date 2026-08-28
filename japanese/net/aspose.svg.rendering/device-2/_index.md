---
title: "DeviceTGraphicContextTRenderingOptions クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Rendering.Device2TGraphicContextTRenderingOptions クラス。特定のレンダリングデバイス実装の基底クラスを表します。"
type: docs
weight: 4820
url: /ja/net/aspose.svg.rendering/device-2/
---
## Device<TGraphicContext,TRenderingOptions> class

特定のレンダリングデバイスの実装のための基底クラスを表します。

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| パラメータ | 説明 |
| --- | --- |
| TGraphicContext | 現在のグラフィック制御パラメータを保持するグラフィックコンテキスト |
| TRenderingOptions | レンダリングオプション |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } | グラフィックコンテキストを取得します。 |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } | レンダリング オプションを取得します。 |
| virtual [Configuration](../../aspose.svg.rendering/device-2/configuration/) { get; } | デバイス構成を取得します。 |
| [OutputStream](../../aspose.svg.rendering/device-2/outputstream/) { get; } | 出力ストリームを設定および取得します。 |
| [StreamProvider](../../aspose.svg.rendering/device-2/streamprovider/) { get; } | ストリームプロバイダーオブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [AddRect](../../aspose.svg.rendering/device-2/addrect/)(*RectangleF*) | 現在のパスに矩形を完全なサブパスとして追加します。 |
| virtual [BeginDocument](../../aspose.svg.rendering/device-2/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | ドキュメントのレンダリングを開始します。 |
| virtual [BeginElement](../../aspose.svg.rendering/device-2/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | ノードのレンダリングを開始します。 |
| virtual [BeginPage](../../aspose.svg.rendering/device-2/beginpage/)(*SizeF*) | 新しいページのレンダリングを開始します。 |
| virtual [Clip](../../aspose.svg.rendering/device-2/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | FillRule を使用して塗りつぶす領域を決定し、現在のパスと交差させて現在のクリッピングパスを変更します。このメソッドは現在のパスを終了します。 |
| virtual [ClosePath](../../aspose.svg.rendering/device-2/closepath/)() | 現在の点からサブパスの開始点まで直線セグメントを追加して現在のサブパスを閉じます。現在のサブパスがすでに閉じている場合、"ClosePath" は何もしません。この演算子は現在のサブパスを終了します。現在のパスに別のセグメントを追加すると、新しいサブパスが開始されます。たとえ新しいセグメントが "ClosePath" メソッドで到達した終点から始まっても同様です。 |
| virtual [CubicBezierTo](../../aspose.svg.rendering/device-2/cubicbezierto/)(*PointF, PointF, PointF*) | 現在のパスに3次ベジエ曲線を追加します。曲線は現在の点から pt2 まで伸び、pt1 と pt2 をベジエ制御点として使用します。新しい現在の点は pt3 です。 |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() | アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| virtual [DrawImage](../../aspose.svg.rendering/device-2/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | 指定された画像を描画します。 |
| virtual [EndDocument](../../aspose.svg.rendering/device-2/enddocument/)() | ドキュメントのレンダリングを終了します。 |
| virtual [EndElement](../../aspose.svg.rendering/device-2/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | ノードのレンダリングを終了します。 |
| virtual [EndPage](../../aspose.svg.rendering/device-2/endpage/)() | 現在のページのレンダリングを終了します。 |
| virtual [Fill](../../aspose.svg.rendering/device-2/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | 現在のパスで囲まれた領域全体を塗りつぶします。パスが複数の切り離されたサブパスで構成されている場合、すべてのサブパスの内部をまとめて塗りつぶします。このメソッドは現在のパスを終了します。 |
| virtual [FillText](../../aspose.svg.rendering/device-2/filltext/)(*string, PointF*) | 指定された位置に指定されたテキスト文字列を塗りつぶします。 |
| virtual [Flush](../../aspose.svg.rendering/device-2/flush/)() | すべてのデータを出力ストリームにフラッシュします。 |
| virtual [LineTo](../../aspose.svg.rendering/device-2/lineto/)(*PointF*) | 現在の点から点 (pt) まで直線セグメントを追加します。新しい現在の点は pt です。 |
| virtual [MoveTo](../../aspose.svg.rendering/device-2/moveto/)(*PointF*) | パラメータ pt の座標に現在の点を移動させ、接続線セグメントを省略することで新しいサブパスを開始します。現在のパスで前のパス構築メソッドが "MoveTo" でも、新しい "MoveTo" がそれを上書きします。パス内に前の "MoveTo" 操作の痕跡は残りません。 |
| virtual [RestoreGraphicContext](../../aspose.svg.rendering/device-2/restoregraphiccontext/)() | スタックからポップして、グラフィック コンテキスト全体を元の値に復元します。 |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device-2/savegraphiccontext/)() | グラフィック コンテキスト全体のコピーをスタックにプッシュします。 |
| virtual [Stroke](../../aspose.svg.rendering/device-2/stroke/)() | 現在のパスに沿って線を描画します。描画された線はパス内の各直線または曲線セグメントに沿い、セグメントの中心に位置し、側面はそれに平行です。パスの各サブパスは個別に処理されます。このメソッドは現在のパスを終了します。 |
| virtual [StrokeAndFill](../../aspose.svg.rendering/device-2/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | 現在のパスを描画し塗りつぶします。このメソッドは現在のパスを終了します。 |
| virtual [StrokeText](../../aspose.svg.rendering/device-2/stroketext/)(*string, PointF*) | 指定された位置に指定されたテキスト文字列を描画します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [DeviceConfiguration<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.deviceconfiguration-2) | デバイス用の構成オブジェクトを表します。 |
| enum [PageWritingStrategy<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.pagewritingstrategy-2) | ページを出力ストリーム\streams に書き込むための戦略タイプを指定します。 |

### 参照

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)

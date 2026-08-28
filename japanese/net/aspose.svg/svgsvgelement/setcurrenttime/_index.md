---
title: "SVGSVGElement.SetCurrentTime"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGSVGElement SetCurrentTime メソッド。この SVG ドキュメントフラグメントの時計を調整し、新しい現在時刻を設定します。たとえば、ドキュメントの SVGLoad イベントがディスパッチされる前に script 要素内のスクリプトが実行されるなど、ドキュメントタイムラインが開始される前に setCurrentTime が呼び出された場合、メソッドの最後の呼び出しで渡された秒数が、タイムライン開始後にドキュメントがシークする時刻となります"
type: docs
weight: 230
url: /ja/net/aspose.svg/svgsvgelement/setcurrenttime/
---
## SVGSVGElement.SetCurrentTime method

この SVG ドキュメントフラグメントのクロックを調整し、新しい現在時刻を設定します。setCurrentTime がドキュメントのタイムライン開始前に呼び出された場合（例として、ドキュメントの SVGLoad イベントがディスパッチされる前に ‘script’ 要素内で実行されるスクリプトなど）、メソッドの最後の呼び出しで指定された秒数の値が、ドキュメントのタイムラインが開始したときにドキュメントがシークする時刻となります。

```csharp
public void SetCurrentTime(float seconds)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 秒 | Single | 現在の SVG ドキュメントフラグメントの開始時刻からの相対秒数で示す新しい現在時刻。 |

### 参照

* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

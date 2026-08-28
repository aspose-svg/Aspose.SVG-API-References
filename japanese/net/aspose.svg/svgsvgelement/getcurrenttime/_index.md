---
title: "SVGSVGElement.GetCurrentTime"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGSVGElement GetCurrentTime メソッド。現在の SVG ドキュメントフラグメントの開始時刻からの相対秒数で現在時刻を返します。たとえば、ドキュメントの SVGLoad イベントがディスパッチされる前に script 要素内のスクリプトが実行されるなど、ドキュメントタイムラインが開始される前に getCurrentTime が呼び出された場合は 0 が返されます"
type: docs
weight: 200
url: /ja/net/aspose.svg/svgsvgelement/getcurrenttime/
---
## SVGSVGElement.GetCurrentTime method

現在の SVG ドキュメントフラグメントの開始時刻からの経過秒数を返します。getCurrentTime がドキュメントのタイムライン開始前に呼び出された場合（例として、ドキュメントの SVGLoad イベントがディスパッチされる前に ‘script’ 要素内で実行されるスクリプトなど）、0 が返されます。

```csharp
public float GetCurrentTime()
```

### 戻り値

現在の時刻（秒単位）。ドキュメントタイムラインがまだ開始されていない場合は 0 です。

### 参照

* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

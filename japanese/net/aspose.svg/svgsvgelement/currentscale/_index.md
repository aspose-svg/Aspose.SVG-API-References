---
title: "SVGSVGElement.CurrentScale"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGSVGElement CurrentScale プロパティ。最外層の svg 要素では、この属性はユーザーの拡大縮小およびパン操作（「拡大縮小とパン」セクションで説明）を考慮した、初期ビューに対する現在のスケール係数を示します。DOM 属性 currentScale と currentTranslate は 2x3 行列 a b c d e f に相当し、currentScale 0 0 currentScale currentTranslate.x currentTranslate.y となります。拡大縮小が有効（例: zoomAndPan='magnify'）な場合、効果は SVG ドキュメントフラグメントの最外層レベル、すなわち最外層 svg 要素の外側に余分な変換が配置されたかのようになります。最外層でない svg 要素でアクセスした場合、この属性の動作は未定義です。"
type: docs
weight: 10
url: /ja/net/aspose.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

最外層の svg 要素において、この属性はユーザーの拡大縮小やパン操作を考慮した、初期ビューに対する現在のスケール係数を示します（「拡大縮小とパン」の項で説明）。DOM 属性 currentScale と currentTranslate は 2x3 行列 [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y] と同等です。\"magnification\" が有効（例: zoomAndPan=\"magnify\"）な場合、追加の変換が SVG ドキュメントフラグメントの最外層（最外層の svg 要素の外側）に配置されたかのように作用します。最外層でない ‘svg’ 要素でこの属性にアクセスした場合、その動作は未定義です。

```csharp
public float CurrentScale { get; set; }
```

### Property Value

現在のスケールです。

### 参照

* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

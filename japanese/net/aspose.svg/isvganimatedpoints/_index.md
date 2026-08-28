---
title: "ISSVGAnimatedPoints インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.ISVGAnimatedPoints インターフェイス。SVGAnimatedPoints インターフェイスは、座標値のリストを保持する points 属性を持ち、その属性をアニメーション化できる要素をサポートします。さらに、XML DOM を介して取得した元の要素の points 属性（例: getAttribute メソッド呼び出し）は、points に対する変更を反映します。"
type: docs
weight: 4070
url: /ja/net/aspose.svg/isvganimatedpoints/
---
## ISVGAnimatedPoints interface

SVGAnimatedPoints インターフェイスは、座標値のリストを保持する ‘points’ 属性を持ち、その属性をアニメーション化できる要素をサポートします。さらに、XML DOM を介して取得した元の要素の ‘points’ 属性（例：getAttribute() メソッド呼び出しを使用）は、points に加えられた変更を反映します。

```csharp
public interface ISVGAnimatedPoints
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AnimatedPoints](../../aspose.svg/isvganimatedpoints/animatedpoints/) { get; } | ‘points’ 属性の現在のアニメーション化された内容へのアクセスを提供します。指定された属性またはプロパティがアニメーション化されている場合、その属性またはプロパティの現在のアニメーション値が含まれます。アニメーション化されていない場合は、points と同じ値が含まれます。 |
| [Points](../../aspose.svg/isvganimatedpoints/points/) { get; } | ‘points’属性の基本（すなわち静的）内容へのアクセスを提供します。 |

### 参照

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

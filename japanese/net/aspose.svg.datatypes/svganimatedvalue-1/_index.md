---
title: "SVGAnimatedValueT クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.DataTypes.SVGAnimatedValue1T クラス。アニメーション可能なタイプの属性に使用されます"
type: docs
weight: 2200
url: /ja/net/aspose.svg.datatypes/svganimatedvalue-1/
---
## SVGAnimatedValue<T> class

アニメーション化可能な型の属性に使用されます。

```csharp
public abstract class SVGAnimatedValue<T> : SVGValueType
```

| パラメータ | 説明 |
| --- | --- |
| T | SVG Value オブジェクトです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [AnimVal](../../aspose.svg.datatypes/svganimatedvalue-1/animval/) { get; } | 指定された属性またはプロパティがアニメーション中の場合、その属性またはプロパティの現在のアニメーション値が含まれます。指定された属性またはプロパティが現在アニメーションされていない場合、baseVal と同じ値が含まれます。 |
| [BaseVal](../../aspose.svg.datatypes/svganimatedvalue-1/baseval/) { get; set; } | アニメーションを適用する前の、指定された属性の基本値です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | アンマネージドリソースと、オプションでマネージドリソースを解放します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |

### 参照

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)

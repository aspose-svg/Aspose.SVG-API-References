---
title: "ISVGAnimatedPathData インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Paths.ISVGAnimatedPathData インターフェイス。SVGAnimatedPathData インターフェイスは、SVG パスデータを保持する d 属性を持つ要素をサポートし、その属性をアニメーション化する機能を提供します"
type: docs
weight: 4550
url: /ja/net/aspose.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

SVGAnimatedPathData インターフェイスは、SVG パスデータを保持する ‘d’ 属性を持つ要素をサポートし、その属性をアニメーション化する機能もサポートします。

```csharp
public interface ISVGAnimatedPathData
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AnimatedPathSegList](../../aspose.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | ‘d’ 属性の現在のアニメーション化された内容に、SVG の構文と 1 対 1 に対応する形でアクセスできるようにします。対象の属性またはプロパティがアニメーション中であれば、その属性またはプロパティの現在のアニメーション値を含み、オブジェクト自体とその内容は読み取り専用です。対象の属性またはプロパティが現在アニメーションされていない場合は、pathSegList と同じ値を含みます。 |
| [PathSegList](../../aspose.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | ‘d’ 属性の基本（すなわち静的）内容に、SVG の構文と 1 対 1 に対応する形でアクセスできるようにします。そのため、‘d’ 属性に「絶対 moveto (M)」と「絶対 arcto (A)」コマンドがある場合、pathSegList には 2 つのエントリが含まれます：SVG_PATHSEG_MOVETO_ABS と SVG_PATHSEG_ARC_ABS。 |

### 参照

* namespace [Aspose.Svg.Paths](../../aspose.svg.paths/)
* assembly [Aspose.SVG](../../)

---
title: "ISVGAnimatedPathData.PathSegList"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "ISVGAnimatedPathData PathSegList プロパティ。SVG の構文と 1 対 1 に一致する形式で、d 属性の基本（すなわち静的）内容へのアクセスを提供します。そのため、d 属性に絶対 moveto M と絶対 arcto A コマンドがある場合、pathSegList には SVG_PATHSEG_MOVETO_ABS と SVG_PATHSEG_ARC_ABS の 2 つのエントリが含まれます。"
type: docs
weight: 20
url: /ja/net/aspose.svg.paths/isvganimatedpathdata/pathseglist/
---
## ISVGAnimatedPathData.PathSegList property

‘d’ 属性の基本（すなわち静的）内容に、SVG の構文と 1 対 1 に対応する形でアクセスできるようにします。そのため、‘d’ 属性に「絶対 moveto (M)」と「絶対 arcto (A)」コマンドがある場合、pathSegList には 2 つのエントリが含まれます：SVG_PATHSEG_MOVETO_ABS と SVG_PATHSEG_ARC_ABS。

```csharp
public SVGPathSegList PathSegList { get; }
```

### Property Value

パスセグメントリスト。

### 参照

* class [SVGPathSegList](../../svgpathseglist/)
* interface [ISVGAnimatedPathData](../)
* namespace [Aspose.Svg.Paths](../../../aspose.svg.paths/)
* assembly [Aspose.SVG](../../../)

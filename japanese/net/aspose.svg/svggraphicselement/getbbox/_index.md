---
title: "SVGGraphicsElement.GetBBox"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGGraphicsElement GetBBox メソッド。現在のユーザー空間（つまり、含まれるすべてのグラフィック要素のジオメトリに対して transform 属性が適用された後）の厳密なバウンディングボックスを返します。ストローク、クリッピング、マスキング、フィルター効果は除外されます。要素がまだ描画されていない場合でも、メソッドが呼び出された時点の実際のバウンディングボックスを返す必要があることに注意してください。"
type: docs
weight: 70
url: /ja/net/aspose.svg/svggraphicselement/getbbox/
---
## SVGGraphicsElement.GetBBox method

すべての含まれるグラフィック要素のジオメトリに対し、現在のユーザー空間（つまり、存在する場合は ‘transform’ 属性が適用された後）でのタイトなバウンディングボックスを返します（ストローク、クリッピング、マスク、フィルター効果は除外）。なお、要素がまだ描画されていない場合でも、メソッドが呼び出された時点の実際のバウンディングボックスを getBBox が返す必要があります。

```csharp
public SVGRect GetBBox()
```

### 戻り値

バウンディングボックスを定義する SVGRect オブジェクトです。

### 参照

* class [SVGRect](../../../aspose.svg.datatypes/svgrect/)
* class [SVGGraphicsElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

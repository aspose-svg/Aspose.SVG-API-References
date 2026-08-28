---
title: "Aspose.Svg.ImageVectorization"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.ImageVectorization 名前空間には、ラスタ画像をベクトル化し SVG ドキュメントに変換するクラスが含まれています。このプロセスは、ビットマップをパス要素で構成された幾何学的形状に縮小し、SVG として保存することを含みます。名前空間には、パスセグメントの構築、トレースポイントの単純化と平滑化、ベクトル化オプションの設定を行うクラスが含まれています。"
type: docs
weight: 190
url: /ja/net/aspose.svg.imagevectorization/
---
**Aspose.Svg.ImageVectorization** 名前空間には、ラスタ画像をベクトル化し SVG ドキュメントに変換するクラスが含まれています。このプロセスは、ビットマップをパス要素からなる幾何学的形状に変換し、SVG として保存することを伴います。名前空間には、パスセグメントの構築、トレースポイントの単純化と平滑化、ベクトル化オプションの設定のためのクラスが含まれています。

## クラス

| クラス | 説明 |
| --- | --- |
| [BezierPathBuilder](./bezierpathbuilder/) | [`BezierPathBuilder`](../aspose.svg.imagevectorization/bezierpathbuilder/) クラスは、与えられた点の集合からベジエパスを構築する役割を担います。ベジエ曲線で点のトレースを近似し、元のトレースにできるだけ近く合致させつつ複雑さを最小化するようにセグメント数を最適化します。 |
| [ImageTraceSimplifier](./imagetracesimplifier/) | ImageTraceSimplifier クラスは、トレースポイントの系列で近似された曲線の点数を削減する役割を担います。 |
| [ImageTraceSmoother](./imagetracesmoother/) | ImageTraceSimplifier クラスは、トレースポイントの系列で近似された曲線の点数を平滑化する役割を担います。このクラスは最近傍法を実装しています。 |
| [ImageVectorizer](./imagevectorizer/) | この ImageVectorizer クラスは PNG、JPG、GIF、BMP などのラスタ画像をベクトル化し、SVGDocument を返します。ベクトル化とは、ビットマップをパス要素で構成された幾何学的形状に縮小し、SVG として保存するプロセスを指します。 |
| [ImageVectorizerConfiguration](./imagevectorizerconfiguration/) | この [`ImageVectorizerConfiguration`](../aspose.svg.imagevectorization/imagevectorizerconfiguration/) クラスは画像ベクトル化手法とオプションの構成を定義します。この構成は ImageVectorizer を初期化するために使用され、画像をベクトル化するための構成オプションを提供します。 |
| [SplinePathBuilder](./splinepathbuilder/) | この [`SplinePathBuilder`](../aspose.svg.imagevectorization/splinepathbuilder/) クラスは、遠心的 Catmull–Rom スプラインをベジェ曲線に変換して滑らかなパスを構築するよう設計されています。ポイントの集合を滑らかに補間するパスを生成するメソッドを提供し、ポイントへの忠実度と曲線の滑らかさのバランスを取ります。 |
| [StencilConfiguration](./stencilconfiguration/) | この [`StencilConfiguration`](../aspose.svg.imagevectorization/stencilconfiguration/) クラスはステンシル効果オプションの構成を定義します。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IImageTraceSimplifier](./iimagetracesimplifier/) | IImageTraceSimplifier インターフェイスはトレース内のポイントの削減を担当します。 |
| [IImageTraceSmoother](./iimagetracesmoother/) | IImageTraceSmoother インターフェイスはトレースの平滑化を担当します。 |
| [IPathBuilder](./ipathbuilder/) | IPathBuilder インターフェイスはトレースポイントのリストからパスセグメント [`SVGPathSeg`](../aspose.svg.paths/svgpathseg/) を構築することを担当します。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [StencilType](./stenciltype/) | この [`StencilType`](../aspose.svg.imagevectorization/stenciltype/) 列挙型はステンシルタイプを定義します。 |

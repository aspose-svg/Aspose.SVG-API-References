---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGGraphicsElement GetScreenCTM メソッド。現在のユーザー単位（つまり、transform 属性が適用された後）から親ユーザーエージェントがピクセルとして認識する単位への変換行列を返します。表示デバイスでは理想的には物理的な画面ピクセルを表します。物理ピクセルサイズが不明な他のデバイスや環境では、CSS2 のピクセル定義に類似したアルゴリズムが使用されます。要素がドキュメントツリーに接続されていない場合は null が返されます。このメソッドは本来 getClientCTM と名付けた方が適切ですが、歴史的理由で getScreenCTM という名前が維持されています。"
type: docs
weight: 90
url: /ja/net/aspose.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

現在のユーザー単位（つまり、存在する場合は ‘transform’ 属性が適用された後）から親ユーザーエージェントの「pixel」の概念への変換行列を返します。表示デバイスの場合、理想的には物理的な画面ピクセルを表します。物理的なピクセルサイズが不明な他のデバイスや環境では、CSS2 の「pixel」定義に類似したアルゴリズムを使用できます。要素がドキュメントツリーに接続されていない場合は null が返されます。このメソッドは本来 getClientCTM と名付ける方が適切ですが、歴史的理由により getScreenCTM という名前が維持されています。

```csharp
public SVGMatrix GetScreenCTM()
```

### 戻り値

指定された変換行列を定義する SVGMatrix オブジェクトです。

### 参照

* class [SVGMatrix](../../../aspose.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

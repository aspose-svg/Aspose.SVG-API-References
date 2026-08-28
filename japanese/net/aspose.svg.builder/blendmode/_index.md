---
title: "BlendMode 列挙体"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.BlendMode 列挙体。SVG で画像や要素を結合する際に利用できるブレンドモードを指定します。"
type: docs
weight: 80
url: /ja/net/aspose.svg.builder/blendmode/
---
## BlendMode enumeration

SVG で画像や要素を合成する際に利用できるブレンドモードを指定します。

```csharp
public enum BlendMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Normal | `0` | ブレンドせずに、ソース画像をそのまま表示します。 |
| Multiply | `1` | ソース画像と背景の色を乗算します。結果は暗い画像になります。 |
| Screen | `2` | ソース画像の暗い部分を明るくし、明るい部分は変えません。 |
| Overlay | `3` | 乗算とスクリーンのブレンドモードを組み合わせてコントラストを強調します。 |
| Darken | `4` | ソース画像の色に基づいて背景を暗くします。 |
| Lighten | `5` | ソース画像の色に基づいて背景を明るくします。 |
| ColorDodge | `6` | 背景を明るくしてソース画像を反映させます。 |
| ColorBurn | `7` | 背景を暗くしてソース画像を反映させます。 |
| HardLight | `8` | ソース画像の明るさに基づいてハードライト効果を作成します。 |
| SoftLight | `9` | ソース画像の明るさに基づいてソフトライト効果を作成します。 |
| Difference | `10` | ソース画像と背景の違いを強調します。 |
| Exclusion | `11` | Difference に似た効果を作成しますが、コントラストは低くなります。 |
| Hue | `12` | ソース画像の色相と背景の輝度・彩度を組み合わせて使用します。 |
| Saturation | `13` | ソース画像の彩度と背景の色相・輝度を組み合わせて使用します。 |
| Color | `14` | ソース画像の色相と彩度を背景の輝度と組み合わせて使用します。 |
| Luminosity | `15` | ソース画像の輝度を背景の色相と彩度と組み合わせて使用します。 |

## 備考

SVG のブレンドモードは、2 つのレイヤーがどのように相互にブレンドされるかを決定するために使用されます。この列挙体は、ブレンドされたレイヤーの色がどのように混ざり合い、さまざまな視覚効果を生み出すかを制御する多様なオプションを提供します。

### 参照

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

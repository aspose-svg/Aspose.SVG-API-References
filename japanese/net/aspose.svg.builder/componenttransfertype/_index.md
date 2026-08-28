---
title: "ComponentTransferType 列挙型"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.ComponentTransferType 列挙型。SVG の FeComponentTransfer フィルタプリミティブに適用されるコンポーネント転送関数のタイプを指定します"
type: docs
weight: 170
url: /ja/net/aspose.svg.builder/componenttransfertype/
---
## ComponentTransferType enumeration

SVG の FeComponentTransfer フィルタプリミティブで適用されるコンポーネント転送関数のタイプを指定します。

```csharp
public enum ComponentTransferType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Identity | `0` | 入力グラフィックに変更がないことを表します。これはデフォルトのタイプです。 |
| Table | `1` | フィルタ内の関数を定義するためにルックアップテーブルを使用します。 |
| Discrete | `2` | フィルタ内の関数を定義するために離散値のセットを使用します。 |
| Linear | `3` | フィルタ内のコンポーネントの線形変換を定義します。 |
| Gamma | `4` | フィルタ内でガンマ補正変換を定義します。 |

## 備考

FeComponentTransfer フィルタプリミティブは、異なるタイプの転送関数を使用して、グラフィック要素のカラーコンポーネント（RGB とアルファ）を個別に操作できるようにします。各タイプは、フィルタ内でのカラーコンポーネント変換の計算方法を異に定義します。

### 参照

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

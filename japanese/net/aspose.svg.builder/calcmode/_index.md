---
title: "CalcMode 列挙体"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.CalcMode 列挙体。SVG アニメーションで値を補間するための計算モードを指定します。"
type: docs
weight: 90
url: /ja/net/aspose.svg.builder/calcmode/
---
## CalcMode enumeration

SVG アニメーションにおける値の補間計算モードを指定します。

```csharp
public enum CalcMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Discrete | `0` | アニメーションは補間せずに、ある値から次の値へジャンプします。 |
| Linear | `1` | アニメーションの値は、アニメーション期間全体で線形に補間されます。 |
| Paced | `2` | アニメーションは、全体の進行が均等になるようにペースが設定されています。 |
| Spline | `3` | アニメーションは、値を補間するために三次ベジェスプラインを使用します。 |

## 備考

計算モードは、SVG アニメーションがアニメーションの進行中に値間をどのように遷移するかを決定します。さまざまなモードを使用して、さまざまな効果を作り出し、アニメーションのペースと滑らかさを制御できます。

### 参照

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

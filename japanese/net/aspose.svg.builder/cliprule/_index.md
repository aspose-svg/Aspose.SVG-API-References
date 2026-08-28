---
title: "ClipRule 列挙型"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.ClipRule 列挙型。SVG グラフィックでパスをどのようにクリップするかを決定するルールを定義します。"
type: docs
weight: 120
url: /ja/net/aspose.svg.builder/cliprule/
---
## ClipRule enumeration

SVG グラフィックスでパスをクリップする方法を決定するルールを定義します。

```csharp
public enum ClipRule
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Nonzero | `0` | パスをクリップするための非ゼロ winding ルールです。 |
| Evenodd | `1` | パスをクリップするための偶数-奇数 winding ルールです。 |

## 備考

SVG の clip rule プロパティは、パスがどのようにクリップされるかを決定します。パスが自分自身と交差する場合や複数のパスが結合される場合に特に重要です。このルールは、パスのどの部分が「内部」とみなされ塗りつぶし（または表示）され、どの部分が「外部」とみなされクリップ（または非表示）されるかを判断するのに役立ちます。

### 参照

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

---
title: "Element.AttachShadow"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Element AttachShadow メソッド。shadow root を作成し、現在の要素にアタッチします。"
type: docs
weight: 220
url: /ja/net/aspose.svg.dom/element/attachshadow/
---
## Element.AttachShadow method

shadow root を作成し、現在の要素にアタッチします。

```csharp
public ShadowRoot AttachShadow(ShadowRootMode mode)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mode | ShadowRootMode | シャドウルートが作成されるモード。 |

### 戻り値

作成された[`ShadowRoot`](../../shadowroot/)。

### 例外

| 例外 | 条件 |
| --- | --- |
| エラー | NotSupportedError: 要素はシャドウツリーをサポートしていません。 |
| エラー | InvalidStateError: 要素はすでにシャドウツリーを持っています。 |

### 参照

* class [ShadowRoot](../../shadowroot/)
* enum [ShadowRootMode](../../shadowrootmode/)
* class [Element](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

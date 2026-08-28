---
title: "Resource.Embed"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Resource Embed メソッド。このリソースを Base64 エンコードして親に埋め込みます。エンコード結果は OutputUrl に書き込まれます"
type: docs
weight: 60
url: /ja/net/aspose.svg.saving/resource/embed/
---
## Resource.Embed method

このリソースを Base64 エンコードして親に埋め込みます。エンコード結果は [`OutputUrl`](../outputurl/) に書き込まれます。

```csharp
public Resource Embed(ResourceHandlingContext context)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| context | ResourceHandlingContext | リソース処理コンテキスト。 |

### 戻り値

このリソースは、呼び出しをチェーンできるようにします。

### 例外

| 例外 | 条件 |
| --- | --- |
| InvalidOperationException | 結果を埋め込む場所がないため、[`ParentResource`](../../resourcehandlingcontext/parentresource/) が存在しない場合にスローされます。 |

### 参照

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)

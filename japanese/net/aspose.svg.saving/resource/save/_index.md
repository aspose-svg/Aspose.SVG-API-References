---
title: "Resource.Save"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Resource Save メソッド。リソースを指定されたストリームに保存します。"
type: docs
weight: 70
url: /ja/net/aspose.svg.saving/resource/save/
---
## Resource.Save method

提供されたストリームにリソースを保存します。

```csharp
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | Stream | リソースが保存されるストリームです。 |
| context | ResourceHandlingContext | リソース処理コンテキスト。 |

### 戻り値

このリソースは、呼び出しをチェーンできるようにします。

### 例外

| 例外 | 条件 |
| --- | --- |
| InvalidOperationException | [`OutputUrl`](../outputurl/) が `null` の場合にスローされます。リソースを保存する前に [`OutputUrl`](../outputurl/) を指定する必要があります。そうしないと、このリソースを参照するリソースで正しい参照を指定できなくなります。 |

### 参照

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)

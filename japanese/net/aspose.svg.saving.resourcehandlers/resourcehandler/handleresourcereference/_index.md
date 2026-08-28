---
title: "ResourceHandler.HandleResourceReference"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "ResourceHandler HandleResourceReference メソッド。このメソッドはリソース参照の処理を担当します。このメソッドでは、処理中のリソースへの参照がどのようになるかを設定できます。"
type: docs
weight: 20
url: /ja/net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

このメソッドはリソース参照の処理を担当します。このメソッド内で、処理対象のリソースへの参照がどのようになるかを設定できます。

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resource | Resource | 処理される [`Resource`](../../../aspose.svg.saving/resource/)。 |
| context | ResourceHandlingContext | リソース処理コンテキスト。 |

### 戻り値

現在処理中のリソースへの参照を表す文字列で、親リソースに書き込まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| InvalidOperationException | [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) が `null` で、[`Status`](../../../aspose.svg.saving/resource/status/) が Saved の場合に発生します。保存されたリソースには [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) を指定する必要があります。指定しないと、このリソースを参照するリソースで正しい参照を指定できなくなります。 |

### 参照

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)

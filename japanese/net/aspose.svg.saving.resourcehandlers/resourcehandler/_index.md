---
title: "ResourceHandler クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Saving.ResourceHandlers.ResourceHandler クラス。このクラスはリソースの処理を担当します。Resource に対して何を行うか、また親 Resource に書き込む参照を制御するメソッドを提供します。"
type: docs
weight: 5730
url: /ja/net/aspose.svg.saving.resourcehandlers/resourcehandler/
---
## ResourceHandler class

このクラスはリソースの処理を担当します。[`Resource`](../../aspose.svg.saving/resource/) に対して何を行うか、また親 [`Resource`](../../aspose.svg.saving/resource/) に書き込む参照を制御するメソッドを提供します。

```csharp
public abstract class ResourceHandler
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [HandleResource](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | このメソッドはリソースの処理を担当します。ここでは、[`Resource`](../../aspose.svg.saving/resource/) をストリームに保存したり、親リソースに埋め込んだりできます。 |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | このメソッドはリソース参照の処理を担当します。このメソッド内で、処理対象のリソースへの参照がどのようになるかを設定できます。 |

### 参照

* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)

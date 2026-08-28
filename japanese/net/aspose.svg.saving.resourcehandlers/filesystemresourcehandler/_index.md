---
title: "FileSystemResourceHandler クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Saving.ResourceHandlers.FileSystemResourceHandler クラス。このクラスは ResourceHandler クラスの実装で、リソースをローカルファイルシステムに保存するように設計されています。"
type: docs
weight: 5720
url: /ja/net/aspose.svg.saving.resourcehandlers/filesystemresourcehandler/
---
## FileSystemResourceHandler class

このクラスは [`ResourceHandler`](../resourcehandler/) クラスの実装で、リソースをローカルファイルシステムに保存するように設計されています。

```csharp
public class FileSystemResourceHandler : ResourceHandler
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor_1)(*string*) | `FileSystemResourceHandler` クラスの新しいインスタンスを初期化します。 |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor)(*[Url](../../aspose.svg/url/)*) | `FileSystemResourceHandler` クラスの新しいインスタンスを初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [HandleResource](../../aspose.svg.saving.resourcehandlers/filesystemresourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | このメソッドはリソースの処理を担当します。ここでは、[`Resource`](../../aspose.svg.saving/resource/) をストリームに保存したり、親リソースに埋め込んだりできます。 |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | このメソッドはリソース参照の処理を担当します。このメソッド内で、処理対象のリソースへの参照がどのようになるかを設定できます。 |

### 参照

* class [ResourceHandler](../resourcehandler/)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)

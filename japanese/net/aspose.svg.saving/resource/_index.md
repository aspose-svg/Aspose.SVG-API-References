---
title: "Resource クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Saving.Resource クラス。このクラスはリソースを記述し、処理のためのメソッドを提供します。"
type: docs
weight: 5710
url: /ja/net/aspose.svg.saving/resource/
---
## Resource class

このクラスはリソースを記述し、それを処理するためのメソッドを提供します。

```csharp
public class Resource
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [MimeType](../../aspose.svg.saving/resource/mimetype/) { get; } | このリソースの !:Html.MimeType を返します。リソースが見つからない場合は `null` になる可能性があります。 |
| [OriginalReference](../../aspose.svg.saving/resource/originalreference/) { get; } | このリソースへの元の参照を含む文字列を返します。 |
| [OriginalUrl](../../aspose.svg.saving/resource/originalurl/) { get; } | このリソースが配置されていた場所を示す URL を返します。 |
| [OutputUrl](../../aspose.svg.saving/resource/outputurl/) { get; set; } | 処理後にリソースが配置される場所を示す URL を取得または設定します。 |
| [Status](../../aspose.svg.saving/resource/status/) { get; } | リソースの現在のステータスを返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Embed](../../aspose.svg.saving/resource/embed/)(*[ResourceHandlingContext](../resourcehandlingcontext/)*) | このリソースを Base64 にエンコードして親に埋め込みます。エンコード結果は [`OutputUrl`](./outputurl/) に書き込まれます。 |
| [Save](../../aspose.svg.saving/resource/save/)(*Stream, [ResourceHandlingContext](../resourcehandlingcontext/)*) | 提供されたストリームにリソースを保存します。 |
| [WithOutputUrl](../../aspose.svg.saving/resource/withoutputurl/)(*[Url](../../aspose.svg/url/)*) | 処理後にリソースが配置される場所を示す新しい URL を指定します。 |

### 参照

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)

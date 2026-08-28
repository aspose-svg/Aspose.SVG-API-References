---
title: "ResourceHandlingOptions クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Saving.ResourceHandlingOptions クラス。リソース処理オプションを表します"
type: docs
weight: 5760
url: /ja/net/aspose.svg.saving/resourcehandlingoptions/
---
## ResourceHandlingOptions class

リソース処理オプションを表します。

```csharp
public class ResourceHandlingOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Default](../../aspose.svg.saving/resourcehandlingoptions/default/) { get; set; } | リソース処理のデフォルト方法を表す列挙体を取得または設定します。現在、Save、Ignore、Embed の値がサポートされています。デフォルト値は Save です。 |
| [JavaScript](../../aspose.svg.saving/resourcehandlingoptions/javascript/) { get; set; } | スクリプトの処理方法を表す列挙体を取得または設定します。現在、Save、Ignore、Discard、Embed の値がサポートされています。デフォルト値は Save です。 |
| [MaxHandlingDepth](../../aspose.svg.saving/resourcehandlingoptions/maxhandlingdepth/) { get; set; } | 処理対象となるページの最大深度を取得または設定します。深度が 1 の場合、保存されたドキュメントから直接参照されたページのみが処理されます。このプロパティを -1 に設定すると、すべてのページが処理対象になります。デフォルト値は 0 です。 |
| [PageUrlRestriction](../../aspose.svg.saving/resourcehandlingoptions/pageurlrestriction/) { get; set; } | 処理対象ページの URL に適用される制限を取得または設定します。デフォルト値は RootAndSubFolders です。 |
| [ResourceUrlRestriction](../../aspose.svg.saving/resourcehandlingoptions/resourceurlrestriction/) { get; set; } | CSS、JS、画像などの処理対象リソースの URL に適用される制限を取得または設定します。デフォルト値は SameHost です。 |

### 参照

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)

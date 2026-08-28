---
title: "ReferrerPolicy 列挙型"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.ReferrerPolicy 列挙型。リソース取得時に使用されるリファラポリシーを指定します。"
type: docs
weight: 1020
url: /ja/net/aspose.svg.builder/referrerpolicy/
---
## ReferrerPolicy enumeration

リソース取得時に使用するリファラーポリシーを指定します。

```csharp
public enum ReferrerPolicy
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | リファラポリシーは設定されていません。 |
| NoReferrer | `1` | Referer ヘッダーは送信されません。 |
| NoReferrerWhenDowngrade | `2` | Referer ヘッダーは、セキュリティが低いオリジン（HTTPS -&gt; HTTP）には送信されません。 |
| SameOrigin | `3` | Referer ヘッダーは、同一オリジンのリクエストに対してのみ送信されます。 |
| Origin | `4` | Referer ヘッダーとして送信されるのは、ドキュメントのオリジンのみです。 |
| StrictOrigin | `5` | セキュアコンテキストの場合、Referer ヘッダーとして送信されるのはドキュメントのオリジンのみです。 |
| OriginWhenCrossOrigin | `6` | 同一オリジンのリクエストではフル URL が Referer ヘッダーとして送信され、クロスオリジンのリクエストではオリジンのみが送信されます。 |
| StrictOriginWhenCrossOrigin | `7` | 同一オリジンのリクエストでは、ドキュメントのオリジンのみが Referer ヘッダーとして送信されますが、セキュリティが確保されていないコンテキストでのクロスオリジンリクエストではヘッダーは送信されません。 |
| UnsafeUrl | `8` | パスとクエリ文字列を含む完全な URL が常に Referer ヘッダーとして送信されます。 |

### 参照

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

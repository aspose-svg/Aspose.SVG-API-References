---
title: "MultipartContent クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Net.MultipartContent クラス。マルチパート/ コンテンツを表します"
type: docs
weight: 4460
url: /ja/net/aspose.svg.net/multipartcontent/
---
## MultipartContent class

multipart/* コンテンツを表します。

```csharp
public class MultipartContent : Content, IEnumerable<Content>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MultipartContent](multipartcontent/#constructor)() | `MultipartContent` クラスの新しいインスタンスを作成します。 |
| [MultipartContent](multipartcontent/#constructor_1)(*string*) | `MultipartContent` クラスの新しいインスタンスをサブタイプ付きで作成します。 |
| [MultipartContent](multipartcontent/#constructor_2)(*string, string*) | `MultipartContent` クラスの新しいインスタンスをサブタイプと境界付きで作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Headers](../../aspose.svg.net/content/headers/) { get; } | HTTP コンテンツ ヘッダーを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [Add](../../aspose.svg.net/multipartcontent/add/)(*[Content](../content/)*) | `MultipartContent` に新しいコンテンツを追加します |
| [Dispose](../../aspose.svg.net/content/dispose/)() | アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [GetEnumerator](../../aspose.svg.net/multipartcontent/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| [ReadAsByteArray](../../aspose.svg.net/content/readasbytearray/)() | HTTP コンテンツをシリアライズし、コンテンツを表すバイト配列を返します。 |
| [ReadAsStream](../../aspose.svg.net/content/readasstream/)() | HTTP コンテンツをシリアライズし、コンテンツを表すストリームを返します。 |
| [ReadAsString](../../aspose.svg.net/content/readasstring/)() | HTTP コンテンツをシリアライズし、コンテンツを表す文字列を返します。 |

### 参照

* class [Content](../content/)
* namespace [Aspose.Svg.Net](../../aspose.svg.net/)
* assembly [Aspose.SVG](../../)

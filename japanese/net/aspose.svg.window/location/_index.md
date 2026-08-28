---
title: "Location クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Window.Location クラス。Location オブジェクトは、ドキュメントの閲覧コンテキスト内でアクティブなドキュメントのアドレスを表現し、履歴オブジェクトにエントリを追加または置換することで、閲覧コンテキストのセッション履歴の現在のエントリを変更できるようにします。"
type: docs
weight: 5950
url: /ja/net/aspose.svg.window/location/
---
## Location class

Location オブジェクトは、ドキュメントの閲覧コンテキスト内でアクティブなドキュメントのアドレスを表現し、履歴オブジェクトにエントリを追加または置換することで、閲覧コンテキストのセッション履歴の現在のエントリを変更できるようにします。

```csharp
public sealed class Location : DOMObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Hash](../../aspose.svg.window/location/hash/) { get; set; } | Location オブジェクトの URL のフラグメントを返します（空でない場合は先頭の # を含みます）。設定可能で、フラグメントを変更した同じ URL にナビゲートします（先頭の # は無視されます）。 |
| [Host](../../aspose.svg.window/location/host/) { get; set; } | Location オブジェクトの URL のホストとポートを返します（スキームのデフォルトポートと異なる場合）。設定可能で、ホストとポートを変更した同じ URL にナビゲートします。 |
| [Hostname](../../aspose.svg.window/location/hostname/) { get; set; } | Location オブジェクトの URL のホストを返します。設定可能で、ホストを変更した同じ URL にナビゲートします。 |
| [Href](../../aspose.svg.window/location/href/) { get; set; } | Location オブジェクトの URL を返します。設定可能で、指定された URL にナビゲートします。 |
| [Origin](../../aspose.svg.window/location/origin/) { get; } | Location オブジェクトの URL のオリジンを返します。 |
| [Pathname](../../aspose.svg.window/location/pathname/) { get; set; } | Location オブジェクトの URL のパスを返します。設定可能で、パスを変更した同じ URL にナビゲートします。 |
| [Port](../../aspose.svg.window/location/port/) { get; set; } | Location オブジェクトの URL のポートを返します。設定可能で、ポートを変更した同じ URL にナビゲートします。 |
| [Protocol](../../aspose.svg.window/location/protocol/) { get; set; } | Location オブジェクトの URL のスキームを返します。設定可能で、スキームを変更した同じ URL にナビゲートします。 |
| [Search](../../aspose.svg.window/location/search/) { get; set; } | Location オブジェクトの URL のクエリを返します（空でない場合は先頭の ? を含みます）。設定可能で、クエリを変更した同じ URL にナビゲートします（先頭の ? は無視されます）。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Assign](../../aspose.svg.window/location/assign/)(*string*) | 指定されたページにナビゲートします。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [Reload](../../aspose.svg.window/location/reload/)() | 現在のページを再読み込みします。 |
| [Replace](../../aspose.svg.window/location/replace/)(*string*) | 現在のページをセッション履歴から削除し、指定されたページにナビゲートします。 |
| override [ToString](../../aspose.svg.window/location/tostring/)() | Location オブジェクトの URL を返します。 |

### 参照

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)

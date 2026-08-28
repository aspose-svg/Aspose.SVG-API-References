---
title: "Configuration クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Configuration クラス。アプリケーションの環境設定を構成するために使用される設定コンテキストオブジェクトを表します"
type: docs
weight: 2050
url: /ja/net/aspose.svg/configuration/
---
## Configuration class

アプリケーションの環境設定を設定するために使用される構成コンテキストオブジェクトを表します。

```csharp
public class Configuration : IDisposable, IServiceProvider
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Configuration](configuration/)() | `Configuration` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Security](../../aspose.svg/configuration/security/) { get; set; } | このプロパティを使用すると、フレームに読み込まれるコンテンツに対して、フォームやスクリプトのブロックなど、複数の制限を設定できます。[sandboxing](https://docs.aspose.com/html/net/environment-configuration/#sandboxing) に関する記事を参照してください。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../aspose.svg/configuration/create/#create)() | Configuration オブジェクトのインスタンスを作成し、構成します。 |
| static [Create](../../aspose.svg/configuration/create/#create_1)(*Action&lt;IConfigurationBuilder&gt;*) | Configuration オブジェクトのインスタンスを作成し、構成します。 |
| [Dispose](../../aspose.svg/configuration/dispose/)() | アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [GetService](../../aspose.svg/configuration/getservice/#getservice)(*Type*) | 要求されたサービスを取得します。 |
| [GetService<T>](../../aspose.svg/configuration/getservice/#getservice_1)() | 要求されたサービスを取得します。 |
| static [SetExtension](../../aspose.svg/configuration/setextension/)(*[IConfigurationExtension](../iconfigurationextension/)*) | 構成の拡張子を設定します。 |

### 参照

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

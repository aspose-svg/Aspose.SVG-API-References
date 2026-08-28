---
title: "License クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.License クラス。コンポーネントのライセンスを付与するメソッドを提供します。"
type: docs
weight: 4260
url: /ja/net/aspose.svg/license/
---
## License class

コンポーネントをライセンスするためのメソッドを提供します。

```csharp
public class License
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [License](license/)() | このクラスの新しいインスタンスを初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense)(*Stream*) | コンポーネントにライセンスを付与します。 |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense_1)(*string*) | コンポーネントにライセンスを付与します。 |

## 例

この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で、MyLicense.lic という名前のライセンスファイルを検索しようとします。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

コンポーネントの jar ファイル:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### 参照

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

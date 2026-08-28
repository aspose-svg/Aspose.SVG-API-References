---
title: "ライセンス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "License コンストラクタ。 このクラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/aspose.svg/license/license/
---
## License constructor

このクラスの新しいインスタンスを初期化します。

```csharp
public License()
```

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

* class [License](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---
title: "Metered クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Metered クラス。メータ付きキーを設定するメソッドを提供します。"
type: docs
weight: 4270
url: /ja/net/aspose.svg/metered/
---
## Metered class

メーターキーを設定するためのメソッドを提供します。

```csharp
public class Metered
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Metered](metered/)() | このクラスの新しいインスタンスを初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SetMeteredKey](../../aspose.svg/metered/setmeteredkey/)(*string, string*) | メータ付きの公開キーとプライベートキーを設定します。メータ付きライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があり、通常はこれだけで十分です。ただし、消費データのアップロードが常に失敗し 24 時間を超えると、ライセンスは評価ステータスに設定されます。そのような事態を防ぐため、ライセンスステータスを定期的に確認し、評価ステータスである場合は再度この API を呼び出してください。 |
| static [GetConsumptionCredit](../../aspose.svg/metered/getconsumptioncredit/)() | 消費クレジットを取得します |
| static [GetConsumptionQuantity](../../aspose.svg/metered/getconsumptionquantity/)() | 消費ファイルサイズを取得します |
| static [IsMeteredLicensed](../../aspose.svg/metered/ismeteredlicensed/)() | メータ付きがライセンスされているか確認します |

## 例

この例では、メータ付きの公開キーとプライベートキーを設定しようとします

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

コンポーネントの jar ファイル:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### 参照

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

---
title: "Metered.SetMeteredKey"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Metered SetMeteredKey メソッド。メーターの公開キーとプライベートキーを設定します。アプリケーション起動時にメーターライセンスを購入した場合、この API を通常通り呼び出せば十分です。ただし、消費データのアップロードが常に失敗し、24 時間を超えるとライセンスが評価ステータスに設定されます。そのような事態を回避するため、ライセンスステータスを定期的に確認し、評価ステータスである場合は再度この API を呼び出す必要があります。"
type: docs
weight: 20
url: /ja/net/aspose.svg/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

メータ付きの公開キーとプライベートキーを設定します。メータ付きライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があり、通常はこれだけで十分です。ただし、消費データのアップロードが常に失敗し 24 時間を超えると、ライセンスは評価ステータスに設定されます。そのような事態を防ぐため、ライセンスステータスを定期的に確認し、評価ステータスである場合は再度この API を呼び出してください。

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| publicKey | String | 公開鍵 |
| privateKey | String | 秘密鍵 |

### 参照

* class [Metered](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

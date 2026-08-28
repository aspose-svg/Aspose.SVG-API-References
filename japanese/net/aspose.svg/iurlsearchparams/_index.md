---
title: "IUrlSearchParams インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.IUrlSearchParams インターフェイス。URL のクエリ文字列を操作するためのメソッドを提供します。"
type: docs
weight: 4140
url: /ja/net/aspose.svg/iurlsearchparams/
---
## IUrlSearchParams interface

URL のクエリ文字列を操作するメソッドを提供します。

```csharp
public interface IUrlSearchParams : IEnumerable<string[]>
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Append](../../aspose.svg/iurlsearchparams/append/)(*string, string*) | 名前が `name` で値が `value` の新しい名前-値ペアを追加します。 |
| [Delete](../../aspose.svg/iurlsearchparams/delete/)(*string*) | 名前が `name` のすべての名前-値ペアを削除します。 |
| [Get](../../aspose.svg/iurlsearchparams/get/)(*string*) | 名前が `name` の最初の名前-値ペアの値を返します。 |
| [GetAll](../../aspose.svg/iurlsearchparams/getall/)(*string*) | 名前が `name` のすべての値を返します。 |
| [Has](../../aspose.svg/iurlsearchparams/has/)(*string*) | リストに名前が `name` の名前-値ペアがあるかどうかを確認します。 |
| [Set](../../aspose.svg/iurlsearchparams/set/)(*string, string*) | 最初に見つかった名前-値ペアの値を指定された値に設定し、他のペアを削除します。指定された名前の名前-値ペアが見つからない場合は、新しいペアがリストに追加されます。 |
| [Sort](../../aspose.svg/iurlsearchparams/sort/)() | 存在するすべての名前-値ペアを名前でソートします。 |

### 参照

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

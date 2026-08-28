---
title: "IBlob インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.IO.IBlob インターフェイス。Blob オブジェクトはバイトシーケンスを指し、サイズ属性はバイトシーケンス内の総バイト数を、タイプ属性はバイトシーケンスのメディアタイプを表す小文字の ASCII エンコード文字列です。"
type: docs
weight: 4030
url: /ja/net/aspose.svg.io/iblob/
---
## IBlob interface

Blob オブジェクトはバイトシーケンスを指し、バイトシーケンスの総バイト数を示す size 属性と、バイトシーケンスのメディアタイプを表す小文字の ASCII エンコード文字列である type 属性を持ちます。

```csharp
public interface IBlob
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Size](../../aspose.svg.io/iblob/size/) { get; } | バイトシーケンスのサイズ（バイト数）を返します。取得時には、準拠したユーザーエージェントは FileReader または FileReaderSync オブジェクトで読み取れる総バイト数を返す必要があり、Blob に読み取るバイトがない場合は 0 を返します。 |
| [Type](../../aspose.svg.io/iblob/type/) { get; } | Blob のメディアタイプを表す小文字の ASCII エンコード文字列です。取得時には、ユーザーエージェントは Blob のタイプを小文字の ASCII エンコード文字列として返す必要があり、バイトシーケンスに変換したときに解析可能な MIME タイプとなるか、タイプが判別できない場合は空文字列（0 バイト）を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Slice](../../aspose.svg.io/iblob/slice/)(*ulong, ulong, string*) | オプションの start パラメータからオプションの end パラメータ（end は含まない）までのバイト範囲を持ち、type 属性がオプションの contentType パラメータの値となる新しい Blob オブジェクトを返します。 |

### 参照

* namespace [Aspose.Svg.IO](../../aspose.svg.io/)
* assembly [Aspose.SVG](../../)

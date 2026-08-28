---
title: "IFile インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.IO.IFile インターフェイス。File オブジェクトは name 属性（文字列）を持つ Blob オブジェクトで、コンストラクタを使用して Web アプリケーション内で作成することも、基盤となる OS のファイルシステムからのバイト列への参照であることもできます。"
type: docs
weight: 4050
url: /ja/net/aspose.svg.io/ifile/
---
## IFile interface

File オブジェクトは name 属性（文字列）を持つ Blob オブジェクトです。Web アプリケーション内でコンストラクタを使用して作成することも、基盤となる（OS）ファイルシステムのファイルからのバイトシーケンスへの参照であることもあります。

```csharp
public interface IFile : IBlob
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [LastModified](../../aspose.svg.io/ifile/lastmodified/) { get; } | ファイルの最終更新日時です。取得時に、ユーザーエージェントがこの情報を提供できる場合、Unix エポックからのミリ秒数としてファイルが最後に更新された時刻を表す long long を返す必要があります。 |
| [Name](../../aspose.svg.io/ifile/name/) { get; } | ファイルの名前です。取得時には、ファイル名を文字列として返す必要があります。 |

### 参照

* interface [IBlob](../iblob/)
* namespace [Aspose.Svg.IO](../../aspose.svg.io/)
* assembly [Aspose.SVG](../../)

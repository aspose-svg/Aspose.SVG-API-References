---
title: Class OutputStream
second_title: Aspose.SVG for .NET API リファレンス
description: Aspose.Svg.IO.OutputStream クラス. サロゲート ストリームは実際の出力ストリームをラップしそれへのアクセスを制御します OutputStream出力ストリームの場所を記述する URI データが含まれています
type: docs
weight: 1980
url: /ja/net/aspose.svg.io/outputstream/
---
## OutputStream class

サロゲート ストリームは実際の出力ストリームをラップし、それへのアクセスを制御します。 `OutputStream`出力ストリームの場所を記述する URI データが含まれています。

```csharp
public class OutputStream : Stream
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [OutputStream](outputstream/)(Stream, string) | の新しいインスタンスを初期化します`OutputStream` class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [CanRead](../../aspose.svg.io/outputstream/canread/) { get; } | ラップされた出力ストリームが読み取りをサポートしているかどうかを示す値を取得します. |
| override [CanSeek](../../aspose.svg.io/outputstream/canseek/) { get; } | ラップされた出力ストリームがシークをサポートするかどうかを示す値を取得します. |
| override [CanWrite](../../aspose.svg.io/outputstream/canwrite/) { get; } | ラップされた出力ストリームが書き込みをサポートしているかどうかを示す値を取得します. |
| override [Length](../../aspose.svg.io/outputstream/length/) { get; } | ラップされた出力ストリームの長さをバイト単位で取得します。 |
| override [Position](../../aspose.svg.io/outputstream/position/) { get; set; } | ラップされた出力ストリーム内の位置を取得または設定します。 |
| [Uri](../../aspose.svg.io/outputstream/uri/) { get; } | ストリームの場所の URI を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Close](../../aspose.svg.io/outputstream/close/)() | ラップされた出力ストリームと現在のストリームを閉じます。 |
| override [Flush](../../aspose.svg.io/outputstream/flush/)() | ラップされた出力ストリームのすべてのバッファをクリアし、バッファリングされたデータを基礎となるデバイスに書き込みます. |
| override [Read](../../aspose.svg.io/outputstream/read/)(byte[], int, int) | ラップされた出力 stream から一連のバイトを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。 |
| override [Seek](../../aspose.svg.io/outputstream/seek/)(long, SeekOrigin) | ラップされた出力ストリーム内の位置を設定します。 |
| override [SetLength](../../aspose.svg.io/outputstream/setlength/)(long) | ラップされた出力ストリームの長さを設定します。 |
| override [Write](../../aspose.svg.io/outputstream/write/)(byte[], int, int) | ラップされた output ストリームに一連のバイトを書き込み、書き込まれた バイト数だけこのストリーム内の現在位置を進めます。 |

### 関連項目

* 名前空間 [Aspose.Svg.IO](../../aspose.svg.io/)
* 組み立て [Aspose.SVG](../../)



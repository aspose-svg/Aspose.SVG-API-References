---
title: "IWindow.Btoa"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IWindow Btoa メソッド。Unicode 文字列（U+0000 から U+00FF の範囲の文字のみで、各文字は 0x00 から 0xFF のバイナリバイトを表す）を受け取り、Base64 表現に変換して返します"
type: docs
weight: 130
url: /ja/net/aspose.svg.window/iwindow/btoa/
---
## IWindow.Btoa method

入力データを、U+0000 から U+00FF の範囲の文字のみを含む Unicode 文字列の形で受け取り、各文字が 0x00 から 0xFF のバイナリバイトを表すものとして、Base64 表現に変換し、返します。

```csharp
public string Btoa(string data)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| データ | String | U+0000 から U+00FF の範囲の文字のみを含む Unicode 文字列です。 |

### 戻り値

Base64 文字列です。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 入力文字列に範囲外の文字が含まれている場合、\"InvalidCharacterError\" DOMException 例外をスローします。 |

### 参照

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)

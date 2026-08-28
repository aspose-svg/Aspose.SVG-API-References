---
title: "IWindow.Atob"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IWindow Atob メソッド。Base64 エンコードされたバイナリデータを含む Unicode 文字列を受け取り、デコードして、U+0000 から U+00FF の範囲の文字（各文字は 0x00 から 0xFF のバイナリバイトを表す）からなる文字列を返します"
type: docs
weight: 120
url: /ja/net/aspose.svg.window/iwindow/atob/
---
## IWindow.Atob method

入力データを、Base64 エンコードされたバイナリデータを含む Unicode 文字列の形で受け取り、デコードし、U+0000 から U+00FF の範囲の文字で構成された文字列を返します。各文字はそれぞれ 0x00 から 0xFF の値を持つバイナリバイトを表します。

```csharp
public string Atob(string data)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| データ | String | Base64 エンコードされたバイナリデータを含む Unicode 文字列です |

### 戻り値

U+0000 から U+00FF の範囲の文字で構成された文字列です

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 入力文字列が有効な Base64 データでない場合、\"InvalidCharacterError\" DOMException をスローします。 |

### 参照

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)

---
title: "IWindow.Atob"
second_title: "Aspose.SVG for .NET API 参考"
description: "IWindow Atob 方法。接受以包含 base64 编码二进制数据的 Unicode 字符串形式的输入数据，对其解码并返回一个由 U0000 到 U00FF 范围内字符组成的字符串，每个字符表示对应的二进制字节，取值为 0x00 到 0xFF。"
type: docs
weight: 120
url: /zh/net/aspose.svg.window/iwindow/atob/
---
## IWindow.Atob method

获取输入数据，形式为包含 base64 编码二进制数据的 Unicode 字符串，解码后返回一个字符串，该字符串由 U+0000 到 U+00FF 范围内的字符组成，每个字符分别表示值为 0x00 到 0xFF 的二进制字节，对应于该二进制数据。

```csharp
public string Atob(string data)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | String | 包含 base64 编码二进制数据的 Unicode 字符串 |

### 返回值

由 U+0000 到 U+00FF 范围内字符组成的字符串

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 如果输入字符串不是有效的 base64 数据，则抛出 "InvalidCharacterError" DOMException。 |

### 另请参阅

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)

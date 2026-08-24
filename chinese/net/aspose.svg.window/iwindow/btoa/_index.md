---
title: "IWindow.Btoa"
second_title: "Aspose.SVG for .NET API 参考"
description: "IWindow Btoa 方法。接受以 Unicode 字符串形式的输入数据，该字符串仅包含 U0000 到 U00FF 范围内的字符，每个字符分别表示值为 0x00 到 0xFF 的二进制字节，并将其转换为 base64 表示形式并返回。"
type: docs
weight: 130
url: /zh/net/aspose.svg.window/iwindow/btoa/
---
## IWindow.Btoa method

获取输入数据，形式为仅包含 U+0000 到 U+00FF 范围字符的 Unicode 字符串，每个字符分别表示值为 0x00 到 0xFF 的二进制字节，并将其转换为 base64 表示形式并返回。

```csharp
public string Btoa(string data)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | String | 仅包含 U+0000 到 U+00FF 范围内字符的 Unicode 字符串。 |

### 返回值

Base64 字符串。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 如果输入字符串包含任何超出范围的字符，则抛出 "InvalidCharacterError" DOMException 异常。 |

### 另请参阅

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)

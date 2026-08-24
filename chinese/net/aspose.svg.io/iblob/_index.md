---
title: "IBlob 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.IO.IBlob 接口。Blob 对象指向一个字节序列，具有 size 属性（字节序列的总字节数）和 type 属性（小写 ASCII 编码字符串，表示字节序列的媒体类型）。"
type: docs
weight: 4030
url: /zh/net/aspose.svg.io/iblob/
---
## IBlob interface

Blob 对象指代一个字节序列，并具有 size 属性，表示该字节序列的总字节数，以及 type 属性，它是一个小写的 ASCII 编码字符串，表示该字节序列的媒体类型。

```csharp
public interface IBlob
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Size](../../aspose.svg.io/iblob/size/) { get; } | 返回字节序列的大小（字节数）。获取时，符合规范的用户代理必须返回 FileReader 或 FileReaderSync 对象可读取的总字节数，如果 Blob 没有可读取的字节则返回 0。 |
| [Type](../../aspose.svg.io/iblob/type/) { get; } | 表示 Blob 媒体类型的小写 ASCII 编码字符串。获取时，用户代理必须返回 Blob 的 type，作为小写 ASCII 编码字符串，使其转换为字节序列后为可解析的 MIME 类型；如果无法确定类型，则返回空字符串（0 字节）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Slice](../../aspose.svg.io/iblob/slice/)(*ulong, ulong, string*) | 返回一个新的 Blob 对象，其字节范围从可选的 start 参数开始，但不包括可选的 end 参数，并且其 type 属性为可选的 contentType 参数的值。 |

### 另请参阅

* namespace [Aspose.Svg.IO](../../aspose.svg.io/)
* assembly [Aspose.SVG](../../)

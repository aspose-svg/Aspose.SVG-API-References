---
title: "IFile 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.IO.IFile 接口。File 对象是具有字符串类型 name 属性的 Blob 对象，可通过构造函数在 Web 应用程序中创建，或引用底层操作系统文件系统中某个文件的字节序列。"
type: docs
weight: 4050
url: /zh/net/aspose.svg.io/ifile/
---
## IFile interface

File 对象是具有 name 属性（字符串）的 Blob 对象；它可以通过构造函数在 Web 应用中创建，或是对底层（操作系统）文件系统中某文件的字节序列的引用。

```csharp
public interface IFile : IBlob
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [LastModified](../../aspose.svg.io/ifile/lastmodified/) { get; } | 文件的最后修改日期。获取时，如果用户代理能够提供此信息，则必须返回一个 long long，表示自 Unix 纪元以来的毫秒数，即文件最后修改的时间。 |
| [Name](../../aspose.svg.io/ifile/name/) { get; } | 文件的名称。获取时，必须返回文件名的字符串。 |

### 另请参阅

* interface [IBlob](../iblob/)
* namespace [Aspose.Svg.IO](../../aspose.svg.io/)
* assembly [Aspose.SVG](../../)

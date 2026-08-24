---
title: "XmlSpace 枚举"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.XmlSpace 枚举。指定 XML 文档中元素内部空白的处理方式"
type: docs
weight: 1980
url: /zh/net/aspose.svg.builder/xmlspace/
---
## XmlSpace enumeration

指定在 XML 文档中元素内部的空白如何处理。

```csharp
public enum XmlSpace
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | `0` | 指示应根据 XML 处理器的默认行为处理空白字符，通常通过删除换行和多余空格来规范化空白。 |
| Preserve | `1` | 指示应保留 XML 文档中出现的空白字符。这对于在空白重要的文本中保持格式非常有用。 |

## 备注

XML 中的 'xml:space' 属性用于控制元素内部的空白是应保留还是规范化。此枚举提供了在 XML 和 SVG 文档中设置此行为的选项。

### 另请参阅

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

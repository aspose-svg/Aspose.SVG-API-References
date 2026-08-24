---
title: "PdfPermissions 枚举"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Rendering.Pdf.Encryption.PdfPermissions 枚举。此枚举表示 PDF 的用户权限。"
type: docs
weight: 5000
url: /zh/net/aspose.svg.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

此枚举表示用户对 PDF 的权限。

```csharp
[Flags]
public enum PdfPermissions
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| PrintDocument | `4` | (Security handlers of revision 2) 打印文档。(Security handlers of revision 3 or greater) 打印文档（可能不是最高质量级别，取决于是否也设置了 PrintingQuality）。 |
| ModifyContent | `8` | 通过除 ModifyTextAnnotations、FillForm 和 11 控制的操作之外的操作修改文档内容。 |
| ExtractContent | `10` | (Security handlers of revision 2) 复制或以其他方式提取文档中的文本和图形，包括提取文本和图形（以支持残障用户的可访问性或出于其他目的）。(Security handlers of revision 3 or greater) 通过除 ExtractContentWithDisabilities 控制的操作之外的操作复制或以其他方式提取文档中的文本和图形。 |
| ModifyTextAnnotations | `20` | 添加或修改文本注释，填写交互式表单字段，如果同时设置了 ModifyContent，则创建或修改交互式表单字段（包括签名字段）。 |
| FillForm | `100` | (Security handlers of revision 3 or greater) 填写现有的交互式表单字段（包括签名字段），即使 ModifyTextAnnotations 已清除。 |
| ExtractContentWithDisabilities | `200` | (Security handlers of revision 3 or greater) 提取文本和图形（以支持残障用户的可访问性或出于其他目的）。 |
| AssembleDocument | `400` | (Security handlers of revision 3 or greater) 组装文档（插入、旋转或删除页面并创建书签或缩略图），即使 ModifyContent 已清除。 |
| PrintingQuality | `800` | (Security handlers of revision 3 or greater) 将文档打印为一种表示形式，可从中生成 PDF 内容的忠实数字副本。当此位被清除（且第 3 位被设置）时，打印被限制为外观的低级表示，可能质量下降。 |

### 另请参阅

* namespace [Aspose.Svg.Rendering.Pdf.Encryption](../../aspose.svg.rendering.pdf.encryption/)
* assembly [Aspose.SVG](../../)

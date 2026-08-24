---
title: "License 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.License 类。提供对组件进行授权的方法"
type: docs
weight: 4260
url: /zh/net/aspose.svg/license/
---
## License class

提供对组件授权的方法。

```csharp
public class License
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [License](license/)() | 初始化此类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense)(*Stream*) | 对组件进行授权。 |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense_1)(*string*) | 对组件进行授权。 |

## 示例

在此示例中，将尝试在包含组件的文件夹、调用程序集所在的文件夹、入口程序集所在的文件夹以及调用程序集的嵌入资源中，查找名为 MyLicense.lic 的许可证文件。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

组件 jar 文件：

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### 另请参阅

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

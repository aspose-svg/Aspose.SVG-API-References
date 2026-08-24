---
title: "许可证"
second_title: "Aspose.SVG for .NET API 参考"
description: "License 构造函数。初始化此类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.svg/license/license/
---
## License constructor

初始化此类的新实例。

```csharp
public License()
```

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

* class [License](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

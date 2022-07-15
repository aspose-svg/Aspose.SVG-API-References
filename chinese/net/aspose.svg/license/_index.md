---
title: License
second_title: Aspose.SVG for .NET API 参考
description: 提供许可组件的方法
type: docs
weight: 2150
url: /zh/net/aspose.svg/license/
---
## License class

提供许可组件的方法。

```csharp
public class License
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [License](license)() | 初始化此类的新实例。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [SetLicense](../../aspose.svg/license/setlicense#setlicense)(Stream) | 许可组件。 |
| [SetLicense](../../aspose.svg/license/setlicense#setlicense_1)(string) | 许可组件。 |

### 例子

在本例中，将尝试在包含  组件，在包含调用程序集的文件夹中， 在条目程序集的文件夹中，然后在嵌入调用程序集的资源。

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

### 也可以看看

* 命名空间 [Aspose.Svg](../../aspose.svg)
* 部件 [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
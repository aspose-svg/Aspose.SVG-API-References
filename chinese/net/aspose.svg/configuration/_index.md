---
title: "配置类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Configuration 类。表示用于为应用程序设置环境设置的配置上下文对象。"
type: docs
weight: 2050
url: /zh/net/aspose.svg/configuration/
---
## Configuration class

表示用于为应用程序设置环境配置的上下文对象。

```csharp
public class Configuration : IDisposable, IServiceProvider
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Configuration](configuration/)() | 初始化 `Configuration` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Security](../../aspose.svg/configuration/security/) { get; set; } | 此属性允许您对框架中加载的内容设置多项限制，例如，阻止表单和脚本。请参阅关于 [sandboxing](https://docs.aspose.com/html/net/environment-configuration/#sandboxing) 的文章。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../aspose.svg/configuration/create/#create)() | 创建并配置 Configuration 对象的实例。 |
| static [Create](../../aspose.svg/configuration/create/#create_1)(*Action&lt;IConfigurationBuilder&gt;*) | 创建并配置 Configuration 对象的实例。 |
| [Dispose](../../aspose.svg/configuration/dispose/)() | 执行应用程序定义的任务，以释放、清理或重置非托管资源。 |
| [GetService](../../aspose.svg/configuration/getservice/#getservice)(*Type*) | 获取请求的服务。 |
| [GetService<T>](../../aspose.svg/configuration/getservice/#getservice_1)() | 获取请求的服务。 |
| static [SetExtension](../../aspose.svg/configuration/setextension/)(*[IConfigurationExtension](../iconfigurationextension/)*) | 为配置设置扩展。 |

### 另请参阅

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

---
title: "MultipartFormDataContent 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Net.MultipartFormDataContent 类。表示用于 multipart/form-data 编码算法的内容"
type: docs
weight: 4470
url: /zh/net/aspose.svg.net/multipartformdatacontent/
---
## MultipartFormDataContent class

表示 multipart/form-data 编码算法的内容。

```csharp
public class MultipartFormDataContent : MultipartContent
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MultipartFormDataContent](multipartformdatacontent/#constructor)() | 初始化 `MultipartFormDataContent` 类的新实例。 |
| [MultipartFormDataContent](multipartformdatacontent/#constructor_1)(*string*) | 初始化 `MultipartFormDataContent` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Headers](../../aspose.svg.net/content/headers/) { get; } | 获取 HTTP 内容标头。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Add](../../aspose.svg.net/multipartformdatacontent/add/#add)(*[Content](../content/)*) | 将内容添加到 `MultipartFormDataContent` 类 |
| [Add](../../aspose.svg.net/multipartformdatacontent/add/#add_1)(*[Content](../content/), string*) | 将内容添加到 `MultipartFormDataContent` 类，并使用字段名称参数 |
| [Add](../../aspose.svg.net/multipartformdatacontent/add/#add_2)(*[Content](../content/), string, string*) | 将内容添加到 `MultipartFormDataContent` 类，并使用字段和文件名参数 |
| [Dispose](../../aspose.svg.net/content/dispose/)() | 执行应用程序定义的任务，以释放、清理或重置非托管资源。 |
| [GetEnumerator](../../aspose.svg.net/multipartcontent/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| [ReadAsByteArray](../../aspose.svg.net/content/readasbytearray/)() | 序列化 HTTP 内容并返回表示该内容的字节数组。 |
| [ReadAsStream](../../aspose.svg.net/content/readasstream/)() | 序列化 HTTP 内容并返回表示该内容的流。 |
| [ReadAsString](../../aspose.svg.net/content/readasstring/)() | 序列化 HTTP 内容并返回表示该内容的字符串。 |

### 另请参阅

* class [MultipartContent](../multipartcontent/)
* namespace [Aspose.Svg.Net](../../aspose.svg.net/)
* assembly [Aspose.SVG](../../)

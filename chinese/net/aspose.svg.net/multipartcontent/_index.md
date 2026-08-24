---
title: "MultipartContent 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Net.MultipartContent 类。表示 multipart/ 内容"
type: docs
weight: 4460
url: /zh/net/aspose.svg.net/multipartcontent/
---
## MultipartContent class

表示 multipart/* 内容。

```csharp
public class MultipartContent : Content, IEnumerable<Content>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MultipartContent](multipartcontent/#constructor)() | 创建 `MultipartContent` 类的新实例。 |
| [MultipartContent](multipartcontent/#constructor_1)(*string*) | 创建带有子类型的 `MultipartContent` 类的新实例。 |
| [MultipartContent](multipartcontent/#constructor_2)(*string, string*) | 创建带有子类型和边界的 `MultipartContent` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Headers](../../aspose.svg.net/content/headers/) { get; } | 获取 HTTP 内容标头。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Add](../../aspose.svg.net/multipartcontent/add/)(*[Content](../content/)*) | 向 `MultipartContent` 添加新内容 |
| [Dispose](../../aspose.svg.net/content/dispose/)() | 执行应用程序定义的任务，以释放、清理或重置非托管资源。 |
| [GetEnumerator](../../aspose.svg.net/multipartcontent/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| [ReadAsByteArray](../../aspose.svg.net/content/readasbytearray/)() | 序列化 HTTP 内容并返回表示该内容的字节数组。 |
| [ReadAsStream](../../aspose.svg.net/content/readasstream/)() | 序列化 HTTP 内容并返回表示该内容的流。 |
| [ReadAsString](../../aspose.svg.net/content/readasstring/)() | 序列化 HTTP 内容并返回表示该内容的字符串。 |

### 另请参阅

* class [Content](../content/)
* namespace [Aspose.Svg.Net](../../aspose.svg.net/)
* assembly [Aspose.SVG](../../)

---
title: "IUrlSearchParams 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.IUrlSearchParams 接口。提供处理 URL 查询字符串的方法。"
type: docs
weight: 4140
url: /zh/net/aspose.svg/iurlsearchparams/
---
## IUrlSearchParams interface

提供用于处理 URL 查询字符串的方法。

```csharp
public interface IUrlSearchParams : IEnumerable<string[]>
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [Append](../../aspose.svg/iurlsearchparams/append/)(*string, string*) | 追加一个新名称-值对，其名称为 `name`，值为 `value`。 |
| [Delete](../../aspose.svg/iurlsearchparams/delete/)(*string*) | 移除所有名称为 `name` 的名称-值对。 |
| [Get](../../aspose.svg/iurlsearchparams/get/)(*string*) | 返回名称为 `name` 的第一个名称-值对的值。 |
| [GetAll](../../aspose.svg/iurlsearchparams/getall/)(*string*) | 返回所有名称为 `name` 的值。 |
| [Has](../../aspose.svg/iurlsearchparams/has/)(*string*) | 检查列表中是否存在名称为 `name` 的名称-值对。 |
| [Set](../../aspose.svg/iurlsearchparams/set/)(*string, string*) | 将首次找到的名称-值对的值设置为指定的值，并移除其他匹配的对。如果未找到具有指定名称的名称-值对，则会在列表中追加一个新的。 |
| [Sort](../../aspose.svg/iurlsearchparams/sort/)() | 按名称对所有名称-值对（如果有）进行排序。 |

### 另请参阅

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

---
title: "IStorage 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.IStorage 接口。该 Web Storage API 接口提供对特定域的会话或本地存储的访问。参见 Web Storage 规范 https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs
weight: 3090
url: /zh/net/aspose.svg.dom/istorage/
---
## IStorage interface

Web Storage API 的此接口提供对特定域的会话或本地存储的访问。参见 Web Storage 规范: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```csharp
public interface IStorage
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Length](../../aspose.svg.dom/istorage/length/) { get; } | 返回键/值对的数量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clear](../../aspose.svg.dom/istorage/clear/)() | 如果存在，则移除所有键/值对。 |
| [GetItem](../../aspose.svg.dom/istorage/getitem/)(*string*) | 返回与给定键关联的当前值，如果该键不存在则返回 null。 |
| [Key](../../aspose.svg.dom/istorage/key/)(*long*) | 返回第 n 个键的名称，如果 n 大于或等于键/值对的数量则返回 null。 |
| [RemoveItem](../../aspose.svg.dom/istorage/removeitem/)(*string*) | 如果存在具有给定键的键/值对，则移除该键/值对。 |
| [SetItem](../../aspose.svg.dom/istorage/setitem/)(*string, string*) | 将由键标识的对的值设置为 value，如果之前不存在该键，则创建一个新的键/值对。 |

### 另请参阅

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

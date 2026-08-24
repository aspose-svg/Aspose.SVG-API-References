---
title: "Element.ToggleAttribute"
second_title: "Aspose.SVG for .NET API 参考"
description: "Element ToggleAttribute 方法。如果未提供 force，则切换 qualifiedName，若已存在则移除，若不存在则添加。如果 force 为 true，则添加 qualifiedName。如果 force 为 false，则移除 qualifiedName。"
type: docs
weight: 440
url: /zh/net/aspose.svg.dom/element/toggleattribute/
---
## ToggleAttribute(*string*) {#toggleattribute}

如果未提供 force，则“切换” qualifiedName：如果它已存在则移除，若不存在则添加。如果 force 为 true，则添加 qualifiedName；如果 force 为 false，则移除 qualifiedName。

```csharp
public bool ToggleAttribute(string qualifiedName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| qualifiedName | String | 属性 QualifiedName。 |

### 返回值

如果 qualifiedName 现在存在则返回 true；否则返回 false。

### 另请参阅

* class [Element](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## ToggleAttribute(*string, bool*) {#toggleattribute_1}

如果未提供 force，则“切换” qualifiedName：如果它已存在则移除，若不存在则添加。如果 force 为 true，则添加 qualifiedName；如果 force 为 false，则移除 qualifiedName。

```csharp
public bool ToggleAttribute(string qualifiedName, bool force)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| qualifiedName | String | 属性 QualifiedName。 |
| force | Boolean | 用于切换属性的 force 选项。 |

### 返回值

如果 qualifiedName 现在存在则返回 true；否则返回 false。

### 另请参阅

* class [Element](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

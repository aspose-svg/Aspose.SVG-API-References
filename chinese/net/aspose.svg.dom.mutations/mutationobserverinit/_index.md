---
title: "MutationObserverInit 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Mutations.MutationObserverInit 类。此类表示用于配置 MutationObserver 的选项集合。"
type: docs
weight: 3120
url: /zh/net/aspose.svg.dom.mutations/mutationobserverinit/
---
## MutationObserverInit class

此类表示用于配置 [`MutationObserver`](../mutationobserver/) 的选项集合。

```csharp
public class MutationObserverInit : IDictionary<string, object>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MutationObserverInit](mutationobserverinit/)() | 初始化 `MutationObserverInit` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AttributeFilter](../../aspose.svg.dom.mutations/mutationobserverinit/attributefilter/) { get; set; } | 如果不需要观察所有属性变更且 attributes 为 true 或省略，则设置为属性本地名称列表（不含命名空间）。 |
| [AttributeOldValue](../../aspose.svg.dom.mutations/mutationobserverinit/attributeoldvalue/) { get; set; } | 如果 attributes 为 true 或省略且需要记录目标属性在变更前的值，则设置为 true。 |
| [Attributes](../../aspose.svg.dom.mutations/mutationobserverinit/attributes/) { get; set; } | 如果要观察目标属性的变更，则设置为 true。如果已指定 attributeOldValue 和/或 attributeFilter，则可以省略此设置。 |
| [CharacterData](../../aspose.svg.dom.mutations/mutationobserverinit/characterdata/) { get; set; } | 如果要观察目标数据的变更，则设置为 true。如果已指定 characterDataOldValue，则可以省略此设置。 |
| [CharacterDataOldValue](../../aspose.svg.dom.mutations/mutationobserverinit/characterdataoldvalue/) { get; set; } | 如果 characterData 被设置为 true 或省略，并且需要记录变更前 target’s 数据，则设为 true。 |
| [ChildList](../../aspose.svg.dom.mutations/mutationobserverinit/childlist/) { get; set; } | 如果要观察 target’s 子节点的变更，则设为 true。 |
| [Count](../../aspose.svg.dom.mutations/mutationobserverinit/count/) { get; } | 获取 `MutationObserverInit` 集合中包含的键/值对的数量。 |
| [IsReadOnly](../../aspose.svg.dom.mutations/mutationobserverinit/isreadonly/) { get; } | 确定 `MutationObserverInit` 集合是否可变。 |
| [Item](../../aspose.svg.dom.mutations/mutationobserverinit/item/) { get; set; } | 获取或设置具有指定键的元素。 |
| [Keys](../../aspose.svg.dom.mutations/mutationobserverinit/keys/) { get; } | 获取包含 `MutationObserverInit` 集合中键的集合。 |
| [Subtree](../../aspose.svg.dom.mutations/mutationobserverinit/subtree/) { get; set; } | 如果要观察不仅 target，还包括 target’s 子孙节点的变更，则设为 true。 |
| [Values](../../aspose.svg.dom.mutations/mutationobserverinit/values/) { get; } | 获取包含 `MutationObserverInit` 集合中值的集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.svg.dom.mutations/mutationobserverinit/add/#add)(*KeyValuePair&lt;string, object&gt;*) | 向 `MutationObserverInit` 集合添加一个元素。 |
| [Add](../../aspose.svg.dom.mutations/mutationobserverinit/add/#add_1)(*string, object*) | 向 `MutationObserverInit` 集合添加指定的键和值。 |
| [Clear](../../aspose.svg.dom.mutations/mutationobserverinit/clear/)() | 从 `MutationObserverInit` 集合中移除所有元素。 |
| [Contains](../../aspose.svg.dom.mutations/mutationobserverinit/contains/)(*KeyValuePair&lt;string, object&gt;*) | 确定 `MutationObserverInit` 是否包含指定的键/值对。 |
| [ContainsKey](../../aspose.svg.dom.mutations/mutationobserverinit/containskey/)(*string*) | 确定 `MutationObserverInit` 集合是否包含指定的键。 |
| [CopyTo](../../aspose.svg.dom.mutations/mutationobserverinit/copyto/)(*KeyValuePair&lt;string, object&gt;[], int*) | 将 `MutationObserverInit` 元素复制到现有的一维数组中，起始于指定的数组索引。 |
| [GetEnumerator](../../aspose.svg.dom.mutations/mutationobserverinit/getenumerator/)() | 返回一个遍历 `MutationObserverInit` 元素的枚举器。 |
| [Remove](../../aspose.svg.dom.mutations/mutationobserverinit/remove/#remove)(*KeyValuePair&lt;string, object&gt;*) | 从 `MutationObserverInit` 集合中移除指定的键/值对。 |
| [Remove](../../aspose.svg.dom.mutations/mutationobserverinit/remove/#remove_1)(*string*) | 从 `MutationObserverInit` 集合中移除与指定键关联的值。 |
| [TryGetValue](../../aspose.svg.dom.mutations/mutationobserverinit/trygetvalue/)(*string, out object*) | 获取与指定键关联的值。 |

### 另请参阅

* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)

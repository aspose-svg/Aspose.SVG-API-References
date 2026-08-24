---
title: "MutationRecord 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Mutations.MutationRecord 类。MutationRecord 表示单个 DOM 突变。它是传递给 MutationObservers 的 MutationCallback 的对象。"
type: docs
weight: 3130
url: /zh/net/aspose.svg.dom.mutations/mutationrecord/
---
## MutationRecord class

MutationRecord 表示单个 DOM 变更。它是传递给 [`MutationObserver`](../mutationobserver/) 的 [`MutationCallback`](../mutationcallback/) 的对象。

```csharp
public class MutationRecord : DOMObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AddedNodes](../../aspose.svg.dom.mutations/mutationrecord/addednodes/) { get; } | 返回添加的节点。 |
| [AttributeName](../../aspose.svg.dom.mutations/mutationrecord/attributename/) { get; } | 返回已更改属性的本地名称，否则返回 null。 |
| [AttributeNamespace](../../aspose.svg.dom.mutations/mutationrecord/attributenamespace/) { get; } | 返回已更改属性的命名空间，否则返回 null。 |
| [NextSibling](../../aspose.svg.dom.mutations/mutationrecord/nextsibling/) { get; } | 返回已添加或已移除节点的下一个兄弟节点，若无则返回 null。 |
| [OldValue](../../aspose.svg.dom.mutations/mutationrecord/oldvalue/) { get; } | 返回值取决于类型。对于 "attributes"，它是更改前属性的值。对于 "characterData"，它是更改前节点的数据。对于 "childList"，则为 null。 |
| [PreviousSibling](../../aspose.svg.dom.mutations/mutationrecord/previoussibling/) { get; } | 返回已添加或已移除节点的前一个兄弟节点，若无则返回 null。 |
| [RemovedNodes](../../aspose.svg.dom.mutations/mutationrecord/removednodes/) { get; } | 返回已移除的节点。 |
| [Target](../../aspose.svg.dom.mutations/mutationrecord/target/) { get; } | 返回受变更影响的节点，取决于类型。对于 "attributes"，它是属性发生变化的元素。对于 "characterData"，它是 CharacterData 节点。对于 "childList"，它是子节点发生变化的节点。 |
| [Type](../../aspose.svg.dom.mutations/mutationrecord/type/) { get; } | 如果是属性变更则返回 "attributes"，如果是对 CharacterData 节点的变更则返回 "characterData"，如果是对节点树的变更则返回 "childList"。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |

### 另请参阅

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)

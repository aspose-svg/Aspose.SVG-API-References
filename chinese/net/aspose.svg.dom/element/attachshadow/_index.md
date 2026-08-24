---
title: "Element.AttachShadow"
second_title: "Aspose.SVG for .NET API 参考"
description: "Element AttachShadow 方法。创建 shadow root 并将其附加到当前元素。"
type: docs
weight: 220
url: /zh/net/aspose.svg.dom/element/attachshadow/
---
## Element.AttachShadow method

创建 shadow root 并将其附加到当前元素。

```csharp
public ShadowRoot AttachShadow(ShadowRootMode mode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 模式 | ShadowRootMode | 创建 shadow root 时的模式。 |

### 返回值

已创建 [`ShadowRoot`](../../shadowroot/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| 错误 | NotSupportedError：Element 不支持 shadow tree。 |
| 错误 | InvalidStateError：Element 已经有 shadow tree。 |

### 另请参阅

* class [ShadowRoot](../../shadowroot/)
* enum [ShadowRootMode](../../shadowrootmode/)
* class [Element](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

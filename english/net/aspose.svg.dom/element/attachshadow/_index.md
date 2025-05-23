---
title: Element.AttachShadow
second_title: Aspose.SVG for .NET API Reference
description: Element AttachShadow method. Creates shadow root and attaches it to current element
type: docs
weight: 220
url: /net/aspose.svg.dom/element/attachshadow/
---
## Element.AttachShadow method

Creates shadow root and attaches it to current element.

```csharp
public ShadowRoot AttachShadow(ShadowRootMode mode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mode | ShadowRootMode | Mode in which shadow root will be created. |

### Return Value

Created [`ShadowRoot`](../../shadowroot/).

### Exceptions

| exception | condition |
| --- | --- |
| Error | NotSupportedError: Element does not support shadow tree. |
| Error | InvalidStateError: Element already has shadow tree. |

### See Also

* class [ShadowRoot](../../shadowroot/)
* enum [ShadowRootMode](../../shadowrootmode/)
* class [Element](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

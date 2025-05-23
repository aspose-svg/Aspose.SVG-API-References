---
title: KeyboardEvent.Repeat
second_title: Aspose.SVG for .NET API Reference
description: KeyboardEvent Repeat property. true if the key has been pressed in a sustained manner. Holding down a key MUST result in the repeating the events keydown beforeinput input in this order at a rate determined by the system configuration. For mobile devices which have long-key-press behavior the first key event with a repeat attribute value of true MUST serve as an indication of a long-key-press. The length of time that the key MUST be pressed in order to begin repeating is configuration-dependent
type: docs
weight: 90
url: /net/aspose.svg.dom.events/keyboardevent/repeat/
---
## KeyboardEvent.Repeat property

true if the key has been pressed in a sustained manner. Holding down a key MUST result in the repeating the events keydown, beforeinput, input in this order, at a rate determined by the system configuration. For mobile devices which have long-key-press behavior, the first key event with a repeat attribute value of true MUST serve as an indication of a long-key-press. The length of time that the key MUST be pressed in order to begin repeating is configuration-dependent.

```csharp
public bool Repeat { get; }
```

### Property Value

`true` if repeat; otherwise, `false`.

### See Also

* class [KeyboardEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

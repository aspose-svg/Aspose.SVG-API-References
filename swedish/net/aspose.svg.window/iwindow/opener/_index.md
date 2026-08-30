---
title: "IWindow.Opener"
second_title: "Aspose.SVG för .NET API-referens"
description: "IWindow Opener-egenskap. Opener-IDL-attributet på Window-objektet vid läsning måste returnera WindowProxy-objektet för den surfkontext som den aktuella surfkontexten skapades från, dess opener-surfkontext om det finns en, om den fortfarande är tillgänglig och om den aktuella surfkontexten inte har avstått sitt opener, annars måste den returnera null. Vid skrivning, om det nya värdet är null, måste den aktuella surfkontexten avstå sitt opener; om det nya värdet är något annat måste användaragenten anropa den interna metoden DefineOwnProperty på Window-objektet och skicka egenskapsnamnet opener som egenskapsnyckel samt Property Descriptor  Value value Writable true Enumerable true Configurable true som egenskapsbeskrivning där value är det nya värdet."
type: docs
weight: 60
url: /sv/net/aspose.svg.window/iwindow/opener/
---
## IWindow.Opener property

opener IDL-attributet på Window-objektet, vid läsning, måste returnera WindowProxy-objektet för den surfkontext som den aktuella surfkontexten skapades från (dess opener-surfkontext), om ett sådant finns, om det fortfarande är tillgängligt, och om den aktuella surfkontexten inte har avstått sitt opener; annars måste det returnera null. Vid skrivning, om det nya värdet är null ska den aktuella surfkontexten avstå sitt opener; om det nya värdet är något annat ska användaragenten anropa den interna metoden [[DefineOwnProperty]] för Window-objektet, skicka egenskapsnamnet "opener" som nyckel, och Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } som egenskapsbeskrivning, där value är det nya värdet.

```csharp
public IWindow Opener { get; }
```

### Property Value

Openern.

### Se även

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)

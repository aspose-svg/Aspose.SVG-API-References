---
title: "KeyboardEvent.Repeat"
second_title: "Aspose.SVG för .NET API-referens"
description: "KeyboardEvent Repeat egenskap. true om tangenten har hållits ned på ett bestående sätt. Att hålla ner en tangent MÅSTE leda till att händelserna keydown, beforeinput och input upprepas i den ordningen med en frekvens som bestäms av systemkonfigurationen. För mobila enheter som har långtangenttryckningsbeteende måste det första tangent‑eventet med repeat‑attributvärdet true fungera som en indikation på ett långtangenttryck. Den tid som tangenten MÅSTE hållas ned för att börja upprepa är beroende av konfigurationen."
type: docs
weight: 90
url: /sv/net/aspose.svg.dom.events/keyboardevent/repeat/
---
## KeyboardEvent.Repeat property

true om tangenten har hållits ned under en längre tid. Att hålla ner en tangent MÅSTE leda till att händelserna keydown, beforeinput, input upprepas i den ordningen, med en frekvens som bestäms av systemkonfigurationen. För mobila enheter som har långtangent‑beteende måste det första tangent‑eventet med repeat‑attributvärdet true fungera som en indikation på ett långtangent‑tryck. Den tid som tangenten MÅSTE hållas ned för att börja upprepa är konfigurationsberoende.

```csharp
public bool Repeat { get; }
```

### Property Value

`true` om repeat; annars, `false`.

### Se även

* class [KeyboardEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

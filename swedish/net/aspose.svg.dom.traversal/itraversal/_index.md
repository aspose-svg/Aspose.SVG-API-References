---
title: "ITraversal-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Traversal.ITraversal interface. Iteratörer används för att gå igenom en uppsättning noder, t.ex. uppsättningen av noder i en NodeList, dokumentets underträd som styrs av en viss Node, resultaten av en fråga eller någon annan uppsättning noder. Uppsättningen av noder som ska itereras bestäms av implementationen av NodeIterator. DOM Level 2 specificerar en enda NodeIterator-implementation för dokumentordnings‑traversering av ett dokumentunderträd. Instanser av dessa iteratörer skapas genom att anropa DocumentTraversal .createNodeIterator"
type: docs
weight: 3260
url: /sv/net/aspose.svg.dom.traversal/itraversal/
---
## ITraversal interface

Iteratorer används för att gå igenom en mängd noder, t.ex. mängden noder i en NodeList, dokumentundernoden som styrs av en specifik Node, resultatet av en fråga eller någon annan mängd noder. Mängden noder som ska itereras bestäms av implementationen av NodeIterator. DOM Level 2 specificerar en enda NodeIterator‑implementation för dokumentordnings‑traversering av ett dokumentundernod. Instanser av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator().

Se även [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface ITraversal : IDisposable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Filter](../../aspose.svg.dom.traversal/itraversal/filter/) { get; } | NodeFilter som används för att filtrera noder. |
| [Root](../../aspose.svg.dom.traversal/itraversal/root/) { get; } | Rotnoden för NodeIterator, enligt specifikationen när den skapades. |
| [WhatToShow](../../aspose.svg.dom.traversal/itraversal/whattoshow/) { get; } | Detta attribut bestämmer vilka nodtyper som presenteras via iteratören. Den tillgängliga uppsättningen av konstanter definieras i NodeFilter‑gränssnittet. Noder som inte accepteras av whatToShow kommer att hoppas över, men deras barn kan fortfarande beaktas. Observera att detta hopp har företräde framför filtret, om något finns. |

### Se även

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)

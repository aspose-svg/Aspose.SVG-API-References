---
title: "IXPathResult-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.XPath.IXPathResult gränssnitt. XPathResult‑gränssnittet representerar resultatet av utvärderingen av ett XPath 1.0‑uttryck inom kontexten för en specifik nod. Eftersom utvärderingen av ett XPath‑uttryck kan ge olika resultattyper möjliggör detta objekt att upptäcka och manipulera typ och värde för resultatet."
type: docs
weight: 3350
url: /sv/net/aspose.svg.dom.xpath/ixpathresult/
---
## IXPathResult interface

Gränssnittet `XPathResult` representerar resultatet av utvärderingen av ett XPath 1.0-uttryck inom kontexten av en specifik nod. Eftersom utvärderingen av ett XPath-uttryck kan ge olika resultattyper, möjliggör detta objekt att upptäcka och manipulera typ och värde på resultatet.

```csharp
public interface IXPathResult
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BooleanValue](../../aspose.svg.dom.xpath/ixpathresult/booleanvalue/) { get; } | Värdet för detta booleska resultat. |
| [InvalidIteratorState](../../aspose.svg.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | Anger att iteratorn har blivit ogiltig. Sant om `resultType` är av typen `UnorderedNodeIterator` eller `OrderedNodeIterator` och dokumentet har ändrats sedan detta resultat returnerades. |
| [NumberValue](../../aspose.svg.dom.xpath/ixpathresult/numbervalue/) { get; } | Värdet för detta numeriska resultat. |
| [ResultType](../../aspose.svg.dom.xpath/ixpathresult/resulttype/) { get; } | En kod som representerar typen av detta resultat, enligt definitionen på http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult [`XPathResultType`](../xpathresulttype/)‑enum. |
| [SingleNodeValue](../../aspose.svg.dom.xpath/ixpathresult/singlenodevalue/) { get; } | Värdet för detta enkelnodresultat, som kan vara `null`. |
| [SnapshotLength](../../aspose.svg.dom.xpath/ixpathresult/snapshotlength/) { get; } | Antalet noder i resultatsnapshottet. Giltiga värden för snapshotItem‑index är `0` till `snapshotLength-1` inklusive. |
| [StringValue](../../aspose.svg.dom.xpath/ixpathresult/stringvalue/) { get; } | Värdet för detta strängresultat. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [IterateNext](../../aspose.svg.dom.xpath/ixpathresult/iteratenext/)() | Itererar och returnerar nästa nod från nodmängden eller `null` om det inte finns fler noder. |
| [SnapshotItem](../../aspose.svg.dom.xpath/ixpathresult/snapshotitem/)(*int*) | Returnerar det `index`:e objektet i snapshot‑samlingen. Om `index` är större än eller lika med antalet noder i listan returnerar denna metod `null`. Till skillnad från iteratorresultatet blir snapshotet inte ogiltigt, men kan eventuellt inte motsvara det aktuella dokumentet om det har förändrats. |

### Se även

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)

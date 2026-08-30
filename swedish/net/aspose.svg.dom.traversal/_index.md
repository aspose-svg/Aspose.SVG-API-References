---
title: "Aspose.Svg.Dom.Traversal"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Traversal‑namnutrymmet innehåller metoder som skapar iteratorer och tree‑walkers för att navigera mellan element och traversera en nod och dess barn i dokumentordning."
type: docs
weight: 120
url: /sv/net/aspose.svg.dom.traversal/
---
Namnrummet **Aspose.Svg.Dom.Traversal** innehåller metoder som skapar iteratorer och träd‑gårare för att navigera mellan element och traversera en nod och dess barn i dokumentordning.

## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal innehåller metoder som skapar iteratorer och tree‑walkers för att traversera en nod och dess barn i dokumentordning (djup först, pre‑order‑traversering, vilket är ekvivalent med den ordning i vilken starttaggarna förekommer i dokumentets textrepresentation). I DOM‑er som stödjer Traversal‑funktionen kommer DocumentTraversal att implementeras av samma objekt som implementerar Document‑gränssnittet. |
| [IElementTraversal](./ielementtraversal/) | ElementTraversal‑gränssnittet är en uppsättning skrivskyddade attribut som låter en författare enkelt navigera mellan element i ett dokument. I konformande implementationer av Element Traversal måste alla objekt som implementerar Element även implementera ElementTraversal‑gränssnittet. |
| [INodeFilter](./inodefilter/) | Filter är objekt som vet hur man \"filtrerar bort\" noder. Om en NodeIterator eller TreeWalker får ett NodeFilter, tillämpas filtret innan nästa nod returneras. Om filtret godkänner noden returneras den av traverseringslogiken; annars söker traverseringen efter nästa nod och låtsas att den avvisade noden inte fanns. |
| [INodeIterator](./inodeiterator/) | Iteratorer används för att gå igenom en mängd noder, t.ex. mängden noder i en NodeList, dokumentundernoden som styrs av en specifik Node, resultatet av en fråga eller någon annan mängd noder. Mängden noder som ska itereras bestäms av implementationen av NodeIterator. DOM Level 2 specificerar en enda NodeIterator‑implementation för dokumentordnings‑traversering av ett dokumentundernod. Instanser av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator(). |
| [ITraversal](./itraversal/) | Iteratorer används för att gå igenom en mängd noder, t.ex. mängden noder i en NodeList, dokumentundernoden som styrs av en specifik Node, resultatet av en fråga eller någon annan mängd noder. Mängden noder som ska itereras bestäms av implementationen av NodeIterator. DOM Level 2 specificerar en enda NodeIterator‑implementation för dokumentordnings‑traversering av ett dokumentundernod. Instanser av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator(). |
| [ITreeWalker](./itreewalker/) | TreeWalker‑objekt används för att navigera i ett dokumentträd eller en undernod med hjälp av dokumentvyn som definieras av deras whatToShow‑flaggor och filter (om sådant finns). Alla funktioner som utför navigering med en TreeWalker kommer automatiskt att stödja vilken vy som helst som definieras av en TreeWalker. |

---
title: "XPathResultType‑enum"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.XPath.XPathResultType enum. En osignerad short som indikerar vilken typ av resultat detta är. Om en specifik typ anges kommer resultatet att returneras som motsvarande typ med hjälp av XPath‑typkonverteringar där det krävs och är möjligt."
type: docs
weight: 3360
url: /sv/net/aspose.svg.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

En osignerad kortvariabel som indikerar vilken typ av resultat detta är. Om en specifik `type` anges, returneras resultatet som motsvarande typ, med XPath-typkonverteringar där det krävs och är möjligt.

```csharp
public enum XPathResultType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Any | `0` | Denna kod representerar ingen specifik typ. En utvärdering av ett XPath‑uttryck kommer aldrig att producera denna typ. Om denna typ begärs returnerar utvärderingen den typ som naturligt uppstår vid utvärderingen av uttrycket. Om det naturliga resultatet är en nodmängd när typen `Any` begärdes, blir `UnorderedNodeIterator` alltid den resulterande typen. Alla andra representationer av en nodmängd måste begäras explicit. |
| Number | `1` | Resultatet är ett tal enligt [XPath 1.0]. Dokumentändringar gör inte talet ogiltigt, men kan innebära att en nyutvärdering inte ger samma tal. |
| String | `2` | Resultatet är en sträng enligt [XPath 1.0]. Dokumentändringar gör inte strängen ogiltig, men kan innebära att strängen inte längre motsvarar det aktuella dokumentet. |
| Boolean | `3` | Resultatet är ett booleskt värde enligt [XPath 1.0]. Dokumentändringar gör inte booleskt värde ogiltigt, men kan innebära att en nyutvärdering inte ger samma booleska värde. |
| UnorderedNodeIterator | `4` | Resultatet är en nodmängd enligt [XPath 1.0] som kommer att nås iterativt, vilket kan innebära att noderna inte levereras i någon särskild ordning. Dokumentändringar gör iterationen ogiltig. Detta är standardtypen som returneras om resultatet är en nodmängd och typen `Any` begärs. |
| OrderedNodeIterator | `5` | Resultatet är en nodmängd enligt [XPath 1.0] som kommer att nås iterativt, vilket kommer att producera dokumentordnade noder. Dokumentändringar gör iterationen ogiltig. |
| UnorderedNodeSnapshot | `6` | Resultatet är en noduppsättning enligt [XPath 1.0] som kommer att nås som en ögonblicksbildlista av noder som kanske inte är i någon särskild ordning. Dokumentändring ogiltigförklarar inte ögonblicksbilden men kan innebära att en omvärdering inte ger samma ögonblicksbild och noder i ögonblicksbilden kan ha ändrats, flyttats eller tagits bort från dokumentet. |
| OrderedNodeSnapshot | `7` | Resultatet är en noduppsättning enligt [XPath 1.0] som kommer att nås som en ögonblicksbildlista av noder som kommer att vara i dokumentets ursprungliga ordning. Dokumentändring ogiltigförklarar inte ögonblicksbilden men kan innebära att en omvärdering inte ger samma ögonblicksbild och noder i ögonblicksbilden kan ha ändrats, flyttats eller tagits bort från dokumentet. |
| AnyUnorderedNode | `8` | Resultatet är en noduppsättning enligt [XPath 1.0] och kommer att nås som en enda nod, som kan vara `null` om noduppsättningen är tom. Dokumentändring ogiltigförklarar inte noden, men kan innebära att resultatnoden inte längre motsvarar det aktuella dokumentet. Detta är en bekvämlighet som möjliggör optimering eftersom implementeringen kan stoppa så snart någon nod i den resulterande uppsättningen har hittats. Om det finns mer än en nod i det faktiska resultatet, kan den returnerade enkelnoden vara annorlunda än den första i dokumentordning. |
| FirstOrderedNode | `9` | Resultatet är en noduppsättning enligt [XPath 1.0] och kommer att nås som en enda nod, som kan vara `null` om noduppsättningen är tom. Dokumentändring ogiltigförklarar inte noden, men kan innebära att resultatnoden inte längre motsvarar det aktuella dokumentet. Detta är en bekvämlighet som möjliggör optimering eftersom implementeringen kan stoppa så snart den första noden i dokumentordning i den resulterande uppsättningen har hittats. Om det finns mer än en nod i det faktiska resultatet, kommer den returnerade enkelnoden att vara den första i dokumentordning. |

### Se även

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)

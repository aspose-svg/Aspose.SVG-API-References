---
title: "IXPathEvaluator-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.XPath.IXPathEvaluator-gränssnitt. Utvärderingen av XPath-uttryck tillhandahålls av IXPathEvaluator"
type: docs
weight: 3310
url: /sv/net/aspose.svg.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

Utvärderingen av XPath-uttryck tillhandahålls av `IXPathEvaluator`.

```csharp
public interface IXPathEvaluator
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CreateExpression](../../aspose.svg.dom.xpath/ixpathevaluator/createexpression/)(*string, [IXPathNSResolver](../ixpathnsresolver/)*) | Skapar ett analyserat XPath-uttryck med upplösta namnrymder. Detta är användbart när ett uttryck kommer att återanvändas i en applikation eftersom det möjliggör att kompilera uttrycksträngen till en mer effektiv intern form och förupplösa alla namnrymdsprefix som förekommer i uttrycket. |
| [CreateNSResolver](../../aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/)(*[Node](../../aspose.svg.dom/node/)*) | Anpassar vilken DOM-nod som helst för att lösa namnrymder så att ett XPath-uttryck enkelt kan utvärderas i förhållande till kontexten för den nod där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3-metoden `lookupNamespaceURI` på noder för att lösa namespaceURI från ett givet prefix med den aktuella informationen som finns i nodens hierarki när lookupNamespaceURI anropas, och löser även korrekt det implicita xml-prefixet. |
| [Evaluate](../../aspose.svg.dom.xpath/ixpathevaluator/evaluate/)(*string, [Node](../../aspose.svg.dom/node/), [IXPathNSResolver](../ixpathnsresolver/), [XPathResultType](../xpathresulttype/), object*) | Utvärderar en XPath-uttrycksträng och returnerar ett resultat av den angivna typen om möjligt. |

### Se även

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)

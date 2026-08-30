---
title: "Document.CreateNSResolver"
second_title: "Aspose.SVG för .NET API-referens"
description: "Document CreateNSResolver method. Anpassar vilken DOM-nod som helst för att lösa namnrymder så att ett XPath-uttryck enkelt kan utvärderas i förhållande till kontexten för den nod där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3-metoden lookupNamespaceURI på noder för att lösa namespaceURI från ett givet prefix med den aktuella informationen som finns i nodens hierarki när lookupNamespaceURI anropas, och löser även korrekt det implicita xml-prefixet"
type: docs
weight: 910
url: /sv/net/aspose.svg.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Anpassar vilken DOM-nod som helst för att lösa namnrymder så att ett XPath-uttryck enkelt kan utvärderas i förhållande till kontexten för den nod där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3-metoden `lookupNamespaceURI` på noder för att lösa namespaceURI från ett givet prefix med den aktuella informationen som finns i nodens hierarki när lookupNamespaceURI anropas, och löser även korrekt det implicita xml-prefixet.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nodeResolver | Node | Noden som ska användas som kontext för namnrymdslösning. |

### Returvärde

[`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/) which resolves namespaces with respect to the definitions in scope for a specified node.

### Se även

* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

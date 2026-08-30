---
title: "IXPathNSResolver-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.XPath.IXPathNSResolver-gränssnitt. XPathNSResolver-gränssnittet tillåter prefixsträngar i uttrycket att korrekt bindas till namespaceURI-strängar. IXPathEvaluator kan konstruera en implementation av IXPathNSResolver från en nod eller så kan gränssnittet implementeras av vilken applikation som helst."
type: docs
weight: 3330
url: /sv/net/aspose.svg.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

Den `XPathNSResolver`-gränssnittet tillåter `prefix`-strängar i uttrycket att korrekt bindas till `namespaceURI`-strängar. [`IXPathEvaluator`](../ixpathevaluator/) kan konstruera en implementation av `IXPathNSResolver` från en nod, eller så kan gränssnittet implementeras av vilken applikation som helst.

```csharp
public interface IXPathNSResolver
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [LookupNamespaceURI](../../aspose.svg.dom.xpath/ixpathnsresolver/lookupnamespaceuri/)(*string*) | Slå upp den namnrymds-URI som är associerad med den givna namnrymdsprefixen. XPath‑utvärderaren får aldrig anropa detta med ett `null`‑ eller tomt argument, eftersom resultatet av detta är odefinierat. |

### Se även

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)

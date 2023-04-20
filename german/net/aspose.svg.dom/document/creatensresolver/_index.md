---
title: Document.CreateNSResolver
second_title: Aspose.SVG für .NET-API-Referenz
description: Document methode. Passt jeden DOMKnoten an um Namespaces aufzulösen so dass ein XPathAusdruck leicht ausgewertet werden kann relativ zum Kontext des Knotens in dem er im Dokument vorkam. Dieser Adapter funktioniert wie die DOMLevel3MethodelookupNamespaceURI auf Knoten beim Auflösen des NamensraumURI aus einem gegebenen Präfix unter Verwendung der aktuellen Informationen die in der Knotenhierarchie zu dem Zeitpunkt verfügbar sind an dem lookupNamespaceURI aufgerufen wird wobei auch das implizite XMLPräfix korrekt aufgelöst wird.
type: docs
weight: 910
url: /de/net/aspose.svg.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Passt jeden DOM-Knoten an, um Namespaces aufzulösen, so dass ein XPath-Ausdruck leicht ausgewertet werden kann relativ zum Kontext des Knotens, in dem er im Dokument vorkam. Dieser Adapter funktioniert wie die DOM-Level-3-Methode`lookupNamespace-URI` auf Knoten beim Auflösen des Namensraum-URI aus einem gegebenen Präfix unter Verwendung der aktuellen Informationen, die in der Knotenhierarchie zu dem Zeitpunkt verfügbar sind, an dem lookupNamespaceURI aufgerufen wird, wobei auch das implizite XML-Präfix korrekt aufgelöst wird.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nodeResolver | Node | Der Knoten, der als Kontext für die Namensraumauflösung verwendet werden soll. |

### Rückgabewert

[`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/) die Namespaces in Bezug auf die Definitionen im Geltungsbereich für einen bestimmten Knoten auflöst.

### Siehe auch

* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* namensraum [Aspose.Svg.Dom](../../document/)
* Montage [Aspose.SVG](../../../)



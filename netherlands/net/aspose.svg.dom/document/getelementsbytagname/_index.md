---
title: "Document.GetElementsByTagName"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Document GetElementsByTagName‑methode. Deze methode retourneert een HTMLCollection van elementen met de opgegeven tagnaam."
type: docs
weight: 980
url: /nl/net/aspose.svg.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

Deze methode retourneert een [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) van elementen met de opgegeven tagnaam.

Het volledige document wordt doorzocht, inclusief het root‑knooppunt. De geretourneerde [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) is live, wat betekent dat deze zichzelf automatisch bijwerkt om gesynchroniseerd te blijven met de DOM‑boom zonder deze methode opnieuw aan te roepen.

```csharp
public HTMLCollection GetElementsByTagName(string tagname)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tagname | String | Een string die de naam van de elementen weergeeft. De speciale string "*" staat voor alle elementen. |

### Retourwaarde

Een live [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) van gevonden elementen in de volgorde waarin ze in de boom verschijnen.

## Opmerkingen

Zie de officiële [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname).

### Zie ook

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

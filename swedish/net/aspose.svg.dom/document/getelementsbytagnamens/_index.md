---
title: "Document.GetElementsByTagNameNS"
second_title: "Aspose.SVG för .NET API-referens"
description: "Document GetElementsByTagNameNS‑metod. Returnerar en lista med element med det angivna taggnamnet som tillhör den angivna namnrymden. Hela dokumentet söks inklusive rot‑noden."
type: docs
weight: 990
url: /sv/net/aspose.svg.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

Returnerar en lista med element med det angivna taggnamnet som tillhör den angivna namnrymden. Hela dokumentet söks, inklusive rot‑noden.

```csharp
public HTMLCollection GetElementsByTagNameNS(string namespaceURI, string localName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namespaceURI | String | Namnrymd‑URI:n för element att söka efter. |
| localName | String | Antingen det lokala namnet på element att söka efter eller det speciella värdet *, som matchar alla element. |

### Returvärde

En levande [`NodeList`](../../../aspose.svg.collections/nodelist/) av hittade element i den ordning de förekommer i trädet.

## Anmärkningar

Se den officiella [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens).

### Se även

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

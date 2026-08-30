---
title: "Document.GetElementsByTagName"
second_title: "Aspose.SVG för .NET API-referens"
description: "Document GetElementsByTagName‑metod. Denna metod returnerar en HTMLCollection av element med det angivna taggnamnet."
type: docs
weight: 980
url: /sv/net/aspose.svg.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

Denna metod returnerar en [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) av element med det angivna taggnamnet.

Det kompletta dokumentet söks, inklusive rotknuten. Den returnerade [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) är dynamisk, vilket betyder att den uppdateras automatiskt för att hålla sig i synk med DOM‑trädet utan att behöva anropa metoden igen.

```csharp
public HTMLCollection GetElementsByTagName(string tagname)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagname | String | En sträng som representerar namnet på elementen. Den speciella strängen "*" representerar alla element. |

### Returvärde

En levande [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) av hittade element i den ordning de förekommer i trädet.

## Anmärkningar

Se den officiella [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname).

### Se även

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

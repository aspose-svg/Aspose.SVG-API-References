---
title: "Document.GetElementsByClassName"
second_title: "Aspose.SVG för .NET API-referens"
description: "Document GetElementsByClassName method. Denna metod returnerar ett arraylikt objekt med alla barn-element som har alla de angivna klassnamnen"
type: docs
weight: 970
url: /sv/net/aspose.svg.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

Denna metod returnerar ett array‑likt objekt med alla underordnade element som har alla de angivna klassnamnen.

När den anropas på dokumentobjektet söks hela dokumentet, inklusive rotknuten. Du kan också anropa denna metod på vilket element som helst; den kommer endast att returnera element som är ättlingar till det angivna rot‑elementet med det eller de angivna klassnamnen.

```csharp
public HTMLCollection GetElementsByClassName(string classNames)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| classNames | String | Strängen som innehåller en oordnad uppsättning av unika mellanslagsskiljda token som representerar klasser (klassnamn) |

### Returvärde

En levande [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) av hittade element.

## Anmärkningar

Se den officiella [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname).

### Se även

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

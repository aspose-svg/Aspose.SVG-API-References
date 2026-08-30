---
title: "Document.CreateElement"
second_title: "Aspose.SVG för .NET API-referens"
description: "Document CreateElement-metod. Skapar HTML-elementet som anges av localName eller ett HTMLUnknownElement om localName inte känns igen"
type: docs
weight: 850
url: /sv/net/aspose.svg.dom/document/createelement/
---
## Document.CreateElement method

Skapar HTML‑elementet som anges av localName, eller ett HTMLUnknownElement om localName inte känns igen.

```csharp
public Element CreateElement(string localName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | String | En sträng som specificerar vilken typ av element som ska skapas. nodeName för det skapade elementet initieras med värdet av localName. Använd inte kvalificerade namn (t.ex. "html:a") med den här metoden. När den anropas på ett HTML-dokument konverterar createElement() localName till gemener innan elementet skapas. |

### Returvärde

Det nya [`Element`](../../element/).

### Se även

* class [Element](../../element/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

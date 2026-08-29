---
title: "Document.CreateElement"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Document CreateElement‑methode. Maakt het HTML‑element dat is opgegeven door localName of een HTMLUnknownElement als localName niet wordt herkend."
type: docs
weight: 850
url: /nl/net/aspose.svg.dom/document/createelement/
---
## Document.CreateElement method

Maakt het HTML‑element aan dat wordt gespecificeerd door localName, of een HTMLUnknownElement als localName niet wordt herkend.

```csharp
public Element CreateElement(string localName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | String | Een string die het type element specificeert dat moet worden gemaakt. De nodeName van het gemaakte element wordt geïnitialiseerd met de waarde van localName. Gebruik geen gekwalificeerde namen (zoals \"html:a\") met deze methode. Wanneer aangeroepen op een HTML‑document, zet createElement() localName om naar kleine letters voordat het element wordt gemaakt. |

### Retourwaarde

Het nieuwe [`Element`](../../element/).

### Zie ook

* class [Element](../../element/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

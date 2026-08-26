---
title: "Document.CreateElement"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Document CreateElement Methode. Erstellt das HTML-Element, das durch localName angegeben ist, oder ein HTMLUnknownElement, wenn localName nicht erkannt wird"
type: docs
weight: 850
url: /de/net/aspose.svg.dom/document/createelement/
---
## Document.CreateElement method

Erstellt das HTML‑Element, das durch localName angegeben ist, oder ein HTMLUnknownElement, wenn localName nicht erkannt wird.

```csharp
public Element CreateElement(string localName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | String | Eine Zeichenkette, die den Typ des zu erstellenden Elements angibt. Der nodeName des erstellten Elements wird mit dem Wert von localName initialisiert. Verwenden Sie mit dieser Methode keine qualifizierten Namen (wie "html:a"). Wenn sie in einem HTML-Dokument aufgerufen wird, konvertiert createElement() localName in Kleinbuchstaben, bevor das Element erstellt wird. |

### Rückgabewert

Das neue [`Element`](../../element/).

### Siehe auch

* class [Element](../../element/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

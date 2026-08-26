---
title: "Document.GetElementsByClassName"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Document GetElementsByClassName Methode. Diese Methode gibt ein array-ähnliches Objekt aller Kind-Elemente zurück, die alle angegebenen Klassennamen besitzen."
type: docs
weight: 970
url: /de/net/aspose.svg.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

Diese Methode gibt ein array‑ähnliches Objekt aller Kind‑Elemente zurück, die alle angegebenen Klassennamen besitzen.

Wenn sie auf dem Dokumentobjekt aufgerufen wird, wird das gesamte Dokument durchsucht, einschließlich des Wurzelknotens. Sie können diese Methode auch auf jedem Element aufrufen; sie gibt nur Elemente zurück, die Nachkommen des angegebenen Wurzelelements mit dem/den angegebenen Klassennamen sind.

```csharp
public HTMLCollection GetElementsByClassName(string classNames)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| classNames | String | Der String, der eine ungeordnete Menge eindeutiger, durch Leerzeichen getrennter Tokens enthält, die Klassen (Klassennamen) darstellen. |

### Rückgabewert

Eine Live-[`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) gefundener Elemente.

## Hinweise

Siehe die offizielle [Spezifikation](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname).

### Siehe auch

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

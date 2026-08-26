---
title: "Document.GetElementsByTagName"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Document GetElementsByTagName‑Methode. Diese Methode gibt eine HTMLCollection von Elementen mit dem angegebenen Tag‑Namen zurück."
type: docs
weight: 980
url: /de/net/aspose.svg.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

Diese Methode gibt eine [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) von Elementen mit dem angegebenen Tag‑Namen zurück.

Das gesamte Dokument wird durchsucht, einschließlich des Wurzelknotens. Die zurückgegebene [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) ist live, das heißt, sie aktualisiert sich automatisch, um mit dem DOM‑Baum synchron zu bleiben, ohne dass diese Methode erneut aufgerufen werden muss.

```csharp
public HTMLCollection GetElementsByTagName(string tagname)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagname | String | Ein String, der den Namen der Elemente darstellt. Der spezielle String "*" steht für alle Elemente. |

### Rückgabewert

Eine live [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) gefundener Elemente in der Reihenfolge, in der sie im Baum erscheinen.

## Hinweise

Siehe die offizielle [Spezifikation](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname).

### Siehe auch

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

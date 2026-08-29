---
title: "NodeList Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Collections.NodeList class. De NodeList biedt de abstractie van een geordende verzameling knooppunten zonder te definiëren of te beperken hoe deze verzameling is geïmplementeerd"
type: docs
weight: 2030
url: /nl/net/aspose.svg.collections/nodelist/
---
## NodeList class

De NodeList biedt de abstractie van een geordende collectie van knooppunten, zonder te definiëren of te beperken hoe deze collectie wordt geïmplementeerd.

```csharp
public abstract class NodeList : DOMObject, IEnumerable<Node>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/nodelist/item/) { get; } | Methode retourneert het index‑de item in de collectie. Als index groter dan of gelijk is aan het aantal knooppunten in de lijst, retourneert dit null. |
| abstract [Length](../../aspose.svg.collections/nodelist/length/) { get; } | Het aantal knooppunten in de lijst. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/nodelist/getenumerator/)() | Retourneert een enumerator die door de collectie iterereert. |
| override [GetPlatformType](../../aspose.svg.collections/nodelist/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |

### Zie ook

* class [DOMObject](../../aspose.svg.dom/domobject/)
* class [Node](../../aspose.svg.dom/node/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)

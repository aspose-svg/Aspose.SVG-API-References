---
title: "IParentNode-Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.IParentNode-Schnittstelle. Definiert die IParentNode-Schnittstelle, die von allen möglichen Eltern implementiert wird."
type: docs
weight: 3080
url: /de/net/aspose.svg.dom/iparentnode/
---
## IParentNode interface

Definiert die `IParentNode`-Schnittstelle, die von allen möglichen Eltern implementiert wird.

```csharp
public interface IParentNode : IElementTraversal
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ChildElementCount](../../aspose.svg.dom/iparentnode/childelementcount/) { get; } | Das Attribut childElementCount muss die Anzahl der Kindknoten des Kontextobjekts zurückgeben, die Elemente sind. |
| [Children](../../aspose.svg.dom/iparentnode/children/) { get; } | Gibt die Kind-Elemente zurück. |
| [FirstElementChild](../../aspose.svg.dom/iparentnode/firstelementchild/) { get; } | Gibt das erste Kind zurück, das ein Element ist, andernfalls null. |
| [LastElementChild](../../aspose.svg.dom/iparentnode/lastelementchild/) { get; } | Gibt das letzte Kind zurück, das ein Element ist, andernfalls null. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [QuerySelector](../../aspose.svg.dom/iparentnode/queryselector/)(*string*) | Gibt das erste Element zurück, das ein Nachkomme des Knotens ist und den Selektoren entspricht. |
| [QuerySelectorAll](../../aspose.svg.dom/iparentnode/queryselectorall/)(*string*) | Gibt alle Elementnachkommen des Knotens zurück, die den Selektoren entsprechen. |

### Siehe auch

* interface [IElementTraversal](../../aspose.svg.dom.traversal/ielementtraversal/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

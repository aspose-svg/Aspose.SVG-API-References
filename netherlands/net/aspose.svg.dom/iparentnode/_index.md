---
title: "IParentNode interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.IParentNode interface. Definieert de IParentNode interface die door alle mogelijke ouders wordt geïmplementeerd."
type: docs
weight: 3080
url: /nl/net/aspose.svg.dom/iparentnode/
---
## IParentNode interface

Definieert de `IParentNode`-interface die wordt geïmplementeerd door alle mogelijke ouders.

```csharp
public interface IParentNode : IElementTraversal
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ChildElementCount](../../aspose.svg.dom/iparentnode/childelementcount/) { get; } | Het attribuut childElementCount moet het aantal kinderen van het contextobject dat elementen zijn, retourneren. |
| [Children](../../aspose.svg.dom/iparentnode/children/) { get; } | Geeft de onderliggende elementen terug. |
| [FirstElementChild](../../aspose.svg.dom/iparentnode/firstelementchild/) { get; } | Retourneert het eerste kind dat een element is, en anders null. |
| [LastElementChild](../../aspose.svg.dom/iparentnode/lastelementchild/) { get; } | Retourneert het laatste kind dat een element is, en anders null. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [QuerySelector](../../aspose.svg.dom/iparentnode/queryselector/)(*string*) | Retourneert het eerste element dat een afstammeling is van node en overeenkomt met selectors. |
| [QuerySelectorAll](../../aspose.svg.dom/iparentnode/queryselectorall/)(*string*) | Retourneert alle elementafstammelingen van node die overeenkomen met selectors. |

### Zie ook

* interface [IElementTraversal](../../aspose.svg.dom.traversal/ielementtraversal/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

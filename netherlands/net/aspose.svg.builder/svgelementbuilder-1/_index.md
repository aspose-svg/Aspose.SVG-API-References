---
title: "SVGElementBuilderT class"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.SVGElementBuilder1T class. Vertegenwoordigt een basisklasse voor het bouwen van SVG-elementen van type T"
type: docs
weight: 1160
url: /nl/net/aspose.svg.builder/svgelementbuilder-1/
---
## SVGElementBuilder<T> class

Stelt een basisklasse voor het bouwen van SVG‑elementen van type *T*.

```csharp
public abstract class SVGElementBuilder<T> : ISVGElementBuilder
    where T : SVGElement
```

| Parameter | Beschrijving |
| --- | --- |
| T | Het type SVG-element waarvoor deze builder verantwoordelijk is om te maken. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } | Haalt de lijst met configuraties op die op het SVG-element moeten worden toegepast. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) | Voegt een attribuutconfiguratie toe aan het SVG-element. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Bouwt het SVG-element en past alle configuraties erop toe. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build_1)(*T*) | Past configuraties toe op een bestaand SVG-element. |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | Bouwt het SVG-element als een generiek SVGElement. |

### Zie ook

* interface [ISVGElementBuilder](../isvgelementbuilder/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

---
title: "SVGElementBuilderT-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGElementBuilder1T-klass. Representerar en basklass för att bygga SVG-element av typen T."
type: docs
weight: 1160
url: /sv/net/aspose.svg.builder/svgelementbuilder-1/
---
## SVGElementBuilder<T> class

Representerar en basklass för att bygga SVG-element av typen *T*.

```csharp
public abstract class SVGElementBuilder<T> : ISVGElementBuilder
    where T : SVGElement
```

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av SVG-element som denna byggare är ansvarig för att skapa. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } | Hämtar listan över konfigurationer som ska tillämpas på SVG-elementet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) | Lägger till en attributkonfiguration till SVG-elementet. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Bygger SVG-elementet och tillämpar alla konfigurationer på det. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build_1)(*T*) | Tillämpar konfigurationer på ett befintligt SVG-element. |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | Bygger SVG-elementet som ett generiskt SVGElement. |

### Se även

* interface [ISVGElementBuilder](../isvgelementbuilder/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

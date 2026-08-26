---
title: "SVGSetElementBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGSetElementBuilder Klasse. Builder‑Klasse zum Erstellen eines SVG‑set‑Elements. Das set‑Element wird verwendet, um eine einfache Animation zu definieren, bei der ein einzelner Attributwert über einen Zeitraum hinweg geändert wird. Diese Klasse bietet Methoden zum Festlegen verschiedener, für das set‑Element spezifischer Attribute, wie das Zielattribut und den zu setzenden Wert."
type: docs
weight: 1610
url: /de/net/aspose.svg.builder/svgsetelementbuilder/
---
## SVGSetElementBuilder class

Builder-Klasse zum Erstellen eines SVG-'set'-Elements. Das 'set'-Element wird verwendet, um eine einfache Animation zu definieren, bei der ein einzelner Attributwert über einen Zeitraum hinweg geändert wird. Diese Klasse bietet Methoden zum Festlegen verschiedener Attribute, die speziell für das 'set'-Element gelten, wie das Zielattribut und der zu setzende Wert.

```csharp
public class SVGSetElementBuilder : SVGElementBuilder<SVGSetElement>, 
    IAnimationEventAttributeSetter, IAnimationTargetAttributeSetter, 
    IAnimationTargetElementAttributeSetter, IAnimationTimingAttributeSetter, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGSetElementBuilder](svgsetelementbuilder/)() | Der Standard‑Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGSetElement](../../aspose.svg/svgsetelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [To](../../aspose.svg.builder/svgsetelementbuilder/to/)(*string*) | Setzt das Attribut 'to' des SVG‑'set'‑Elements und gibt den endgültigen Wert des Attributs an, das während der Animation geändert wird. |

### Siehe auch

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGSetElement](../../aspose.svg/svgsetelement/)
* interface [IAnimationEventAttributeSetter](../ianimationeventattributesetter/)
* interface [IAnimationTargetAttributeSetter](../ianimationtargetattributesetter/)
* interface [IAnimationTargetElementAttributeSetter](../ianimationtargetelementattributesetter/)
* interface [IAnimationTimingAttributeSetter](../ianimationtimingattributesetter/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

---
title: "SVGFEBaseLightingElementBuilderTElementTBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGFEBaseLightingElementBuilder2TElementTBuilder Klasse. Abstrakte Basisklasse für Builder von SVG‑Filtereffekt‑Beleuchtungselementen"
type: docs
weight: 1180
url: /de/net/aspose.svg.builder/svgfebaselightingelementbuilder-2/
---
## SVGFEBaseLightingElementBuilder<TElement,TBuilder> class

Abstrakte Basisklasse für Builder von SVG-Filtereffekt‑Beleuchtungselementen.

```csharp
public abstract class SVGFEBaseLightingElementBuilder<TElement, TBuilder> : 
    SVGElementBuilder<TElement>, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
    where TElement : SVGElement
    where TBuilder : SVGFEBaseLightingElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TElement | Der Typ des zu erstellenden SVG‑Elements. |
| TBuilder | Der Typ des Builders selbst. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Fügt dem Element eine Skriptkonfiguration hinzu. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Erstellt das SVG‑Element und wendet die Lichtquellenkonfiguration an, falls angegeben. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*TElement*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [WithFeDistantLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfedistantlight/)(*Action&lt;SVGFEDistantLightElementBuilder&gt;*) | Konfiguriert eine entfernte Lichtquelle für den Filtereffekt. |
| [WithFePointLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfepointlight/)(*Action&lt;SVGFEPointLightElementBuilder&gt;*) | Konfiguriert eine Punktlichtquelle für den Filtereffekt. |
| [WithFeSpotLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfespotlight/)(*Action&lt;SVGFESpotLightElementBuilder&gt;*) | Konfiguriert eine Spotlichtquelle für den Filtereffekt. |

### Siehe auch

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

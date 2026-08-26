---
title: "SVGImageElementBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGImageElementBuilder Klasse. Builder-Klasse zum Erstellen eines SVG‑Bildelements. Dieses Element wird verwendet, um Bilder in SVG‑Grafiken einzubetten. Sie bietet Methoden zum Festlegen verschiedener Attribute, die spezifisch für das Bildelement sind, und zum Hinzufügen zusätzlicher Konfigurationen wie Clip‑Pfad‑Masken, Stile und Skripte."
type: docs
weight: 1470
url: /de/net/aspose.svg.builder/svgimageelementbuilder/
---
## SVGImageElementBuilder class

Builder-Klasse zum Erstellen eines SVG‑'image'-Elements. Dieses Element wird verwendet, um Bilder in SVG‑Grafiken einzubetten. Es bietet Methoden zum Festlegen verschiedener, für das 'image'-Element spezifischer Attribute sowie zum Hinzufügen zusätzlicher Konfigurationen wie Clip‑Pfaden, Masken, Stilen und Skripten.

```csharp
public class SVGImageElementBuilder : SVGElementBuilder<SVGImageElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGImageElementBuilder](svgimageelementbuilder/)() | Der Standard‑Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddClipPath](../../aspose.svg.builder/svgimageelementbuilder/addclippath/)(*Action&lt;SVGClipPathElementBuilder&gt;*) | Fügt dem SVG‑'image'-Element eine Clip‑Pfad‑Konfiguration hinzu. |
| [AddMask](../../aspose.svg.builder/svgimageelementbuilder/addmask/)(*Action&lt;SVGMaskElementBuilder&gt;*) | Fügt dem SVG‑'image'-Element eine Masken‑Konfiguration hinzu. |
| [AddScript](../../aspose.svg.builder/svgimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Fügt dem SVG‑'image'-Element eine Skript‑Konfiguration hinzu. |
| [AddStyle](../../aspose.svg.builder/svgimageelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Fügt dem SVG‑'image'-Element eine Stil‑Konfiguration hinzu. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGImageElement](../../aspose.svg/svgimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgimageelementbuilder/href/)(*string*) | Setzt das 'href'-Attribut des SVG‑'image'-Elements und gibt die URL des einzubettenden Bildes an. |
| [HrefBase64FromBytes](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64frombytes/)(*byte[], string*) | Setzt das 'href'-Attribut des SVG‑'image'-Elements mithilfe von base64‑kodierten Bytes eines Bildes. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile)(*string*) | Setzt das 'href'-Attribut des SVG‑'image'-Elements unter Verwendung einer base64‑kodierten Bilddatei. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile_1)(*string, string*) | Setzt das 'href'-Attribut des SVG‑'image'-Elements unter Verwendung einer base64‑kodierten Bilddatei mit einem angegebenen MIME‑Typ. |

### Siehe auch

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGImageElement](../../aspose.svg/svgimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

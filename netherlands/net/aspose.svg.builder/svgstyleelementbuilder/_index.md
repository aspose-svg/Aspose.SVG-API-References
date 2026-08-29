---
title: "SVGStyleElementBuilder Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.SVGStyleElementBuilder class. Een builderklasse voor het construeren van een SVG style-element. Deze klasse vergemakkelijkt de creatie en configuratie van een SVG style-element met CSS-regels"
type: docs
weight: 1630
url: /nl/net/aspose.svg.builder/svgstyleelementbuilder/
---
## SVGStyleElementBuilder class

Een builder-klasse voor het construeren van een SVG 'style'-element. Deze klasse vergemakkelijkt het maken en configureren van een SVG style-element met CSS-regels.

```csharp
public class SVGStyleElementBuilder : SVGElementBuilder<SVGStyleElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGStyleElementBuilder](svgstyleelementbuilder/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddComment](../../aspose.svg.builder/svgstyleelementbuilder/addcomment/)(*string*) | Voegt een commentaar toe aan de stijlinhoud. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule)(*string, Action&lt;RuleBuilder&gt;*) | Voegt een CSS-regel toe aan het style-element met behulp van een RuleBuilder. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule_1)(*string, string*) | Voegt een CSS-regel toe aan het style-element. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgstyleelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Bouwt het SVG style-element met de verzamelde CSS-regels en voegt het toe aan het opgegeven document. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStyleElement](../../aspose.svg/svgstyleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Media](../../aspose.svg.builder/svgstyleelementbuilder/media/)(*string*) | Stelt het 'media'-attribuut van het SVG 'style'-element in. Dit attribuut specificeert de media waarvoor de stijlen bedoeld zijn, waardoor de stijlen afhankelijk kunnen zijn van het mediatype. |
| [Title](../../aspose.svg.builder/svgstyleelementbuilder/title/)(*string*) | Stelt het 'title'-attribuut van het SVG 'style'-element in. Dit attribuut biedt een adviserende titel voor het style-element, wat nuttig kan zijn voor toegankelijkheid en tooltip-tekst. |
| [Type](../../aspose.svg.builder/svgstyleelementbuilder/type/)(*string*) | Stelt het 'type'-attribuut van het SVG 'style'-element in. Dit attribuut specificeert de stijlbladtaal van de inhoud van het element. |

### Zie ook

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStyleElement](../../aspose.svg/svgstyleelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

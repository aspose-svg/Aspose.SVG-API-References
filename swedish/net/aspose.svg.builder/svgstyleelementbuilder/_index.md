---
title: "SVGStyleElementBuilder Class"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGStyleElementBuilder class. En byggarklass för att konstruera ett SVG-stil-element. Denna klass underlättar skapandet och konfigurationen av ett SVG-stil-element med CSS-regler"
type: docs
weight: 1630
url: /sv/net/aspose.svg.builder/svgstyleelementbuilder/
---
## SVGStyleElementBuilder class

En builder-klass för att konstruera ett SVG 'style'-element. Denna klass underlättar skapandet och konfigurationen av ett SVG style-element med CSS-regler.

```csharp
public class SVGStyleElementBuilder : SVGElementBuilder<SVGStyleElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGStyleElementBuilder](svgstyleelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddComment](../../aspose.svg.builder/svgstyleelementbuilder/addcomment/)(*string*) | Lägger till en kommentar i stilinnehållet. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule)(*string, Action&lt;RuleBuilder&gt;*) | Lägger till en CSS-regel i stil-elementet med en RuleBuilder. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule_1)(*string, string*) | Lägger till en CSS-regel i stil-elementet. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgstyleelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Bygger SVG‑stilelementet med de samlade CSS‑reglerna och lägger till det i det angivna dokumentet. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStyleElement](../../aspose.svg/svgstyleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Media](../../aspose.svg.builder/svgstyleelementbuilder/media/)(*string*) | Ställer in attributet 'media' för SVG‑elementet 'style'. Detta attribut specificerar vilka medier stilarna är avsedda för, vilket gör att stilarna kan vara villkorade beroende på medietypen. |
| [Title](../../aspose.svg.builder/svgstyleelementbuilder/title/)(*string*) | Ställer in attributet 'title' för SVG‑elementet 'style'. Detta attribut ger en rådgivande titel för stilelementet, vilket kan vara användbart för tillgänglighet och verktygstips‑text. |
| [Type](../../aspose.svg.builder/svgstyleelementbuilder/type/)(*string*) | Ställer in attributet 'type' för SVG‑elementet 'style'. Detta attribut specificerar stilmallspråket för elementets innehåll. |

### Se även

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStyleElement](../../aspose.svg/svgstyleelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

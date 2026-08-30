---
title: "Clase SVGStyleElementBuilder"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Clase Aspose.Svg.Builder.SVGStyleElementBuilder. Una clase constructora para crear un elemento de estilo SVG. Esta clase facilita la creación y configuración de un elemento de estilo SVG con reglas CSS"
type: docs
weight: 1630
url: /es/net/aspose.svg.builder/svgstyleelementbuilder/
---
## SVGStyleElementBuilder class

Clase Builder para construir un elemento SVG 'style'. Esta clase facilita la creación y configuración de un elemento de estilo SVG con reglas CSS.

```csharp
public class SVGStyleElementBuilder : SVGElementBuilder<SVGStyleElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SVGStyleElementBuilder](svgstyleelementbuilder/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddComment](../../aspose.svg.builder/svgstyleelementbuilder/addcomment/)(*string*) | Agrega un comentario al contenido del estilo. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule)(*string, Action&lt;RuleBuilder&gt;*) | Agrega una regla CSS al elemento de estilo usando un RuleBuilder. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule_1)(*string, string*) | Agrega una regla CSS al elemento de estilo. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgstyleelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Construye el elemento de estilo SVG con las reglas CSS acumuladas y lo agrega al documento especificado. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStyleElement](../../aspose.svg/svgstyleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Media](../../aspose.svg.builder/svgstyleelementbuilder/media/)(*string*) | Establece el atributo 'media' del elemento SVG 'style'. Este atributo especifica los medios para los que se destinan los estilos, permitiendo que los estilos sean condicionales según el tipo de medio. |
| [Title](../../aspose.svg.builder/svgstyleelementbuilder/title/)(*string*) | Establece el atributo 'title' del elemento SVG 'style'. Este atributo proporciona un título descriptivo para el elemento de estilo, lo que puede ser útil para la accesibilidad y el texto de información sobre herramientas. |
| [Type](../../aspose.svg.builder/svgstyleelementbuilder/type/)(*string*) | Establece el atributo 'type' del elemento SVG 'style'. Este atributo especifica el lenguaje de la hoja de estilo del contenido del elemento. |

### Ver también

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStyleElement](../../aspose.svg/svgstyleelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

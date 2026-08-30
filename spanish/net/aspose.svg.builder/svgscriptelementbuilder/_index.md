---
title: "Clase SVGScriptElementBuilder"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Clase Aspose.Svg.Builder.SVGScriptElementBuilder. Clase constructora para crear un elemento script SVG. El elemento script se utiliza para incrustar o referenciar scripts ejecutables dentro de documentos SVG. Esta clase proporciona métodos para establecer varios atributos específicos del elemento script, como type, source y configuraciones de cross-origin."
type: docs
weight: 1600
url: /es/net/aspose.svg.builder/svgscriptelementbuilder/
---
## SVGScriptElementBuilder class

Clase Builder para construir un elemento SVG 'script'. El elemento 'script' se usa para incrustar o referenciar scripts ejecutables dentro de documentos SVG. Esta clase proporciona métodos para establecer varios atributos específicos del elemento 'script', como tipo, origen y configuraciones de origen cruzado.

```csharp
public class SVGScriptElementBuilder : SVGElementBuilder<SVGScriptElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SVGScriptElementBuilder](svgscriptelementbuilder/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGScriptElement](../../aspose.svg/svgscriptelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Crossorigin](../../aspose.svg.builder/svgscriptelementbuilder/crossorigin/)(*string*) | Establece el atributo 'crossorigin' del elemento 'script' SVG, especificando la configuración CORS para el script externo. |
| [Href](../../aspose.svg.builder/svgscriptelementbuilder/href/)(*string*) | Establece el atributo 'href' del elemento 'script' SVG, especificando la URL de un archivo de script externo. |
| [Type](../../aspose.svg.builder/svgscriptelementbuilder/type/)(*string*) | Establece el atributo 'type' del elemento 'script' SVG, especificando el tipo de lenguaje de secuencias de comandos (p.ej., "text/javascript"). |

### Ver también

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGScriptElement](../../aspose.svg/svgscriptelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

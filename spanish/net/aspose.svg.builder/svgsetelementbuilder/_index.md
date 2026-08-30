---
title: "Clase SVGSetElementBuilder"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Clase Aspose.Svg.Builder.SVGSetElementBuilder. Clase constructora para crear un elemento SVG set. El elemento set se utiliza para definir una animación simple donde el valor de un solo atributo cambia durante un período de tiempo. Esta clase proporciona métodos para establecer varios atributos específicos del elemento set, como el atributo objetivo y el valor a establecer."
type: docs
weight: 1610
url: /es/net/aspose.svg.builder/svgsetelementbuilder/
---
## SVGSetElementBuilder class

Clase Builder para construir un elemento SVG 'set'. El elemento 'set' se usa para definir una animación simple donde el valor de un solo atributo cambia durante un período de tiempo. Esta clase proporciona métodos para establecer varios atributos específicos del elemento 'set', como el atributo objetivo y el valor a establecer.

```csharp
public class SVGSetElementBuilder : SVGElementBuilder<SVGSetElement>, 
    IAnimationEventAttributeSetter, IAnimationTargetAttributeSetter, 
    IAnimationTargetElementAttributeSetter, IAnimationTimingAttributeSetter, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SVGSetElementBuilder](svgsetelementbuilder/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGSetElement](../../aspose.svg/svgsetelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [To](../../aspose.svg.builder/svgsetelementbuilder/to/)(*string*) | Establece el atributo 'to' del elemento SVG 'set', especificando el valor final del atributo que se cambiará durante la animación. |

### Ver también

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

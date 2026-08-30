---
title: "Clase SVGPatternElementBuilder"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Clase Aspose.Svg.Builder.SVGPatternElementBuilder. Clase constructora para crear un elemento de patrón SVG que se utiliza para definir un patrón que se empleará para rellenar elementos gráficos dentro de SVG. Esta clase proporciona métodos para establecer varios atributos específicos del elemento de patrón y para construir su contenido."
type: docs
weight: 1540
url: /es/net/aspose.svg.builder/svgpatternelementbuilder/
---
## SVGPatternElementBuilder class

Clase Builder para construir un elemento SVG 'pattern', que se utiliza para definir un patrón que se usará para rellenar elementos gráficos dentro de SVG. Esta clase proporciona métodos para establecer varios atributos específicos del elemento 'pattern' y para construir su contenido.

```csharp
public class SVGPatternElementBuilder : SVGElementBuilder<SVGPatternElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, IRectAttributeSetter, 
    IViewBoxAttributeSetter
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SVGPatternElementBuilder](svgpatternelementbuilder/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPatternElement](../../aspose.svg/svgpatternelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgpatternelementbuilder/href/)(*string*) | Establece el atributo 'href' del elemento SVG 'pattern', especificando una referencia a otro patrón del cual este patrón hereda atributos. |
| [PatternContentUnits](../../aspose.svg.builder/svgpatternelementbuilder/patterncontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Establece el atributo 'patternContentUnits' del elemento SVG 'pattern', especificando el sistema de coordenadas para el contenido del patrón. |
| [PatternTransform](../../aspose.svg.builder/svgpatternelementbuilder/patterntransform/)(*Func&lt;TransformBuilder, TransformBuilder&gt;*) | Establece el atributo 'patternTransform' del elemento SVG 'pattern', aplicando una transformación al patrón. |
| [PatternUnits](../../aspose.svg.builder/svgpatternelementbuilder/patternunits/)(*[CoordinateUnits](../coordinateunits/)*) | Establece el atributo 'patternUnits' del elemento SVG 'pattern', especificando el sistema de coordenadas para la x, y, ancho y alto del patrón. |

### Ver también

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGPatternElement](../../aspose.svg/svgpatternelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

---
title: "Clase SVGLinearGradientElementBuilder"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Clase Aspose.Svg.Builder.SVGLinearGradientElementBuilder. Clase constructora para crear un elemento SVG linearGradient que se utiliza para definir un degradado lineal dentro de los gráficos SVG. Permite la construcción de contenido dentro del elemento linearGradient y proporciona métodos para establecer varios atributos específicos del elemento linearGradient en SVG."
type: docs
weight: 1490
url: /es/net/aspose.svg.builder/svglineargradientelementbuilder/
---
## SVGLinearGradientElementBuilder class

Clase Builder para construir un elemento SVG 'linearGradient', que se utiliza para definir un degradado lineal dentro de gráficos SVG. Permite la creación de contenido dentro del elemento 'linearGradient' y proporciona métodos para establecer varios atributos específicos del elemento 'linearGradient' en SVG.

```csharp
public class SVGLinearGradientElementBuilder : SVGElementBuilder<SVGLinearGradientElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, IGradientStopElementBuilder, 
    IPresentationAttributeSetter
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SVGLinearGradientElementBuilder](svglineargradientelementbuilder/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svglineargradientelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | Agrega una configuración de animación de transformación al elemento SVG 'linearGradient'. |
| [AddScript](../../aspose.svg.builder/svglineargradientelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Agrega una configuración de script al elemento SVG 'linearGradient'. |
| [AddStyle](../../aspose.svg.builder/svglineargradientelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Agrega una configuración de estilo al elemento SVG 'linearGradient'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGLinearGradientElement](../../aspose.svg/svglineargradientelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svglineargradientelementbuilder/href/)(*string*) | Establece el atributo 'href' del elemento SVG 'linearGradient', especificando una referencia a otro degradado. |
| [X1](../../aspose.svg.builder/svglineargradientelementbuilder/x1/)(*double, [LengthType](../lengthtype/)*) | Establece el atributo 'x1' del elemento SVG 'linearGradient', especificando la coordenada x del punto inicial del degradado. |
| [X2](../../aspose.svg.builder/svglineargradientelementbuilder/x2/)(*double, [LengthType](../lengthtype/)*) | Establece el atributo 'x2' del elemento SVG 'linearGradient', especificando la coordenada x del punto final del degradado. |
| [Y1](../../aspose.svg.builder/svglineargradientelementbuilder/y1/)(*double, [LengthType](../lengthtype/)*) | Establece el atributo 'y1' del elemento SVG 'linearGradient', especificando la coordenada y del punto inicial del degradado. |
| [Y2](../../aspose.svg.builder/svglineargradientelementbuilder/y2/)(*double, [LengthType](../lengthtype/)*) | Establece el atributo 'y2' del elemento SVG 'linearGradient', especificando la coordenada y del punto final del degradado. |

### Ver también

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGLinearGradientElement](../../aspose.svg/svglineargradientelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IGradientStopElementBuilder](../igradientstopelementbuilder/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

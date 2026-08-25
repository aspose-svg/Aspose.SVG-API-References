---
title: "Classe SVGFEBaseLightingElementBuilderTElementTBuilder"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Classe Aspose.Svg.Builder.SVGFEBaseLightingElementBuilder2TElementTBuilder. Classe de base abstraite pour les constructeurs d'éléments d'éclairage d'effets de filtre SVG"
type: docs
weight: 1180
url: /fr/net/aspose.svg.builder/svgfebaselightingelementbuilder-2/
---
## SVGFEBaseLightingElementBuilder<TElement,TBuilder> class

Classe de base abstraite pour les constructeurs d'éléments d'éclairage d'effets de filtre SVG.

```csharp
public abstract class SVGFEBaseLightingElementBuilder<TElement, TBuilder> : 
    SVGElementBuilder<TElement>, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
    where TElement : SVGElement
    where TBuilder : SVGFEBaseLightingElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TElement | Le type d'élément SVG en cours de construction. |
| TBuilder | Le type du constructeur lui-même. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Ajoute une configuration de script à l'élément. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Construit l'élément SVG, en appliquant la configuration de la source lumineuse si spécifiée. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*TElement*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [WithFeDistantLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfedistantlight/)(*Action&lt;SVGFEDistantLightElementBuilder&gt;*) | Configure une source de lumière distante pour l'effet de filtre. |
| [WithFePointLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfepointlight/)(*Action&lt;SVGFEPointLightElementBuilder&gt;*) | Configure une source de lumière ponctuelle pour l'effet de filtre. |
| [WithFeSpotLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfespotlight/)(*Action&lt;SVGFESpotLightElementBuilder&gt;*) | Configure une source de lumière spot pour l'effet de filtre. |

### Voir aussi

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

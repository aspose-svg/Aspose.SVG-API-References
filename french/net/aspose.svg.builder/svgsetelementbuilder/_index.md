---
title: "Classe SVGSetElementBuilder"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Aspose.Svg.Builder.SVGSetElementBuilder classe. Classe de constructeur pour créer un élément SVG set. L'élément set est utilisé pour définir une animation simple où la valeur d'un attribut unique change sur une période de temps. Cette classe fournit des méthodes pour définir divers attributs spécifiques à l'élément set tels que l'attribut cible et la valeur à définir"
type: docs
weight: 1610
url: /fr/net/aspose.svg.builder/svgsetelementbuilder/
---
## SVGSetElementBuilder class

Classe de constructeur pour créer un élément SVG 'set'. L'élément 'set' est utilisé pour définir une animation simple où la valeur d'un attribut unique change sur une période de temps. Cette classe fournit des méthodes pour définir divers attributs spécifiques à l'élément 'set', tels que l'attribut cible et la valeur à définir.

```csharp
public class SVGSetElementBuilder : SVGElementBuilder<SVGSetElement>, 
    IAnimationEventAttributeSetter, IAnimationTargetAttributeSetter, 
    IAnimationTargetElementAttributeSetter, IAnimationTimingAttributeSetter, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SVGSetElementBuilder](svgsetelementbuilder/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Méthodes

| Nom | Description |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGSetElement](../../aspose.svg/svgsetelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [To](../../aspose.svg.builder/svgsetelementbuilder/to/)(*string*) | Définit l'attribut 'to' de l'élément SVG 'set', en spécifiant la valeur finale de l'attribut qui sera modifiée pendant l'animation. |

### Voir aussi

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

---
title: Interface ICSSImportRule
second_title: Référence de l'API Aspose.SVG pour .NET
description: Aspose.Svg.Dom.Css.ICSSImportRule interface. Linterface CSSImportRule représente une règle import dans une feuille de style CSS. La règle import est utilisée pour importer des règles de style à partir dautres feuilles de style.
type: docs
weight: 560
url: /fr/net/aspose.svg.dom.css/icssimportrule/
---
## ICSSImportRule interface

L'interface CSSImportRule représente une règle @import dans une feuille de style CSS. La règle @import est utilisée pour importer des règles de style à partir d'autres feuilles de style.

```csharp
public interface ICSSImportRule : ICSSRule
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Href](../../aspose.svg.dom.css/icssimportrule/href/) { get; } | L'emplacement de la feuille de style à importer. L'attribut ne contiendra pas le spécificateur "url(...)" autour de l'URI. |
| [Media](../../aspose.svg.dom.css/icssimportrule/media/) { get; } | Une liste des types de médias pour lesquels cette feuille de style peut être utilisée. |
| [StyleSheet](../../aspose.svg.dom.css/icssimportrule/stylesheet/) { get; } | La feuille de style référencée par cette règle, si elle a été chargée. La valeur de cet attribut est nulle si la feuille de style n'a pas encore été chargée ou si elle ne le sera pas (par exemple si la feuille de style est pour un type de média non pris en charge par l'agent utilisateur). |

### Voir également

* interface [ICSSRule](../icssrule/)
* espace de noms [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* Assemblée [Aspose.SVG](../../)



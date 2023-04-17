---
title: Interface ICSSStyleDeclaration
second_title: Référence de l'API Aspose.SVG pour .NET
description: Aspose.Svg.Dom.Css.ICSSStyleDeclaration interface. Linterface CSSStyleDeclaration représente un seul bloc de déclaration CSS. Cette interface peut être utilisée pour déterminer les propriétés de style actuellement définies dans un bloc ou pour définir explicitement les propriétés de style dans le bloc.
type: docs
weight: 640
url: /fr/net/aspose.svg.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

L'interface CSSStyleDeclaration représente un seul bloc de déclaration CSS. Cette interface peut être utilisée pour déterminer les propriétés de style actuellement définies dans un bloc ou pour définir explicitement les propriétés de style dans le bloc.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssstyledeclaration/csstext/) { get; set; } | La représentation textuelle analysable du bloc de déclaration (à l'exclusion des accolades environnantes). La définition de cet attribut entraînera l'analyse de la nouvelle valeur et la réinitialisation de toutes les propriétés dans le bloc de déclaration, y compris la suppression ou l'ajout de propriétés. |
| [Item](../../aspose.svg.dom.css/icssstyledeclaration/item/) { get; } | Utilisé pour récupérer les propriétés qui ont été explicitement définies dans ce bloc de déclaration. L'ordre des propriétés récupérées à l'aide de cette méthode ne doit pas nécessairement correspondre à l'ordre dans lequel elles ont été définies. Cette méthode peut être utilisée pour parcourir toutes les propriétés de ce bloc de déclaration. |
| [Length](../../aspose.svg.dom.css/icssstyledeclaration/length/) { get; } | Le nombre de propriétés explicitement définies dans ce bloc de déclaration. La plage d'indices valides est de 0 à longueur-1 inclus. |
| [ParentRule](../../aspose.svg.dom.css/icssstyledeclaration/parentrule/) { get; } | La règle CSS qui contient ce bloc de déclaration ou null si cette CSSStyleDeclaration n'est pas attachée à une CSSRule. |

## Méthodes

| Nom | La description |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | Utilisé pour récupérer la représentation objet de la valeur d'une propriété CSS si elle a été explicitement définie dans ce bloc de déclaration. Cette méthode renvoie null si la propriété est une propriété abrégée. Les valeurs de propriété abrégées ne peuvent être consultées et modifiées que sous forme de chaînes, à l'aide des méthodes getPropertyValue et setProperty. |
| [GetPropertyPriority](../../aspose.svg.dom.css/icssstyledeclaration/getpropertypriority/)(string) | Utilisé pour récupérer la priorité d'une propriété CSS (par exemple le qualificateur "important") si la propriété a été explicitement définie dans ce bloc de déclaration. |
| [GetPropertyValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | Utilisé pour récupérer la valeur d'une propriété CSS si elle a été explicitement définie dans ce bloc de déclaration. |
| [RemoveProperty](../../aspose.svg.dom.css/icssstyledeclaration/removeproperty/)(string) | Utilisé pour supprimer une propriété CSS si elle a été explicitement définie dans ce bloc de déclaration. |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | Utilisé pour définir une valeur de propriété avec une priorité par défaut dans ce bloc de déclaration. La priorité par défaut n'est pas "importante", c'est-à-dire String.Empty |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | Utilisé pour définir une valeur de propriété et une priorité dans ce bloc de déclaration. |

### Voir également

* interface [ICSS2Properties](../icss2properties/)
* espace de noms [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* Assemblée [Aspose.SVG](../../)



---
title: Interface ICSSStyleSheet
second_title: Référence de l'API Aspose.SVG pour .NET
description: Aspose.Svg.Dom.Css.ICSSStyleSheet interface. Linterface CSSStyleSheet est une interface concrète permettant de représenter une feuille de style CSS cest à dire une feuille de style dont le type de contenu est text/css.
type: docs
weight: 660
url: /fr/net/aspose.svg.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

L'interface CSSStyleSheet est une interface concrète permettant de représenter une feuille de style CSS c'est à dire une feuille de style dont le type de contenu est "text/css".

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## Propriétés

| Nom | La description |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icssstylesheet/cssrules/) { get; } | La liste de toutes les règles CSS contenues dans la feuille de style. Cela inclut à la fois les ensembles de règles et les règles at. |
| [OwnerRule](../../aspose.svg.dom.css/icssstylesheet/ownerrule/) { get; } | Si cette feuille de style provient d'une règle @import, l'attribut ownerRule contiendra la CSSImportRule. Dans ce cas, l'attribut ownerNode dans l'interface StyleSheet sera nul. Si la feuille de style provient d'un élément ou d'une instruction de traitement, l'attribut ownerRule sera nul et l'attribut ownerNode contiendra le Node. |

## Méthodes

| Nom | La description |
| --- | --- |
| [DeleteRule](../../aspose.svg.dom.css/icssstylesheet/deleterule/)(int) | Utilisé pour supprimer une règle de la feuille de style. |
| [InsertRule](../../aspose.svg.dom.css/icssstylesheet/insertrule/)(string, int) | Utilisé pour insérer une nouvelle règle dans la feuille de style. La nouvelle règle fait désormais partie de la cascade. |

### Voir également

* interface [IStyleSheet](../istylesheet/)
* espace de noms [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* Assemblée [Aspose.SVG](../../)



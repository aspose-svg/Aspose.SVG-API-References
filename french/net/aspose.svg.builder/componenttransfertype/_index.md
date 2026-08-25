---
title: "Enum ComponentTransferType"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Aspose.Svg.Builder.ComponentTransferType enum. Spécifie le type de fonction de transfert de composant à appliquer dans le primitive de filtre FeComponentTransfer d'un SVG"
type: docs
weight: 170
url: /fr/net/aspose.svg.builder/componenttransfertype/
---
## ComponentTransferType enumeration

Spécifie le type de fonction de transfert de composant à appliquer dans le primitive de filtre FeComponentTransfer d’un SVG.

```csharp
public enum ComponentTransferType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Identity | `0` | Représente aucune modification du graphique d'entrée. C'est le type par défaut. |
| Table | `1` | Utilise une table de correspondance pour définir la fonction au sein du filtre. |
| Discrete | `2` | Utilise un ensemble de valeurs discrètes pour définir la fonction dans le filtre. |
| Linear | `3` | Définit une transformation linéaire du composant au sein du filtre. |
| Gamma | `4` | Définit une transformation de correction gamma dans le filtre. |

## Remarques

Le primitive de filtre FeComponentTransfer permet la manipulation individuelle des composants de couleur (RGB et alpha) des éléments graphiques en utilisant différents types de fonctions de transfert. Chaque type définit une méthode distincte de calcul pour la transformation des composants de couleur au sein du filtre.

### Voir aussi

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

---
title: "SVGFEColorMatrixElementBuilder.TypeAndValues"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode TypeAndValues de SVGFEColorMatrixElementBuilder. Définit les attributs type et values de l'élément feColorMatrix spécifiant l'opération de matrice de couleur et ses paramètres"
type: docs
weight: 30
url: /fr/net/aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/
---
## SVGFEColorMatrixElementBuilder.TypeAndValues method

Définit les attributs 'type' et 'values' de l'élément feColorMatrix, spécifiant l'opération de matrice de couleur et ses paramètres.

```csharp
public SVGFEColorMatrixElementBuilder TypeAndValues(ColorMatrixOperation type, 
    params double[] values)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | ColorMatrixOperation | La valeur d'énumération ColorMatrixOperation représentant le type d'opération de matrice de couleur. |
| valeurs | Double[] | Les paramètres de l'opération de matrice de couleur. |

### Valeur de retour

L’instance actuelle du builder.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque les valeurs fournies ne correspondent pas aux exigences du type spécifié. |
| NotSupportedException | Lancée lorsque un type d'opération de matrice non pris en charge est fourni. |

### Voir aussi

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [SVGFEColorMatrixElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

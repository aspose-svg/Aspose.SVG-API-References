---
title: "SVGGeometryElement.Combine"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode Combine de SVGGeometryElement. Combine cette géométrie avec une autre géométrie SVG en utilisant une opération booléenne et renvoie un nouvel élément de chemin contenant le résultat."
type: docs
weight: 20
url: /fr/net/aspose.svg/svggeometryelement/combine/
---
## SVGGeometryElement.Combine method

Combine cette géométrie avec une autre géométrie SVG en utilisant une opération booléenne, et renvoie un nouvel élément `<path>` contenant le résultat.

```csharp
public SVGPathElement Combine(SVGGeometryElement geometryElement, BooleanPathOp op)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| geometryElement | SVGGeometryElement | L'autre géométrie à combiner. Doit être dans le même document. |
| op | BooleanPathOp | L'opérateur booléen à appliquer : Union (A UNION B), Différence (A - B), Intersection (A INTERSECT B) ou Exclusion (XOR). |

### Valeur de retour

Un nouveau [`SVGPathElement`](../../svgpathelement/) dont l'attribut `d` encode le résultat dans l'espace utilisateur racine `<svg>` (px CSS). L'élément n'est pas ajouté au DOM.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée si *geometryElement* est nul. |
| InvalidOperationException | Lancée si cet élément n'a aucun document propriétaire. |
| NotSupportedException | Lancée lorsque les opérations booléennes de chemin ne sont pas disponibles ; cette fonctionnalité nécessite le backend SkiaSharp (installez le package Aspose.SVG.Drawing.SkiaSharp). |

### Voir aussi

* class [SVGPathElement](../../svgpathelement/)
* enum [BooleanPathOp](../../../aspose.svg.rendering/booleanpathop/)
* class [SVGGeometryElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

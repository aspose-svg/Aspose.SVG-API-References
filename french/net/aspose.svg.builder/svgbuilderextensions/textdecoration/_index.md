---
title: "SVGBuilderExtensions.TextDecoration"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode TextDecoration de SVGBuilderExtensions. Définit l'attribut text-decoration pour un élément SVG définissant les décorations ajoutées au texte"
type: docs
weight: 2210
url: /fr/net/aspose.svg.builder/svgbuilderextensions/textdecoration/
---
## SVGBuilderExtensions.TextDecoration<TBuilder> method

Définit l'attribut 'text-decoration' pour un élément SVG, en définissant les décorations qui sont ajoutées au texte.

```csharp
public static TBuilder TextDecoration<TBuilder>(this TBuilder builder, bool underline = false, 
    bool overline = false, bool lineThrough = false, bool blink = false)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| souligné | Spécifie si le texte doit être souligné. |
| ligne supérieure | Spécifie si le texte doit avoir une ligne supérieure. |
| barré | Spécifie si le texte doit être barré. |
| clignoter | Spécifie si le texte doit clignoter (non recommandé). |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

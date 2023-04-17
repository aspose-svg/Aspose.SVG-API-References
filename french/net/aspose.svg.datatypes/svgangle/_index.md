---
title: Class SVGAngle
second_title: Référence de l'API Aspose.SVG pour .NET
description: Aspose.Svg.DataTypes.SVGAngle classe. Linterface SVGAngle correspond au type de données de base dangle.
type: docs
weight: 80
url: /fr/net/aspose.svg.datatypes/svgangle/
---
## SVGAngle class

L'interface SVGAngle correspond au type de données de base d'angle.

```csharp
public class SVGAngle : SVGValueType
```

## Propriétés

| Nom | La description |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svgangle/unittype/) { get; } | Le type de la valeur tel que spécifié par l'une des constantes SVG_ANGLETYPE_* définies sur cette interface. |
| [Value](../../aspose.svg.datatypes/svgangle/value/) { get; set; } | La valeur de l'angle sous forme de valeur à virgule flottante, en degrés. La définition de cet attribut entraînera la mise à jour automatique de valueInSpecifiedUnits et valueAsString pour refléter ce paramètre. |
| [ValueAsString](../../aspose.svg.datatypes/svgangle/valueasstring/) { get; set; } | La valeur d'angle sous forme de valeur de chaîne, dans les unités exprimées par unitType. La définition de cet attribut entraînera la mise à jour automatique de value, valueInSpecifiedUnits et unitType pour refléter ce paramètre. |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | La valeur d'angle sous forme de valeur à virgule flottante, dans les unités exprimées par unitType. La définition de cet attribut entraînera la mise à jour automatique de value et valueAsString pour refléter ce paramètre. |

## Méthodes

| Nom | La description |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | Préserve la même valeur stockée sous-jacente, mais réinitialise l'identifiant d'unité stocké sur le type d'unité donné. Les attributs d'objet unitType, valueInSpecifiedUnits et valueAsString peuvent être modifiés à la suite de cette méthode. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Libère les ressources non gérées et - éventuellement - gérées. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | Réinitialisez la valeur sous forme de nombre avec un type d'unité associé, remplaçant ainsi les valeurs de tous les attributs de l'objet. |
| override [ToString](../../aspose.svg.datatypes/svgangle/tostring/)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.svg.datatypes/svgangle/svg_angletype_deg/) | Le type d'unité a été explicitement défini sur degrés. |
| const [SVG_ANGLETYPE_GRAD](../../aspose.svg.datatypes/svgangle/svg_angletype_grad/) | Le type d'unité est le radian. |
| const [SVG_ANGLETYPE_RAD](../../aspose.svg.datatypes/svgangle/svg_angletype_rad/) | Le type d'unité est le radian. |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.svg.datatypes/svgangle/svg_angletype_unknown/) | Le type d'unité ne fait pas partie des types d'unité prédéfinis. Il n'est pas valide de tenter de définir une nouvelle valeur de ce type ou de tenter de basculer une valeur existante vers ce type. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.svg.datatypes/svgangle/svg_angletype_unspecified/) | Aucun type d'unité n'a été fourni (c'est-à-dire qu'une valeur sans unité a été spécifiée). Pour les angles, une valeur sans unité est traitée de la même manière que si des degrés étaient spécifiés. |

### Voir également

* class [SVGValueType](../svgvaluetype/)
* espace de noms [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* Assemblée [Aspose.SVG](../../)



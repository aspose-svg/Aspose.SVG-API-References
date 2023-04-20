---
title: SVGAngle.NewValueSpecifiedUnits
second_title: Référence de l'API Aspose.SVG pour .NET
description: SVGAngle méthode. Réinitialisez la valeur sous forme de nombre avec un type dunité associé remplaçant ainsi les valeurs de tous les attributs de lobjet.
type: docs
weight: 60
url: /fr/net/aspose.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Réinitialisez la valeur sous forme de nombre avec un type d'unité associé, remplaçant ainsi les valeurs de tous les attributs de l'objet.

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| newUnitType | UInt16 | Le type d'unité pour la valeur (par exemple, SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | La valeur de l'angle. |

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) Levé si unitType est SVG_ANGLETYPE_UNKNOWN ou n'est pas une constante de type d'unité valide (l'une des autres constantes SVG_ANGLETYPE_* définies sur cette interface). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Levé lorsque l'angle correspond à un attribut en lecture seule ou lorsque l'objet lui-même est en lecture seule. |

### Voir également

* class [SVGAngle](../)
* espace de noms [Aspose.Svg.DataTypes](../../svgangle/)
* Assemblée [Aspose.SVG](../../../)



---
title: "SVGTransform Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.DataTypes.SVGTransform klasse. SVGTransform is de interface voor een van de componenttransformaties binnen een SVGTransformList, dus een SVGTransform-object komt overeen met een enkele component, bijv. schaal of matrix binnen een transform-attribuutspecificatie"
type: docs
weight: 2310
url: /nl/net/aspose.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform is de interface voor een van de componenttransformaties binnen een SVGTransformList; een SVGTransform‑object komt dus overeen met één component (bijv. 'scale(…)' of 'matrix(…)') binnen een ‘transform’-attribuutspecificatie.

```csharp
public class SVGTransform : SVGValueType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Angle](../../aspose.svg.datatypes/svgtransform/angle/) { get; } | Een handig attribuut voor SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX en SVG_TRANSFORM_SKEWY. Het bevat de opgegeven hoek. Voor SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE en SVG_TRANSFORM_SCALE zal de hoek nul zijn. |
| [Matrix](../../aspose.svg.datatypes/svgtransform/matrix/) { get; } | De matrix die deze transformatie vertegenwoordigt. Het matrixobject is live, wat betekent dat elke wijziging aan het SVGTransform-object onmiddellijk wordt weerspiegeld in het matrixobject en omgekeerd. Als het matrixobject rechtstreeks wordt gewijzigd (d.w.z. zonder de methoden op de SVGTransform-interface zelf te gebruiken), verandert het type van de SVGTransform naar SVG_TRANSFORM_MATRIX. Voor SVG_TRANSFORM_MATRIX bevat de matrix de a, b, c, d, e, f-waarden die door de gebruiker zijn opgegeven. Voor SVG_TRANSFORM_TRANSLATE vertegenwoordigen e en f de translatiewaarden (a= 1, b= 0, c= 0 en d = 1). Voor SVG_TRANSFORM_SCALE vertegenwoordigen a en d de schaalwaarden (b= 0, c= 0, e= 0 en f = 0). Voor SVG_TRANSFORM_SKEWX en SVG_TRANSFORM_SKEWY vertegenwoordigen a, b, c en d de matrix die resulteert in de opgegeven scheefstand (e= 0 en f = 0). Voor SVG_TRANSFORM_ROTATE vertegenwoordigen a, b, c, d, e en f samen de matrix die resulteert in de opgegeven rotatie. Wanneer de rotatie rond het middelpunt (0, 0) plaatsvindt, zullen e en f nul zijn. |
| [Type](../../aspose.svg.datatypes/svgtransform/type/) { get; } | Het type van de waarde zoals gespecificeerd door een van de SVG_TRANSFORM_*-constanten die op deze interface zijn gedefinieerd. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Vrijgeeft niet‑beheerde en - optioneel - beheerde bronnen. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [SetMatrix](../../aspose.svg.datatypes/svgtransform/setmatrix/)(*[SVGMatrix](../svgmatrix/)*) | Stelt het transformatietype in op SVG_TRANSFORM_MATRIX, met parameter matrix die de nieuwe transformatie definieert. De waarden van de matrixparameter worden gekopieerd; de matrixparameter vervangt niet SVGTransform::matrix. |
| [SetRotate](../../aspose.svg.datatypes/svgtransform/setrotate/)(*float, float, float*) | Stelt het transformatietype in op SVG_TRANSFORM_ROTATE, met parameter angle die de rotatiehoek definieert en parameters cx en cy die het optionele rotatiecentrum definiëren. |
| [SetScale](../../aspose.svg.datatypes/svgtransform/setscale/)(*float, float*) | Stelt het transformatietype in op SVG_TRANSFORM_SCALE, met parameters sx en sy die de schaalwaarden definiëren. |
| [SetSkewX](../../aspose.svg.datatypes/svgtransform/setskewx/)(*float*) | Stelt het transformatietype in op SVG_TRANSFORM_SKEWX, met parameter angle die de mate van scheefstand definieert. |
| [SetSkewY](../../aspose.svg.datatypes/svgtransform/setskewy/)(*float*) | Stelt het transformatietype in op SVG_TRANSFORM_SKEWY, met parameter angle die de mate van scheefstand definieert. |
| [SetTranslate](../../aspose.svg.datatypes/svgtransform/settranslate/)(*float, float*) | Stelt het transformatietype in op SVG_TRANSFORM_TRANSLATE, met de parameters tx en ty die de translatiewaarden definiëren. |
| override [ToString](../../aspose.svg.datatypes/svgtransform/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.svg.datatypes/svgtransform/svg_transform_matrix/) | Een 'matrix(…)' transformatie. |
| const [SVG_TRANSFORM_ROTATE](../../aspose.svg.datatypes/svgtransform/svg_transform_rotate/) | Een 'rotate(…)' transformatie. |
| const [SVG_TRANSFORM_SCALE](../../aspose.svg.datatypes/svgtransform/svg_transform_scale/) | Een 'scale(…)' transformatie. |
| const [SVG_TRANSFORM_SKEWX](../../aspose.svg.datatypes/svgtransform/svg_transform_skewx/) | Een 'skewX(…)' transformatie. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.svg.datatypes/svgtransform/svg_transform_skewy/) | Een 'skewY(…)' transformatie. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.svg.datatypes/svgtransform/svg_transform_translate/) | Een 'translate(…)' transformatie. |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.svg.datatypes/svgtransform/svg_transform_unknown/) | Het eenheidstype is geen van de vooraf gedefinieerde typen. Het is ongeldig om te proberen een nieuwe waarde van dit type te definiëren of om te proberen een bestaande waarde naar dit type te wijzigen. |

### Zie ook

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)

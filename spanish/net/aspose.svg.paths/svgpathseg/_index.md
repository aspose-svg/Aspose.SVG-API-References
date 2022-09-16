---
title: SVGPathSeg
second_title: Referencia de API de Aspose.SVG para .NET
description: La interfaz SVGPathSeg es una interfaz base que corresponde a un solo comando dentro de una especificación de datos de ruta.
type: docs
weight: 2460
url: /es/net/aspose.svg.paths/svgpathseg/
---
## SVGPathSeg class

La interfaz SVGPathSeg es una interfaz base que corresponde a un solo comando dentro de una especificación de datos de ruta.

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [PathSegType](../../aspose.svg.paths/svgpathseg/pathsegtype) { get; } | El tipo de segmento de ruta especificado por una de las constantes definidas en esta interfaz. |
| [PathSegTypeAsLetter](../../aspose.svg.paths/svgpathseg/pathsegtypeasletter) { get; } | El tipo del segmento de ruta, especificado por el nombre de comando de un carácter correspondiente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose)() | Libera recursos no administrados y, opcionalmente, administrados. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_arc_abs) | Corresponde a un comando de datos de ruta "absolute arcto" (A). |
| const [PATHSEG_ARC_REL](../../aspose.svg.paths/svgpathseg/pathseg_arc_rel) | Corresponde a un "arco relativo" (a) comando de datos de ruta. |
| const [PATHSEG_CLOSEPATH](../../aspose.svg.paths/svgpathseg/pathseg_closepath) | Corresponde a un comando de datos de ruta "closepath" (z). |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_abs) | Corresponde a un comando de datos de ruta "absolute cubic Bézier curveto" (C). |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_rel) | Corresponde a un comando de datos de ruta "curva Bézier cúbica relativa a" (c). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs) | Corresponde a un comando de datos de ruta de "curva cúbica suave absoluta a" (S). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel) | Corresponde a un comando de datos de ruta de "curva cúbica suave relativa a" (s). |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs) | Corresponde a un comando de datos de ruta "absolute quadratic Bézier curveto" (Q). |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel) | Corresponde a un comando de datos de ruta "curva de Bézier cuadrática relativa a" (q). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs) | Corresponde a un comando de datos de trayectoria de "curva cuadrática suave absoluta hacia" (T). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel) | Corresponde a un comando de datos de trayectoria de "curva cuadrática suave relativa a" (t). |
| const [PATHSEG_LINETO_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_abs) | Corresponde a un comando de datos de ruta "línea a absoluta" (L). |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs) | Corresponde a un comando de datos de ruta "línea horizontal absoluta a" (H). |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel) | Corresponde a un comando de datos de ruta de "línea horizontal relativa a" (h). |
| const [PATHSEG_LINETO_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_rel) | Corresponde a un comando de datos de ruta "relativa línea a" (l). |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.svg.paths/svgpathseg/pathseg_lineto_vertical_abs) | Corresponde a un comando de datos de ruta "línea vertical absoluta a" (V). |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.svg.paths/svgpathseg/pathseg_lineto_vertical_rel) | Corresponde a un comando de datos de ruta de "línea vertical relativa a" (v). |
| const [PATHSEG_MOVETO_ABS](../../aspose.svg.paths/svgpathseg/pathseg_moveto_abs) | Corresponde a un comando de datos de ruta "movimiento absoluto a" (M). |
| const [PATHSEG_MOVETO_REL](../../aspose.svg.paths/svgpathseg/pathseg_moveto_rel) | Corresponde a un comando de datos de ruta de "movimiento relativo a" (m). |
| const [PATHSEG_UNKNOWN](../../aspose.svg.paths/svgpathseg/pathseg_unknown) | El tipo de unidad no es uno de los tipos predefinidos. No es válido intentar definir un nuevo valor de este tipo o intentar cambiar un valor existente a este tipo. |

### Ver también

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype)
* espacio de nombres [Aspose.Svg.Paths](../../aspose.svg.paths)
* asamblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->

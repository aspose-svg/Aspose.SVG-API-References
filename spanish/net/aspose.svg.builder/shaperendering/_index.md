---
title: "Enumeración ShapeRendering"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Enumeración Aspose.Svg.Builder.ShapeRendering. Especifica el modo de renderizado de formas para elementos SVG"
type: docs
weight: 1720
url: /es/net/aspose.svg.builder/shaperendering/
---
## ShapeRendering enumeration

Especifica el modo de renderizado de forma para los elementos SVG.

```csharp
public enum ShapeRendering
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | `0` | El navegador hace compromisos entre velocidad, suavidad y precisión geométrica al renderizar formas. |
| OptimizeSpeed | `1` | El navegador enfatiza la velocidad de renderizado sobre la precisión geométrica y la suavidad. Este modo puede producir un renderizado más rápido pero formas menos precisas. |
| CrispEdges | `2` | El navegador intenta preservar bordes y esquinas nítidas. Este modo es útil para renderizar gráficos con líneas y bordes rectos. |
| GeometricPrecision | `3` | El navegador enfatiza la precisión geométrica en el renderizado a costa de la velocidad. Este modo es adecuado para renderizado de alta calidad donde la geometría precisa es importante. |

### Ver también

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

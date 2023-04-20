---
title: Class XpsDevice
second_title: Referencia de API de Aspose.SVG para .NET
description: Aspose.Svg.Rendering.Xps.XpsDevice clase. Representa la representación en un documento xps.
type: docs
weight: 3050
url: /es/net/aspose.svg.rendering.xps/xpsdevice/
---
## XpsDevice class

Representa la representación en un documento xps.

```csharp
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | Inicializa una nueva instancia del`XpsDevice` clase. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | Inicializa una nueva instancia del`XpsDevice` clase. |
| [XpsDevice](xpsdevice/#constructor_5)(string) | Inicializa una nueva instancia del`XpsDevice` clase. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Inicializa una nueva instancia del`XpsDevice` clase por opciones de representación y proveedor de flujo. |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | Inicializa una nueva instancia del`XpsDevice` clase por opciones de representación y flujo de salida. |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, string) | Inicializa una nueva instancia del`XpsDevice` clase por opciones de representación y nombre de archivo de salida. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } |  |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [AddRect](../../aspose.svg.rendering.xps/xpsdevice/addrect/)(RectangleF) | Agrega un rectángulo a la ruta actual como una subruta completa. |
| override [BeginDocument](../../aspose.svg.rendering.xps/xpsdevice/begindocument/)(Document) | Comienza a renderizar el documento. |
| override [BeginElement](../../aspose.svg.rendering.xps/xpsdevice/beginelement/)(Element, RectangleF) | Comienza el renderizado del elemento. |
| override [BeginPage](../../aspose.svg.rendering.xps/xpsdevice/beginpage/)(SizeF) | Comienza a renderizar la nueva página. |
| override [Clip](../../aspose.svg.rendering.xps/xpsdevice/clip/)(FillMode) | Modifica la ruta de recorte actual al intersectarla con la ruta actual, utilizando la regla FillMode para determinar la región a rellenar. Este método finaliza la ruta actual. |
| override [ClosePath](../../aspose.svg.rendering.xps/xpsdevice/closepath/)() | Cierra el subtrayecto actual agregando un segmento de línea recta desde el punto actual hasta el punto inicial del subtrayecto. Si la subruta actual ya está cerrada, "ClosePath" no hace nada. Este operador finaliza la subruta actual. Al agregar otro segmento a la ruta actual, comienza una nueva subruta, incluso si el nuevo segmento comienza en el punto final alcanzado por el método "ClosePath". |
| override [CubicBezierTo](../../aspose.svg.rendering.xps/xpsdevice/cubicbezierto/)(PointF, PointF, PointF) | Agrega una curva de Bézier cúbica a la ruta actual. La curva se extiende desde el punto actual hasta el punto pt2, utilizando pt1 y pt2 como puntos de control Bézier. El nuevo punto actual es pt3. |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.svg.rendering.xps/xpsdevice/drawimage/)(byte[], ImageType, RectangleF) | Dibuja la imagen especificada. |
| virtual [EndDocument](../../aspose.svg.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.svg.rendering.xps/xpsdevice/endelement/)(Element) | Finaliza el renderizado del elemento. |
| override [EndPage](../../aspose.svg.rendering.xps/xpsdevice/endpage/)() | Finaliza el renderizado de la página actual. |
| override [Fill](../../aspose.svg.rendering.xps/xpsdevice/fill/)(FillMode) | Rellena toda la región encerrada por la ruta actual. Si el camino consta de varios subcaminos desconectados, llena el interior de todos los subcaminos, considerados juntos. Este método finaliza la ruta actual. |
| override [FillText](../../aspose.svg.rendering.xps/xpsdevice/filltext/)(string, PointF) | Rellena la cadena de texto especificada en la ubicación especificada. |
| override [Flush](../../aspose.svg.rendering.xps/xpsdevice/flush/)() | Vacía todos los datos al flujo de salida. |
| override [LineTo](../../aspose.svg.rendering.xps/xpsdevice/lineto/)(PointF) | Agrega un segmento de línea recta desde el punto actual hasta el punto (pt). El nuevo punto actual es pt. |
| override [MoveTo](../../aspose.svg.rendering.xps/xpsdevice/moveto/)(PointF) | Comienza un nuevo subtrayecto moviendo el punto actual a las coordenadas del parámetro pt, omitiendo cualquier segmento de línea de conexión. Si el método de construcción de ruta anterior en la ruta actual también era "Mover a", el nuevo "Mover a" lo anula; no queda ningún vestigio de la operación anterior "Mover a" en la ruta. |
| override [RestoreGraphicContext](../../aspose.svg.rendering.xps/xpsdevice/restoregraphiccontext/)() | Restaura todo el contexto de gráficos a su valor anterior extrayéndolo de la pila. |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device-2/savegraphiccontext/)() |  |
| override [Stroke](../../aspose.svg.rendering.xps/xpsdevice/stroke/)() | Traza una línea a lo largo de la ruta actual. La línea trazada sigue cada segmento recto o curvo del camino, centrado en el segmento con lados paralelos a él. Cada uno de los subtrayectos de la ruta se trata por separado. Este método finaliza la ruta actual. |
| override [StrokeAndFill](../../aspose.svg.rendering.xps/xpsdevice/strokeandfill/)(FillMode) | Trazos y relleno de la ruta actual. Este método finaliza la ruta actual. |
| override [StrokeText](../../aspose.svg.rendering.xps/xpsdevice/stroketext/)(string, PointF) | Traza la cadena de texto especificada en la ubicación especificada. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| class [XpsGraphicContext](xpsdevice.xpsgraphiccontext/) | Contiene los parámetros de control de gráficos actuales para XpsDevice. Estos parámetros definen el marco global dentro del cual se ejecutan los operadores de gráficos. |

### Ver también

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.svg.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* espacio de nombres [Aspose.Svg.Rendering.Xps](../../aspose.svg.rendering.xps/)
* asamblea [Aspose.SVG](../../)



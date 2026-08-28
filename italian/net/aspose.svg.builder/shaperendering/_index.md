---
title: "Enum ShapeRendering"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Enum Aspose.Svg.Builder.ShapeRendering. Specifica la modalità di rendering delle forme per gli elementi SVG."
type: docs
weight: 1720
url: /it/net/aspose.svg.builder/shaperendering/
---
## ShapeRendering enumeration

Specifica la modalità di rendering della forma per gli elementi SVG.

```csharp
public enum ShapeRendering
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | `0` | Il browser fa compromessi tra velocità, fluidità e precisione geometrica durante il rendering delle forme. |
| OptimizeSpeed | `1` | Il browser enfatizza la velocità di rendering rispetto alla precisione geometrica e alla fluidità. Questa modalità può portare a un rendering più veloce ma a forme meno accurate. |
| CrispEdges | `2` | Il browser tenta di preservare bordi e angoli netti. Questa modalità è utile per il rendering di grafica con linee e spigoli rettilinei. |
| GeometricPrecision | `3` | Il browser enfatizza la precisione geometrica nel rendering a scapito della velocità. Questa modalità è adatta per rendering di alta qualità dove la geometria precisa è importante. |

### Vedi anche

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

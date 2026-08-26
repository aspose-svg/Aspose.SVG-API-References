---
title: "SVGBuilderExtensions.MarkerEnd"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions MarkerEnd-Methode. Setzt das marker-end-Attribut für ein SVG-Element, das den Marker am Ende eines Pfades angibt."
type: docs
weight: 1120
url: /de/net/aspose.svg.builder/svgbuilderextensions/markerend/
---
## MarkerEnd<TBuilder>(*this TBuilder, string*) {#markerend_1}

Setzt das Attribut 'marker-end' für ein SVG-Element und gibt den Marker am Ende eines Pfads an.

```csharp
public static TBuilder MarkerEnd<TBuilder>(this TBuilder builder, string markerId)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| markerId | Die ID des zu verwendenden Markers. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## MarkerEnd<TBuilder>(*this TBuilder, [MarkerPos](../../markerpos/)*) {#markerend}

Setzt das Attribut 'marker-end' für ein SVG-Element unter Verwendung einer vordefinierten Markerposition.

```csharp
public static TBuilder MarkerEnd<TBuilder>(this TBuilder builder, MarkerPos value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Der zu setzende Positionswert des Markers. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [MarkerPos](../../markerpos/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---
title: "SVGBuilderExtensions.Filter"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions Filter-Methode. Setzt das filter-Attribut für ein SVG-Element mithilfe einer benutzerdefinierten Konfiguration"
type: docs
weight: 840
url: /de/net/aspose.svg.builder/svgbuilderextensions/filter/
---
## SVGBuilderExtensions.Filter<TBuilder> method

Setzt das Attribut 'filter' für ein SVG-Element mit einer benutzerdefinierten Konfiguration.

```csharp
public static TBuilder Filter<TBuilder>(this TBuilder builder, 
    Action<FilterValueListBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Ein Delegat, um den FilterValueListBuilder zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [FilterValueListBuilder](../../filtervaluelistbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---
title: "SVGBuilderExtensions.LightingColor"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions LightingColor. Imposta l'attributo lighting-color per un elemento SVG utilizzando un valore di colore specificato"
type: docs
weight: 1110
url: /it/net/aspose.svg.builder/svgbuilderextensions/lightingcolor/
---
## LightingColor<TBuilder>(*this TBuilder, Color*) {#lightingcolor_1}

Imposta l'attributo 'lighting-color' per un elemento SVG utilizzando un valore di colore specificato.

```csharp
public static TBuilder LightingColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| colorValue | Il valore di colore da impostare per l'effetto di illuminazione. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## LightingColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#lightingcolor}

Imposta l'attributo 'lighting-color' per un elemento SVG usando una configurazione colore personalizzata.

```csharp
public static TBuilder LightingColor<TBuilder>(this TBuilder builder, 
    Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | Un delegato per configurare il colore. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

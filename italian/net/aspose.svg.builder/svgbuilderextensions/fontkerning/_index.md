---
title: "SVGBuilderExtensions.FontKerning"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions FontKerning. Imposta l'attributo font-kerning per un elemento SVG usando un valore numerico e un tipo di lunghezza specifico."
type: docs
weight: 880
url: /it/net/aspose.svg.builder/svgbuilderextensions/fontkerning/
---
## FontKerning<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontkerning_1}

Imposta l'attributo 'font-kerning' per un elemento SVG utilizzando un valore numerico e un tipo di lunghezza specifico.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| value | Il valore di kerning del carattere da impostare. |
| tipo | Il tipo di lunghezza (ad es., px, em). |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## FontKerning<TBuilder>(*this TBuilder, [Kerning](../../kerning/)*) {#fontkerning}

Imposta l'attributo 'font-kerning' per un elemento SVG utilizzando un valore di kerning predefinito.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, Kerning value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| value | Il valore di kerning predefinito da impostare. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [Kerning](../../kerning/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

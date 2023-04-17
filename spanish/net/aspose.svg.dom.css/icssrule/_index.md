---
title: Interface ICSSRule
second_title: Referencia de API de Aspose.SVG para .NET
description: Aspose.Svg.Dom.Css.ICSSRule interfaz. La interfaz CSSRule es la interfaz base abstracta para cualquier tipo de declaración CSS. Esto incluye conjuntos de reglas y reglas at. Se espera que una implementación conserve todas las reglas especificadas en una hoja de estilo CSS incluso si el analizador no reconoce la regla. Las reglas no reconocidas se representan mediante elICSSUnknownRule interfaz.
type: docs
weight: 620
url: /es/net/aspose.svg.dom.css/icssrule/
---
## ICSSRule interface

La interfaz CSSRule es la interfaz base abstracta para cualquier tipo de declaración CSS. Esto incluye conjuntos de reglas y reglas at. Se espera que una implementación conserve todas las reglas especificadas en una hoja de estilo CSS, incluso si el analizador no reconoce la regla. Las reglas no reconocidas se representan mediante el!:ICSSUnknownRule interfaz.

```csharp
public interface ICSSRule
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssrule/csstext/) { get; set; } | La representación textual analizable de la regla. Esto refleja el estado actual de la regla y no su valor inicial. |
| [ParentRule](../../aspose.svg.dom.css/icssrule/parentrule/) { get; } | Si esta regla está contenida dentro de otra regla (por ejemplo, una regla de estilo dentro de un bloque @media), esta es la regla contenedora. Si esta regla no está anidada dentro de ninguna otra regla, devuelve null. |
| [ParentStyleSheet](../../aspose.svg.dom.css/icssrule/parentstylesheet/) { get; } | La hoja de estilo que contiene esta regla. |
| [Type](../../aspose.svg.dom.css/icssrule/type/) { get; } | El tipo de la regla, como se define arriba. La expectativa es que los métodos de conversión específicos de enlace se puedan usar para convertir una instancia de la interfaz CSSRule a la interfaz derivada específica implícita en el tipo. |

### Ver también

* espacio de nombres [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* asamblea [Aspose.SVG](../../)



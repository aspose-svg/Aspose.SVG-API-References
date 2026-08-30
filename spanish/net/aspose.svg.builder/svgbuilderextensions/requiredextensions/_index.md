---
title: "SVGBuilderExtensions.RequiredExtensions"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions RequiredExtensions. Establece el atributo requiredExtensions en el elemento SVG. Este atributo especifica qué extensiones son necesarias para que el fragmento de documento SVG sea procesado"
type: docs
weight: 1970
url: /es/net/aspose.svg.builder/svgbuilderextensions/requiredextensions/
---
## SVGBuilderExtensions.RequiredExtensions<TBuilder> method

Establece el atributo 'requiredExtensions' en el elemento SVG. Este atributo especifica qué extensiones son necesarias para que el fragmento del documento SVG sea procesado.

```csharp
public static TBuilder RequiredExtensions<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IConditionalProcessingAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El generador de elementos SVG en el que se establece el atributo. |
| value | Un valor de cadena que representa las extensiones requeridas. |

### Valor de retorno

El generador de elementos SVG original para encadenamiento de métodos.

### Ver también

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../../iconditionalprocessingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

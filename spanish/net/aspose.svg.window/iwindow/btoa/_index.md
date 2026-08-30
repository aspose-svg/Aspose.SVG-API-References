---
title: "IWindow.Btoa"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Propiedad Btoa de IWindow. Toma los datos de entrada en forma de una cadena Unicode que contiene solo caracteres en el rango U+0000 a U+00FF, cada uno representando un byte binario con valores 0x00 a 0xFF respectivamente, y los convierte a su representación base64, la cual devuelve."
type: docs
weight: 130
url: /es/net/aspose.svg.window/iwindow/btoa/
---
## IWindow.Btoa method

Toma los datos de entrada, en forma de una cadena Unicode que contiene solo caracteres en el rango U+0000 a U+00FF, cada uno representando un byte binario con valores 0x00 a 0xFF respectivamente, y los convierte a su representación base64, la cual devuelve.

```csharp
public string Btoa(string data)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | String | La cadena Unicode que contiene solo caracteres en el rango U+0000 a U+00FF. |

### Valor de retorno

La cadena base64.

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Lanza una excepción DOMException "InvalidCharacterError" si la cadena de entrada contiene caracteres fuera de rango. |

### Ver también

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)

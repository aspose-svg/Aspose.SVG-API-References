---
title: "IWindow.Atob"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método IWindow Atob. Toma los datos de entrada en forma de una cadena Unicode que contiene datos binarios codificados en base64, los decodifica y devuelve una cadena compuesta por caracteres en el rango U0000 a U00FF, cada uno representando un byte binario con valores 0x00 a 0xFF respectivamente, correspondientes a esos datos binarios."
type: docs
weight: 120
url: /es/net/aspose.svg.window/iwindow/atob/
---
## IWindow.Atob method

Toma los datos de entrada, en forma de una cadena Unicode que contiene datos binarios codificados en base64, los decodifica y devuelve una cadena compuesta por caracteres en el rango U+0000 a U+00FF, cada uno representando un byte binario con valores 0x00 a 0xFF respectivamente, correspondientes a esos datos binarios.

```csharp
public string Atob(string data)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | String | La cadena Unicode que contiene datos binarios codificados en base64. |

### Valor de retorno

La cadena compuesta por caracteres en el rango U+0000 a U+00FF.

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Lanza una excepción DOMException "InvalidCharacterError" si la cadena de entrada no es un dato base64 válido. |

### Ver también

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)

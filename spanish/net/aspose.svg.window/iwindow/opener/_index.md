---
title: IWindow.Opener
second_title: Referencia de API de Aspose.SVG para .NET
description: IWindow propiedad. El atributo IDL de apertura en el objeto Ventana al obtenerlo debe devolver el objeto WindowProxy del contexto de exploración a partir del cual se creó el contexto de exploración actual su contexto de exploración de apertura si lo hay si todavía está disponible y si el contexto de navegación actual no ha repudiado a su abridor de lo contrario debe devolver nulo. En la configuración si el nuevo valor es nulo el contexto de navegación actual debe rechazar su abridor si el nuevo valor es cualquier otra cosa entonces el agente de usuario debe llamar al método interno DefineOwnProperty del objeto Ventana pasando el nombre de propiedad abridor como clave de propiedad y el Descriptor de propiedad  Valor valor  Writable true Enumerable true Configurable true  como descriptor de propiedad donde value es el nuevo valor.
type: docs
weight: 50
url: /es/net/aspose.svg.window/iwindow/opener/
---
## IWindow.Opener property

El atributo IDL de apertura en el objeto Ventana, al obtenerlo, debe devolver el objeto WindowProxy del contexto de exploración a partir del cual se creó el contexto de exploración actual (su contexto de exploración de apertura), si lo hay, si todavía está disponible y si el contexto de navegación actual no ha repudiado a su abridor; de lo contrario, debe devolver nulo. En la configuración, si el nuevo valor es nulo, el contexto de navegación actual debe rechazar su abridor; si el nuevo valor es cualquier otra cosa, entonces el agente de usuario debe llamar al método interno [[DefineOwnProperty]] del objeto Ventana, pasando el nombre de propiedad "abridor" como clave de propiedad, y el Descriptor de propiedad { [[Valor]]: valor , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } como descriptor de propiedad, donde value es el nuevo valor.

```csharp
public IWindow Opener { get; }
```

### El valor de la propiedad

El abridor.

### Ver también

* interface [IWindow](../)
* espacio de nombres [Aspose.Svg.Window](../../iwindow/)
* asamblea [Aspose.SVG](../../../)



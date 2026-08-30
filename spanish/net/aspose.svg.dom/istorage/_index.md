---
title: "Interfaz IStorage"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Interfaz Aspose.Svg.Dom.IStorage. Esta interfaz de la API Web Storage proporciona acceso a la sesión o almacenamiento local de un dominio particular. Ver la especificación Web Storage https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs
weight: 3090
url: /es/net/aspose.svg.dom/istorage/
---
## IStorage interface

Esta interfaz de la API Web Storage proporciona acceso a la sesión o almacenamiento local de un dominio particular. Ver la especificación Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```csharp
public interface IStorage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Length](../../aspose.svg.dom/istorage/length/) { get; } | Devuelve el número de pares clave/valor. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clear](../../aspose.svg.dom/istorage/clear/)() | Elimina todos los pares clave/valor, si existen. |
| [GetItem](../../aspose.svg.dom/istorage/getitem/)(*string*) | Devuelve el valor actual asociado a la clave dada, o null si la clave dada no existe. |
| [Key](../../aspose.svg.dom/istorage/key/)(*long*) | Devuelve el nombre de la n‑ésima clave, o null si n es mayor o igual que el número de pares clave/valor. |
| [RemoveItem](../../aspose.svg.dom/istorage/removeitem/)(*string*) | Elimina el par clave/valor con la clave dada, si existe un par clave/valor con esa clave. |
| [SetItem](../../aspose.svg.dom/istorage/setitem/)(*string, string*) | Establece el valor del par identificado por la clave a value, creando un nuevo par clave/valor si previamente no existía ninguno para esa clave. |

### Ver también

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

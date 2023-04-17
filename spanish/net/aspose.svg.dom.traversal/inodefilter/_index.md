---
title: Interface INodeFilter
second_title: Referencia de API de Aspose.SVG para .NET
description: Aspose.Svg.Dom.Traversal.INodeFilter interfaz. Los filtros son objetos que saben cómo filtrar los nodos. Si un NodeIterator o TreeWalker recibe un NodeFilter aplica el filtro antes de devolver el siguiente nodo . Si el filtro dice que acepte el nodo la lógica transversal lo devuelve  de lo contrario el cruce busca el siguiente nodo y finge que el nodo que fue rechazado no estaba allí.
type: docs
weight: 1240
url: /es/net/aspose.svg.dom.traversal/inodefilter/
---
## INodeFilter interface

Los filtros son objetos que saben cómo "filtrar" los nodos. Si un NodeIterator o TreeWalker recibe un NodeFilter, aplica el filtro antes de devolver el siguiente nodo . Si el filtro dice que acepte el nodo, la lógica transversal lo devuelve ; de lo contrario, el cruce busca el siguiente nodo y finge que el nodo que fue rechazado no estaba allí.

El DOM no proporciona ningún filtro. NodeFilter es solo una interfaz que los usuarios pueden implementar para proporcionar sus propios filtros.

NodeFilters no necesita saber cómo atravesar del nodo al nodo, ni necesitan saber nada sobre la estructura de datos que se está recorriendo . Esto hace que sea muy fácil escribir filtros, ya que lo único que tienen que saber hacer es evaluar un solo nodo. Se puede usar un filtro con varios tipos diferentes de recorridos, fomentando la reutilización del código.

Véase también el[Modelo de objeto de documento (DOM) Nivel 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @desde DOM Nivel 2

```csharp
public interface INodeFilter
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AcceptNode](../../aspose.svg.dom.traversal/inodefilter/acceptnode/)(Node) | Prueba si un nodo específico está visible en la vista lógica de un TreeWalker o NodeIterator. Esta función será llamada por la implementación de TreeWalker y NodeIterator; normalmente no se llama directamente desde el código de usuario . (Aunque podría hacerlo si quisiera usar el mismo filtro para guiar su propia lógica de aplicación). |

### Ver también

* espacio de nombres [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* asamblea [Aspose.SVG](../../)



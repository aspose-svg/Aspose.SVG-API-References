---
title: Interface INodeIterator
second_title: Referencia de API de Aspose.SVG para .NET
description: Aspose.Svg.Dom.Traversal.INodeIterator interfaz. Los iteradores se utilizan para recorrer un conjunto de nodos por ejemplo el conjunto de nodos en una lista de nodos el subárbol de documentos gobernado por un nodo particular los resultados de una consulta o cualquier otro conjunto de nodos. El conjunto de nodos a iterar está determinado por la implementación del NodeIterator. El nivel 2 de DOM especifica una implementación única de NodeIterator para el recorrido de orden de documentos de un subárbol de documentos. Las instancias de estos iteradores se crean llamando a DocumentTraversal .createNodeIterator.
type: docs
weight: 1250
url: /es/net/aspose.svg.dom.traversal/inodeiterator/
---
## INodeIterator interface

Los iteradores se utilizan para recorrer un conjunto de nodos, por ejemplo, el conjunto de nodos en una lista de nodos, el subárbol de documentos gobernado por un nodo particular, los resultados de una consulta o cualquier otro conjunto de nodos. El conjunto de nodos a iterar está determinado por la implementación del NodeIterator. El nivel 2 de DOM especifica una implementación única de NodeIterator para el recorrido de orden de documentos de un subárbol de documentos. Las instancias de estos iteradores se crean llamando a DocumentTraversal .createNodeIterator().

Véase también el[Modelo de objeto de documento (DOM) Nivel 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @desde DOM Nivel 2

```csharp
public interface INodeIterator : ITraversal
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | El valor de esta marca determina si los hijos de los nodos de referencia de entidad son visibles para el iterador. Si es falso, ellos y sus descendientes serán rechazados. Tenga en cuenta que este rechazo tiene prioridad sobre whatToShow y el filtro. También tenga en cuenta que esta es actualmente la única situación en la que NodeIterators puede rechazar un subárbol completo en lugar de omitir nodos individuales. Para producir una vista del documento que tiene referencias de entidad expandidas y no expone el nodo de referencia de entidad en sí, use las banderas whatToShow para oculte la referencia a la entidad node y establezca expandEntityReferences en verdadero al crear el iterador . Para producir una vista del documento que tiene nodos de referencia de entidad pero sin expansión de entidad, use whatToShow flags para mostrar el nodo de referencia de entidad y establezca expandEntityReferences en falso. |
| [ReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/referencenode/) { get; } | El nodo de referencia actual. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Detach](../../aspose.svg.dom.traversal/inodeiterator/detach/)() | Separa el NodeIterator del conjunto sobre el que iteró , liberando cualquier recurso computacional y colocando el iterator en el estado NO VÁLIDO. Después de invocar la desconexión, las llamadas a nextNode o previousNode generarán la excepción INVALID_STATE_ERR. |
| [NextNode](../../aspose.svg.dom.traversal/inodeiterator/nextnode/)() | Devuelve el siguiente nodo del conjunto y avanza la posición del iterador en el conjunto. Después de crear un NodeIterator, la primera llamada a nextNode() devuelve el primer nodo en el conjunto. |
| [PreviousNode](../../aspose.svg.dom.traversal/inodeiterator/previousnode/)() | Devuelve el nodo anterior en el conjunto y mueve la posición del iterador de nodo hacia atrás en el conjunto. |

### Ver también

* interface [ITraversal](../itraversal/)
* espacio de nombres [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* asamblea [Aspose.SVG](../../)



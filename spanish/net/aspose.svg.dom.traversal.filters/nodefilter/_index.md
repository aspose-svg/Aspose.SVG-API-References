---
title: Class NodeFilter
second_title: Referencia de API de Aspose.SVG para .NET
description: Aspose.Svg.Dom.Traversal.Filters.NodeFilter clase. Los filtros son objetos que saben filtrar los nodos.
type: docs
weight: 1210
url: /es/net/aspose.svg.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Los filtros son objetos que saben "filtrar" los nodos.

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [AcceptNode](../../aspose.svg.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Prueba si un nodo especificado está visible en la vista lógica de a TreeWalker o NodeIterator. Esta función será llamada por la implementación de TreeWalker y NodeIterator; normalmente no se llama directamente desde código de usuario. (Aunque podría hacerlo si quisiera usar el mismo filtro para guiar su propia lógica de aplicación). |
| override [GetPlatformType](../../aspose.svg.dom.traversal.filters/nodefilter/getplatformtype/)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_accept/) | Aceptar el nodo. Los métodos de navegación definidos para NodeIterator o TreeWalker devolverán este node. |
| const [FILTER_REJECT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_reject/) | Rechazar el nodo. Los métodos de navegación definidos para NodeIterator o TreeWalker no devolverán este nodo. Para TreeWalker, los hijos de este nodo también serán rechazados. NodeIterators trata esto como un sinónimo para FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.svg.dom.traversal.filters/nodefilter/filter_skip/) | Omita este único nodo. Los métodos de navegación definidos para NodeIterator o TreeWalker no devolverán este nodo. Tanto para NodeIterator como para TreeWalker, los elementos secundarios de este nodo seguirán considerándose . |
| const [SHOW_ALL](../../aspose.svg.dom.traversal.filters/nodefilter/show_all/) | Mostrar todos los Nodos. |
| const [SHOW_ATTRIBUTE](../../aspose.svg.dom.traversal.filters/nodefilter/show_attribute/) | Mostrar nodos Attr. Esto es significativo solo cuando se crea un iterador o un caminante de árboles con un nodo de atributo como su raíz ; en este caso, significa que el nodo de atributo aparecerá en la primera posición de la iteración o recorrido. Dado que los atributos nunca son elementos secundarios de otros nodos, no aparecen al atravesar el árbol del documento. |
| const [SHOW_CDATA_SECTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_cdata_section/) | Mostrar nodos CDATASection. |
| const [SHOW_COMMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_comment/) | Mostrar nodos de comentarios. |
| const [SHOW_DOCUMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document/) | Mostrar nodos de documento. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_fragment/) | Mostrar nodos de fragmento de documento. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_type/) | Mostrar nodos DocumentType. |
| const [SHOW_ELEMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_element/) | Mostrar nodos de elemento. |
| const [SHOW_ENTITY](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity/) | Mostrar nodos de entidad. Esto es significativo solo cuando se crea un iterador o un caminante de árboles con un nodo Entity como su raíz ; en este caso, significa que el nodo Entity aparecerá en la primera posición del recorrido. Dado que las entidades no forman parte del árbol del documento, no aparecen cuando atraviesa el árbol del documento. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity_reference/) | Mostrar nodos de referencia de entidad. |
| const [SHOW_NOTATION](../../aspose.svg.dom.traversal.filters/nodefilter/show_notation/) | Mostrar nodos de notación. Esto es significativo solo cuando se crea un iterador o un trepador de árboles con un nodo de Notación como su raíz ; en este caso, significa que el nodo de Notación aparecerá en la primera posición del recorrido . Dado que las anotaciones no forman parte del árbol del documento, no aparecen al desplazarse por el árbol del documento. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_processing_instruction/) | Mostrar nodos ProcessingInstruction. |
| const [SHOW_TEXT](../../aspose.svg.dom.traversal.filters/nodefilter/show_text/) | Mostrar nodos de texto. |

### Ver también

* class [DOMObject](../../aspose.svg.dom/domobject/)
* interface [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)
* espacio de nombres [Aspose.Svg.Dom.Traversal.Filters](../../aspose.svg.dom.traversal.filters/)
* asamblea [Aspose.SVG](../../)



---
title: Node
second_title: Referencia de API de Aspose.SVG para .NET
description: La interfaz de nodo es el tipo de datos principal para todo el modelo de objetos de documento. Representa un solo nodo en el árbol del documento.
type: docs
weight: 1150
url: /es/net/aspose.svg.dom/node/
---
## Node class

La interfaz de nodo es el tipo de datos principal para todo el modelo de objetos de documento. Representa un solo nodo en el árbol del documento.

```csharp
public abstract class Node : EventTarget, IXPathNSResolver
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [Attributes](../../aspose.svg.dom/node/attributes) { get; } | Un NamedNodeMap que contiene los atributos de este nodo (si es un Elemento) o nulo en caso contrario. |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri) { get; } | El URI base absoluto de este nodo o nulo si la implementación no pudo obtener un URI absoluto. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes) { get; } | Una lista de nodos que contiene todos los elementos secundarios de este nodo. Si no hay hijos, esta es una lista de nodos que no contiene nodos.. |
| [FirstChild](../../aspose.svg.dom/node/firstchild) { get; } | El primer hijo de este nodo. Si no existe tal nodo, esto devuelve nulo. |
| [LastChild](../../aspose.svg.dom/node/lastchild) { get; } | El último hijo de este nodo. Si no existe tal nodo, esto devuelve nulo. |
| virtual [LocalName](../../aspose.svg.dom/node/localname) { get; } | Devuelve la parte local del nombre calificado de este nodo. Para los nodos de cualquier tipo que no sean ELEMENT_NODE y ATTRIBUTE_NODE y los nodos creados con un método DOM Nivel 1, como Document.createElement(), esto siempre es nulo. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri) { get; } | El URI del espacio de nombres de este nodo, o nulo si no se especifica. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling) { get; } | El nodo que sigue inmediatamente a este nodo. Si no existe tal nodo, esto devuelve nulo. |
| abstract [NodeName](../../aspose.svg.dom/node/nodename) { get; } | El nombre de este nodo, dependiendo de su tipo. |
| abstract [NodeType](../../aspose.svg.dom/node/nodetype) { get; } | Un código que representa el tipo del objeto subyacente. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue) { get; set; } | El valor de este nodo, según su tipo. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument) { get; } | El objeto Documento asociado con este nodo. Este es también el objeto Documento utilizado para crear nuevos nodos. Cuando este nodo es un Documento o un Tipo de documento que aún no se usa con ningún Documento, es nulo. |
| [ParentElement](../../aspose.svg.dom/node/parentelement) { get; } | Obtiene el padre[`Element`](../element) de este nodo. |
| [ParentNode](../../aspose.svg.dom/node/parentnode) { get; } | El padre de este nodo. Todos los nodos, excepto Attr, Document, DocumentFragment, Entity y Notation pueden tener un padre. Sin embargo, si se acaba de crear un nodo y aún no se ha agregado al árbol, o si se ha eliminado del árbol, este es nulo. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix) { get; set; } | El prefijo del espacio de nombres de este nodo, o nulo si no se especifica. Cuando se define como nulo, configurarlo no tiene efecto |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling) { get; } | El nodo inmediatamente anterior a este nodo. Si no existe tal nodo, esto devuelve nulo. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent) { get; set; } | Este atributo devuelve el contenido de texto de este nodo y sus descendientes. Cuando se define como nulo, establecerlo no tiene ningún efecto. En la configuración, se eliminan todos los posibles elementos secundarios que este nodo pueda tener y, si la nueva cadena no está vacía o es nula, se reemplaza por un solo nodo de texto que contiene la cadena en la que se establece este atributo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, IEventListener) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AppendChild](../../aspose.svg.dom/node/appendchild)(Node) | Agrega el nodo newChild al final de la lista de hijos de este nodo. Si newChild ya está en el árbol, primero se elimina. |
| [CloneNode](../../aspose.svg.dom/node/clonenode#clonenode)() | Devuelve un duplicado de este nodo, es decir, sirve como constructor de copia genérico para nodos. El nodo duplicado no tiene padre (parentNode es nulo) y no tiene datos de usuario. |
| [CloneNode](../../aspose.svg.dom/node/clonenode#clonenode_1)(bool) | Devuelve un duplicado de este nodo, es decir, sirve como constructor de copia genérico para nodos. El nodo duplicado no tiene padre (parentNode es nulo) y no tiene datos de usuario. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent)(Event) | Este método permite el envío de eventos al modelo de eventos de implementaciones. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose)() | Realiza tareas definidas por la aplicación asociadas con liberar, liberar o restablecer recursos no administrados. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| virtual [HasAttributes](../../aspose.svg.dom/node/hasattributes)() | Devuelve si este nodo (si es un elemento) tiene algún atributo |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes)() | Devuelve si este nodo tiene hijos. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore)(Node, Node) | Inserta el nodo antes del nodo secundario existente. Si hijo es nulo, inserte el nodo al final de la lista de hijos. Si hijo es un objeto DocumentFragment, todos sus hijos se insertan, en el mismo orden, antes de hijo. Si el niño ya está en el árbol, primero se elimina. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace)(string) | Este método comprueba si el namespaceURI especificado es el espacio de nombres predeterminado o no. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode)(Node) | Comprueba si dos nodos son iguales. Este método comprueba la igualdad de los nodos, no la uniformidad (es decir, si los dos nodos son referencias al mismo objeto) que se puede probar con Node.isSameNode(). Todos los nodos que son iguales también serán iguales, aunque lo contrario puede no ser cierto. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode)(Node) | Devuelve si este nodo es el mismo nodo que el dado. Este método proporciona una forma de determinar si dos referencias de nodo devueltas por la implementación hacen referencia al mismo objeto. Cuando dos referencias de Nodo son referencias al mismo objeto, incluso a través de un proxy, las referencias se pueden usar de manera completamente intercambiable, de modo que todos los atributos tengan los mismos valores y llamar al mismo método DOM en cualquiera de las referencias siempre tiene exactamente el mismo efecto. |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri)(string) | Busque el URI del espacio de nombres asociado al prefijo dado, a partir de este nodo. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix)(string) | Busque el prefijo asociado al URI del espacio de nombres dado, a partir de este nodo. Este método ignora las declaraciones de espacios de nombres predeterminados. Consulte Búsqueda de prefijo de espacio de nombres para obtener detalles sobre el algoritmo utilizado por este método. |
| [Normalize](../../aspose.svg.dom/node/normalize)() | Coloca todos los nodos de texto en toda la profundidad del subárbol debajo de este nodo, incluidos los nodos de atributos, en una forma "normal" donde solo la estructura (p. ej., elementos, comentarios, instrucciones de procesamiento, secciones CDATA y referencias a entidades) separa el texto nodos, es decir, no hay nodos de Texto adyacentes ni nodos de Texto vacíos. Esto se puede usar para garantizar que la vista DOM de un documento sea la misma que si se hubiera guardado y vuelto a cargar, y es útil cuando las operaciones (como las búsquedas de XPointer [XPointer]) que dependen de una estructura de árbol de documento en particular deben realizarse. ser usado. Si el parámetro "normalize-characters" del objeto DOMConfiguration adjunto a Node.ownerDocument es verdadero, este método también normalizará por completo los caracteres de Text nodes. |
| [RemoveChild](../../aspose.svg.dom/node/removechild)(Node) | Elimina el nodo hijo indicado por oldChild de la lista de hijos y lo devuelve. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, IEventListener) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) se elimina de un[`EventTarget`](../eventtarget) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) se elimina de un[`EventTarget`](../eventtarget) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) se elimina de un[`EventTarget`](../eventtarget) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild)(Node, Node) | Reemplaza el nodo secundario oldChild con newChild en la lista de elementos secundarios y devuelve el nodo oldChild. Si newChild es un objeto DocumentFragment, oldChild se reemplaza por todos los hijos de DocumentFragment, que se insertan en el mismo orden. Si newChild ya está en el árbol, primero se elimina. |
| override [ToString](../../aspose.svg.dom/node/tostring)() | Devuelve unString que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [ATTRIBUTE_NODE](../../aspose.svg.dom/node/attribute_node) | Un atributo node |
| const [CDATA_SECTION_NODE](../../aspose.svg.dom/node/cdata_section_node) | Una sección cdata node |
| const [COMMENT_NODE](../../aspose.svg.dom/node/comment_node) | Un nodo de comentario |
| const [DOCUMENT_FRAGMENT_NODE](../../aspose.svg.dom/node/document_fragment_node) | Un fragmento de documento node |
| const [DOCUMENT_NODE](../../aspose.svg.dom/node/document_node) | Un nodo de documento |
| const [DOCUMENT_TYPE_NODE](../../aspose.svg.dom/node/document_type_node) | Un tipo de documento node |
| const [ELEMENT_NODE](../../aspose.svg.dom/node/element_node) | Un elemento node |
| const [ENTITY_NODE](../../aspose.svg.dom/node/entity_node) | Un nodo de entidad |
| const [ENTITY_REFERENCE_NODE](../../aspose.svg.dom/node/entity_reference_node) | Un nodo de referencia de entidad |
| const [NOTATION_NODE](../../aspose.svg.dom/node/notation_node) | Un nodo de notación |
| const [PROCESSING_INSTRUCTION_NODE](../../aspose.svg.dom/node/processing_instruction_node) | Una instrucción de procesamiento node |
| const [TEXT_NODE](../../aspose.svg.dom/node/text_node) | Un nodo de texto |

### Ver también

* class [EventTarget](../eventtarget)
* interface [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver)
* espacio de nombres [Aspose.Svg.Dom](../../aspose.svg.dom)
* asamblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->

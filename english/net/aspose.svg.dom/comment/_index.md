---
title: Comment Class
second_title: Aspose.SVG for .NET API Reference
description: Aspose.Svg.Dom.Comment class. Inherits from CharacterData and represents the content of a comment i.e. all the characters between the starting 
type: docs
weight: 2460
url: /net/aspose.svg.dom/comment/
---
## Comment class

Inherits from CharacterData and represents the content of a comment, i.e., all the characters between the starting ''.

```csharp
public class Comment : CharacterData
```

## Properties

| Name | Description |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | The absolute base URI of this node or null if the implementation wasn't able to obtain an absolute URI. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | A NodeList that contains all children of this node. If there are no children, this is a NodeList containing no nodes.. |
| virtual [Data](../../aspose.svg.dom/characterdata/data/) { get; set; } | The character data of the node that implements this interface. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | The first child of this node. If there is no such node, this returns null. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | The last child of this node. If there is no such node, this returns null. |
| [Length](../../aspose.svg.dom/characterdata/length/) { get; } | The number of 16-bit units that are available through data and the substringData method below. This may have the value zero, i.e., CharacterData nodes may be empty. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Returns the local part of the qualified name of this node. For nodes of any type other than ELEMENT_NODE and ATTRIBUTE_NODE and nodes created with a DOM Level 1 method, such as Document.createElement(), this is always null. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | The namespace URI of this node, or null if it is unspecified. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | The node immediately following this node. If there is no such node, this returns null. |
| override [NodeName](../../aspose.svg.dom/comment/nodename/) { get; } | The name of this node, depending on its type. |
| override [NodeType](../../aspose.svg.dom/comment/nodetype/) { get; } | A code representing the type of the underlying object. |
| override [NodeValue](../../aspose.svg.dom/comment/nodevalue/) { get; set; } | The value of this node, depending on its type. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | The Document object associated with this node. This is also the Document object used to create new nodes. When this node is a Document or a DocumentType which is not used with any Document yet, this is null. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Gets the parent [`Element`](../element/) of this node. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | The parent of this node. All nodes, except Attr, Document, DocumentFragment, Entity, and Notation may have a parent. However, if a node has just been created and not yet added to the tree, or if it has been removed from the tree, this is null. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | The node immediately preceding this node. If there is no such node, this returns null. |
| override [TextContent](../../aspose.svg.dom/comment/textcontent/) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | This method allows the registration of event listeners on the event target. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | This method allows the registration of event listeners on the event target. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | This method allows the registration of event listeners on the event target. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | Adds the node newChild to the end of the list of children of this node. If the newChild is already in the tree, it is first removed. |
| virtual [AppendData](../../aspose.svg.dom/characterdata/appenddata/)(*string*) | Append the string to the end of the character data of the node. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| virtual [DeleteData](../../aspose.svg.dom/characterdata/deletedata/)(*int, int*) | Remove a range of 16-bit units from the node. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | This method allows the dispatch of events into the implementations event model. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | This method is used to retrieve ECMAScript object Type. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Returns whether this node has any children. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children. If child is a DocumentFragment object, all of its children are inserted, in the same order, before child. If the child is already in the tree, it is first removed. |
| virtual [InsertData](../../aspose.svg.dom/characterdata/insertdata/)(*int, string*) | Insert a string at the specified 16-bit unit offset. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | This method checks if the specified namespaceURI is the default namespace or not. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | Tests whether two nodes are equal. This method tests for equality of nodes, not sameness (i.e., whether the two nodes are references to the same object) which can be tested with Node.isSameNode(). All nodes that are the same will also be equal, though the reverse may not be true. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | Returns whether this node is the same node as the given one. This method provides a way to determine whether two Node references returned by the implementation reference the same object. When two Node references are references to the same object, even if through a proxy, the references may be used completely interchangeably, such that all attributes have the same values and calling the same DOM method on either reference always has exactly the same effect. |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. See Namespace Prefix Lookup for details on the algorithm used by this method. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | Removes the child node indicated by oldChild from the list of children, and returns it. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) is removed from an [`EventTarget`](../eventtarget/) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) is removed from an [`EventTarget`](../eventtarget/) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) is removed from an [`EventTarget`](../eventtarget/) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a DocumentFragment object, oldChild is replaced by all of the DocumentFragment children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| virtual [ReplaceData](../../aspose.svg.dom/characterdata/replacedata/)(*int, int, string*) | Replace the characters starting at the specified 16-bit unit offset with the specified string. |
| virtual [SubstringData](../../aspose.svg.dom/characterdata/substringdata/)(*int, int*) | Extracts a range of data from the node. |
| override [ToString](../../aspose.svg.dom/characterdata/tostring/)() | Returns a String that represents this instance. |

### See Also

* class [CharacterData](../characterdata/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

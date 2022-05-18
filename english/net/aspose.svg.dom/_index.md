---
title: Aspose.Svg.Dom
second_title: Aspose.SVG for .NET API Reference
description: The Aspose.Svg.Dom Document Object Model namespace provides API that represents and interacts with any HTML XML or SVG documents. The DOM is a document model loaded in the browser and representing the document as a node tree where each node represents part of the document e.g. an element text string or comment.
type: docs
weight: 50
url: /net/aspose.svg.dom/
---
The **Aspose.Svg.Dom (Document Object Model)** namespace provides API that represents and interacts with any HTML, XML or SVG documents. The DOM is a document model loaded in the browser and representing the document as a node tree, where each node represents part of the document (e.g. an element, text string, or comment).

## Classes

| Class | Description |
| --- | --- |
| [Attr](./attr) | The Attr interface represents an attribute in an Element object. Typically the allowable values for the attribute are defined in a schema associated with the document. |
| [CDATASection](./cdatasection) | CDATA sections are used to escape blocks of text containing characters that would otherwise be regarded as markup. |
| [CharacterData](./characterdata) | The CharacterData extends Node with a set of attributes and methods for accessing character data in the DOM. |
| [Comment](./comment) | Inherits from CharacterData and represents the content of a comment, i.e., all the characters between the starting ''. |
| [Document](./document) | The Document represents the entire HTML, XML or SVG document. Conceptually, it is the root of the document tree, and provides the primary access to the document's data. |
| [DocumentFragment](./documentfragment) | DocumentFragment is a "lightweight" or "minimal" Document object. It is very common to want to be able to extract a portion of a document's tree or to create a new fragment of a document. |
| [DocumentType](./documenttype) | The DocumentType provides an interface to the list of entities that are defined for the document |
| [DOMException](./domexception) | The DOMException interface represents an abnormal event (../called an exception) which occurs as a result of calling a method or accessing a property of a web API. This is basically how error conditions are described in web APIs. |
| [DOMObject](./domobject) | The DOMObject type is used to represent an base object for the entire Document Object Model. For Java and ECMAScript, DOMObject is bound to the Object type. |
| [Element](./element) | The Element interface represents an element in an HTML or XML document. |
| [Entity](./entity) | Represents a known entity, either parsed or unparsed, in an XML document. |
| [EntityReference](./entityreference) | EntityReference nodes may be used to represent an entity reference in the tree. |
| [EventTarget](./eventtarget) | The [`EventTarget`](../aspose.svg.dom/eventtarget) interface is implemented by all Nodes in an implementation which supports the DOM Event Model. Therefore, this interface can be obtained by using binding-specific casting methods on an instance of the Node interface. The interface allows registration and removal of Event Listeners on an [`EventTarget`](../aspose.svg.dom/eventtarget) and dispatch of events to that [`IEventTarget`](../aspose.svg.dom.events/ieventtarget). |
| [Node](./node) | The Node interface is the primary datatype for the entire Document object Model. It represents a single node in the document tree. |
| [Notation](./notation) | Represents a notation declared in the DTD. |
| [ProcessingInstruction](./processinginstruction) | The ProcessingInstruction represents a "processing instruction", used in XML as a way to keep processor-specific information in the text of the document. |
| [ShadowRoot](./shadowroot) | ShadowRoot is a root node of shadow tree. |
| [Text](./text) | The Text interface inherits from CharacterData and represents the textual content (../termed character data in XML) of an Element or Attr. |
| [TypeInfo](./typeinfo) | The TypeInfo represents a type referenced from Element or Attr nodes, specified in the schemas associated with the document. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext) | A browsing context is an environment in which [`Document`](../aspose.svg.dom/document) objects are presented to the user. |
| [IChildNode](./ichildnode) | Defines [`IChildNode`](../aspose.svg.dom/ichildnode) interface that should be implemented by [`Node`](../aspose.svg.dom/node) that can have a parent. |
| [IDocumentInit](./idocumentinit) | This interface provides [`Document`](../aspose.svg.dom/document) initialization info. |
| [IDOMImplementation](./idomimplementation) | The DOMImplementation interface provides a number of methods for performing operations that are independent of any particular instance of the document object model. |
| [IElementInit](./ielementinit) | This interface provides [`Element`](../aspose.svg.dom/element) initialization info. |
| [IGlobalEventHandlers](./iglobaleventhandlers) | Represents interface that must be inherited by all element that is supported system event handling |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode) | Defines [`IChildNode`](../aspose.svg.dom/ichildnode) that are not [`DOCUMENT_TYPE_NODE`](../aspose.svg.dom/node/document_type_node). |
| [INonElementParentNode](./inonelementparentnode) | Defines [`IParentNode`](../aspose.svg.dom/iparentnode) that are not Element type. |
| [IParentNode](./iparentnode) | Defines the [`IParentNode`](../aspose.svg.dom/iparentnode) interface that is implemented by any possible parents. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [ShadowRootMode](./shadowrootmode) | Modes in which ShadowRoot can operate. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->

﻿---
title: SVGDocument class
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 280
url: /python-net/aspose.svg/svgdocument/
is_root: false
---

## SVGDocument class

An `SVGDocument` is the root of the SVG hierarchy and holds the entire content. Besides providing access to the hierarchy, it also provides some convenience methods for accessing certain sets of information from the document.
When an ‘svg’ element is embedded inline as a component of a document from another namespace, such as when an ‘svg’ element is embedded inline within an XHTML document [XHTML], then an SVGDocument object will not exist; instead, the root object in the document object hierarchy will be a Document object of a different type, such as an HTMLDocument object.
However, an SVGDocument object will indeed exist when the root element of the XML document hierarchy is an ‘svg’ element, such as when viewing a stand-alone SVG file(i.e., a file with MIME type "image/svg+xml"). In this case, the SVGDocument object will be the root object of the document object model hierarchy.



**Inheritance:** [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) → 
[`Document`](/svg/python-net/aspose.svg.dom/document) → 
[`Node`](/svg/python-net/aspose.svg.dom/node) → 
[`EventTarget`](/svg/python-net/aspose.svg.dom/eventtarget) → 
[`DOMObject`](/svg/python-net/aspose.svg.dom/domobject)



The SVGDocument type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. |
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#aspose.svg.Configuration) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. |
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#str) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.).
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#aspose.svg.Url) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.).
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#str-aspose.svg.Configuration) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.).
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#aspose.svg.Url-aspose.svg.Configuration) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.).
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#io.RawIOBase-str) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.).
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#io.RawIOBase-str-aspose.svg.Configuration) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.).
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#io.RawIOBase-aspose.svg.Url) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.).
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#io.RawIOBase-aspose.svg.Url-aspose.svg.Configuration) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.).
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#str-str) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.).
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#str-str-aspose.svg.Configuration) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.).
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#str-aspose.svg.Url) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.).
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#str-aspose.svg.Url-aspose.svg.Configuration) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.).
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#aspose.svg.net.RequestMessage) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.).
| [__init__](/svg/python-net/aspose.svg/svgdocument/__init__/#aspose.svg.net.RequestMessage-aspose.svg.Configuration) | Initializes a new instance of the [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.).


### Properties
| Property | Description |
| :- | :- |
| [node_type](/svg/python-net/aspose.svg/svgdocument/node_type) | A code representing the type of the underlying object. |
| [local_name](/svg/python-net/aspose.svg/svgdocument/local_name) | Returns the local part of the qualified name of this node.
| [namespace_uri](/svg/python-net/aspose.svg/svgdocument/namespace_uri) | The namespace URI of this node, or null if it is unspecified. |
| [prefix](/svg/python-net/aspose.svg/svgdocument/prefix) | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [node_name](/svg/python-net/aspose.svg/svgdocument/node_name) | The name of this node, depending on its type. |
| [base_uri](/svg/python-net/aspose.svg/svgdocument/base_uri) | The absolute base URI of this node or null if the implementation wasn't able to obtain an absolute URI. |
| [owner_document](/svg/python-net/aspose.svg/svgdocument/owner_document) | Gets the owner document. |
| [parent_node](/svg/python-net/aspose.svg/svgdocument/parent_node) | The parent of this node. All nodes, except Attr, Document, DocumentFragment, Entity, and Notation may have a parent. However, if a node has just been created and not yet added to the tree, or if it has been removed from the tree, this is null. |
| [parent_element](/svg/python-net/aspose.svg/svgdocument/parent_element) | Gets the parent [`Element`](/svg/python-net/aspose.svg.dom/element) of this node. |
| [child_nodes](/svg/python-net/aspose.svg/svgdocument/child_nodes) | A NodeList that contains all children of this node. If there are no children, this is a NodeList containing no nodes.. |
| [first_child](/svg/python-net/aspose.svg/svgdocument/first_child) | The first child of this node. If there is no such node, this returns null. |
| [last_child](/svg/python-net/aspose.svg/svgdocument/last_child) | The last child of this node. If there is no such node, this returns null. |
| [previous_sibling](/svg/python-net/aspose.svg/svgdocument/previous_sibling) | The node immediately preceding this node. If there is no such node, this returns null. |
| [next_sibling](/svg/python-net/aspose.svg/svgdocument/next_sibling) | The node immediately following this node. If there is no such node, this returns null. |
| [node_value](/svg/python-net/aspose.svg/svgdocument/node_value) | The value of this node, depending on its type. |
| [text_content](/svg/python-net/aspose.svg/svgdocument/text_content) | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [ELEMENT_NODE](/svg/python-net/aspose.svg/svgdocument/element_node) | An element node |
| [ATTRIBUTE_NODE](/svg/python-net/aspose.svg/svgdocument/attribute_node) | An attribute node |
| [TEXT_NODE](/svg/python-net/aspose.svg/svgdocument/text_node) | A text node |
| [CDATA_SECTION_NODE](/svg/python-net/aspose.svg/svgdocument/cdata_section_node) | A cdata section node |
| [ENTITY_REFERENCE_NODE](/svg/python-net/aspose.svg/svgdocument/entity_reference_node) | An entity reference node |
| [ENTITY_NODE](/svg/python-net/aspose.svg/svgdocument/entity_node) | An entity node |
| [PROCESSING_INSTRUCTION_NODE](/svg/python-net/aspose.svg/svgdocument/processing_instruction_node) | A processing instruction node |
| [COMMENT_NODE](/svg/python-net/aspose.svg/svgdocument/comment_node) | A comment node |
| [DOCUMENT_NODE](/svg/python-net/aspose.svg/svgdocument/document_node) | A document node |
| [DOCUMENT_TYPE_NODE](/svg/python-net/aspose.svg/svgdocument/document_type_node) | A document type node |
| [DOCUMENT_FRAGMENT_NODE](/svg/python-net/aspose.svg/svgdocument/document_fragment_node) | A document fragment node |
| [NOTATION_NODE](/svg/python-net/aspose.svg/svgdocument/notation_node) | A notation node |
| [context](/svg/python-net/aspose.svg/svgdocument/context) | Gets the current browsing context. |
| [implementation](/svg/python-net/aspose.svg/svgdocument/implementation) | The DOMImplementation object that handles this document. |
| [location](/svg/python-net/aspose.svg/svgdocument/location) | The location of the document. |
| [document_uri](/svg/python-net/aspose.svg/svgdocument/document_uri) | The location of the document or null if undefined or if the Document was created using DOMImplementation.createDocument. |
| [origin](/svg/python-net/aspose.svg/svgdocument/origin) | Gets the document origin. |
| [character_set](/svg/python-net/aspose.svg/svgdocument/character_set) | Gets the document's encoding. |
| [charset](/svg/python-net/aspose.svg/svgdocument/charset) | Gets the document's encoding. |
| [input_encoding](/svg/python-net/aspose.svg/svgdocument/input_encoding) | Gets the document's encoding. |
| [content_type](/svg/python-net/aspose.svg/svgdocument/content_type) | Gets the document content type. |
| [ready_state](/svg/python-net/aspose.svg/svgdocument/ready_state) | Returns the document readiness. The "loading" while the Document is loading, "interactive" once it is finished parsing but still loading sub-resources, and "complete" once it has loaded. |
| [doctype](/svg/python-net/aspose.svg/svgdocument/doctype) | The Document Type Declaration associated with this document. |
| [document_element](/svg/python-net/aspose.svg/svgdocument/document_element) | This is a convenience attribute that allows direct access to the child node that is the document element of the document. |
| [first_element_child](/svg/python-net/aspose.svg/svgdocument/first_element_child) | Returns the first child element node of this element. null if this element has no child elements. |
| [last_element_child](/svg/python-net/aspose.svg/svgdocument/last_element_child) | Returns the last child element node of this element. null if this element has no child elements. |
| [previous_element_sibling](/svg/python-net/aspose.svg/svgdocument/previous_element_sibling) | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [next_element_sibling](/svg/python-net/aspose.svg/svgdocument/next_element_sibling) | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [child_element_count](/svg/python-net/aspose.svg/svgdocument/child_element_count) | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [children](/svg/python-net/aspose.svg/svgdocument/children) | Returns the child elements. |
| [xml_standalone](/svg/python-net/aspose.svg/svgdocument/xml_standalone) | An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
| [xml_version](/svg/python-net/aspose.svg/svgdocument/xml_version) | An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |
| [strict_error_checking](/svg/python-net/aspose.svg/svgdocument/strict_error_checking) | An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [default_view](/svg/python-net/aspose.svg/svgdocument/default_view) | The defaultView IDL attribute of the Document interface, on getting, 
| [style_sheets](/svg/python-net/aspose.svg/svgdocument/style_sheets) | A list containing all the style sheets explicitly linked into or embedded in a document. For HTML documents, this includes external style sheets, included via the HTML LINK element, and inline STYLE elements. |
| [title](/svg/python-net/aspose.svg/svgdocument/title) | The title of a document as specified by the ‘title’ sub-element of the ‘svg’ root element (i.e., ) |
| [referrer](/svg/python-net/aspose.svg/svgdocument/referrer) | Returns the URI of the page that linked to this page. The value is an empty string if the user navigated to the page directly (not through a link, but, for example, via a bookmark). |
| [domain](/svg/python-net/aspose.svg/svgdocument/domain) | The domain name of the server that served the document, or a null string if the server cannot be identified by a domain name. |
| [url](/svg/python-net/aspose.svg/svgdocument/url) | The complete URI of the document. |
| [root_element](/svg/python-net/aspose.svg/svgdocument/root_element) | The root ‘svg’ in the document hierarchy. |


### Methods
| Method | Description |
| :- | :- |
| [add_event_listener](/svg/python-net/aspose.svg/svgdocument/add_event_listener/#str-aspose.svg.dom.events.IEventListener) | This method allows the registration of event listeners on the event target. |
| [add_event_listener](/svg/python-net/aspose.svg/svgdocument/add_event_listener/#str-aspose.svg.dom.events.IEventListener-bool) | This method allows the registration of event listeners on the event target. |
| [remove_event_listener](/svg/python-net/aspose.svg/svgdocument/remove_event_listener/#str-aspose.svg.dom.events.IEventListener) | This method allows the removal of event listeners from the event target.
| [remove_event_listener](/svg/python-net/aspose.svg/svgdocument/remove_event_listener/#str-aspose.svg.dom.events.IEventListener-bool) | This method allows the removal of event listeners from the event target.
| [clone_node](/svg/python-net/aspose.svg/svgdocument/clone_node/#) | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [clone_node](/svg/python-net/aspose.svg/svgdocument/clone_node/#bool) | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [navigate](/svg/python-net/aspose.svg/svgdocument/navigate/#str) | Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content. |
| [navigate](/svg/python-net/aspose.svg/svgdocument/navigate/#aspose.svg.Url) | Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content. |
| [navigate](/svg/python-net/aspose.svg/svgdocument/navigate/#str-str) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. |
| [navigate](/svg/python-net/aspose.svg/svgdocument/navigate/#str-aspose.svg.Url) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. |
| [navigate](/svg/python-net/aspose.svg/svgdocument/navigate/#io.RawIOBase-str) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content.
| [navigate](/svg/python-net/aspose.svg/svgdocument/navigate/#io.RawIOBase-aspose.svg.Url) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content.
| [navigate](/svg/python-net/aspose.svg/svgdocument/navigate/#aspose.svg.net.RequestMessage) | Loads the document based on specified request object, replacing the previous content. |
| [create_node_iterator](/svg/python-net/aspose.svg/svgdocument/create_node_iterator/#aspose.svg.dom.Node) | Create a new NodeIterator over the subtree rooted at the
| [create_node_iterator](/svg/python-net/aspose.svg/svgdocument/create_node_iterator/#aspose.svg.dom.Node-int) | Create a new NodeIterator over the subtree rooted at the
| [create_node_iterator](/svg/python-net/aspose.svg/svgdocument/create_node_iterator/#aspose.svg.dom.Node-int-aspose.svg.dom.traversal.INodeFilter) | Create a new NodeIterator over the subtree rooted at the
| [create_tree_walker](/svg/python-net/aspose.svg/svgdocument/create_tree_walker/#aspose.svg.dom.Node) | Create a new TreeWalker over the subtree rooted at the
| [create_tree_walker](/svg/python-net/aspose.svg/svgdocument/create_tree_walker/#aspose.svg.dom.Node-int) | Create a new TreeWalker over the subtree rooted at the
| [create_tree_walker](/svg/python-net/aspose.svg/svgdocument/create_tree_walker/#aspose.svg.dom.Node-int-aspose.svg.dom.traversal.INodeFilter) | Create a new TreeWalker over the subtree rooted at the
| [save](/svg/python-net/aspose.svg/svgdocument/save/#aspose.svg.Url) | Saves the document to local file specified by `url`. All resources used in this document will be saved in 
| [save](/svg/python-net/aspose.svg/svgdocument/save/#str) | Saves the document to local file specified by `path`. All resources used in this document will be saved in 
| [save](/svg/python-net/aspose.svg/svgdocument/save/#aspose.svg.saving.resourcehandlers.ResourceHandler) | Saves the document content and resources using the [`ResourceHandler`](/svg/python-net/aspose.svg.saving.resourcehandlers/resourcehandler). |
| [save](/svg/python-net/aspose.svg/svgdocument/save/#aspose.svg.io.IOutputStorage) | Saves the document content and resources to the output storage. |
| [save](/svg/python-net/aspose.svg/svgdocument/save/#str-aspose.svg.saving.SVGSaveFormat) | Saves the document to local file specified by `path`. All resources used in this document will be saved in 
| [save](/svg/python-net/aspose.svg/svgdocument/save/#aspose.svg.saving.resourcehandlers.ResourceHandler-aspose.svg.saving.SVGSaveFormat) | Saves the document content and resources using the [`ResourceHandler`](/svg/python-net/aspose.svg.saving.resourcehandlers/resourcehandler). |
| [save](/svg/python-net/aspose.svg/svgdocument/save/#aspose.svg.io.IOutputStorage-aspose.svg.saving.SVGSaveFormat) | Saves the document content and resources to the output storage. |
| [save](/svg/python-net/aspose.svg/svgdocument/save/#str-aspose.svg.saving.SVGSaveOptions) | Saves the document to local file specified by `path`. All resources used in this document will be saved in 
| [save](/svg/python-net/aspose.svg/svgdocument/save/#aspose.svg.saving.resourcehandlers.ResourceHandler-aspose.svg.saving.SVGSaveOptions) | Saves the document content and resources using the [`ResourceHandler`](/svg/python-net/aspose.svg.saving.resourcehandlers/resourcehandler). |
| [save](/svg/python-net/aspose.svg/svgdocument/save/#aspose.svg.io.IOutputStorage-aspose.svg.saving.SVGSaveOptions) | Saves the document content and resources to the output storage. |
| [save](/svg/python-net/aspose.svg/svgdocument/save/#aspose.svg.Url-aspose.svg.saving.SVGSaveFormat) | Saves the document to local file specified by `url`. All resources used in this document will be saved in 
| [save](/svg/python-net/aspose.svg/svgdocument/save/#aspose.svg.Url-aspose.svg.saving.SVGSaveOptions) | Saves the document to local file specified by `url`. All resources used in this document will be saved in 
| [get_platform_type](/svg/python-net/aspose.svg/svgdocument/get_platform_type/#) | This method is used to retrieve ECMAScript object Type. |
| [dispatch_event](/svg/python-net/aspose.svg/svgdocument/dispatch_event/#aspose.svg.dom.events.Event) | This method allows the dispatch of events into the implementations event model. |
| [has_child_nodes](/svg/python-net/aspose.svg/svgdocument/has_child_nodes/#) | Returns whether this node has any children. |
| [normalize](/svg/python-net/aspose.svg/svgdocument/normalize/#) | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [is_equal_node](/svg/python-net/aspose.svg/svgdocument/is_equal_node/#aspose.svg.dom.Node) | Tests whether two nodes are equal.
| [is_same_node](/svg/python-net/aspose.svg/svgdocument/is_same_node/#aspose.svg.dom.Node) | Returns whether this node is the same node as the given one. 
| [lookup_prefix](/svg/python-net/aspose.svg/svgdocument/lookup_prefix/#str) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. 
| [lookup_namespace_uri](/svg/python-net/aspose.svg/svgdocument/lookup_namespace_uri/#str) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [is_default_namespace](/svg/python-net/aspose.svg/svgdocument/is_default_namespace/#str) | This method checks if the specified namespaceURI is the default namespace or not. |
| [insert_before](/svg/python-net/aspose.svg/svgdocument/insert_before/#aspose.svg.dom.Node-aspose.svg.dom.Node) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children.
| [replace_child](/svg/python-net/aspose.svg/svgdocument/replace_child/#aspose.svg.dom.Node-aspose.svg.dom.Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. 
| [remove_child](/svg/python-net/aspose.svg/svgdocument/remove_child/#aspose.svg.dom.Node) | Removes the child node indicated by oldChild from the list of children, and returns it. |
| [append_child](/svg/python-net/aspose.svg/svgdocument/append_child/#aspose.svg.dom.Node) | Adds the node newChild to the end of the list of children of this node. If the newChild is already in the tree, it is first removed. |
| [create_element](/svg/python-net/aspose.svg/svgdocument/create_element/#str) | Creates an element of the type specified. Note that the instance returned implements the Element interface, so attributes can be specified directly on the returned object. |
| [create_element_ns](/svg/python-net/aspose.svg/svgdocument/create_element_ns/#str-str) | Creates an element of the given qualified name and namespace URI. |
| [create_document_fragment](/svg/python-net/aspose.svg/svgdocument/create_document_fragment/#) | Creates an empty DocumentFragment object. |
| [create_text_node](/svg/python-net/aspose.svg/svgdocument/create_text_node/#str) | Creates a Text node given the specified string. |
| [create_comment](/svg/python-net/aspose.svg/svgdocument/create_comment/#str) | Creates a Comment node given the specified string. |
| [create_cdata_section](/svg/python-net/aspose.svg/svgdocument/create_cdata_section/#str) | Creates a CDATASection node whose value is the specified string. |
| [create_processing_instruction](/svg/python-net/aspose.svg/svgdocument/create_processing_instruction/#str-str) | Creates a ProcessingInstruction node given the specified name and data strings. |
| [create_attribute](/svg/python-net/aspose.svg/svgdocument/create_attribute/#str) | Creates an Attr of the given name. |
| [create_attribute_ns](/svg/python-net/aspose.svg/svgdocument/create_attribute_ns/#str-str) | Creates an attribute of the given qualified name and namespace URI. |
| [create_entity_reference](/svg/python-net/aspose.svg/svgdocument/create_entity_reference/#str) | Creates an EntityReference object. In addition, if the referenced entity is known, the child list of the EntityReference node is made the same as that of the corresponding Entity node. |
| [create_document_type](/svg/python-net/aspose.svg/svgdocument/create_document_type/#str-str-str-str) | Creates a DocumentType node. |
| [get_elements_by_tag_name](/svg/python-net/aspose.svg/svgdocument/get_elements_by_tag_name/#str) | Returns a NodeList of all the Elements in document order with a given tag name and are contained in the document. |
| [get_elements_by_tag_name_ns](/svg/python-net/aspose.svg/svgdocument/get_elements_by_tag_name_ns/#str-str) | Returns a NodeList of all the Elements with a given local name and namespace URI in document order. |
| [get_element_by_id](/svg/python-net/aspose.svg/svgdocument/get_element_by_id/#str) | Returns the Element that has an ID attribute with the given value. If no such element exists, this returns null. If more than one element has an ID attribute with that value, what is returned is undefined. |
| [get_elements_by_class_name](/svg/python-net/aspose.svg/svgdocument/get_elements_by_class_name/#str) | Returns a live NodeList object containing all the elements in the document that have all the classes specified in argument.
| [query_selector_all](/svg/python-net/aspose.svg/svgdocument/query_selector_all/#str) | Returns a NodeList of all the Elements in document, which match selector |
| [query_selector](/svg/python-net/aspose.svg/svgdocument/query_selector/#str) | Returns the first Element in document, which match selector |
| [import_node](/svg/python-net/aspose.svg/svgdocument/import_node/#aspose.svg.dom.Node-bool) | Imports a node from another document to this document, without altering or removing the source node from the original document; this method creates a new copy of the source node. |
| [create_event](/svg/python-net/aspose.svg/svgdocument/create_event/#str) | Creates an [`Event`](/svg/python-net/aspose.svg.dom.events/event) of a type supported by the implementation. |
| [write](/svg/python-net/aspose.svg/svgdocument/write/#list) | Write a string of text to a document stream opened by
| [write_ln](/svg/python-net/aspose.svg/svgdocument/write_ln/#list) | Write a string of text followed by a newline character to a document
| [create_expression](/svg/python-net/aspose.svg/svgdocument/create_expression/#str-aspose.svg.dom.xpath.IXPathNSResolver) | Creates a parsed XPath expression with resolved namespaces. This is useful 
| [create_ns_resolver](/svg/python-net/aspose.svg/svgdocument/create_ns_resolver/#aspose.svg.dom.Node) | Adapts any DOM node to resolve namespaces so that an XPath expression can be easily evaluated
| [evaluate](/svg/python-net/aspose.svg/svgdocument/evaluate/#str-aspose.svg.dom.Node-aspose.svg.dom.xpath.IXPathNSResolver-aspose.svg.dom.xpath.XPathResultType-any) | Evaluates an XPath expression string and returns a result of the specified type if possible. |
| [render_to](/svg/python-net/aspose.svg/svgdocument/render_to/#aspose.svg.rendering.IDevice) | This method is used to print the contents of the current document to the specified device. |
| [get_override_style](/svg/python-net/aspose.svg/svgdocument/get_override_style/#aspose.svg.dom.Element-str) | This method is used to retrieve the override style declaration for a specified element and a specified pseudo-element. |



### See Also
* module [`aspose.svg`](..)
* class [`DOMObject`](/svg/python-net/aspose.svg.dom/domobject)
* class [`Document`](/svg/python-net/aspose.svg.dom/document)
* class [`Element`](/svg/python-net/aspose.svg.dom/element)
* class [`Event`](/svg/python-net/aspose.svg.dom.events/event)
* class [`EventTarget`](/svg/python-net/aspose.svg.dom/eventtarget)
* class [`IEventListener`](/svg/python-net/aspose.svg.dom.events/ieventlistener)
* class [`Node`](/svg/python-net/aspose.svg.dom/node)
* class [`ResourceHandler`](/svg/python-net/aspose.svg.saving.resourcehandlers/resourcehandler)
* class [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument)
﻿---
title: NodeFilter class
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 10
url: /python-net/aspose.svg.dom.traversal.filters/nodefilter/
is_root: false
---

## NodeFilter class

Filters are objects that know how to "filter out" nodes.



**Inheritance:** [`NodeFilter`](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter) → 
[`DOMObject`](/svg/python-net/aspose.svg.dom/domobject)



The NodeFilter type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [FILTER_ACCEPT](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/filter_accept) | Accept the node. Navigation methods defined for <br/>NodeIterator or TreeWalker will return this <br/>node. |
| [FILTER_REJECT](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/filter_reject) | Reject the node. Navigation methods defined for <br/>NodeIterator or TreeWalker will not return <br/>this node. For TreeWalker, the children of this node <br/>will also be rejected. NodeIterators treat this as a <br/>synonym for FILTER_SKIP. |
| [FILTER_SKIP](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/filter_skip) | Skip this single node. Navigation methods defined for <br/>NodeIterator or TreeWalker will not return <br/>this node. For both NodeIterator and <br/>TreeWalker, the children of this node will still be <br/>considered. |
| [SHOW_ALL](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/show_all) | Show all Nodes. |
| [SHOW_ELEMENT](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/show_element) | Show Element nodes. |
| [SHOW_ATTRIBUTE](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/show_attribute) | Show Attr nodes. This is meaningful only when creating an <br/>iterator or tree-walker with an attribute node as its <br/>root; in this case, it means that the attribute node <br/>will appear in the first position of the iteration or traversal. <br/>Since attributes are never children of other nodes, they do not <br/>appear when traversing over the document tree. |
| [SHOW_TEXT](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/show_text) | Show Text nodes. |
| [SHOW_CDATA_SECTION](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/show_cdata_section) | Show CDATASection nodes. |
| [SHOW_ENTITY_REFERENCE](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/show_entity_reference) | Show EntityReference nodes. |
| [SHOW_ENTITY](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/show_entity) | Show Entity nodes. This is meaningful only when creating <br/>an iterator or tree-walker with an Entity node as its <br/>root; in this case, it means that the Entity<br/>node will appear in the first position of the traversal. Since <br/>entities are not part of the document tree, they do not appear when <br/>traversing over the document tree. |
| [SHOW_PROCESSING_INSTRUCTION](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/show_processing_instruction) | Show ProcessingInstruction nodes. |
| [SHOW_COMMENT](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/show_comment) | Show Comment nodes. |
| [SHOW_DOCUMENT](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/show_document) | Show Document nodes. |
| [SHOW_DOCUMENT_TYPE](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/show_document_type) | Show DocumentType nodes. |
| [SHOW_DOCUMENT_FRAGMENT](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/show_document_fragment) | Show DocumentFragment nodes. |
| [SHOW_NOTATION](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/show_notation) | Show Notation nodes. This is meaningful only when creating <br/>an iterator or tree-walker with a Notation node as its <br/>root; in this case, it means that the <br/>Notation node will appear in the first position of the <br/>traversal. Since notations are not part of the document tree, they do <br/>not appear when traversing over the document tree. |


### Methods
| Method | Description |
| :- | :- |
| [get_platform_type](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/get_platform_type/#) | This method is used to retrieve ECMAScript object Type. |
| [accept_node](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter/accept_node/#aspose.svg.dom.Node) | Test whether a specified node is visible in the logical view of a<br/>TreeWalker or NodeIterator. This function<br/>will be called by the implementation of TreeWalker and<br/>NodeIterator; it is not normally called directly from<br/>user code. (Though you could do so if you wanted to use the same<br/>filter to guide your own application logic.) |



### See Also
* module [`aspose.svg.dom.traversal.filters`](..)
* class [`DOMObject`](/svg/python-net/aspose.svg.dom/domobject)
* class [`NodeFilter`](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter)

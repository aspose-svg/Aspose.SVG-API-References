﻿---
title: SVGSVGElement class
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 520
url: /python-net/aspose.svg/svgsvgelement/
is_root: false
---

## SVGSVGElement class

A key interface definition is the SVGSVGElement interface, which is the interface that corresponds to the ‘svg’ element. This interface contains various miscellaneous commonly-used utility methods, such as matrix operations and the ability to control the time of redraw on visual rendering devices.



**Inheritance:** [`SVGSVGElement`](/svg/python-net/aspose.svg/svgsvgelement) → 
[`SVGGraphicsElement`](/svg/python-net/aspose.svg/svggraphicselement) → 
[`SVGElement`](/svg/python-net/aspose.svg/svgelement) → 
[`Element`](/svg/python-net/aspose.svg.dom/element) → 
[`Node`](/svg/python-net/aspose.svg.dom/node) → 
[`EventTarget`](/svg/python-net/aspose.svg.dom/eventtarget) → 
[`DOMObject`](/svg/python-net/aspose.svg.dom/domobject)



The SVGSVGElement type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [node_type](/svg/python-net/aspose.svg/svgsvgelement/node_type) | A code representing the type of the underlying object. |
| [local_name](/svg/python-net/aspose.svg/svgsvgelement/local_name) | Returns the local part of the qualified name of this node.<br/>For nodes of any type other than ELEMENT_NODE and ATTRIBUTE_NODE and nodes created with a DOM Level 1 method, such as Document.createElement(), this is always null. |
| [namespace_uri](/svg/python-net/aspose.svg/svgsvgelement/namespace_uri) | The namespace URI of this node, or null if it is unspecified. |
| [prefix](/svg/python-net/aspose.svg/svgsvgelement/prefix) | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [node_name](/svg/python-net/aspose.svg/svgsvgelement/node_name) | The name of this node, depending on its type. |
| [base_uri](/svg/python-net/aspose.svg/svgsvgelement/base_uri) | The absolute base URI of this node or null if the implementation wasn't able to obtain an absolute URI. |
| [owner_document](/svg/python-net/aspose.svg/svgsvgelement/owner_document) | The Document object associated with this node. This is also the Document object used to create new nodes. When this node is a Document or a DocumentType which is not used with any Document yet, this is null. |
| [parent_node](/svg/python-net/aspose.svg/svgsvgelement/parent_node) | The parent of this node. All nodes, except Attr, Document, DocumentFragment, Entity, and Notation may have a parent. However, if a node has just been created and not yet added to the tree, or if it has been removed from the tree, this is null. |
| [parent_element](/svg/python-net/aspose.svg/svgsvgelement/parent_element) | Gets the parent [`Element`](/svg/python-net/aspose.svg.dom/element) of this node. |
| [child_nodes](/svg/python-net/aspose.svg/svgsvgelement/child_nodes) | A NodeList that contains all children of this node. If there are no children, this is a NodeList containing no nodes.. |
| [first_child](/svg/python-net/aspose.svg/svgsvgelement/first_child) | The first child of this node. If there is no such node, this returns null. |
| [last_child](/svg/python-net/aspose.svg/svgsvgelement/last_child) | The last child of this node. If there is no such node, this returns null. |
| [previous_sibling](/svg/python-net/aspose.svg/svgsvgelement/previous_sibling) | The node immediately preceding this node. If there is no such node, this returns null. |
| [next_sibling](/svg/python-net/aspose.svg/svgsvgelement/next_sibling) | The node immediately following this node. If there is no such node, this returns null. |
| [node_value](/svg/python-net/aspose.svg/svgsvgelement/node_value) | The value of this node, depending on its type. |
| [text_content](/svg/python-net/aspose.svg/svgsvgelement/text_content) | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [ELEMENT_NODE](/svg/python-net/aspose.svg/svgsvgelement/element_node) | An element node |
| [ATTRIBUTE_NODE](/svg/python-net/aspose.svg/svgsvgelement/attribute_node) | An attribute node |
| [TEXT_NODE](/svg/python-net/aspose.svg/svgsvgelement/text_node) | A text node |
| [CDATA_SECTION_NODE](/svg/python-net/aspose.svg/svgsvgelement/cdata_section_node) | A cdata section node |
| [ENTITY_REFERENCE_NODE](/svg/python-net/aspose.svg/svgsvgelement/entity_reference_node) | An entity reference node |
| [ENTITY_NODE](/svg/python-net/aspose.svg/svgsvgelement/entity_node) | An entity node |
| [PROCESSING_INSTRUCTION_NODE](/svg/python-net/aspose.svg/svgsvgelement/processing_instruction_node) | A processing instruction node |
| [COMMENT_NODE](/svg/python-net/aspose.svg/svgsvgelement/comment_node) | A comment node |
| [DOCUMENT_NODE](/svg/python-net/aspose.svg/svgsvgelement/document_node) | A document node |
| [DOCUMENT_TYPE_NODE](/svg/python-net/aspose.svg/svgsvgelement/document_type_node) | A document type node |
| [DOCUMENT_FRAGMENT_NODE](/svg/python-net/aspose.svg/svgsvgelement/document_fragment_node) | A document fragment node |
| [NOTATION_NODE](/svg/python-net/aspose.svg/svgsvgelement/notation_node) | A notation node |
| [tag_name](/svg/python-net/aspose.svg/svgsvgelement/tag_name) | The name of the element. |
| [id](/svg/python-net/aspose.svg/svgsvgelement/id) | The value of the ‘id’ attribute on the given element, or the empty string if ‘id’ is not present. |
| [class_name](/svg/python-net/aspose.svg/svgsvgelement/class_name) | Corresponds to attribute ‘class’ on the given element. |
| [attributes](/svg/python-net/aspose.svg/svgsvgelement/attributes) | A NamedNodeMap containing the attributes of this node (if it is an Element) or null otherwise. |
| [first_element_child](/svg/python-net/aspose.svg/svgsvgelement/first_element_child) | Returns the first child element node of this element. null if this element has no child elements. |
| [last_element_child](/svg/python-net/aspose.svg/svgsvgelement/last_element_child) | Returns the last child element node of this element. null if this element has no child elements. |
| [previous_element_sibling](/svg/python-net/aspose.svg/svgsvgelement/previous_element_sibling) | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [next_element_sibling](/svg/python-net/aspose.svg/svgsvgelement/next_element_sibling) | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [child_element_count](/svg/python-net/aspose.svg/svgsvgelement/child_element_count) | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [children](/svg/python-net/aspose.svg/svgsvgelement/children) | Returns the child elements of current element. |
| [inner_html](/svg/python-net/aspose.svg/svgsvgelement/inner_html) | Returns a fragment of HTML or XML that represents the element's contents.<br/>Can be set, to replace the contents of the element with nodes parsed from the given string. |
| [outer_html](/svg/python-net/aspose.svg/svgsvgelement/outer_html) | Returns a fragment of HTML or XML that represents the element and its contents.<br/>Can be set, to replace the element with nodes parsed from the given string. |
| [shadow_root](/svg/python-net/aspose.svg/svgsvgelement/shadow_root) | Returns shadowRoot stored on this element or null if it's closed. |
| [owner_svg_element](/svg/python-net/aspose.svg/svgsvgelement/owner_svg_element) | The nearest ancestor ‘svg’ element. Null if the given element is the outermost svg element. |
| [viewport_element](/svg/python-net/aspose.svg/svgsvgelement/viewport_element) | The element which established the current viewport. Often, the nearest ancestor ‘svg’ element. Null if the given element is the outermost svg element. |
| [style](/svg/python-net/aspose.svg/svgsvgelement/style) | Corresponds to attribute ‘style’ on the given element. If the user agent does not support styling with CSS, then this attribute must always have the value of null. |
| [nearest_viewport_element](/svg/python-net/aspose.svg/svgsvgelement/nearest_viewport_element) | The element which established the current viewport. Often, the nearest ancestor ‘svg’ element. Null if the current element is the outermost svg element. |
| [farthest_viewport_element](/svg/python-net/aspose.svg/svgsvgelement/farthest_viewport_element) | The farthest ancestor ‘svg’ element. Null if the current element is the outermost svg element. |
| [transform](/svg/python-net/aspose.svg/svgsvgelement/transform) | Corresponds to attribute ‘transform’ on the given element. |
| [required_features](/svg/python-net/aspose.svg/svgsvgelement/required_features) | Corresponds to attribute ‘requiredFeatures’ on the given element. |
| [required_extensions](/svg/python-net/aspose.svg/svgsvgelement/required_extensions) | Corresponds to attribute ‘requiredExtensions’ on the given element. |
| [system_language](/svg/python-net/aspose.svg/svgsvgelement/system_language) | Corresponds to attribute ‘systemLanguage’ on the given element. |
| [x](/svg/python-net/aspose.svg/svgsvgelement/x) | Corresponds to attribute ‘x’ on the given ‘svg’ element. |
| [y](/svg/python-net/aspose.svg/svgsvgelement/y) | Corresponds to attribute ‘y’ on the given ‘svg’ element. |
| [width](/svg/python-net/aspose.svg/svgsvgelement/width) | Corresponds to attribute ‘width’ on the given ‘svg’ element. |
| [height](/svg/python-net/aspose.svg/svgsvgelement/height) | Corresponds to attribute ‘height’ on the given ‘svg’ element. |
| [current_scale](/svg/python-net/aspose.svg/svgsvgelement/current_scale) | On an outermost svg element, this attribute indicates the current scale factor relative to the initial view to take into account user magnification and panning operations, as described under Magnification and panning. DOM attributes currentScale and currentTranslate are equivalent to the 2x3 matrix [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. If "magnification" is enabled (i.e., zoomAndPan="magnify"), then the effect is as if an extra transformation were placed at the outermost level on the SVG document fragment (i.e., outside the outermost svg element).<br/>When accessed on an ‘svg’ element that is not an outermost svg element, it is undefined what behavior this attribute has. |
| [current_translate](/svg/python-net/aspose.svg/svgsvgelement/current_translate) | On an outermost svg element, the corresponding translation factor that takes into account user "magnification".<br/>When accessed on an ‘svg’ element that is not an outermost svg element, it is undefined what behavior this attribute has. |
| [view_box](/svg/python-net/aspose.svg/svgsvgelement/view_box) | Corresponds to attribute ‘viewBox’ on the given element. |
| [preserve_aspect_ratio](/svg/python-net/aspose.svg/svgsvgelement/preserve_aspect_ratio) | Corresponds to attribute ‘preserveAspectRatio’ on the given element. |
| [zoom_and_pan](/svg/python-net/aspose.svg/svgsvgelement/zoom_and_pan) | Corresponds to attribute ‘zoomAndPan’ on the given element. The value must be one of the SVG_ZOOMANDPAN_* constants defined on this interface. |


### Methods
| Method | Description |
| :- | :- |
| [add_event_listener](/svg/python-net/aspose.svg/svgsvgelement/add_event_listener/#str-aspose.svg.dom.events.IEventListener) | This method allows the registration of event listeners on the event target. |
| [add_event_listener](/svg/python-net/aspose.svg/svgsvgelement/add_event_listener/#str-aspose.svg.dom.events.IEventListener-bool) | This method allows the registration of event listeners on the event target. |
| [remove_event_listener](/svg/python-net/aspose.svg/svgsvgelement/remove_event_listener/#str-aspose.svg.dom.events.IEventListener) | This method allows the removal of event listeners from the event target.<br/>If an [`IEventListener`](/svg/python-net/aspose.svg.dom.events/ieventlistener) is removed from an [`EventTarget`](/svg/python-net/aspose.svg.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.<br/>Event Listeners can never be invoked after being removed. |
| [remove_event_listener](/svg/python-net/aspose.svg/svgsvgelement/remove_event_listener/#str-aspose.svg.dom.events.IEventListener-bool) | This method allows the removal of event listeners from the event target.<br/>If an [`IEventListener`](/svg/python-net/aspose.svg.dom.events/ieventlistener) is removed from an [`EventTarget`](/svg/python-net/aspose.svg.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.<br/>Event Listeners can never be invoked after being removed. |
| [clone_node](/svg/python-net/aspose.svg/svgsvgelement/clone_node/#) | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [clone_node](/svg/python-net/aspose.svg/svgsvgelement/clone_node/#bool) | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [toggle_attribute](/svg/python-net/aspose.svg/svgsvgelement/toggle_attribute/#str) | If force is not given, "toggles" qualifiedName, removing it if it is present and adding it if it is not present. If force is true, adds qualifiedName.<br/>If force is false, removes qualifiedName. |
| [toggle_attribute](/svg/python-net/aspose.svg/svgsvgelement/toggle_attribute/#str-bool) | If force is not given, "toggles" qualifiedName, removing it if it is present and adding it if it is not present. If force is true, adds qualifiedName.<br/>If force is false, removes qualifiedName. |
| [get_platform_type](/svg/python-net/aspose.svg/svgsvgelement/get_platform_type/#) | This method is used to retrieve ECMAScript object Type. |
| [dispatch_event](/svg/python-net/aspose.svg/svgsvgelement/dispatch_event/#aspose.svg.dom.events.Event) | This method allows the dispatch of events into the implementations event model. |
| [has_child_nodes](/svg/python-net/aspose.svg/svgsvgelement/has_child_nodes/#) | Returns whether this node has any children. |
| [normalize](/svg/python-net/aspose.svg/svgsvgelement/normalize/#) | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [is_equal_node](/svg/python-net/aspose.svg/svgsvgelement/is_equal_node/#aspose.svg.dom.Node) | Tests whether two nodes are equal.<br/>This method tests for equality of nodes, not sameness (i.e., whether the two nodes are references to the same object) which can be tested with Node.isSameNode(). All nodes that are the same will also be equal, though the reverse may not be true. |
| [is_same_node](/svg/python-net/aspose.svg/svgsvgelement/is_same_node/#aspose.svg.dom.Node) | Returns whether this node is the same node as the given one. <br/>This method provides a way to determine whether two Node references returned by the implementation reference the same object. When two Node references are references to the same object, even if through a proxy, the references may be used completely interchangeably, such that all attributes have the same values and calling the same DOM method on either reference always has exactly the same effect. |
| [lookup_prefix](/svg/python-net/aspose.svg/svgsvgelement/lookup_prefix/#str) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. <br/>See Namespace Prefix Lookup for details on the algorithm used by this method. |
| [lookup_namespace_uri](/svg/python-net/aspose.svg/svgsvgelement/lookup_namespace_uri/#str) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [is_default_namespace](/svg/python-net/aspose.svg/svgsvgelement/is_default_namespace/#str) | This method checks if the specified namespaceURI is the default namespace or not. |
| [insert_before](/svg/python-net/aspose.svg/svgsvgelement/insert_before/#aspose.svg.dom.Node-aspose.svg.dom.Node) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children.<br/>If child is a DocumentFragment object, all of its children are inserted, in the same order, before child. If the child is already in the tree, it is first removed. |
| [replace_child](/svg/python-net/aspose.svg/svgsvgelement/replace_child/#aspose.svg.dom.Node-aspose.svg.dom.Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. <br/>If newChild is a DocumentFragment object, oldChild is replaced by all of the DocumentFragment children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| [remove_child](/svg/python-net/aspose.svg/svgsvgelement/remove_child/#aspose.svg.dom.Node) | Removes the child node indicated by oldChild from the list of children, and returns it. |
| [append_child](/svg/python-net/aspose.svg/svgsvgelement/append_child/#aspose.svg.dom.Node) | Adds the node newChild to the end of the list of children of this node. If the newChild is already in the tree, it is first removed. |
| [get_attribute_names](/svg/python-net/aspose.svg/svgsvgelement/get_attribute_names/#) | Returns the attribute names of the element as an Array of strings. If the element has no attributes it returns an empty array. |
| [has_attributes](/svg/python-net/aspose.svg/svgsvgelement/has_attributes/#) | Returns whether this node (if it is an element) has any attributes |
| [get_attribute](/svg/python-net/aspose.svg/svgsvgelement/get_attribute/#str) | Retrieves an attribute value by name. |
| [get_attribute_ns](/svg/python-net/aspose.svg/svgsvgelement/get_attribute_ns/#str-str) | Retrieves an attribute value by local name and namespace URI. |
| [set_attribute](/svg/python-net/aspose.svg/svgsvgelement/set_attribute/#str-str) | Adds a new attribute. If an attribute with that name is already present in the element, its value is changed to be that of the value parameter |
| [set_attribute_ns](/svg/python-net/aspose.svg/svgsvgelement/set_attribute_ns/#str-str-str) | Adds a new attribute. If an attribute with the same local name and namespace URI is already present on the element, its prefix is changed to be the prefix part of the qualifiedName, and its value is changed to be the value parameter. |
| [remove_attribute](/svg/python-net/aspose.svg/svgsvgelement/remove_attribute/#str) | Removes an attribute by name. |
| [remove_attribute_ns](/svg/python-net/aspose.svg/svgsvgelement/remove_attribute_ns/#str-str) | Removes an attribute by local name and namespace URI. |
| [has_attribute](/svg/python-net/aspose.svg/svgsvgelement/has_attribute/#str) | Returns true when an attribute with a given name is specified on this element or has a default value, false otherwise. |
| [has_attribute_ns](/svg/python-net/aspose.svg/svgsvgelement/has_attribute_ns/#str-str) | Returns true when an attribute with a given local name and namespace URI is specified on this element or has a default value, false otherwise. |
| [get_attribute_node](/svg/python-net/aspose.svg/svgsvgelement/get_attribute_node/#str) | Retrieves an attribute node by name. |
| [set_attribute_node](/svg/python-net/aspose.svg/svgsvgelement/set_attribute_node/#aspose.svg.dom.Attr) | Adds a new attribute node. If an attribute with that name (nodeName) is already present in the element, it is replaced by the new one. |
| [remove_attribute_node](/svg/python-net/aspose.svg/svgsvgelement/remove_attribute_node/#aspose.svg.dom.Attr) | Removes the specified attribute node. |
| [get_attribute_node_ns](/svg/python-net/aspose.svg/svgsvgelement/get_attribute_node_ns/#str-str) | Retrieves an Attr node by local name and namespace URI. |
| [set_attribute_node_ns](/svg/python-net/aspose.svg/svgsvgelement/set_attribute_node_ns/#aspose.svg.dom.Attr) | Adds a new attribute. If an attribute with that local name and that namespace URI is already present in the element, it is replaced by the new one. |
| [get_elements_by_tag_name](/svg/python-net/aspose.svg/svgsvgelement/get_elements_by_tag_name/#str) | Returns a NodeList of all descendant Elements with a given tag name, in document order. |
| [get_elements_by_tag_name_ns](/svg/python-net/aspose.svg/svgsvgelement/get_elements_by_tag_name_ns/#str-str) | Returns a NodeList of all the descendant Elements with a given local name and namespace URI in document order. |
| [remove](/svg/python-net/aspose.svg/svgsvgelement/remove/#) | Removes this instance. |
| [query_selector_all](/svg/python-net/aspose.svg/svgsvgelement/query_selector_all/#str) | Returns a NodeList of all the Elements in document, which match selector |
| [query_selector](/svg/python-net/aspose.svg/svgsvgelement/query_selector/#str) | Returns the first Element in document, which match selector |
| [attach_shadow](/svg/python-net/aspose.svg/svgsvgelement/attach_shadow/#aspose.svg.dom.ShadowRootMode) | Creates shadow root and attaches it to current element. |
| [get_elements_by_class_name](/svg/python-net/aspose.svg/svgsvgelement/get_elements_by_class_name/#str) | Returns a live NodeList object containing all the elements in the document that have all the classes specified in argument.<br/>http://www.w3.org/TR/dom/ |
| [get_b_box](/svg/python-net/aspose.svg/svgsvgelement/get_b_box/#) | Returns the tight bounding box in current user space (i.e., after application of the ‘transform’ attribute, if any) on the geometry of all contained graphics elements, exclusive of stroking, clipping, masking and filter effects). Note that getBBox must return the actual bounding box at the time the method was called, even in case the element has not yet been rendered. |
| [get_ctm](/svg/python-net/aspose.svg/svgsvgelement/get_ctm/#) | Returns the transformation matrix from current user units (i.e., after application of the ‘transform’ attribute, if any) to the viewport coordinate system for the nearestViewportElement. |
| [get_screen_ctm](/svg/python-net/aspose.svg/svgsvgelement/get_screen_ctm/#) | Returns the transformation matrix from current user units (i.e., after application of the ‘transform’ attribute, if any) to the parent user agent's notice of a "pixel". For display devices, ideally this represents a physical screen pixel. For other devices or environments where physical pixel sizes are not known, then an algorithm similar to the CSS2 definition of a "pixel" can be used instead. Note that null is returned if this element is not hooked into the document tree. This method would have been more aptly named as getClientCTM, but the name getScreenCTM is kept for historical reasons. |
| [pause_animations](/svg/python-net/aspose.svg/svgsvgelement/pause_animations/#) | Suspends (i.e., pauses) all currently running animations that are defined within the SVG document fragment corresponding to this ‘svg’ element, causing the animation clock corresponding to this document fragment to stand still until it is unpaused. |
| [unpause_animations](/svg/python-net/aspose.svg/svgsvgelement/unpause_animations/#) | Unsuspends (i.e., unpauses) currently running animations that are defined within the SVG document fragment, causing the animation clock to continue from the time at which it was suspended. |
| [animations_paused](/svg/python-net/aspose.svg/svgsvgelement/animations_paused/#) | Returns true if this SVG document fragment is in a paused state. |
| [get_current_time](/svg/python-net/aspose.svg/svgsvgelement/get_current_time/#) | Returns the current time in seconds relative to the start time for the current SVG document fragment. If getCurrentTime is called before the document timeline has begun (for example, by script running in a ‘script’ element before the document's SVGLoad event is dispatched), then 0 is returned. |
| [set_current_time](/svg/python-net/aspose.svg/svgsvgelement/set_current_time/#float) | Adjusts the clock for this SVG document fragment, establishing a new current time. If setCurrentTime is called before the document timeline has begun (for example, by script running in a ‘script’ element before the document's SVGLoad event is dispatched), then the value of seconds in the last invocation of the method gives the time that the document will seek to once the document timeline has begun. |
| [create_svg_number](/svg/python-net/aspose.svg/svgsvgelement/create_svg_number/#) | Creates an SVGNumber object outside of any document trees. The object is initialized to a value of zero. |
| [create_svg_length](/svg/python-net/aspose.svg/svgsvgelement/create_svg_length/#) | Creates an SVGLength object outside of any document trees. The object is initialized to the value of 0 user units. |
| [create_svg_angle](/svg/python-net/aspose.svg/svgsvgelement/create_svg_angle/#) | Creates an SVGAngle object outside of any document trees. The object is initialized to the value 0 degrees (unitless). |
| [create_svg_point](/svg/python-net/aspose.svg/svgsvgelement/create_svg_point/#) | Creates an SVGPoint object outside of any document trees. The object is initialized to the point (0,0) in the user coordinate system. |
| [create_svg_matrix](/svg/python-net/aspose.svg/svgsvgelement/create_svg_matrix/#) | Creates an SVGMatrix object outside of any document trees. The object is initialized to the identity matrix. |
| [create_svg_rect](/svg/python-net/aspose.svg/svgsvgelement/create_svg_rect/#) | Creates an SVGRect object outside of any document trees. The object is initialized such that all values are set to 0 user units. |
| [create_svg_transform](/svg/python-net/aspose.svg/svgsvgelement/create_svg_transform/#) | Creates an SVGTransform object outside of any document trees. The object is initialized to an identity matrix transform (SVG_TRANSFORM_MATRIX). |
| [create_svg_transform_from_matrix](/svg/python-net/aspose.svg/svgsvgelement/create_svg_transform_from_matrix/#aspose.svg.datatypes.SVGMatrix) | Creates an SVGTransform object outside of any document trees. The object is initialized to the given matrix transform (i.e., SVG_TRANSFORM_MATRIX). The values from the parameter matrix are copied, the matrix parameter is not adopted as SVGTransform::matrix. |
| [get_element_by_id](/svg/python-net/aspose.svg/svgsvgelement/get_element_by_id/#str) | Searches this SVG document fragment (i.e., the search is restricted to a subset of the document tree) for an Element whose id is given by elementId. If an Element is found, that Element is returned. If no such element exists, returns null. Behavior is not defined if more than one element has this id. |
| [create_event](/svg/python-net/aspose.svg/svgsvgelement/create_event/#str) | Creates an [`Event`](/svg/python-net/aspose.svg.dom.events/event) of a type supported by the implementation. |



### See Also
* module [`aspose.svg`](..)
* class [`DOMObject`](/svg/python-net/aspose.svg.dom/domobject)
* class [`Element`](/svg/python-net/aspose.svg.dom/element)
* class [`Event`](/svg/python-net/aspose.svg.dom.events/event)
* class [`EventTarget`](/svg/python-net/aspose.svg.dom/eventtarget)
* class [`IEventListener`](/svg/python-net/aspose.svg.dom.events/ieventlistener)
* class [`Node`](/svg/python-net/aspose.svg.dom/node)
* class [`SVGElement`](/svg/python-net/aspose.svg/svgelement)
* class [`SVGGraphicsElement`](/svg/python-net/aspose.svg/svggraphicselement)
* class [`SVGSVGElement`](/svg/python-net/aspose.svg/svgsvgelement)

﻿---
title: ITreeWalker class
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 60
url: /python-net/aspose.svg.dom.traversal/itreewalker/
is_root: false
---

## ITreeWalker class

TreeWalker objects are used to navigate a document tree or 
subtree using the view of the document defined by their 
whatToShow flags and filter (if any). Any function which 
performs navigation using a TreeWalker will automatically 
support any view defined by a TreeWalker.

Omitting nodes from the logical view of a subtree can result in a 
structure that is substantially different from the same subtree in the 
complete, unfiltered document. Nodes that are siblings in the 
TreeWalker view may be children of different, widely 
separated nodes in the original view. For instance, consider a 
NodeFilter that skips all nodes except for Text nodes and 
the root node of a document. In the logical view that results, all text 
nodes will be siblings and appear as direct children of the root node, no 
matter how deeply nested the structure of the original document.



See also the [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113).
@since DOM Level 2



The ITreeWalker type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [current_node](/svg/python-net/aspose.svg.dom.traversal/itreewalker/current_node) | The node at which the TreeWalker is currently positioned.
| [root](/svg/python-net/aspose.svg.dom.traversal/itreewalker/root) | The root node of the NodeIterator, as specified when it
| [what_to_show](/svg/python-net/aspose.svg.dom.traversal/itreewalker/what_to_show) | This attribute determines which node types are presented via the
| [filter](/svg/python-net/aspose.svg.dom.traversal/itreewalker/filter) | The NodeFilter used to screen nodes. |


### Methods
| Method | Description |
| :- | :- |
| [parent_node](/svg/python-net/aspose.svg.dom.traversal/itreewalker/parent_node/#) | Moves to and returns the closest visible ancestor node of the current
| [first_child](/svg/python-net/aspose.svg.dom.traversal/itreewalker/first_child/#) | Moves the TreeWalker to the first visible child of the
| [last_child](/svg/python-net/aspose.svg.dom.traversal/itreewalker/last_child/#) | Moves the TreeWalker to the last visible child of the
| [previous_sibling](/svg/python-net/aspose.svg.dom.traversal/itreewalker/previous_sibling/#) | Moves the TreeWalker to the previous sibling of the
| [next_sibling](/svg/python-net/aspose.svg.dom.traversal/itreewalker/next_sibling/#) | Moves the TreeWalker to the next sibling of the current
| [previous_node](/svg/python-net/aspose.svg.dom.traversal/itreewalker/previous_node/#) | Moves the TreeWalker to the previous visible node in
| [next_node](/svg/python-net/aspose.svg.dom.traversal/itreewalker/next_node/#) | Moves the TreeWalker to the next visible node in document



### See Also
* module [`aspose.svg.dom.traversal`](..)
* class [`ITraversal`](/svg/python-net/aspose.svg.dom.traversal/itraversal)
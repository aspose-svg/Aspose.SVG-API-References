﻿---
title: IXPathResult class
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 50
url: /python-net/aspose.svg.dom.xpath/ixpathresult/
is_root: false
---

## IXPathResult class

The `XPathResult` interface represents the result of the evaluation of an 
XPath 1.0 expression within the context of a particular node. Since evaluation 
of an XPath expression can result in various result types, this object makes it 
possible to discover and manipulate the type and value of the result.



The IXPathResult type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [result_type](/svg/python-net/aspose.svg.dom.xpath/ixpathresult/result_type) | A code representing the type of this result, as defined by the 
| [number_value](/svg/python-net/aspose.svg.dom.xpath/ixpathresult/number_value) | The value of this number result. |
| [string_value](/svg/python-net/aspose.svg.dom.xpath/ixpathresult/string_value) | The value of this string result. |
| [boolean_value](/svg/python-net/aspose.svg.dom.xpath/ixpathresult/boolean_value) | The value of this boolean result. |
| [single_node_value](/svg/python-net/aspose.svg.dom.xpath/ixpathresult/single_node_value) | The value of this single node result, which may be `null`. |
| [invalid_iterator_state](/svg/python-net/aspose.svg.dom.xpath/ixpathresult/invalid_iterator_state) | Signifies that the iterator has become invalid. True if `resultType` 
| [snapshot_length](/svg/python-net/aspose.svg.dom.xpath/ixpathresult/snapshot_length) | The number of nodes in the result snapshot. Valid values for snapshotItem 


### Methods
| Method | Description |
| :- | :- |
| [iterate_next](/svg/python-net/aspose.svg.dom.xpath/ixpathresult/iterate_next/#) | Iterates and returns the next node from the node set or `null` if there are no more nodes. |
| [snapshot_item](/svg/python-net/aspose.svg.dom.xpath/ixpathresult/snapshot_item/#int) | Returns the `index`th item in the snapshot collection. If `index` is greater than 



### See Also
* module [`aspose.svg.dom.xpath`](..)
* class [`XPathResultType`](/svg/python-net/aspose.svg.dom.xpath/xpathresulttype)
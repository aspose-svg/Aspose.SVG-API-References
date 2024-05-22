﻿---
title: TypeInfo class
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 280
url: /python-net/aspose.svg.dom/typeinfo/
is_root: false
---

## TypeInfo class

The TypeInfo represents a type referenced from Element or Attr nodes, specified in the schemas associated with the document.



**Inheritance:** [`TypeInfo`](/svg/python-net/aspose.svg.dom/typeinfo) → 
[`DOMObject`](/svg/python-net/aspose.svg.dom/domobject)



The TypeInfo type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [type_name](/svg/python-net/aspose.svg.dom/typeinfo/type_name) | The name of a type declared for the associated element or attribute, or null if unknown. |
| [type_namespace](/svg/python-net/aspose.svg.dom/typeinfo/type_namespace) | Gets the type namespace.The namespace of the type declared for the associated element or attribute or null if the element does not have declaration or if no namespace information is available. |
| [DERIVATION_RESTRICTION](/svg/python-net/aspose.svg.dom/typeinfo/derivation_restriction) | If the document's schema is an XML Schema [XML Schema Part 1], this constant represents the derivation by restriction if complex types are involved, or a restriction if simple types are involved. |
| [DERIVATION_EXTENSION](/svg/python-net/aspose.svg.dom/typeinfo/derivation_extension) | If the document's schema is an XML Schema [XML Schema Part 1], this constant represents the derivation by extension. |
| [DERIVATION_UNION](/svg/python-net/aspose.svg.dom/typeinfo/derivation_union) | If the document's schema is an XML Schema [XML Schema Part 1], this constant represents the union if simple types are involved. |
| [DERIVATION_LIST](/svg/python-net/aspose.svg.dom/typeinfo/derivation_list) | If the document's schema is an XML Schema [XML Schema Part 1], this constant represents the list. |


### Methods
| Method | Description |
| :- | :- |
| [get_platform_type](/svg/python-net/aspose.svg.dom/typeinfo/get_platform_type/#) | This method is used to retrieve ECMAScript object Type. |
| [is_derived_from](/svg/python-net/aspose.svg.dom/typeinfo/is_derived_from/#str-str-int) | This method returns if there is a derivation between the reference type definition, i.e. the TypeInfo on which the method is being called, and the other type definition, i.e. the one passed as parameters. |



### See Also
* module [`aspose.svg.dom`](..)
* class [`DOMObject`](/svg/python-net/aspose.svg.dom/domobject)
* class [`TypeInfo`](/svg/python-net/aspose.svg.dom/typeinfo)

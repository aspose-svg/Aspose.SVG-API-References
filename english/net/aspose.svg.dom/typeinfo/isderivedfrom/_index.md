---
title: TypeInfo.IsDerivedFrom
second_title: Aspose.SVG for .NET API Reference
description: TypeInfo method. This method returns if there is a derivation between the reference type definition i.e. the TypeInfo on which the method is being called and the other type definition i.e. the one passed as parameters
type: docs
weight: 30
url: /net/aspose.svg.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

This method returns if there is a derivation between the reference type definition, i.e. the TypeInfo on which the method is being called, and the other type definition, i.e. the one passed as parameters.

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| Parameter | Type | Description |
| --- | --- | --- |
| typeNamespaceArg | String | the namespace of the other type definition |
| typeNameArg | String | the name of the other type definition. |
| derivationMethod | UInt64 | the type of derivation and conditions applied between two types, as described in the list of constants provided in this interface. |

### Return Value

If the document's schema is a DTD or no schema is associated with the document, this method will always return false. If the document's schema is an XML Schema, the method will true if the reference type definition is derived from the other type definition according to the derivation parameter. If the value of the parameter is 0 (no bit is set to 1 for the derivationMethod parameter), the method will return true if the other type definition can be reached by recursing any combination of {base type definition}, {item type definition}, or {member type definitions} from the reference type definition.

### See Also

* class [TypeInfo](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

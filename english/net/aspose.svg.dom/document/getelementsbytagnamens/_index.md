---
title: Document.GetElementsByTagNameNS
second_title: Aspose.SVG for .NET API Reference
description: Document GetElementsByTagNameNS method. Returns a list of elements with the given tag name belonging to the given namespace. The complete document is searched including the root node
type: docs
weight: 990
url: /net/aspose.svg.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

Returns a list of elements with the given tag name belonging to the given namespace. The complete document is searched, including the root node.

```csharp
public HTMLCollection GetElementsByTagNameNS(string namespaceURI, string localName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceURI | String | The namespace URI of elements to look for. |
| localName | String | Either the local name of elements to look for or the special value *, which matches all elements. |

### Return Value

A live [`NodeList`](../../../aspose.svg.collections/nodelist/) of found elements in the order they appear in the tree.

## Remarks

Refer to official [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens).

### See Also

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

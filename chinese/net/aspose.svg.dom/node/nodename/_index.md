---
title: "Node.NodeName"
second_title: "Aspose.SVG for .NET API 参考"
description: "Node NodeName 属性。返回当前节点的名称，作为字符串"
type: docs
weight: 80
url: /zh/net/aspose.svg.dom/node/nodename/
---
## Node.NodeName property

以字符串形式返回当前节点的名称。

```csharp
public abstract string NodeName { get; }
```

### Property Value

字符串，节点的不同类型的取值如下：

[`Attr`](../../attr/) - The value of Attr.name, that is the qualified name of the attribute.[`CDATASection`](../../cdatasection/) - The string "#cdata-section".[`Comment`](../../comment/) - The string "#comment".[`Document`](../../document/) - The string "#document".[`DocumentFragment`](../../documentfragment/) - The string "#document-fragment".[`DocumentType`](../../documenttype/) - The value of [`Name`](../../documenttype/name/)[`Element`](../../element/) - The value of [`TagName`](../../element/tagname/), that is the uppercase name of the element tag if an HTML element, or the lowercase element tag if an XML element (like an SVG or MATHML element).[`ProcessingInstruction`](../../processinginstruction/) - The value of [`Target`](../../processinginstruction/target/)[`Text`](../../text/) - The string "#text".

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-nodename).

### 另请参阅

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

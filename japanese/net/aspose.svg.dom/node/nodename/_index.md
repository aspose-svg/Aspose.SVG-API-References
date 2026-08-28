---
title: "Node.NodeName"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Node NodeName プロパティ。現在のノードの名前を文字列として返します。"
type: docs
weight: 80
url: /ja/net/aspose.svg.dom/node/nodename/
---
## Node.NodeName property

現在のノードの名前を文字列として返します。

```csharp
public abstract string NodeName { get; }
```

### Property Value

文字列で、さまざまなノードタイプの値は次のとおりです:

[`Attr`](../../attr/) - The value of Attr.name, that is the qualified name of the attribute.[`CDATASection`](../../cdatasection/) - The string "#cdata-section".[`Comment`](../../comment/) - The string "#comment".[`Document`](../../document/) - The string "#document".[`DocumentFragment`](../../documentfragment/) - The string "#document-fragment".[`DocumentType`](../../documenttype/) - The value of [`Name`](../../documenttype/name/)[`Element`](../../element/) - The value of [`TagName`](../../element/tagname/), that is the uppercase name of the element tag if an HTML element, or the lowercase element tag if an XML element (like an SVG or MATHML element).[`ProcessingInstruction`](../../processinginstruction/) - The value of [`Target`](../../processinginstruction/target/)[`Text`](../../text/) - The string "#text".

## 備考

参照:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-nodename).

### 参照

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

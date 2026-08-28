---
title: "IXPathEvaluator.CreateNSResolver"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IXPathEvaluator CreateNSResolver メソッド。任意の DOM ノードを適応させ、名前空間を解決できるようにします。これにより、XPath 式をドキュメント内でそのノードが出現したコンテキストに対して容易に評価できます。このアダプタは、ノード上の DOM Level 3 メソッド lookupNamespaceURI と同様に動作し、lookupNamespaceURI が呼び出された時点でノード階層に利用可能な現在の情報を使用して、指定されたプレフィックスから namespaceURI を解決し、暗黙の xml プレフィックスも正しく解決します。"
type: docs
weight: 20
url: /ja/net/aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Adapts any DOM node to resolve namespaces so that an XPath expression can be easily evaluated relative to the context of the node where it appeared within the document. This adapter works like the DOM Level 3 method `lookupNamespaceURI` on nodes in resolving the namespaceURI from a given prefix using the current information available in the node's hierarchy at the time lookupNamespaceURI is called, also correctly resolving the implicit xml prefix.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| nodeResolver | ノード | 名前空間解決のコンテキストとして使用されるノードです。 |

### 戻り値

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves namespaces with respect to the definitions in scope for a specified node.

### 参照

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)

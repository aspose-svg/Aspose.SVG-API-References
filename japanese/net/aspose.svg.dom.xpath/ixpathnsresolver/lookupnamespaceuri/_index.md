---
title: "IXPathNSResolver.LookupNamespaceURI"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IXPathNSResolver LookupNamespaceURI メソッド。指定された名前空間プレフィックスに関連付けられた名前空間 URI を検索します。XPath 評価器は null または空の引数でこのメソッドを呼び出してはならず、そうすると結果は未定義になります。"
type: docs
weight: 10
url: /ja/net/aspose.svg.dom.xpath/ixpathnsresolver/lookupnamespaceuri/
---
## IXPathNSResolver.LookupNamespaceURI method

Look up the namespace URI associated to the given namespace prefix. The XPath evaluator must never call this with a `null` or empty argument, because the result of doing this is undefined.

```csharp
public string LookupNamespaceURI(string prefix)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| プレフィックス | String | 検索するプレフィックスです。 |

### 戻り値

関連付けられた名前空間 URI を返します。見つからない場合は `null` を返します。

### 参照

* interface [IXPathNSResolver](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)

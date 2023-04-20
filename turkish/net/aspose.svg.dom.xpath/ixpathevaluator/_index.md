---
title: Interface IXPathEvaluator
second_title: Aspose.SVG for .NET API Referansı
description: Aspose.Svg.Dom.XPath.IXPathEvaluator arayüz. XPath ifadelerinin değerlendirmesi şu şekilde sağlanırIXPathEvaluator .
type: docs
weight: 1310
url: /tr/net/aspose.svg.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

XPath ifadelerinin değerlendirmesi şu şekilde sağlanır:`IXPathEvaluator` .

```csharp
public interface IXPathEvaluator
```

## yöntemler

| İsim | Tanım |
| --- | --- |
| [CreateExpression](../../aspose.svg.dom.xpath/ixpathevaluator/createexpression/)(string, IXPathNSResolver) | Çözülmüş ad alanlarıyla ayrıştırılmış bir XPath ifadesi oluşturur. Bu, ifade dizesini daha verimli bir dahili biçimde derlemeyi ve ifade içinde oluşan tüm ad alanı öneklerini önceden çözmeyi mümkün kıldığından, bir ifade bir uygulamada yeniden kullanılacağında yararlıdır. |
| [CreateNSResolver](../../aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Herhangi bir DOM düğümünü ad alanlarını çözecek şekilde uyarlar, böylece bir XPath ifadesi belgede göründüğü düğümün bağlamına göre kolayca değerlendirilebilir. Bu bağdaştırıcı, DOM Düzey 3 yöntemi gibi çalışır `aramaNamespaceURI` namespaceURI öğesini belirli bir önekten çözümlemede düğümlerde, düğümün hiyerarşisinde lookupNamespaceURI çağrıldığında mevcut olan geçerli bilgileri kullanarak, aynı zamanda örtük xml önekini doğru bir şekilde çözerek. |
| [Evaluate](../../aspose.svg.dom.xpath/ixpathevaluator/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Bir XPath ifade dizesini değerlendirir ve mümkünse belirtilen türden bir sonuç döndürür. |

### Ayrıca bakınız

* ad alanı [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* toplantı [Aspose.SVG](../../)



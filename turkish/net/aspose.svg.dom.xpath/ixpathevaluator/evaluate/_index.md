---
title: IXPathEvaluator.Evaluate
second_title: Aspose.SVG for .NET API Referansı
description: IXPathEvaluator yöntem. Bir XPath ifade dizesini değerlendirir ve mümkünse belirtilen türden bir sonuç döndürür.
type: docs
weight: 30
url: /tr/net/aspose.svg.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Bir XPath ifade dizesini değerlendirir ve mümkünse belirtilen türden bir sonuç döndürür.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| expression | String | Ayrıştırılacak ve değerlendirilecek XPath ifade dizesi. |
| contextNode | Node | bu`bağlam` bu XPath ifadesinin değerlendirilmesi için bağlam düğümüdür. Eğer[`IXPathEvaluator`](../) yayınlanarak elde edildi[`Document`](../../../aspose.svg.dom/document/) o zaman bu aynı belgeye ait olmalı ve bir olmalıdır[`Document`](../../../aspose.svg.dom/document/) ,[`Element`](../../../aspose.svg.dom/element/) ,[`Attr`](../../../aspose.svg.dom/attr/) ,[`Text`](../../../aspose.svg.dom/text/) , [`CDATASection`](../../../aspose.svg.dom/cdatasection/) ,[`Comment`](../../../aspose.svg.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/) , veyaXPathNamespace düğüm. Bağlam düğümü bir[`Text`](../../../aspose.svg.dom/text/) veya bir [`CDATASection`](../../../aspose.svg.dom/cdatasection/)bu durumda bağlam, XPath bağlamı olarak hizmet vermeyebilecek boş olmadığı sürece, XPath tarafından görüldüğü gibi tüm mantıksal metin düğümü olarak yorumlanır. |
| resolver | IXPathNSResolver | bu`çözücü` dahil olmak üzere tüm öneklerin çevirisine izin verir`xml` ad alanı öneki, XPath ifadesi içinde uygun ad alanı URI'lerine. Bu, şu şekilde belirtilirse`hükümsüz` , ifade içindeki herhangi bir ad alanı öneki, ile sonuçlanacaktır.[`DOMException`](../../../aspose.svg.dom/domexception/) kod ile atılıyor`NAMESPACE_ERR`. |
| type | XPathResultType | eğer belirli`tip` belirtilirse sonuç, karşılık gelen tür olarak döndürülür. XPath 1.0 sonuçları için bu, değerlerinden biri olmalıdır.[`XPathResultType`](../../xpathresulttype/) Sıralama. |
| result | Object | bu`sonuç` yeniden kullanılabilen ve bu yöntemle döndürülebilen belirli bir sonuç nesnesini belirtir. Bu olarak belirtilirse`hükümsüz`veya uygulama belirtilen sonucu yeniden kullanmaz, yeni bir sonuç nesnesi oluşturulur ve döndürülür. XPath 1.0 sonuçları için bu nesne şu türde olacaktır:[`IXPathResult`](../../ixpathresult/). |

### Geri dönüş değeri

XPath ifadesinin değerlendirmesinin sonucu. XPath 1.0 sonuçları için, bu nesne türünde olacaktır[`IXPathResult`](../../ixpathresult/).

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR: İfade, kurallarına göre geçerli değilse ortaya çıkar.[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: Sonuç, belirtilen tipini döndürmek için dönüştürülemezse yükseltilir. |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR: İfade, belirtilen tarafından çözümlenemeyen ad alanı önekleri içeriyorsa tetiklenir.[`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: Düğüm, bunun tarafından desteklenmeyen bir belgeden.[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Düğüm, XPath bağlamı düğümü olarak izin verilen bir tür değil veya istek türüne bu düğüm tarafından izin verilmiyor[`IXPathEvaluator`](../). |

### Ayrıca bakınız

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* ad alanı [Aspose.Svg.Dom.XPath](../../ixpathevaluator/)
* toplantı [Aspose.SVG](../../../)



---
title: "OneOf-2.Match"
second_title: "Aspose.SVG for .NET API Reference"
description: "OneOf Match yöntemi. Sağlanan işlevlerden birini, değerin temel türüne göre yürütür."
type: docs
weight: 20
url: /tr/net/aspose.svg.builder/oneof-2/match/
---
## OneOf<T1,T2>.Match<TResult> method

Değerin temel türüne göre sağlanan işlevlerden birini yürütür.

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2)
```

| Parametre | Açıklama |
| --- | --- |
| TResult | İşlevlerin dönüş tipi. |
| func1 | Değer T1 türündeyse yürütülecek işlev. |
| func2 | Değer T2 türündeyse yürütülecek işlev. |

### Dönüş Değeri

Yürütülen işlevin sonucu.

### Ayrıca Bakınız

* class [OneOf&lt;T1,T2&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

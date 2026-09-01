---
title: "IStorage Arayüzü"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Dom.IStorage arayüzü. Web Storage API'sinin bu arayüzü, belirli bir alanın oturum veya yerel depolamasına erişim sağlar. Web Storage spesifikasyonuna bakın https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs
weight: 3090
url: /tr/net/aspose.svg.dom/istorage/
---
## IStorage interface

Web Storage API'sinin bu arayüzü, belirli bir alanın oturum veya yerel depolamasına erişim sağlar. Web Storage spesifikasyonuna bakın: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```csharp
public interface IStorage
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Length](../../aspose.svg.dom/istorage/length/) { get; } | Anahtar/değer çiftlerinin sayısını döndürür. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Clear](../../aspose.svg.dom/istorage/clear/)() | Varsa tüm anahtar/değer çiftlerini kaldırır. |
| [GetItem](../../aspose.svg.dom/istorage/getitem/)(*string*) | Verilen anahtara bağlı mevcut değeri döndürür; anahtar mevcut değilse null döner. |
| [Key](../../aspose.svg.dom/istorage/key/)(*long*) | n'inci anahtarın adını döndürür; n, anahtar/değer çifti sayısına eşit veya büyükse null döner. |
| [RemoveItem](../../aspose.svg.dom/istorage/removeitem/)(*string*) | Verilen anahtara sahip anahtar/değer çiftini kaldırır; böyle bir çift mevcutsa. |
| [SetItem](../../aspose.svg.dom/istorage/setitem/)(*string, string*) | Anahtar tarafından tanımlanan çiftin değerini value olarak ayarlar; daha önce anahtar için bir çift yoksa yeni bir anahtar/değer çifti oluşturur. |

### Ayrıca Bakınız

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

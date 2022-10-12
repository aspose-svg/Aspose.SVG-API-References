---
title: InitEvent
second_title: Aspose.SVG for .NET API Referansı
description: InitEventaspose.svg.dom.events/event/initevent yöntemi bir değerin değerini başlatmak için kullanılır.Eventaspose.svg.dom.events/event the aracılığıyla oluşturulduIDocumentEventaspose.svg.dom.events/idocumentevent arayüz.
type: docs
weight: 110
url: /tr/net/aspose.svg.dom.events/event/initevent/
---
## Event.InitEvent method

`InitEvent` yöntemi, bir değerin değerini başlatmak için kullanılır.[`Event`](../../event) the aracılığıyla oluşturuldu[`IDocumentEvent`](../../idocumentevent) arayüz.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| type | String | Etkinlik türü. |
| bubbles | Boolean | ayarlanırsa`doğru` [kabarcıklar]. |
| cancelable | Boolean | ayarlanırsa`doğru` [iptal edilebilir]. |

### Notlar

Bu yöntem, yalnızca Olay şu adres aracılığıyla gönderilmeden önce çağrılabilir:[`DispatchEvent`](../../ieventtarget/dispatchevent) method, gerekirse bu aşamada birden çok kez çağrılabilir. Birden çok kez çağrılırsa son çağrı önceliklidir. Event arabiriminin bir alt sınıfından çağrılırsa yalnızca initEvent yönteminde belirtilen değerler değiştirilir, diğer tüm öznitelikler değişmeden bırakılır.

### Ayrıca bakınız

* class [Event](../../event)
* ad alanı [Aspose.Svg.Dom.Events](../../event)
* toplantı [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
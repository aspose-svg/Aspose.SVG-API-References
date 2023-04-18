---
title: Class SVGZoomEvent
second_title: Aspose.SVG for .NET API Referansı
description: Aspose.Svg.Events.SVGZoomEvent sınıf. Yakınlaştırma olayı kullanıcı SVG belge parçasının geçerli görünümünün yeniden ölçeklendirilmesine neden olan bir eylem başlattığında gerçekleşir. Olay işleyicileri yalnızca svg öğelerinde tanınır.
type: docs
weight: 1620
url: /tr/net/aspose.svg.events/svgzoomevent/
---
## SVGZoomEvent class

Yakınlaştırma olayı, kullanıcı SVG belge parçasının geçerli görünümünün yeniden ölçeklendirilmesine neden olan bir eylem başlattığında gerçekleşir. Olay işleyicileri yalnızca 'svg' öğelerinde tanınır.

```csharp
public class SVGZoomEvent : Event
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Bir olayın köpüren bir olay olup olmadığını belirtmek için kullanılır. Olay kabarabiliyorsa değer doğrudur, aksi takdirde değer yanlıştır. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Bir olayın varsayılan eyleminin engellenip engellenemeyeceğini belirtmek için kullanılır. Varsayılan eylem önlenebiliyorsa değer doğrudur, aksi takdirde değer yanlıştır. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | belirtmek için kullanılır[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) kimin[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) s şu anda işleniyor. Bu, özellikle yakalama ve köpürme sırasında kullanışlıdır. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | İptal edilebilir öznitelik değeri true iken, allowDefault() çağrıldıysa true, aksi takdirde false döndürür. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Şu anda olay akışının hangi aşamasının değerlendirildiğini belirtmek için kullanılır. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Güvenilir özellik, başlatıldığı değeri döndürmelidir. Bir olay oluşturulduğunda, öznitelik false. olarak başlatılmalıdır. |
| [NewScale](../../aspose.svg.events/svgzoomevent/newscale/) { get; } | Yakınlaştırma işlemi işlendikten sonra yerinde olacak ölçek faktörü. |
| [NewTranslate](../../aspose.svg.events/svgzoomevent/newtranslate/) { get; } | Yakınlaştırma işlemi yapıldıktan sonra yerinde olacak çeviri değerleri. SVGPoint nesnesi salt okunurdur. |
| [PreviousScale](../../aspose.svg.events/svgzoomevent/previousscale/) { get; } | Yakınlaştırma işlemi gerçekleşmeden önce mevcut olan önceki yakınlaştırma işlemlerinden alınan ölçek faktörü. |
| [PreviousTranslate](../../aspose.svg.events/svgzoomevent/previoustranslate/) { get; } | Yakınlaştırma işlemi gerçekleşmeden önce yürürlükte olan önceki yakınlaştırma işlemlerinden çeviri değerleri. SVGPoint nesnesi salt okunurdur. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | belirtmek için kullanılır[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) olayın orijinal olarak gönderildiği yer. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Olayın oluşturulduğu zamanı (döneme göre milisaniye cinsinden) belirtmek için kullanılır. Bazı sistemlerin bu bilgiyi sağlayamaması nedeniyle, timeStamp değeri tüm olaylar için mevcut olmayabilir. Mevcut olmadığında , 0 değeri döndürülecektir. Dönem zamanına örnek olarak sistemin başlama zamanı veya 0:0:0 UTC 1 Ocak 1970 verilebilir. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Olayın adı (büyük/küçük harfe duyarsız). Ad, bir XML adı olmalıdır. |
| [ZoomRectScreen](../../aspose.svg.events/svgzoomevent/zoomrectscreen/) { get; } | Ekran birimlerinde belirtilen yakınlaştırma dikdörtgeni. SVGRect nesnesi salt okunurdur. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(string, bool, bool) | [`InitEvent`](../../aspose.svg.dom.events/event/initevent/) yöntemi, bir değeri başlatmak için kullanılır[`Event`](../../aspose.svg.dom.events/event/) the aracılığıyla oluşturuldu[`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent/) arayüz. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Bir olay iptal edilebilirse,[`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault/) yöntemi, olayın iptal edileceğini belirtmek için kullanılır, , olayın sonucu olarak uygulama tarafından normalde gerçekleştirilen herhangi bir varsayılan eylemin gerçekleşmeyeceği anlamına gelir. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Bu yöntemi çağırmak, olayın geçerli olandan sonra kayıtlı herhangi bir olay dinleyicisine ulaşmasını engeller ve bir ağaçta gönderildiğinde, olayın başka herhangi bir nesneye ulaşmasını da engeller. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | [`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation/) yöntem, olay akışı sırasında bir olayın daha fazla yayılmasını önlemek için kullanılır. |

### Ayrıca bakınız

* class [Event](../../aspose.svg.dom.events/event/)
* ad alanı [Aspose.Svg.Events](../../aspose.svg.events/)
* toplantı [Aspose.SVG](../../)



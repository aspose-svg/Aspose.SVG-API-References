---
title: Class Event
second_title: Aspose.SVG for .NET API Referansı
description: Aspose.Svg.Dom.Events.Event sınıf. Event olayı işleyen işleyiciye bir olay hakkında bağlamsal bilgi sağlamak için kullanılır.
type: docs
weight: 920
url: /tr/net/aspose.svg.dom.events/event/
---
## Event class

`Event` olayı işleyen işleyiciye bir olay hakkında bağlamsal bilgi sağlamak için kullanılır.

```csharp
public class Event : DOMObject
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Event](event/#constructor)(string) | Yeni bir örneğini başlatır.`Event` sınıf. |
| [Event](event/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Yeni bir örneğini başlatır.`Event` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Bir olayın köpüren bir olay olup olmadığını belirtmek için kullanılır. Olay kabarabiliyorsa değer doğrudur, aksi takdirde değer yanlıştır. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Bir olayın varsayılan eyleminin engellenip engellenemeyeceğini belirtmek için kullanılır. Varsayılan eylem önlenebiliyorsa değer doğrudur, aksi takdirde değer yanlıştır. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | belirtmek için kullanılır[`IEventTarget`](../ieventtarget/) kimin[`IEventListener`](../ieventlistener/) s şu anda işleniyor. Bu, özellikle yakalama ve köpürme sırasında kullanışlıdır. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | İptal edilebilir öznitelik değeri true iken, allowDefault() çağrıldıysa true, aksi takdirde false döndürür. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Şu anda olay akışının hangi aşamasının değerlendirildiğini belirtmek için kullanılır. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Güvenilir özellik, başlatıldığı değeri döndürmelidir. Bir olay oluşturulduğunda, öznitelik false. olarak başlatılmalıdır. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | belirtmek için kullanılır[`IEventTarget`](../ieventtarget/) olayın orijinal olarak gönderildiği yer. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Olayın oluşturulduğu zamanı (döneme göre milisaniye cinsinden) belirtmek için kullanılır. Bazı sistemlerin bu bilgiyi sağlayamaması nedeniyle, timeStamp değeri tüm olaylar için mevcut olmayabilir. Mevcut olmadığında , 0 değeri döndürülecektir. Dönem zamanına örnek olarak sistemin başlama zamanı veya 0:0:0 UTC 1 Ocak 1970 verilebilir. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Olayın adı (büyük/küçük harfe duyarsız). Ad, bir XML adı olmalıdır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(string, bool, bool) | [`InitEvent`](./initevent/) yöntemi, bir değeri başlatmak için kullanılır`Event` the aracılığıyla oluşturuldu[`IDocumentEvent`](../idocumentevent/) arayüz. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Bir olay iptal edilebilirse,[`PreventDefault`](./preventdefault/) yöntemi, olayın iptal edileceğini belirtmek için kullanılır, , olayın sonucu olarak uygulama tarafından normalde gerçekleştirilen herhangi bir varsayılan eylemin gerçekleşmeyeceği anlamına gelir. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Bu yöntemi çağırmak, olayın geçerli olandan sonra kayıtlı herhangi bir olay dinleyicisine ulaşmasını engeller ve bir ağaçta gönderildiğinde, olayın başka herhangi bir nesneye ulaşmasını da engeller. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | [`StopPropagation`](./stoppropagation/) yöntem, olay akışı sırasında bir olayın daha fazla yayılmasını önlemek için kullanılır. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [AtTargetPhase](../../aspose.svg.dom.events/event/attargetphase/) | Geçerli olay aşaması, yakalama aşamasıdır. |
| const [BubblingPhase](../../aspose.svg.dom.events/event/bubblingphase/) | Geçerli olay aşaması, köpürme aşamasıdır. |
| const [CapturingPhase](../../aspose.svg.dom.events/event/capturingphase/) | Olay şu anda hedefte değerlendiriliyor[`IEventTarget`](../ieventtarget/) . |
| const [NonePhase](../../aspose.svg.dom.events/event/nonephase/) | Şu anda gönderilmeyen olaylar bu aşamadadır. |

### Notlar

Şunu uygulayan bir nesne:`Event` genellikle bir olay işleyiciye ilk parametre olarak iletilir. Daha spesifik bağlam bilgileri, olay işleyicilerine, şuradan ek arabirimler türetilerek iletilir:`Event` doğrudan eşlik ettikleri olayın türüyle ilgili bilgileri içerir. Bu türetilmiş arabirimler ayrıca olay dinleyicisine iletilen nesne tarafından da uygulanır.

### Ayrıca bakınız

* class [DOMObject](../../aspose.svg.dom/domobject/)
* ad alanı [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* toplantı [Aspose.SVG](../../)



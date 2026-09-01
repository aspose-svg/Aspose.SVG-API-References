---
title: "MediaQueryList Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Window.MediaQueryList sınıfı. Bir MediaQueryList nesnesi, bir belgeye uygulanan bir medya sorgusu hakkında bilgi depolar ve belgenin durumuna karşı hem anlık hem de olay tabanlı eşleşmeyi destekler. CSSOM View Module spesifikasyonuna bakın https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs
weight: 5960
url: /tr/net/aspose.svg.window/mediaquerylist/
---
## MediaQueryList class

Bir MediaQueryList nesnesi, bir belgeye uygulanan bir medya sorgusu hakkında bilgi depolar ve belgenin durumuna karşı hem anlık hem de olay tabanlı eşleşmeyi destekler. CSSOM View Module spesifikasyonuna bakın: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Document](../../aspose.svg.window/mediaquerylist/document/) { get; } | Bağlam nesnesinin ilişkili belgesi. |
| [Matches](../../aspose.svg.window/mediaquerylist/matches/) { get; } | Belgenin şu anda medya sorgu listesiyle eşleşip eşleşmediğini belirten, eşleşiyorsa true, aksi takdirde false döndüren bir boolean değer. |
| [Media](../../aspose.svg.window/mediaquerylist/media/) { get; } | Serileştirilmiş bir medya sorgusunu temsil eden bir dize. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Belirtilen olay hedefe iletildiğinde çağrılacak bir işlevi ayarlar. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Belirtilen olay hedefe iletildiğinde çağrılacak bir işlevi ayarlar. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Belirtilen olay hedefe iletildiğinde çağrılacak bir işlevi ayarlar. |
| [AddListener](../../aspose.svg.window/mediaquerylist/addlistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | MediaQueryList eşleşme durum değişikliği olay dinleyicisini ekle. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Belirtilen [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) üzerinde bir Olay gönderir, (senkron olarak) etkilenen EventListener'ları uygun sırayla çağırır. Normal olay işleme kuralları (yakalama ve isteğe bağlı kabarcık aşaması dahil) ayrıca [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/) ile manuel olarak gönderilen olaylara da uygulanır. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Yönetilmeyen kaynakların serbest bırakılması, salınması veya sıfırlanmasıyla ilgili uygulama tanımlı görevleri gerçekleştirir. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Bu yöntem, ECMAScript nesne Tipini almak için kullanılır. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Bu yöntem, olay hedefinden olay dinleyicilerinin kaldırılmasına izin verir. Bir [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) bir [`EventTarget`](../../aspose.svg.dom/eventtarget/) üzerinden bir olayı işlerken kaldırılırsa, mevcut eylemler tarafından tetiklenmez. Olay Dinleyicileri kaldırıldıktan sonra asla çağrılamaz. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Bu yöntem, olay hedefinden olay dinleyicilerinin kaldırılmasına izin verir. Bir [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) bir [`EventTarget`](../../aspose.svg.dom/eventtarget/) üzerinden bir olayı işlerken kaldırılırsa, mevcut eylemler tarafından tetiklenmez. Olay Dinleyicileri kaldırıldıktan sonra asla çağrılamaz. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Bu yöntem, olay hedefinden olay dinleyicilerinin kaldırılmasına izin verir. Bir [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) bir [`EventTarget`](../../aspose.svg.dom/eventtarget/) üzerinden bir olayı işlerken kaldırılırsa, mevcut eylemler tarafından tetiklenmez. Olay Dinleyicileri kaldırıldıktan sonra asla çağrılamaz. |
| [RemoveListener](../../aspose.svg.window/mediaquerylist/removelistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | MediaQueryList eşleşme durum değişikliği olay dinleyicisini kaldır. |

## Olaylar

| Ad | Açıklama |
| --- | --- |
| event [OnChange](../../aspose.svg.window/mediaquerylist/onchange/) | Eşleşme durumu değiştiğinde MediaQueryList üzerinde tetiklenen olay. |

### Ayrıca Bakınız

* class [EventTarget](../../aspose.svg.dom/eventtarget/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)

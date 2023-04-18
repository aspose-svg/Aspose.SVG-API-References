---
title: EventTarget.DispatchEvent
second_title: Aspose.SVG for .NET API Referansı
description: EventTarget yöntem. Bu yöntem olayların uygulama olay modeline gönderilmesine izin verir.
type: docs
weight: 20
url: /tr/net/aspose.svg.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Bu yöntem, olayların uygulama olay modeline gönderilmesine izin verir.

```csharp
public bool DispatchEvent(Event @event)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| event | Event | Olayın işlenmesinde kullanılacak olay tipini, davranışı ve bağlamsal bilgileri belirtir. |

### Geri dönüş değeri

Dönüş değeri`DispatchEvent` olayı işleyen dinleyicilerden herhangi birinin çağrılıp çağrılmadığını gösterir.[`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/) . Eğer[`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/) değer yanlış olarak adlandırıldı, aksi takdirde değer doğrudur.

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../domexception/) |  |

### Notlar

Bu şekilde gönderilen olaylar, doğrudan uygulama tarafından gönderilen olaylarla aynı yakalama ve köpürme davranışına sahip olacaktır. Olayın hedefi,[`EventTarget`](../) hangisinde`DispatchEvent` olarak adlandırılır

### Ayrıca bakınız

* class [Event](../../../aspose.svg.dom.events/event/)
* class [EventTarget](../)
* ad alanı [Aspose.Svg.Dom](../../eventtarget/)
* toplantı [Aspose.SVG](../../../)



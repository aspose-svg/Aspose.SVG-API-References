---
title: Class CustomEvent
second_title: Aspose.SVG untuk Referensi .NET API
description: Aspose.Svg.Dom.Events.CustomEvent kelas. Acara yang menggunakan antarmuka CustomEvent dapat digunakan untuk membawa data khusus.
type: docs
weight: 880
url: /id/net/aspose.svg.dom.events/customevent/
---
## CustomEvent class

Acara yang menggunakan antarmuka CustomEvent dapat digunakan untuk membawa data khusus.

```csharp
public class CustomEvent : Event
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [CustomEvent](customevent/#constructor)(string) | Menginisialisasi instance baru dari`CustomEvent` kelas. |
| [CustomEvent](customevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Menginisialisasi instance baru dari`CustomEvent` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Digunakan untuk menunjukkan apakah suatu peristiwa merupakan peristiwa menggelegak atau tidak. Jika peristiwa dapat menggembungkan nilainya benar, jika tidak, nilainya salah. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Digunakan untuk menunjukkan apakah suatu peristiwa dapat dicegah tindakan defaultnya atau tidak. Jika tindakan default dapat dicegah, nilainya benar, jika tidak, nilainya salah. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Digunakan untuk menunjukkan[`IEventTarget`](../ieventtarget/) yang[`IEventListener`](../ieventlistener/) s sedang diproses. Ini sangat berguna selama menangkap dan menggelegak. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Mengembalikan true jika preventDefault() dipanggil sementara nilai atribut yang dapat dibatalkan adalah true, dan false jika sebaliknya. |
| [Detail](../../aspose.svg.dom.events/customevent/detail/) { get; } | Mendapatkan data khusus. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Digunakan untuk menunjukkan fase aliran peristiwa mana yang sedang dievaluasi. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Atribut isTrusted harus mengembalikan nilai yang diinisialisasi. Ketika suatu peristiwa dibuat, atribut harus diinisialisasi ke false. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Digunakan untuk menunjukkan[`IEventTarget`](../ieventtarget/) ke mana acara tersebut awalnya dikirim. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Digunakan untuk menentukan waktu (dalam milidetik relatif terhadap zaman) saat peristiwa dibuat. Karena beberapa sistem mungkin tidak memberikan informasi ini, nilai timeStamp mungkin tidak tersedia untuk semua peristiwa. Jika tidak tersedia , nilai 0 akan dikembalikan. Contoh waktu zaman adalah waktu sistem mulai atau 0:0:0 UTC 1 Januari 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Nama acara (peka huruf besar-kecil). Nama harus berupa nama XML. |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| [InitCustomEvent](../../aspose.svg.dom.events/customevent/initcustomevent/)(string, bool, bool, object) | /// Itu[`InitEvent`](../event/initevent/) Metode ini digunakan untuk menginisialisasi nilai an[`Event`](../event/) diciptakan melalui[`IDocumentEvent`](../idocumentevent/) antarmuka. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(string, bool, bool) | Itu[`InitEvent`](../event/initevent/) Metode ini digunakan untuk menginisialisasi nilai an[`Event`](../event/) dibuat melalui the [`IDocumentEvent`](../idocumentevent/) antarmuka. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Jika suatu acara dapat dibatalkan, maka[`PreventDefault`](../event/preventdefault/) metode digunakan untuk menandakan bahwa acara tersebut akan dibatalkan, artinya tindakan default apa pun yang biasanya diambil oleh implementasi sebagai akibat dari acara tersebut tidak akan terjadi. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Memanggil metode ini mencegah acara menjangkau pendengar acara apa pun yang terdaftar setelah yang sekarang dan saat dikirim dalam pohon juga mencegah acara menjangkau objek lain. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Itu[`StopPropagation`](../event/stoppropagation/) metode digunakan untuk mencegah penyebaran lebih lanjut dari suatu peristiwa selama aliran peristiwa. |

### Lihat juga

* class [Event](../event/)
* ruang nama [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* perakitan [Aspose.SVG](../../)



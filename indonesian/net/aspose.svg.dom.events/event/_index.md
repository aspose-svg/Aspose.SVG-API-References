---
title: Class Event
second_title: Aspose.SVG untuk Referensi .NET API
description: Aspose.Svg.Dom.Events.Event kelas. ItuEvent digunakan untuk memberikan informasi kontekstual tentang suatu peristiwa kepada penangan yang memproses peristiwa tersebut.
type: docs
weight: 920
url: /id/net/aspose.svg.dom.events/event/
---
## Event class

Itu`Event` digunakan untuk memberikan informasi kontekstual tentang suatu peristiwa kepada penangan yang memproses peristiwa tersebut.

```csharp
public class Event : DOMObject
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Event](event/#constructor)(string) | Menginisialisasi instance baru dari`Event` kelas. |
| [Event](event/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Menginisialisasi instance baru dari`Event` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Digunakan untuk menunjukkan apakah suatu peristiwa merupakan peristiwa menggelegak atau tidak. Jika peristiwa dapat menggembungkan nilainya benar, jika tidak, nilainya salah. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Digunakan untuk menunjukkan apakah suatu peristiwa dapat dicegah tindakan defaultnya atau tidak. Jika tindakan default dapat dicegah, nilainya benar, jika tidak, nilainya salah. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Digunakan untuk menunjukkan[`IEventTarget`](../ieventtarget/) yang[`IEventListener`](../ieventlistener/) s sedang diproses. Ini sangat berguna selama menangkap dan menggelegak. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Mengembalikan true jika preventDefault() dipanggil sementara nilai atribut yang dapat dibatalkan adalah true, dan false jika sebaliknya. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Digunakan untuk menunjukkan fase aliran peristiwa mana yang sedang dievaluasi. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Atribut isTrusted harus mengembalikan nilai yang diinisialisasi. Ketika suatu peristiwa dibuat, atribut harus diinisialisasi ke false. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Digunakan untuk menunjukkan[`IEventTarget`](../ieventtarget/) ke mana acara tersebut awalnya dikirim. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Digunakan untuk menentukan waktu (dalam milidetik relatif terhadap zaman) saat peristiwa dibuat. Karena beberapa sistem mungkin tidak memberikan informasi ini, nilai timeStamp mungkin tidak tersedia untuk semua peristiwa. Jika tidak tersedia , nilai 0 akan dikembalikan. Contoh waktu zaman adalah waktu sistem mulai atau 0:0:0 UTC 1 Januari 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Nama acara (peka huruf besar-kecil). Nama harus berupa nama XML. |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(string, bool, bool) | Itu[`InitEvent`](./initevent/) Metode ini digunakan untuk menginisialisasi nilai an`Event` dibuat melalui the [`IDocumentEvent`](../idocumentevent/) antarmuka. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Jika suatu acara dapat dibatalkan, maka[`PreventDefault`](./preventdefault/) metode digunakan untuk menandakan bahwa acara tersebut akan dibatalkan, artinya tindakan default apa pun yang biasanya diambil oleh implementasi sebagai akibat dari acara tersebut tidak akan terjadi. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Memanggil metode ini mencegah acara menjangkau pendengar acara apa pun yang terdaftar setelah yang sekarang dan saat dikirim dalam pohon juga mencegah acara menjangkau objek lain. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Itu[`StopPropagation`](./stoppropagation/) metode digunakan untuk mencegah penyebaran lebih lanjut dari suatu peristiwa selama aliran peristiwa. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [AtTargetPhase](../../aspose.svg.dom.events/event/attargetphase/) | Fase event saat ini adalah fase penangkapan. |
| const [BubblingPhase](../../aspose.svg.dom.events/event/bubblingphase/) | Fase peristiwa saat ini adalah fase gelembung. |
| const [CapturingPhase](../../aspose.svg.dom.events/event/capturingphase/) | Acara saat ini sedang dievaluasi sesuai target[`IEventTarget`](../ieventtarget/) . |
| const [NonePhase](../../aspose.svg.dom.events/event/nonephase/) | Acara yang saat ini tidak dikirim sedang dalam fase ini. |

### Perkataan

Objek yang mengimplementasikan`Event` umumnya diteruskan sebagai parameter pertama ke event handler. Informasi konteks yang lebih spesifik diteruskan ke event handler dengan menurunkan antarmuka tambahan dari`Event` yang berisi informasi yang berkaitan langsung dengan jenis acara yang menyertainya. Antarmuka turunan ini juga diimplementasikan oleh objek yang diteruskan ke pendengar acara.

### Lihat juga

* class [DOMObject](../../aspose.svg.dom/domobject/)
* ruang nama [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* perakitan [Aspose.SVG](../../)



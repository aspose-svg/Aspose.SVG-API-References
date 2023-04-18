---
title: Class DocumentLoadErrorEvent
second_title: Aspose.SVG untuk Referensi .NET API
description: Aspose.Svg.Dom.Events.DocumentLoadErrorEvent kelas. ItuDocumentLoadErrorEvent terjadi ketika sumber daya yang diminta tidak tersedia.
type: docs
weight: 900
url: /id/net/aspose.svg.dom.events/documentloaderrorevent/
---
## DocumentLoadErrorEvent class

Itu`DocumentLoadErrorEvent` terjadi ketika sumber daya yang diminta tidak tersedia.

```csharp
public class DocumentLoadErrorEvent : ErrorEvent
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Digunakan untuk menunjukkan apakah suatu peristiwa merupakan peristiwa menggelegak atau tidak. Jika peristiwa dapat menggembungkan nilainya benar, jika tidak, nilainya salah. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Digunakan untuk menunjukkan apakah suatu peristiwa dapat dicegah tindakan defaultnya atau tidak. Jika tindakan default dapat dicegah, nilainya benar, jika tidak, nilainya salah. |
| [ColNo](../../aspose.svg.dom.events/errorevent/colno/) { get; } | Atribut colno harus mengembalikan nilai yang diinisialisasi. Saat objek dibuat, atribut ini harus diinisialisasi ke nol. Ini mewakili nomor kolom tempat kesalahan terjadi pada skrip. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Digunakan untuk menunjukkan[`IEventTarget`](../ieventtarget/) yang[`IEventListener`](../ieventlistener/) s sedang diproses. Ini sangat berguna selama menangkap dan menggelegak. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Mengembalikan true jika preventDefault() dipanggil sementara nilai atribut yang dapat dibatalkan adalah true, dan false jika sebaliknya. |
| [Error](../../aspose.svg.dom.events/errorevent/error/) { get; } | Atribut kesalahan harus mengembalikan nilai yang diinisialisasi. Saat objek dibuat, atribut ini harus diinisialisasi ke nol. Jika sesuai, ini disetel ke objek yang mewakili kesalahan (mis. objek pengecualian dalam kasus pengecualian DOM yang tidak tertangkap). |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Digunakan untuk menunjukkan fase aliran peristiwa mana yang sedang dievaluasi. |
| [FileName](../../aspose.svg.dom.events/errorevent/filename/) { get; } | Atribut nama file harus mengembalikan nilai yang diinisialisasi. Saat objek dibuat, atribut ini harus diinisialisasi ke string kosong. Ini mewakili URL absolut dari skrip tempat kesalahan awalnya terjadi. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Atribut isTrusted harus mengembalikan nilai yang diinisialisasi. Ketika suatu peristiwa dibuat, atribut harus diinisialisasi ke false. |
| [LineNo](../../aspose.svg.dom.events/errorevent/lineno/) { get; } | Atribut lineno harus mengembalikan nilai yang diinisialisasi. Saat objek dibuat, atribut ini harus diinisialisasi ke nol. Ini mewakili nomor baris tempat kesalahan terjadi pada skrip. |
| [Message](../../aspose.svg.dom.events/errorevent/message/) { get; } | Atribut pesan harus mengembalikan nilai yang diinisialisasi. Saat objek dibuat, atribut ini harus diinisialisasi ke string kosong. Ini mewakili pesan kesalahan. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Digunakan untuk menunjukkan[`IEventTarget`](../ieventtarget/) ke mana acara tersebut awalnya dikirim. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Digunakan untuk menentukan waktu (dalam milidetik relatif terhadap zaman) saat peristiwa dibuat. Karena beberapa sistem mungkin tidak memberikan informasi ini, nilai timeStamp mungkin tidak tersedia untuk semua peristiwa. Jika tidak tersedia , nilai 0 akan dikembalikan. Contoh waktu zaman adalah waktu sistem mulai atau 0:0:0 UTC 1 Januari 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Nama acara (peka huruf besar-kecil). Nama harus berupa nama XML. |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(string, bool, bool) | Itu[`InitEvent`](../event/initevent/) Metode ini digunakan untuk menginisialisasi nilai an[`Event`](../event/) dibuat melalui the [`IDocumentEvent`](../idocumentevent/) antarmuka. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Jika suatu acara dapat dibatalkan, maka[`PreventDefault`](../event/preventdefault/) metode digunakan untuk menandakan bahwa acara tersebut akan dibatalkan, artinya tindakan default apa pun yang biasanya diambil oleh implementasi sebagai akibat dari acara tersebut tidak akan terjadi. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Memanggil metode ini mencegah acara menjangkau pendengar acara apa pun yang terdaftar setelah yang sekarang dan saat dikirim dalam pohon juga mencegah acara menjangkau objek lain. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Itu[`StopPropagation`](../event/stoppropagation/) metode digunakan untuk mencegah penyebaran lebih lanjut dari suatu peristiwa selama aliran peristiwa. |

### Lihat juga

* class [ErrorEvent](../errorevent/)
* ruang nama [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* perakitan [Aspose.SVG](../../)



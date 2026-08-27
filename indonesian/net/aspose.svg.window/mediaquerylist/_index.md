---
title: "Kelas MediaQueryList"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Kelas Aspose.Svg.Window.MediaQueryList. Sebuah objek MediaQueryList menyimpan informasi tentang kueri media yang diterapkan pada dokumen dengan dukungan untuk pencocokan langsung maupun berbasis peristiwa terhadap status dokumen. Lihat spesifikasi CSSOM View Module https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs
weight: 5960
url: /id/net/aspose.svg.window/mediaquerylist/
---
## MediaQueryList class

Objek MediaQueryList menyimpan informasi tentang kueri media yang diterapkan pada dokumen, dengan dukungan untuk pencocokan langsung maupun berbasis peristiwa terhadap status dokumen. Lihat spesifikasi CSSOM View Module: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Document](../../aspose.svg.window/mediaquerylist/document/) { get; } | Dokumen yang terkait dengan objek Context. |
| [Matches](../../aspose.svg.window/mediaquerylist/matches/) { get; } | Nilai boolean yang mengembalikan true jika dokumen saat ini cocok dengan daftar kueri media, atau false jika tidak. |
| [Media](../../aspose.svg.window/mediaquerylist/media/) { get; } | String yang merepresentasikan kueri media yang diserialisasi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Menyiapkan fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Menyiapkan fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Menyiapkan fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [AddListener](../../aspose.svg.window/mediaquerylist/addlistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Tambahkan pendengar peristiwa perubahan status cocok MediaQueryList. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Men-dispatch sebuah Event pada [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (secara sinkron) memanggil EventListeners yang terpengaruh dalam urutan yang tepat. Aturan pemrosesan peristiwa normal (termasuk fase penangkapan dan fase bubbling opsional) juga berlaku untuk peristiwa yang di-dispatch secara manual dengan [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mengatur ulang sumber daya yang tidak dikelola. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil Tipe objek ECMAScript. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) dihapus dari sebuah [`EventTarget`](../../aspose.svg.dom/eventtarget/) saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) dihapus dari sebuah [`EventTarget`](../../aspose.svg.dom/eventtarget/) saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) dihapus dari sebuah [`EventTarget`](../../aspose.svg.dom/eventtarget/) saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [RemoveListener](../../aspose.svg.window/mediaquerylist/removelistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Hapus pendengar peristiwa perubahan status cocok MediaQueryList. |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [OnChange](../../aspose.svg.window/mediaquerylist/onchange/) | Peristiwa yang dipicu pada MediaQueryList ketika status cocok berubah. |

### Lihat Juga

* class [EventTarget](../../aspose.svg.dom/eventtarget/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)

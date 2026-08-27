---
title: "IWindow.Btoa"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "IWindow Btoa method. Menerima data masukan berupa string Unicode yang hanya berisi karakter dalam rentang U0000 hingga U00FF, masing‑masing mewakili byte biner dengan nilai 0x00 hingga 0xFF, dan mengonversinya ke representasi base64 yang kemudian dikembalikan."
type: docs
weight: 130
url: /id/net/aspose.svg.window/iwindow/btoa/
---
## IWindow.Btoa method

Mengambil data masukan, dalam bentuk string Unicode yang hanya berisi karakter dalam rentang U+0000 hingga U+00FF, masing-masing mewakili byte biner dengan nilai 0x00 hingga 0xFF, dan mengubahnya menjadi representasi base64, yang kemudian dikembalikan.

```csharp
public string Btoa(string data)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | String | String Unicode yang hanya berisi karakter dalam rentang U+0000 hingga U+00FF. |

### Nilai Kembalian

String base64.

### Pengecualian

| exception | kondisi |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Melemparkan pengecualian DOMException "InvalidCharacterError" jika string masukan berisi karakter di luar rentang. |

### Lihat Juga

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)

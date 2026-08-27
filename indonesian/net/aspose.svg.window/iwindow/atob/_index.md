---
title: "IWindow.Atob"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "IWindow Atob method. Menerima data masukan berupa string Unicode yang berisi data biner yang dienkode base64, mendekodenya, dan mengembalikan string yang terdiri dari karakter dalam rentang U0000 hingga U00FF, masing‑masing mewakili byte biner dengan nilai 0x00 hingga 0xFF yang sesuai dengan data biner tersebut."
type: docs
weight: 120
url: /id/net/aspose.svg.window/iwindow/atob/
---
## IWindow.Atob method

Menerima data masukan, dalam bentuk string Unicode yang berisi data biner yang dienkode base64, mendekodenya, dan mengembalikan string yang terdiri dari karakter dalam rentang U+0000 hingga U+00FF, masing-masing mewakili byte biner dengan nilai 0x00 hingga 0xFF secara berurutan, yang sesuai dengan data biner tersebut.

```csharp
public string Atob(string data)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | String | String Unicode yang berisi data biner yang dienkode base64. |

### Nilai Kembalian

String yang terdiri dari karakter dalam rentang U+0000 hingga U+00FF.

### Pengecualian

| exception | kondisi |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Melemparkan DOMException "InvalidCharacterError" jika string masukan bukan data base64 yang valid. |

### Lihat Juga

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)

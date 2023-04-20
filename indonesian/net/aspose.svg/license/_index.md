---
title: Class License
second_title: Aspose.SVG untuk Referensi .NET API
description: Aspose.Svg.License kelas. Menyediakan metode untuk melisensikan komponen.
type: docs
weight: 2190
url: /id/net/aspose.svg/license/
---
## License class

Menyediakan metode untuk melisensikan komponen.

```csharp
public class License
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [License](license/)() | Menginisialisasi instance baru dari kelas ini. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense)(Stream) | Lisensi komponen. |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense_1)(string) | Lisensi komponen. |

### Contoh

Dalam contoh ini, upaya akan dilakukan untuk menemukan file lisensi bernama MyLicense.lic di folder yang berisi  komponen, di folder yang berisi rakitan pemanggil, di folder rakitan entri, lalu di sumber daya tertanam rakitan pemanggil.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

file jar komponen:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Lihat juga

* ruang nama [Aspose.Svg](../../aspose.svg/)
* perakitan [Aspose.SVG](../../)



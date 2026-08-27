---
title: "BlendMode Enum"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Aspose.Svg.Builder.BlendMode enum. Menentukan mode pencampuran yang tersedia untuk menggabungkan gambar atau elemen dalam SVG"
type: docs
weight: 80
url: /id/net/aspose.svg.builder/blendmode/
---
## BlendMode enumeration

Menentukan mode pencampuran yang tersedia untuk menggabungkan gambar atau elemen dalam SVG.

```csharp
public enum BlendMode
```

### Nilai-nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Normal | `0` | Menampilkan gambar sumber apa adanya, tanpa pencampuran apapun. |
| Multiply | `1` | Mengalikan warna gambar sumber dan latar belakang. Hasilnya adalah gambar yang lebih gelap. |
| Screen | `2` | Menjadikan bagian gelap gambar sumber lebih terang dan bagian terang tetap tidak berubah. |
| Overlay | `3` | Menggabungkan mode campuran Multiply dan Screen untuk meningkatkan kontras. |
| Darken | `4` | Menggelapkan latar belakang berdasarkan warna gambar sumber. |
| Lighten | `5` | Menerangkan latar belakang berdasarkan warna gambar sumber. |
| ColorDodge | `6` | Menerangi latar belakang untuk mencerminkan gambar sumber. |
| ColorBurn | `7` | Menggelapkan latar belakang untuk mencerminkan gambar sumber. |
| HardLight | `8` | Membuat efek hard light berdasarkan kecerahan gambar sumber. |
| SoftLight | `9` | Membuat efek soft light berdasarkan kecerahan gambar sumber. |
| Difference | `10` | Menyoroti perbedaan antara gambar sumber dan latar belakang. |
| Exclusion | `11` | Membuat efek serupa dengan Difference, tetapi dengan kontras lebih rendah. |
| Hue | `12` | Menggunakan hue gambar sumber yang digabungkan dengan luminansi dan saturasi latar belakang. |
| Saturation | `13` | Menggunakan saturasi gambar sumber yang digabungkan dengan hue dan luminansi latar belakang. |
| Color | `14` | Menggunakan hue dan saturasi gambar sumber yang digabungkan dengan luminansi latar belakang. |
| Luminosity | `15` | Menggunakan luminansi gambar sumber yang digabungkan dengan hue dan saturasi latar belakang. |

## Catatan

Mode pencampuran dalam SVG digunakan untuk menentukan bagaimana dua lapisan dicampur satu sama lain. Enum ini menyediakan berbagai opsi yang mengontrol bagaimana warna lapisan yang dicampur berbaur dan menghasilkan efek visual yang berbeda.

### Lihat Juga

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

---
title: Class SVGLength
second_title: Aspose.SVG untuk Referensi .NET API
description: Aspose.Svg.DataTypes.SVGLength kelas. Antarmuka SVGLength sesuai dengan panjang tipe data dasar. Objek SVGLength dapat ditetapkan sebagai hanya baca yang berarti bahwa upaya untuk mengubah objek akan menghasilkan pengecualian seperti dijelaskan di bawah.
type: docs
weight: 220
url: /id/net/aspose.svg.datatypes/svglength/
---
## SVGLength class

Antarmuka SVGLength sesuai dengan panjang tipe data dasar. Objek SVGLength dapat ditetapkan sebagai hanya baca, yang berarti bahwa upaya untuk mengubah objek akan menghasilkan pengecualian, seperti dijelaskan di bawah.

```csharp
public class SVGLength : SVGValueType
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svglength/unittype/) { get; } | Jenis nilai seperti yang ditentukan oleh salah satu konstanta SVG_LENGTHTYPE_* yang ditentukan pada antarmuka ini. |
| [Value](../../aspose.svg.datatypes/svglength/value/) { get; set; } | Nilai sebagai nilai floating point, dalam unit pengguna. Menetapkan atribut ini akan menyebabkan valueInSpecifiedUnits dan valueAsString diperbarui secara otomatis untuk mencerminkan pengaturan ini. |
| [ValueAsString](../../aspose.svg.datatypes/svglength/valueasstring/) { get; set; } | Nilai sebagai nilai string, dalam satuan yang dinyatakan oleh unitType. Menyetel atribut ini akan menyebabkan nilai, valueInSpecifiedUnits, dan unitType diperbarui secara otomatis untuk mencerminkan setelan ini. |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | Nilai sebagai nilai floating point, dalam satuan yang dinyatakan oleh unitType. Menyetel atribut ini akan menyebabkan value dan valueAsString diperbarui secara otomatis untuk mencerminkan setelan ini. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | Pertahankan nilai tersimpan dasar yang sama, tetapi setel ulang pengidentifikasi unit tersimpan ke unitType yang diberikan. Atribut objek unitType, valueInSpecifiedUnits, dan valueAsString mungkin dimodifikasi sebagai hasil dari metode ini. Misalnya, jika nilai aslinya adalah "0,5 cm" dan metode dipanggil untuk diubah menjadi milimeter, maka unitType akan diubah menjadi SVG_LENGTHTYPE_MM, valueInSpecifiedUnits akan diubah menjadi nilai numerik 5 dan valueAsString akan diubah menjadi "5mm". |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Merilis sumber daya yang tidak dikelola dan - opsional - dikelola. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | Setel ulang nilai sebagai angka dengan unitType terkait, sehingga mengganti nilai untuk semua atribut pada objek. |
| override [ToString](../../aspose.svg.datatypes/svglength/tostring/)() | Mengembalikan aString yang mewakili instance ini. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.svg.datatypes/svglength/svg_lengthtype_cm/) | Nilai ditentukan menggunakan satuan cm yang ditentukan di CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../aspose.svg.datatypes/svglength/svg_lengthtype_ems/) | Nilai ditentukan menggunakan unit em yang ditentukan di CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../aspose.svg.datatypes/svglength/svg_lengthtype_exs/) | Nilai ditentukan menggunakan unit ex yang ditentukan di CSS2. |
| const [SVG_LENGTHTYPE_IN](../../aspose.svg.datatypes/svglength/svg_lengthtype_in/) | Nilai ditentukan menggunakan satuan dalam yang ditentukan di CSS2. |
| const [SVG_LENGTHTYPE_MM](../../aspose.svg.datatypes/svglength/svg_lengthtype_mm/) | Nilai ditentukan menggunakan satuan mm yang ditentukan di CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.svg.datatypes/svglength/svg_lengthtype_number/) | Tidak ada jenis unit yang diberikan (yaitu, nilai tanpa unit ditentukan), yang menunjukkan nilai dalam unit pengguna. |
| const [SVG_LENGTHTYPE_PC](../../aspose.svg.datatypes/svglength/svg_lengthtype_pc/) | Nilai ditentukan menggunakan unit pc yang ditentukan di CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.svg.datatypes/svglength/svg_lengthtype_percentage/) | Nilai persentase ditentukan. |
| const [SVG_LENGTHTYPE_PT](../../aspose.svg.datatypes/svglength/svg_lengthtype_pt/) | Nilai ditentukan menggunakan unit pt yang ditentukan di CSS2. |
| const [SVG_LENGTHTYPE_PX](../../aspose.svg.datatypes/svglength/svg_lengthtype_px/) | Nilai ditentukan menggunakan unit px yang ditentukan di CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.svg.datatypes/svglength/svg_lengthtype_unknown/) | Tipe unit bukan salah satu dari tipe unit yang telah ditentukan sebelumnya. Tidak valid mencoba menentukan nilai baru dari jenis ini atau mencoba mengalihkan nilai yang ada ke jenis ini. |

### Lihat juga

* class [SVGValueType](../svgvaluetype/)
* ruang nama [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* perakitan [Aspose.SVG](../../)



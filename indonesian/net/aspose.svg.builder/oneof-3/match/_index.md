---
title: "OneOf-3.Match"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode Match OneOf. Menjalankan salah satu fungsi yang disediakan berdasarkan tipe dasar nilai"
type: docs
weight: 20
url: /id/net/aspose.svg.builder/oneof-3/match/
---
## OneOf<T1,T2,T3>.Match<TResult> method

Menjalankan salah satu fungsi yang disediakan berdasarkan tipe dasar nilai tersebut.

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2, 
    Func<T3, TResult> func3)
```

| Parameter | Deskripsi |
| --- | --- |
| TResult | Tipe pengembalian fungsi-fungsi. |
| func1 | Fungsi yang akan dijalankan jika nilai berjenis T1. |
| func2 | Fungsi yang akan dijalankan jika nilai berjenis T2. |
| func3 | Fungsi yang akan dijalankan jika nilai bertipe T3. |

### Nilai Kembalian

Hasil dari fungsi yang dijalankan.

### Lihat Juga

* class [OneOf&lt;T1,T2,T3&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

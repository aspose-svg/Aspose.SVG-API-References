---
title: "Enum ReferrerPolicy"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Aspose.Svg.Builder.ReferrerPolicy enum. Menentukan kebijakan referer yang akan digunakan saat mengambil sumber daya"
type: docs
weight: 1020
url: /id/net/aspose.svg.builder/referrerpolicy/
---
## ReferrerPolicy enumeration

Menentukan kebijakan referer yang akan digunakan saat mengambil sumber daya.

```csharp
public enum ReferrerPolicy
```

### Nilai-nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | `0` | Tidak ada kebijakan referer yang diatur. |
| NoReferrer | `1` | Header Referer tidak akan dikirim. |
| NoReferrerWhenDowngrade | `2` | Header Referer tidak akan dikirim ke asal dengan keamanan lebih rendah (HTTPS -&gt; HTTP). |
| SameOrigin | `3` | Header Referer hanya akan dikirim untuk permintaan same-origin. |
| Origin | `4` | Hanya asal dokumen yang akan dikirim sebagai header Referer. |
| StrictOrigin | `5` | Hanya asal dokumen yang akan dikirim sebagai header Referer untuk konteks aman. |
| OriginWhenCrossOrigin | `6` | URL lengkap akan dikirim sebagai header Referer untuk permintaan same-origin, tetapi hanya asal untuk permintaan cross-origin. |
| StrictOriginWhenCrossOrigin | `7` | Hanya asal dokumen yang akan dikirim sebagai header Referer untuk permintaan same-origin, tetapi tidak ada header untuk permintaan cross-origin dalam konteks tidak aman. |
| UnsafeUrl | `8` | URL lengkap, termasuk jalur dan string kueri, akan selalu dikirim sebagai header Referer. |

### Lihat Juga

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

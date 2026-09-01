---
title: "ReferrerPolicy Enum"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.ReferrerPolicy enum. Kaynakları alırken kullanılacak yönlendirme politikasını belirtir."
type: docs
weight: 1020
url: /tr/net/aspose.svg.builder/referrerpolicy/
---
## ReferrerPolicy enumeration

Kaynakları alırken kullanılacak yönlendiren (referrer) politikasını belirtir.

```csharp
public enum ReferrerPolicy
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | `0` | Yönlendirme politikası ayarlanmamış. |
| NoReferrer | `1` | Referer başlığı gönderilmeyecek. |
| NoReferrerWhenDowngrade | `2` | Referer başlığı daha az güvenli (HTTPS -&gt; HTTP) kaynaklara gönderilmeyecek. |
| SameOrigin | `3` | Referer başlığı yalnızca aynı kökenli istekler için gönderilecek. |
| Origin | `4` | Belgenin yalnızca kökeni Referer başlığı olarak gönderilecek. |
| StrictOrigin | `5` | Güvenli bağlamlarda belgenin yalnızca kökeni Referer başlığı olarak gönderilecek. |
| OriginWhenCrossOrigin | `6` | Tam URL aynı kökenli isteklerde Referer başlığı olarak gönderilecek, ancak çapraz kökenli isteklerde yalnızca köken gönderilecek. |
| StrictOriginWhenCrossOrigin | `7` | Belgenin kökeni aynı kökenli isteklerde Referer başlığı olarak gönderilecek, ancak güvenli olmayan bağlamlarda çapraz kökenli isteklerde başlık gönderilmeyecek. |
| UnsafeUrl | `8` | Tam URL, yol ve sorgu dizesi dahil, her zaman Referer başlığı olarak gönderilecek. |

### Ayrıca Bakınız

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

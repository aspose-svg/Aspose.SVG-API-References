---
title: "IWindow.Atob"
second_title: "Aspose.SVG for .NET API Reference"
description: "IWindow Atob yöntemi. Base64 kodlu ikili veri içeren bir Unicode dizesi biçimindeki girdi verisini alır, çözer ve U0000 ile U00FF aralığındaki karakterlerden oluşan bir dize döndürür; her karakter ilgili ikili baytı 0x00 ile 0xFF değerleriyle temsil eder."
type: docs
weight: 120
url: /tr/net/aspose.svg.window/iwindow/atob/
---
## IWindow.Atob method

Base64 kodlu ikili veri içeren bir Unicode dizesi biçimindeki girdi verisini alır, çözer ve U+0000 ile U+00FF aralığındaki karakterlerden oluşan bir dize döndürür; her karakter ilgili ikili baytı 0x00 ile 0xFF değerleriyle temsil eder.

```csharp
public string Atob(string data)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | String | Base64 kodlu ikili veri içeren Unicode dizesi |

### Dönüş Değeri

U+0000 ile U+00FF aralığındaki karakterlerden oluşan dize

### İstisnalar

| istisna | koşul |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Girdi dizesi geçerli bir base64 verisi değilse bir "InvalidCharacterError" DOMException fırlatır. |

### Ayrıca Bakınız

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)

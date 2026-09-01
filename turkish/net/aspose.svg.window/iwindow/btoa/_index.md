---
title: "IWindow.Btoa"
second_title: "Aspose.SVG for .NET API Reference"
description: "IWindow Btoa yöntemi. Girdi verisini, yalnızca U0000 ile U00FF aralığındaki karakterleri içeren bir Unicode dizesi biçiminde alır; her karakter sırasıyla 0x00 ile 0xFF değerlerine sahip bir ikili baytı temsil eder ve bunu base64 temsiline dönüştürerek döndürür."
type: docs
weight: 130
url: /tr/net/aspose.svg.window/iwindow/btoa/
---
## IWindow.Btoa method

Girdi verisini, yalnızca U+0000 ile U+00FF aralığındaki karakterleri içeren bir Unicode dizesi biçiminde alır; her karakter sırasıyla 0x00 ile 0xFF değerlerine sahip bir ikili baytı temsil eder ve bunu base64 temsiline dönüştürerek döndürür.

```csharp
public string Btoa(string data)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | String | U+0000 ile U+00FF aralığındaki yalnızca karakterleri içeren Unicode dizesi. |

### Dönüş Değeri

Base64 dizesi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Girdi dizesi aralık dışı karakterler içeriyorsa bir "InvalidCharacterError" DOMException hatası fırlatır. |

### Ayrıca Bakınız

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)

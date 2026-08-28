---
title: "Enum ReferrerPolicy"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Aspose.Svg.Builder.ReferrerPolicy enum. Specifica la politica di referrer da utilizzare durante il recupero delle risorse"
type: docs
weight: 1020
url: /it/net/aspose.svg.builder/referrerpolicy/
---
## ReferrerPolicy enumeration

Specifica la politica del referrer da utilizzare durante il recupero delle risorse.

```csharp
public enum ReferrerPolicy
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Nessuna politica di referrer è impostata. |
| NoReferrer | `1` | L'intestazione Referer non verrà inviata. |
| NoReferrerWhenDowngrade | `2` | L'intestazione Referer non verrà inviata a origini con minore sicurezza (HTTPS -&gt; HTTP). |
| SameOrigin | `3` | L'intestazione Referer verrà inviata solo per richieste della stessa origine. |
| Origin | `4` | Solo l'origine del documento verrà inviata come intestazione Referer. |
| StrictOrigin | `5` | Solo l'origine del documento verrà inviata come intestazione Referer per contesti sicuri. |
| OriginWhenCrossOrigin | `6` | L'URL completo verrà inviato come intestazione Referer per richieste della stessa origine, ma solo l'origine per richieste cross-origin. |
| StrictOriginWhenCrossOrigin | `7` | Solo l'origine del documento verrà inviata come intestazione Referer per richieste della stessa origine, ma nessuna intestazione per richieste cross-origin in contesti non sicuri. |
| UnsafeUrl | `8` | L'URL completo, includendo il percorso e la stringa di query, verrà sempre inviato come intestazione Referer. |

### Vedi anche

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

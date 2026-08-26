---
title: "ReferrerPolicy-Enum"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.ReferrerPolicy enum. Gibt die zu verwendende Referrer-Policy beim Abrufen von Ressourcen an."
type: docs
weight: 1020
url: /de/net/aspose.svg.builder/referrerpolicy/
---
## ReferrerPolicy enumeration

Gibt die Referrer-Richtlinie an, die beim Abrufen von Ressourcen verwendet werden soll.

```csharp
public enum ReferrerPolicy
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Keine Referrer-Policy ist festgelegt. |
| NoReferrer | `1` | Der Referer-Header wird nicht gesendet. |
| NoReferrerWhenDowngrade | `2` | Der Referer-Header wird nicht an Ursprünge mit geringerer Sicherheit gesendet (HTTPS -&gt; HTTP). |
| SameOrigin | `3` | Der Referer-Header wird nur für Same-Origin-Anfragen gesendet. |
| Origin | `4` | Nur die Herkunft des Dokuments wird als Referer-Header gesendet. |
| StrictOrigin | `5` | Nur die Herkunft des Dokuments wird als Referer-Header für sichere Kontexte gesendet. |
| OriginWhenCrossOrigin | `6` | Die vollständige URL wird als Referer-Header für Same-Origin-Anfragen gesendet, aber nur die Herkunft für Cross-Origin-Anfragen. |
| StrictOriginWhenCrossOrigin | `7` | Nur die Herkunft des Dokuments wird als Referer-Header für Same-Origin-Anfragen gesendet, aber kein Header für Cross-Origin-Anfragen in unsicheren Kontexten. |
| UnsafeUrl | `8` | Die vollständige URL, einschließlich Pfad und Abfragezeichenfolge, wird immer als Referer-Header gesendet. |

### Siehe auch

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

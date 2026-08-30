---
title: "ReferrerPolicy Enum"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.ReferrerPolicy enum. Anger den referenspolicy som ska användas när resurser hämtas."
type: docs
weight: 1020
url: /sv/net/aspose.svg.builder/referrerpolicy/
---
## ReferrerPolicy enumeration

Anger vilken hänvisningspolicy som ska användas vid hämtning av resurser.

```csharp
public enum ReferrerPolicy
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Ingen referenspolicy är angiven. |
| NoReferrer | `1` | Referer‑huvudet kommer inte att skickas. |
| NoReferrerWhenDowngrade | `2` | Referer‑huvudet kommer inte att skickas till ursprung med lägre säkerhet (HTTPS -&gt; HTTP). |
| SameOrigin | `3` | Referer‑huvudet kommer endast att skickas för förfrågningar med samma ursprung. |
| Origin | `4` | Endast dokumentets ursprung kommer att skickas som Referer‑huvud. |
| StrictOrigin | `5` | Endast dokumentets ursprung kommer att skickas som Referer‑huvud för säkra sammanhang. |
| OriginWhenCrossOrigin | `6` | Den fullständiga URL:en kommer att skickas som Referer‑huvud för förfrågningar med samma ursprung, men endast ursprunget för kors‑ursprungsförfrågningar. |
| StrictOriginWhenCrossOrigin | `7` | Endast dokumentets ursprung kommer att skickas som Referer‑huvud för förfrågningar med samma ursprung, men inget huvud för kors‑ursprungsförfrågningar i osäkra sammanhang. |
| UnsafeUrl | `8` | Den fullständiga URL:en, inklusive sökväg och frågesträng, kommer alltid att skickas som Referer‑huvud. |

### Se även

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

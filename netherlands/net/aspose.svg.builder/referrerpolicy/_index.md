---
title: "ReferrerPolicy-enumeratie"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.ReferrerPolicy-enumeratie. Specificeert het referrer-beleid dat moet worden gebruikt bij het ophalen van bronnen"
type: docs
weight: 1020
url: /nl/net/aspose.svg.builder/referrerpolicy/
---
## ReferrerPolicy enumeration

Specificeert het referrer‑beleid dat moet worden gebruikt bij het ophalen van bronnen.

```csharp
public enum ReferrerPolicy
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | `0` | Er is geen referrer-beleid ingesteld. |
| NoReferrer | `1` | De Referer-header wordt niet verzonden. |
| NoReferrerWhenDowngrade | `2` | De Referer-header wordt niet verzonden naar origins met minder beveiliging (HTTPS -&gt; HTTP). |
| SameOrigin | `3` | De Referer-header wordt alleen verzonden voor verzoeken van dezelfde origin. |
| Origin | `4` | Alleen de origin van het document wordt verzonden als de Referer-header. |
| StrictOrigin | `5` | Alleen de origin van het document wordt verzonden als de Referer-header voor beveiligde contexten. |
| OriginWhenCrossOrigin | `6` | De volledige URL wordt verzonden als de Referer-header voor verzoeken van dezelfde origin, maar alleen de origin voor cross-origin verzoeken. |
| StrictOriginWhenCrossOrigin | `7` | Alleen de origin van het document wordt verzonden als de Referer-header voor verzoeken van dezelfde origin, maar er wordt geen header verzonden voor cross-origin verzoeken in onveilige contexten. |
| UnsafeUrl | `8` | De volledige URL, inclusief het pad en de querystring, wordt altijd verzonden als de Referer-header. |

### Zie ook

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

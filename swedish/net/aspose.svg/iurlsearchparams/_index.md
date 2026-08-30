---
title: "IUrlSearchParams-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.IUrlSearchParams-gränssnitt. Tillhandahåller metoder för att arbeta med URL:ers frågesträng"
type: docs
weight: 4140
url: /sv/net/aspose.svg/iurlsearchparams/
---
## IUrlSearchParams interface

Tillhandahåller metoder för att arbeta med URL‑frågesträng.

```csharp
public interface IUrlSearchParams : IEnumerable<string[]>
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Append](../../aspose.svg/iurlsearchparams/append/)(*string, string*) | Lägger till ett nytt namn‑värde‑par vars namn är `name` och värde är `value`. |
| [Delete](../../aspose.svg/iurlsearchparams/delete/)(*string*) | Tar bort alla namn‑värde‑par vars namn är `name`. |
| [Get](../../aspose.svg/iurlsearchparams/get/)(*string*) | Returnerar värdet för det första namn‑värde‑paret vars namn är `name`. |
| [GetAll](../../aspose.svg/iurlsearchparams/getall/)(*string*) | Returnerar alla värden vars namn är `name`. |
| [Has](../../aspose.svg/iurlsearchparams/has/)(*string*) | Kontrollerar om det finns ett namn‑värde‑par vars namn är `name` i listan. |
| [Set](../../aspose.svg/iurlsearchparams/set/)(*string, string*) | Sätter värdet för det första hittade namn‑värde‑paret till det angivna värdet och tar bort de övriga. Om inga namn‑värde‑par med det angivna namnet hittas, kommer ett nytt att läggas till i listan. |
| [Sort](../../aspose.svg/iurlsearchparams/sort/)() | Sorterar alla namn‑värde‑par, om några finns, efter deras namn. |

### Se även

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

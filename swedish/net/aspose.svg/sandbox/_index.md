---
title: "Sandbox‑enum"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Sandbox‑enum. En sandbox‑flaggsats är en uppsättning av noll eller fler av följande flaggor som används för att begränsa de förmågor som potentiellt icke‑betrodda resurser har."
type: docs
weight: 5680
url: /sv/net/aspose.svg/sandbox/
---
## Sandbox enumeration

En sandbox‑flaggsats är en uppsättning av noll eller fler av följande flaggor, som används för att begränsa de förmågor som potentiellt opålitliga resurser har.

```csharp
[Flags]
public enum Sandbox
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Ingen flagga är satt, varje sandbox‑funktion accepteras. |
| Navigation | `1` | Denna flagga förhindrar att innehåll navigerar i webbläsarkontexter annat än den sandlådade webbläsarkontexten själv (eller webbläsarkontexter som är ytterligare inbäddade i den), hjälparwebbläsarkontexter (som skyddas av flaggan för sandlådad hjälparnavigering av webbläsarkontext som definieras nedan), och toppnivåns webbläsarkontext (som skyddas av flaggan för sandlådad toppnivånavigering av webbläsarkontext som definieras nedan). Om flaggan för sandlådad hjälparnavigering av webbläsarkontext inte är satt, så tillåter begränsningarna i vissa fall ändå popup-fönster (nya toppnivåns webbläsarkontexter) att öppnas. Dessa webbläsarkontexter har alltid en tillåten sandlådad navigator, inställd när webbläsarkontexten skapas, vilket gör att den webbläsarkontext som skapade dem faktiskt kan navigera dem. (Annars skulle flaggan för sandlådad navigering av webbläsarkontext förhindra att de navigeras även om de öppnades.) |
| AuxiliaryNavigation | `2` | Denna flagga förhindrar att innehåll skapar nya hjälparwebbläsarkontexter, t.ex. genom att använda target-attributet eller window.open()-metoden. |
| TopLevelNavigation | `4` | Denna flagga förhindrar att innehåll navigerar sin toppnivåns webbläsarkontext och förhindrar att innehåll stänger sin toppnivåns webbläsarkontext. När flaggan för sandlådad toppnivånavigering av webbläsarkontext inte är satt, kan innehåll navigera sin toppnivåns webbläsarkontext, men andra webbläsarkontexter är fortfarande skyddade av flaggan för sandlådad navigering av webbläsarkontext och eventuellt flaggan för sandlådad hjälparnavigering av webbläsarkontext. |
| Plugins | `8` | Denna flagga förhindrar att innehåll instansierar plugin-moduler, oavsett om embed-elementet, object-elementet, applet-elementet används eller genom navigering av en inbäddad webbläsarkontext, såvida inte dessa plugin-moduler kan säkras. |
| Origin | `10` | Denna flagga tvingar innehåll till en unik ursprung, vilket förhindrar att det får åtkomst till annat innehåll från samma ursprung. |
| Forms | `20` | Denna flagga blockerar formulärinlämning. |
| PointerLock | `40` | Denna flagga inaktiverar Pointer Lock API. |
| Scripts | `80` | Denna flagga blockerar skriptkörning. |
| AutomaticFeatures | `100` | Denna flagga blockerar funktioner som triggas automatiskt, såsom att automatiskt spela upp en video eller automatiskt fokusera ett formulärkontroll. |
| Fullscreen | `200` | Denna flagga förhindrar att innehåll använder requestFullscreen()‑metoden. |
| DocumentDomain | `400` | Denna flagga förhindrar att innehåll använder document.domain-funktionen för att ändra det effektiva skriptursprunget. |
| Images | `800` | Denna flagga inaktiverar bildladdning. |

### Se även

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

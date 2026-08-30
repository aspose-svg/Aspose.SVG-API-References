---
title: "Location-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Window.Location-klass. Location-objekt ger en representation av adressen till det aktiva dokumentet i deras Documents‑bläddrakontext och möjliggör att den aktuella posten i bläddrarkontextens sessionshistorik ändras genom att lägga till eller ersätta poster i historikobjektet."
type: docs
weight: 5950
url: /sv/net/aspose.svg.window/location/
---
## Location class

Location-objekt ger en representation av adressen till det aktiva dokumentet i deras dokuments webbläsarkontext, och tillåter att den aktuella posten i webbläsarkontextens sessionshistorik ändras genom att lägga till eller ersätta poster i historikobjektet.

```csharp
public sealed class Location : DOMObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Hash](../../aspose.svg.window/location/hash/) { get; set; } | Returnerar fragmentet i Location‑objektets URL (inkluderar inledande "#" om det inte är tomt). Kan sättas för att navigera till samma URL med ett ändrat fragment (ignorerar inledande "#"). |
| [Host](../../aspose.svg.window/location/host/) { get; set; } | Returnerar värd och port i Location‑objektets URL (om de skiljer sig från standardporten för schemat). Kan sättas för att navigera till samma URL med en ändrad värd och port. |
| [Hostname](../../aspose.svg.window/location/hostname/) { get; set; } | Returnerar värd i Location‑objektets URL. Kan sättas för att navigera till samma URL med en ändrad värd. |
| [Href](../../aspose.svg.window/location/href/) { get; set; } | Returnerar Location‑objektets URL. Kan sättas för att navigera till den angivna URL:en. |
| [Origin](../../aspose.svg.window/location/origin/) { get; } | Returnerar ursprunget för Location‑objektets URL. |
| [Pathname](../../aspose.svg.window/location/pathname/) { get; set; } | Returnerar sökvägen i Location‑objektets URL. Kan sättas för att navigera till samma URL med en ändrad sökväg. |
| [Port](../../aspose.svg.window/location/port/) { get; set; } | Returnerar porten i Location‑objektets URL. Kan sättas för att navigera till samma URL med en ändrad port. |
| [Protocol](../../aspose.svg.window/location/protocol/) { get; set; } | Returnerar schemat i Location‑objektets URL. Kan sättas för att navigera till samma URL med ett ändrat schema. |
| [Search](../../aspose.svg.window/location/search/) { get; set; } | Returnerar Location-objektets URL:s query (inkluderar inledande "?" om den inte är tom). Kan sättas för att navigera till samma URL med en ändrad query (ignorerar inledande "?"). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Assign](../../aspose.svg.window/location/assign/)(*string*) | Navigerar till den angivna sidan. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [Reload](../../aspose.svg.window/location/reload/)() | Laddar om den aktuella sidan. |
| [Replace](../../aspose.svg.window/location/replace/)(*string*) | Tar bort den aktuella sidan från sessionshistoriken och navigerar till den angivna sidan. |
| override [ToString](../../aspose.svg.window/location/tostring/)() | Returnerar Location-objektets URL. |

### Se även

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)

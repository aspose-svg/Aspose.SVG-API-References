---
title: "Location Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Window.Location klasse. Location‑objecten bieden een weergave van het adres van het actieve document van hun Document‑browsing‑context en stellen de huidige invoer van de sessiegeschiedenis van de browsing‑context in staat te worden gewijzigd door invoer toe te voegen of te vervangen in het geschiedenisobject."
type: docs
weight: 5950
url: /nl/net/aspose.svg.window/location/
---
## Location class

Locatie-objecten bieden een weergave van het adres van het actieve document van hun Document-browsecontext, en stellen toe dat het huidige item van de sessiegeschiedenis van de browsecontext wordt gewijzigd door items toe te voegen of te vervangen in het geschiedenisobject.

```csharp
public sealed class Location : DOMObject
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Hash](../../aspose.svg.window/location/hash/) { get; set; } | Retourneert het fragment van de URL van het Location‑object (inclusief leidende "#" indien niet leeg). Kan worden ingesteld om naar dezelfde URL te navigeren met een gewijzigd fragment (negeert leidende "#"). |
| [Host](../../aspose.svg.window/location/host/) { get; set; } | Geeft de host en poort van de URL van het Location-object terug (indien verschillend van de standaardpoort voor het schema). Kan worden ingesteld om naar dezelfde URL te navigeren met een gewijzigde host en poort. |
| [Hostname](../../aspose.svg.window/location/hostname/) { get; set; } | Geeft de host van de URL van het Location-object terug. Kan worden ingesteld om naar dezelfde URL te navigeren met een gewijzigde host. |
| [Href](../../aspose.svg.window/location/href/) { get; set; } | Geeft de URL van het Location-object terug. Kan worden ingesteld om naar de opgegeven URL te navigeren. |
| [Origin](../../aspose.svg.window/location/origin/) { get; } | Geeft de origin van de URL van het Location-object terug. |
| [Pathname](../../aspose.svg.window/location/pathname/) { get; set; } | Geeft het pad van de URL van het Location-object terug. Kan worden ingesteld om naar dezelfde URL te navigeren met een gewijzigd pad. |
| [Port](../../aspose.svg.window/location/port/) { get; set; } | Geeft de poort van de URL van het Location-object terug. Kan worden ingesteld om naar dezelfde URL te navigeren met een gewijzigde poort. |
| [Protocol](../../aspose.svg.window/location/protocol/) { get; set; } | Geeft het schema van de URL van het Location-object terug. Kan worden ingesteld om naar dezelfde URL te navigeren met een gewijzigd schema. |
| [Search](../../aspose.svg.window/location/search/) { get; set; } | Geeft de query van de URL van het Location-object terug (inclusief leidende "?" indien niet leeg). Kan worden ingesteld om naar dezelfde URL te navigeren met een gewijzigde query (negeert leidende "?"). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Assign](../../aspose.svg.window/location/assign/)(*string*) | Navigeert naar de opgegeven pagina. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [Reload](../../aspose.svg.window/location/reload/)() | Laadt de huidige pagina opnieuw. |
| [Replace](../../aspose.svg.window/location/replace/)(*string*) | Verwijdert de huidige pagina uit de sessiegeschiedenis en navigeert naar de opgegeven pagina. |
| override [ToString](../../aspose.svg.window/location/tostring/)() | Geeft de URL van het Location-object terug. |

### Zie ook

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)

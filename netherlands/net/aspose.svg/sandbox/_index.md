---
title: "Sandbox-enumeratie"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Sandbox enum. Een sandbox‑vlagset is een verzameling van nul of meer van de volgende vlaggen die worden gebruikt om de mogelijkheden van potentieel onbetrouwbare bronnen te beperken."
type: docs
weight: 5680
url: /nl/net/aspose.svg/sandbox/
---
## Sandbox enumeration

Een sandbox‑vlagset is een verzameling van nul of meer van de volgende vlaggen, die worden gebruikt om de mogelijkheden van potentieel onbetrouwbare bronnen te beperken.

```csharp
[Flags]
public enum Sandbox
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | `0` | Er is geen vlag ingesteld, elke sandbox‑functie wordt geaccepteerd. |
| Navigation | `1` | Deze vlag voorkomt dat inhoud andere browse‑contexten navigeert dan de gesandboxt browse‑context zelf (of verder geneste browse‑contexten daarin), hulpbrowse‑contexten (die worden beschermd door de hieronder gedefinieerde gesandboxt hulpnavigatie‑browse‑context‑vlag), en de top‑level browse‑context (die wordt beschermd door de verderop gedefinieerde gesandboxt top‑level navigatie‑browse‑context‑vlag). Als de gesandboxt hulpnavigatie‑browse‑context‑vlag niet is ingesteld, dan staan de beperkingen in bepaalde gevallen toch pop‑ups (nieuwe top‑level browse‑contexten) toe om geopend te worden. Deze browse‑contexten hebben altijd één toegestane gesandboxt navigator, ingesteld bij het aanmaken van de browse‑context, die de browse‑context die hen heeft gecreëerd in staat stelt ze daadwerkelijk te navigeren. (Anders zou de gesandboxt navigatie‑browse‑context‑vlag voorkomen dat ze genavigeerd kunnen worden, zelfs als ze geopend zijn.) |
| AuxiliaryNavigation | `2` | Deze vlag voorkomt dat inhoud nieuwe hulpbrowse‑contexten creëert, bijv. via het target‑attribuut of de window.open()-methode. |
| TopLevelNavigation | `4` | Deze vlag voorkomt dat inhoud hun top‑level browse‑context navigeert en voorkomt dat inhoud hun top‑level browse‑context sluit. Wanneer de gesandboxt top‑level navigatie‑browse‑context‑vlag niet is ingesteld, kan inhoud hun top‑level browse‑context navigeren, maar andere browse‑contexten blijven beschermd door de gesandboxt navigatie‑browse‑context‑vlag en mogelijk de gesandboxt hulpnavigatie‑browse‑context‑vlag. |
| Plugins | `8` | Deze vlag voorkomt dat inhoud plug‑ins instantiateert, of dit nu gebeurt via het embed‑element, het object‑element, het applet‑element, of via navigatie van een geneste browse‑context, tenzij die plug‑ins beveiligd kunnen worden. |
| Origin | `10` | Deze vlag dwingt inhoud naar een unieke oorsprong, waardoor het voorkomen wordt dat het toegang krijgt tot andere inhoud van dezelfde oorsprong. |
| Forms | `20` | Deze vlag blokkeert het verzenden van formulieren. |
| PointerLock | `40` | Deze vlag schakelt de Pointer Lock API uit. |
| Scripts | `80` | Deze vlag blokkeert de uitvoering van scripts. |
| AutomaticFeatures | `100` | Deze vlag blokkeert functies die automatisch worden geactiveerd, zoals het automatisch afspelen van een video of het automatisch focussen van een formulierelement. |
| Fullscreen | `200` | Deze vlag voorkomt dat inhoud de requestFullscreen()-methode gebruikt. |
| DocumentDomain | `400` | Deze vlag voorkomt dat inhoud de document.domain‑functie gebruikt om de effectieve script‑oorsprong te wijzigen. |
| Images | `800` | Deze vlag schakelt het laden van afbeeldingen uit. |

### Zie ook

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

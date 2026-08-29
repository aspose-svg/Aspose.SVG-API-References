---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGGraphicsElement GetScreenCTM-methode. Retourneert de transformatie‑matrix van de huidige gebruikers‑eenheden, d.w.z. na toepassing van het attribuut transform, indien aanwezig, op de pixel die de ouder‑user‑agent waarneemt. Voor weergave‑apparaten vertegenwoordigt dit idealiter een fysieke schermpixel. Voor andere apparaten of omgevingen waar de fysieke pixelgrootte niet bekend is, kan in plaats daarvan een algoritme dat lijkt op de CSS2-definitie van een pixel worden gebruikt. Merk op dat null wordt geretourneerd als dit element niet is gekoppeld aan de documentboom. Deze methode zou beter getiteld kunnen zijn als getClientCTM, maar de naam getScreenCTM wordt om historische redenen behouden."
type: docs
weight: 90
url: /nl/net/aspose.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

Retourneert de transformatie‑matrix van de huidige gebruikerseenheden (d.w.z. na toepassing van het ‘transform’-attribuut, indien aanwezig) naar de perceptie van een \"pixel\" door de bovenliggende user‑agent. Voor weergave‑apparaten vertegenwoordigt dit idealiter een fysiek scherm‑pixel. Voor andere apparaten of omgevingen waar fysieke pixelgroottes onbekend zijn, kan in plaats daarvan een algoritme worden gebruikt dat lijkt op de CSS2‑definitie van een \"pixel\". Merk op dat null wordt geretourneerd als dit element niet is gekoppeld aan de documentboom. Deze methode zou beter getiteld kunnen zijn als getClientCTM, maar de naam getScreenCTM wordt om historische redenen behouden.

```csharp
public SVGMatrix GetScreenCTM()
```

### Retourwaarde

Een SVGMatrix‑object dat de opgegeven transformatie‑matrix definieert.

### Zie ook

* class [SVGMatrix](../../../aspose.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

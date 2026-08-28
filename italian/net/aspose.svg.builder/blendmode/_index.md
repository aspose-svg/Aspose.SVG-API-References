---
title: "Enum BlendMode"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Enum Aspose.Svg.Builder.BlendMode. Specifica le modalità di fusione disponibili per combinare immagini o elementi in SVG"
type: docs
weight: 80
url: /it/net/aspose.svg.builder/blendmode/
---
## BlendMode enumeration

Specifica le modalità di fusione disponibili per combinare immagini o elementi in SVG.

```csharp
public enum BlendMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Normal | `0` | Visualizza l'immagine sorgente così com'è, senza alcuna fusione. |
| Multiply | `1` | Moltiplica i colori dell'immagine sorgente e dello sfondo. Il risultato è un'immagine più scura. |
| Screen | `2` | Rende più chiari i punti scuri dell'immagine sorgente lasciando invariati i punti chiari. |
| Overlay | `3` | Combina le modalità di fusione Moltiplica e Schermo per aumentare il contrasto. |
| Darken | `4` | Scurisce lo sfondo in base ai colori dell'immagine sorgente. |
| Lighten | `5` | Schiarisce lo sfondo in base ai colori dell'immagine sorgente. |
| ColorDodge | `6` | Illumina lo sfondo per riflettere l'immagine sorgente. |
| ColorBurn | `7` | Oscura lo sfondo per riflettere l'immagine sorgente. |
| HardLight | `8` | Crea un effetto luce dura basato sulla luminosità dell'immagine sorgente. |
| SoftLight | `9` | Crea un effetto luce soffusa basato sulla luminosità dell'immagine sorgente. |
| Difference | `10` | Evidenzia le differenze tra l'immagine sorgente e lo sfondo. |
| Exclusion | `11` | Crea un effetto simile a Difference, ma con contrasto più basso. |
| Hue | `12` | Utilizza la tinta dell'immagine sorgente combinata con la luminanza e la saturazione dello sfondo. |
| Saturation | `13` | Utilizza la saturazione dell'immagine sorgente combinata con la tinta e la luminanza dello sfondo. |
| Color | `14` | Utilizza la tinta e la saturazione dell'immagine sorgente combinata con la luminanza dello sfondo. |
| Luminosity | `15` | Utilizza la luminanza dell'immagine sorgente combinata con la tinta e la saturazione dello sfondo. |

## Osservazioni

Le modalità di fusione in SVG sono utilizzate per determinare come due livelli si fondono tra loro. Questa enum fornisce una varietà di opzioni che controllano come i colori dei livelli fusi si mescolano e producono diversi effetti visivi.

### Vedi anche

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

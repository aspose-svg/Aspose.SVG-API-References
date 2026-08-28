---
title: "FillRule Enum"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Aspose.Svg.Builder.FillRule enum. Specifica la regola per determinare quali parti di una forma sono interne o esterne nella grafica SVG"
type: docs
weight: 270
url: /it/net/aspose.svg.builder/fillrule/
---
## FillRule enumeration

Specifica la regola per determinare quali parti di una forma sono all'interno o all'esterno nella grafica SVG.

```csharp
public enum FillRule
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Nonzero | `0` | La regola di avvolgimento non zero: determina la "insideness" di un punto nella forma tracciando un raggio da quel punto all'infinito in qualsiasi direzione e contando il numero di segmenti di percorso della forma data che il raggio attraversa. Se questo numero è dispari, il punto è interno; se è pari, il punto è esterno. |
| Evenodd | `1` | La regola di avvolgimento pari-dispari: determina la "insideness" di un punto nella forma tracciando un raggio da quel punto all'infinito in qualsiasi direzione e contando il numero di segmenti di percorso della forma data che il raggio attraversa. Se questo numero è pari, il punto è esterno; se è dispari, il punto è interno. |

### Vedi anche

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

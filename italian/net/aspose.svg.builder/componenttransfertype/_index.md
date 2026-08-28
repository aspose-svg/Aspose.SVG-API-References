---
title: "Enumerazione ComponentTransferType"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Aspose.Svg.Builder.ComponentTransferType enum. Specifica il tipo di funzione di trasferimento del componente da applicare nella primitiva di filtro FeComponentTransfer di un SVG."
type: docs
weight: 170
url: /it/net/aspose.svg.builder/componenttransfertype/
---
## ComponentTransferType enumeration

Specifica il tipo di funzione di trasferimento del componente da applicare nella primitiva di filtro FeComponentTransfer di un SVG.

```csharp
public enum ComponentTransferType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Identity | `0` | Rappresenta nessuna modifica nel grafico di input. Questo è il tipo predefinito. |
| Table | `1` | Utilizza una tabella di ricerca per definire la funzione all'interno del filtro. |
| Discrete | `2` | Utilizza un insieme di valori discreti per definire la funzione nel filtro. |
| Linear | `3` | Definisce una trasformazione lineare del componente all'interno del filtro. |
| Gamma | `4` | Definisce una trasformazione di correzione gamma nel filtro. |

## Osservazioni

La primitiva di filtro FeComponentTransfer consente la manipolazione individuale dei componenti di colore (RGB e alfa) degli elementi grafici utilizzando diversi tipi di funzioni di trasferimento. Ogni tipo definisce un metodo distinto di calcolo per la trasformazione del componente di colore all'interno del filtro.

### Vedi anche

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

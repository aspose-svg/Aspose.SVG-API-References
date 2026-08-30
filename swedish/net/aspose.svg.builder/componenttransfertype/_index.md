---
title: "ComponentTransferType‑enum"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.ComponentTransferType‑enum. Anger typen av komponentöverföringsfunktion som ska tillämpas i FeComponentTransfer-filterprimitive för en SVG."
type: docs
weight: 170
url: /sv/net/aspose.svg.builder/componenttransfertype/
---
## ComponentTransferType enumeration

Anger vilken typ av komponentöverföringsfunktion som ska tillämpas i FeComponentTransfer-filterprimitivet i en SVG.

```csharp
public enum ComponentTransferType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Identity | `0` | Representerar ingen förändring i den ingående grafiken. Detta är standardtypen. |
| Table | `1` | Använder en uppslagstabell för att definiera funktionen i filtret. |
| Discrete | `2` | Använder en uppsättning diskreta värden för att definiera funktionen i filtret. |
| Linear | `3` | Definierar en linjär transformation av komponenten i filtret. |
| Gamma | `4` | Definierar en gamma‑korrektionstransformation i filtret. |

## Anmärkningar

FeComponentTransfer-filterprimitive möjliggör individuell manipulation av färgkomponenter (RGB och alfa) i grafikelement med olika typer av överföringsfunktioner. Varje typ definierar en särskild beräkningsmetod för färgkomponentens transformation i filtret.

### Se även

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

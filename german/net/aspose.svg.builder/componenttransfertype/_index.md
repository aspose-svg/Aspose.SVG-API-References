---
title: "ComponentTransferType Aufzählung"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.ComponentTransferType Aufzählung. Gibt den Typ der Komponentenübertragungsfunktion an, die im FeComponentTransfer-Filterprimitive eines SVG angewendet wird"
type: docs
weight: 170
url: /de/net/aspose.svg.builder/componenttransfertype/
---
## ComponentTransferType enumeration

Gibt den Typ der Komponenten-Transferfunktion an, die im FeComponentTransfer-Filterprimitive eines SVG angewendet wird.

```csharp
public enum ComponentTransferType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Identity | `0` | Stellt keine Änderung an der Eingabegrafik dar. Dies ist der Standardtyp. |
| Table | `1` | Verwendet eine Nachschlagetabelle, um die Funktion im Filter zu definieren. |
| Discrete | `2` | Verwendet eine Menge diskreter Werte, um die Funktion im Filter zu definieren. |
| Linear | `3` | Definiert eine lineare Transformation der Komponente im Filter. |
| Gamma | `4` | Definiert eine Gamma-Korrektur-Transformation im Filter. |

## Hinweise

Das FeComponentTransfer-Filterprimitive ermöglicht die individuelle Manipulation von Farbkomponenten (RGB und Alpha) von Grafikelementen mithilfe verschiedener Arten von Transferfunktionen. Jeder Typ definiert eine eigene Berechnungsmethode für die Farbkomponententransformation im Filter.

### Siehe auch

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

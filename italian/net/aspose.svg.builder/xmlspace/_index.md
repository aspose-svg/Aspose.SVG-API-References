---
title: "XmlSpace Enum"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Aspose.Svg.Builder.XmlSpace enum. Specifica come gli spazi bianchi all'interno degli elementi sono gestiti nei documenti XML"
type: docs
weight: 1980
url: /it/net/aspose.svg.builder/xmlspace/
---
## XmlSpace enumeration

Specifica come gli spazi bianchi all'interno degli elementi vengono gestiti nei documenti XML.

```csharp
public enum XmlSpace
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Default | `0` | Indica che gli spazi bianchi dovrebbero essere gestiti secondo il comportamento predefinito del processore XML, tipicamente normalizzando gli spazi bianchi rimuovendo interruzioni di linea e spazi extra. |
| Preserve | `1` | Indica che gli spazi bianchi dovrebbero essere preservati così come appaiono nel documento XML. Questo è utile per mantenere la formattazione del testo dove gli spazi bianchi sono significativi. |

## Osservazioni

L'attributo 'xml:space' in XML è usato per controllare se gli spazi bianchi all'interno degli elementi devono essere preservati o normalizzati. Questa enumerazione fornisce opzioni per impostare questo comportamento nei documenti XML e SVG.

### Vedi anche

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

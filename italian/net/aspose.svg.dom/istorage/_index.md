---
title: "Interfaccia IStorage"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Interfaccia Aspose.Svg.Dom.IStorage. Questa interfaccia dell'API Web Storage fornisce l'accesso alla sessione o allo storage locale di un dominio specifico. Vedi la specifica Web Storage https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs
weight: 3090
url: /it/net/aspose.svg.dom/istorage/
---
## IStorage interface

Questa interfaccia dell'API Web Storage fornisce l'accesso alla sessione o allo storage locale di un dominio specifico. Vedi la specifica Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```csharp
public interface IStorage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Length](../../aspose.svg.dom/istorage/length/) { get; } | Restituisce il numero di coppie chiave/valore. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clear](../../aspose.svg.dom/istorage/clear/)() | Rimuove tutte le coppie chiave/valore, se presenti. |
| [GetItem](../../aspose.svg.dom/istorage/getitem/)(*string*) | Restituisce il valore corrente associato alla chiave fornita, o null se la chiave fornita non esiste. |
| [Key](../../aspose.svg.dom/istorage/key/)(*long*) | Restituisce il nome della n‑esima chiave, o null se n è maggiore o uguale al numero di coppie chiave/valore. |
| [RemoveItem](../../aspose.svg.dom/istorage/removeitem/)(*string*) | Rimuove la coppia chiave/valore con la chiave fornita, se esiste una coppia chiave/valore con quella chiave. |
| [SetItem](../../aspose.svg.dom/istorage/setitem/)(*string, string*) | Imposta il valore della coppia identificata dalla chiave a value, creando una nuova coppia chiave/valore se in precedenza non ne esisteva una per la chiave. |

### Vedi anche

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

---
title: Interface IXPathResult
second_title: Riferimento API Aspose.SVG per .NET
description: Aspose.Svg.Dom.XPath.IXPathResult interfaccia. IlRisultato XPath interface rappresenta il risultato della valutazione di unespressione XPath 1.0 allinterno del contesto di un particolare nodo. Poiché la valutazione di unespressione XPath può portare a vari tipi di risultato questo oggetto consente di scoprire e manipolare il tipo e il valore del risultato.
type: docs
weight: 1350
url: /it/net/aspose.svg.dom.xpath/ixpathresult/
---
## IXPathResult interface

Il`Risultato XPath` interface rappresenta il risultato della valutazione di un'espressione XPath 1.0 all'interno del contesto di un particolare nodo. Poiché la valutazione di un'espressione XPath può portare a vari tipi di risultato, questo oggetto consente di scoprire e manipolare il tipo e il valore del risultato.

```csharp
public interface IXPathResult
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BooleanValue](../../aspose.svg.dom.xpath/ixpathresult/booleanvalue/) { get; } | Il valore di questo risultato booleano. |
| [InvalidIteratorState](../../aspose.svg.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | Indica che l'iteratore è diventato non valido. Vero se`resultType` è`UnorderedNodeIterator` digitare o`OrderedNodeIterator` type e il documento è stato modificato da quando è stato restituito questo risultato. |
| [NumberValue](../../aspose.svg.dom.xpath/ixpathresult/numbervalue/) { get; } | Il valore di questo risultato numerico. |
| [ResultType](../../aspose.svg.dom.xpath/ixpathresult/resulttype/) { get; } | Un codice che rappresenta il tipo di questo risultato, come definito da http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult [`XPathResultType`](../xpathresulttype/) enum. |
| [SingleNodeValue](../../aspose.svg.dom.xpath/ixpathresult/singlenodevalue/) { get; } | Il valore di questo singolo risultato del nodo, che può essere`nullo` . |
| [SnapshotLength](../../aspose.svg.dom.xpath/ixpathresult/snapshotlength/) { get; } | Il numero di nodi nello snapshot dei risultati. I valori validi per gli indici snapshotItem sono`0` A`snapshotLength-1` inclusi. |
| [StringValue](../../aspose.svg.dom.xpath/ixpathresult/stringvalue/) { get; } | Il valore di questa stringa result. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [IterateNext](../../aspose.svg.dom.xpath/ixpathresult/iteratenext/)() | Itera e restituisce il nodo successivo dal set di nodi o`nullo` se non ci sono più nodi. |
| [SnapshotItem](../../aspose.svg.dom.xpath/ixpathresult/snapshotitem/)(int) | Restituisce il`indice` esimo elemento nella raccolta di istantanee. Se`indice`è maggiore di o uguale al numero di nodi nell'elenco, questo metodo restituisce`nullo` . A differenza del risultato dell'iteratore , lo snapshot non diventa non valido, ma potrebbe non corrispondere al documento corrente se viene modificato. |

### Guarda anche

* spazio dei nomi [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assemblea [Aspose.SVG](../../)



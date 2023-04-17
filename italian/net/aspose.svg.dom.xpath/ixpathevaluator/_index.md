---
title: Interface IXPathEvaluator
second_title: Riferimento API Aspose.SVG per .NET
description: Aspose.Svg.Dom.XPath.IXPathEvaluator interfaccia. La valutazione delle espressioni XPath è fornita daIXPathEvaluator .
type: docs
weight: 1310
url: /it/net/aspose.svg.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

La valutazione delle espressioni XPath è fornita da`IXPathEvaluator` .

```csharp
public interface IXPathEvaluator
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CreateExpression](../../aspose.svg.dom.xpath/ixpathevaluator/createexpression/)(string, IXPathNSResolver) | Crea un'espressione XPath analizzata con spazi dei nomi risolti. Questo è utile quando un'espressione verrà riutilizzata in un'applicazione poiché rende possibile compilare la stringa dell'espressione in un formato interno più efficiente e pre-risolvere tutti i prefissi dello spazio dei nomi che ricorrono all'interno dell'espressione. |
| [CreateNSResolver](../../aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Adatta qualsiasi nodo DOM per risolvere gli spazi dei nomi in modo che un'espressione XPath possa essere facilmente valutata rispetto al contesto del nodo in cui è apparsa all'interno del documento. Questo adattatore funziona come il metodo DOM Level 3`lookupNamespaceURI` sui nodi nel risolvere il namespaceURI da un dato prefisso utilizzando le informazioni correnti disponibili nella gerarchia del nodo al momento viene chiamato lookupNamespaceURI, risolvendo anche correttamente il prefisso xml implicito. |
| [Evaluate](../../aspose.svg.dom.xpath/ixpathevaluator/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Valuta una stringa di espressione XPath e, se possibile, restituisce un risultato del tipo specificato. |

### Guarda anche

* spazio dei nomi [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assemblea [Aspose.SVG](../../)



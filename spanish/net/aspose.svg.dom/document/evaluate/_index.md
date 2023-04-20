---
title: Document.Evaluate
second_title: Referencia de API de Aspose.SVG para .NET
description: Document método. Evalúa una cadena de expresión XPath y devuelve un resultado del tipo especificado si es posible.
type: docs
weight: 950
url: /es/net/aspose.svg.dom/document/evaluate/
---
## Document.Evaluate method

Evalúa una cadena de expresión XPath y devuelve un resultado del tipo especificado si es posible.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| expression | String | La cadena de expresión XPath que se analizará y evaluará. |
| contextNode | Node | El contexto es un nodo de contexto para la evaluación de esta expresión XPath. |
| resolver | IXPathNSResolver | El resolutor permite la traducción de todos los prefijos, incluido el prefijo de espacio de nombres xml , dentro de la expresión XPath en URI de espacio de nombres apropiados. |
| type | XPathResultType | Si se especifica un tipo específico, el resultado se devolverá como el tipo correspondiente. |
| result | Object | El resultado especifica un objeto de resultado específico que este método puede reutilizar y devolver. |

### Valor_devuelto

El resultado de la evaluación de la expresión XPath.

### Ver también

* interface [IXPathResult](../../../aspose.svg.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.svg.dom.xpath/xpathresulttype/)
* class [Document](../)
* espacio de nombres [Aspose.Svg.Dom](../../document/)
* asamblea [Aspose.SVG](../../../)



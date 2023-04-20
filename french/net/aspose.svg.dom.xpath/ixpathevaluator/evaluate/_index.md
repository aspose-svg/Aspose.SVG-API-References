---
title: IXPathEvaluator.Evaluate
second_title: Référence de l'API Aspose.SVG pour .NET
description: IXPathEvaluator méthode. Évalue une chaîne dexpression XPath et renvoie un résultat du type spécifié si possible.
type: docs
weight: 30
url: /fr/net/aspose.svg.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Évalue une chaîne d'expression XPath et renvoie un résultat du type spécifié si possible.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| expression | String | La chaîne d'expression XPath à analyser et à évaluer. |
| contextNode | Node | Le`contexte` est le nœud de contexte pour l'évaluation de cette expression XPath . Si la[`IXPathEvaluator`](../) a été obtenu en jetant le [`Document`](../../../aspose.svg.dom/document/) alors cela doit appartenir au même document et doit être un [`Document`](../../../aspose.svg.dom/document/) ,[`Element`](../../../aspose.svg.dom/element/) ,[`Attr`](../../../aspose.svg.dom/attr/) ,[`Text`](../../../aspose.svg.dom/text/) , [`CDATASection`](../../../aspose.svg.dom/cdatasection/) ,[`Comment`](../../../aspose.svg.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/) , ouXPathNamespace nœud. Si le nœud de contexte est un[`Text`](../../../aspose.svg.dom/text/) ou un [`CDATASection`](../../../aspose.svg.dom/cdatasection/)alors le contexte est interprété comme le nœud de texte logique entier tel qu'il est vu par XPath, sauf si le nœud est vide, auquel cas il ne peut pas servir de contexte XPath. |
| resolver | IXPathNSResolver | Le`résolveur` permet la traduction de tous les préfixes, y compris le`XML` préfixe d'espace de noms, dans l'expression XPath dans les URI d'espace de noms appropriés. Si cela est spécifié comme`nul` , tout préfixe d'espace de noms dans l'expression entraînera dans[`DOMException`](../../../aspose.svg.dom/domexception/) être jeté avec le code`NAMESPACE_ERR`. |
| type | XPathResultType | Si un spécifique`taper` est spécifié, le résultat sera renvoyé sous la forme le type correspondant. Pour les résultats XPath 1.0, il doit s'agir de l'une des valeurs de [`XPathResultType`](../../xpathresulttype/) énumération. |
| result | Object | Le`résultat` spécifie un objet de résultat spécifique qui peut être réutilisé et renvoyé par cette méthode. Si cela est spécifié comme`nul`ou si l'implémentation ne réutilise le résultat spécifié, un nouvel objet de résultat sera construit et renvoyé. Pour les résultats XPath 1.0 , cet objet sera de type[`IXPathResult`](../../ixpathresult/). |

### Return_Value

Résultat de l'évaluation de l'expression XPath. Pour les résultats XPath 1.0, cet objet sera de type[`IXPathResult`](../../ixpathresult/).

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR : déclenché si l'expression n'est pas légale selon selon les règles de[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR : déclenché si le résultat ne peut pas être converti pour renvoyer le type spécifié . |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR : déclenché si l'expression contient des préfixes d'espace de noms qui ne peuvent pas être résolus par le spécifié[`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR : le nœud provient d'un document qui n'est pas pris en charge par ce[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR : le nœud n'est pas un type autorisé en tant que nœud de contexte XPath ou le type de demande n'est pas autorisé par cette[`IXPathEvaluator`](../). |

### Voir également

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* espace de noms [Aspose.Svg.Dom.XPath](../../ixpathevaluator/)
* Assemblée [Aspose.SVG](../../../)



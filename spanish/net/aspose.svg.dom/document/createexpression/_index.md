---
title: Document.CreateExpression
second_title: Referencia de API de Aspose.SVG para .NET
description: Document método. Crea una expresión XPath analizada con espacios de nombres resueltos. Esto es útil cuando se va a reutilizar una expresión en una aplicación ya que permite compilar la cadena de expresión en un formato interno más eficiente y preresolver todos los prefijos de espacio de nombres que se producen dentro de la expresión.
type: docs
weight: 890
url: /es/net/aspose.svg.dom/document/createexpression/
---
## Document.CreateExpression method

Crea una expresión XPath analizada con espacios de nombres resueltos. Esto es útil cuando se va a reutilizar una expresión en una aplicación, ya que permite compilar la cadena de expresión en un formato interno más eficiente y preresolver todos los prefijos de espacio de nombres que se producen dentro de la expresión.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| expression | String | La cadena de expresión XPath que se va a analizar. |
| resolver | IXPathNSResolver | El`resolver` permite la traducción de todos los prefijos, incluido el`xml` prefijo de espacio de nombres, dentro de la expresión XPath en URI de espacio de nombres apropiados. Si esto se especifica como`nulo` , cualquier prefijo de espacio de nombres dentro de la expresión dará como resultado[`DOMException`](../../domexception/) siendo arrojado con el código`ESPACIO DE NOMBRES_ERR`. |

### Valor_devuelto

La forma compilada de la expresión XPath.

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Se genera si la expresión no es legal de acuerdo con las reglas de la[`IXPathEvaluator`](../../../aspose.svg.dom.xpath/ixpathevaluator/). |
| [DOMException](../../domexception/) | NAMESPACE_ERR: se genera si la expresión contiene prefijos de espacio de nombres que no pueden ser resueltos por el especificado[`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/). |

### Ver también

* interface [IXPathExpression](../../../aspose.svg.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* espacio de nombres [Aspose.Svg.Dom](../../document/)
* asamblea [Aspose.SVG](../../../)



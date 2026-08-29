---
title: "Document.CreateExpression"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Document CreateExpression. Создаёт разобранное XPath‑выражение с разрешёнными пространствами имён. Это полезно, когда выражение будет переиспользоваться в приложении, поскольку позволяет скомпилировать строку выражения во более эффективную внутреннюю форму и предварительно разрешить все префиксы пространств имён, встречающиеся в выражении."
type: docs
weight: 890
url: /ru/net/aspose.svg.dom/document/createexpression/
---
## Document.CreateExpression method

Создаёт разобранное XPath‑выражение с разрешёнными пространствами имён. Это полезно, когда выражение будет переиспользоваться в приложении, поскольку позволяет компилировать строку выражения в более эффективную внутреннюю форму и предварительно разрешать все префиксы пространств имён, встречающиеся в выражении.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| expression | String | Строка XPath‑выражения, которую нужно разобрать. |
| resolver | IXPathNSResolver | Параметр `resolver` позволяет переводить все префиксы, включая префикс пространства имён `xml`, внутри XPath‑выражения в соответствующие URI пространств имён. Если он указан как `null`, любой префикс пространства имён внутри выражения приведёт к выбросу [`DOMException`](../../domexception/) с кодом `NAMESPACE_ERR`. |

### Возвращаемое значение

Скомпилированная форма XPath‑выражения.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Возникает, если выражение не является допустимым согласно правилам [`IXPathEvaluator`](../../../aspose.svg.dom.xpath/ixpathevaluator/). |
| [DOMException](../../domexception/) | NAMESPACE_ERR: Возникает, если выражение содержит префиксы пространств имён, которые не могут быть разрешены указанным [`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/). |

### См. также

* interface [IXPathExpression](../../../aspose.svg.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

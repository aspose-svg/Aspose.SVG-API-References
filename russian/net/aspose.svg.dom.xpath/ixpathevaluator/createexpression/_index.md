---
title: "IXPathEvaluator.CreateExpression"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод IXPathEvaluator CreateExpression. Создаёт разобранное XPath‑выражение с разрешёнными пространствами имён. Это полезно, когда выражение будет переиспользоваться в приложении, так как позволяет компилировать строку выражения во более эффективную внутреннюю форму и предварительно разрешать все префиксы пространств имён, встречающиеся в выражении."
type: docs
weight: 10
url: /ru/net/aspose.svg.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Создаёт разобранное XPath‑выражение с разрешёнными пространствами имён. Это полезно, когда выражение будет переиспользоваться в приложении, поскольку позволяет компилировать строку выражения в более эффективную внутреннюю форму и предварительно разрешать все префиксы пространств имён, встречающиеся в выражении.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| expression | String | Строка XPath‑выражения, которую нужно разобрать. |
| resolver | IXPathNSResolver | Параметр `resolver` позволяет переводить все префиксы, включая префикс пространства имён `xml`, внутри XPath‑выражения в соответствующие URI пространств имён. Если он указан как `null`, любой префикс пространства имён внутри выражения приведёт к выбросу [`DOMException`](../../../aspose.svg.dom/domexception/) с кодом `NAMESPACE_ERR`. |

### Возвращаемое значение

Скомпилированная форма XPath‑выражения.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR: вызывается, если выражение недопустимо согласно правилам [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR: вызывается, если выражение содержит префиксы пространств имён, которые не могут быть разрешены указанным [`IXPathNSResolver`](../../ixpathnsresolver/). |

### См. также

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)

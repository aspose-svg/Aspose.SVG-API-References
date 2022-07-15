---
title: CreateExpression
second_title: Справочник по Aspose.SVG для .NET API
description: Создает проанализированное выражение XPath с разрешенными пространствами имен. Это полезно  когда выражение будет повторно использоваться в приложении поскольку позволяет скомпилировать строку выражения в более эффективную внутреннюю форму и предварительно разрешить все встречающиеся префиксы пространств имен. внутри выражения.
type: docs
weight: 890
url: /ru/net/aspose.svg.dom/document/createexpression/
---
## Document.CreateExpression method

Создает проанализированное выражение XPath с разрешенными пространствами имен. Это полезно , когда выражение будет повторно использоваться в приложении, поскольку позволяет скомпилировать строку выражения в более эффективную внутреннюю форму и предварительно разрешить все встречающиеся префиксы пространств имен. внутри выражения.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| expression | String | Строка выражения XPath для анализа. |
| resolver | IXPathNSResolver | Преобразователь позволяет переводить все префиксы, включая` xml` префикс пространства имен, в выражении XPath в соответствующие URI пространства имен. Если это указано как` null` , любой префикс пространства имен в выражении приведет к тому, что[`DOMException`](../../domexception)будет@ бросил с кодом` NAMESPACE_ERR` . |

### Возвращаемое значение

Скомпилированная форма выражения XPath.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception) | INVALID_EXPRESSION_ERR: Возникает, если выражение не является допустимым в соответствии с правилами[`IXPathEvaluator`](../../../aspose.svg.dom.xpath/ixpathevaluator). |
| [DOMException](../../domexception) | NAMESPACE_ERR: Возникает, если выражение содержит префиксы пространств имен , которые не могут быть разрешены указанным[`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver). |

### Смотрите также

* interface [IXPathExpression](../../../aspose.svg.dom.xpath/ixpathexpression)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver)
* class [Document](../../document)
* пространство имен [Aspose.Svg.Dom](../../document)
* сборка [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
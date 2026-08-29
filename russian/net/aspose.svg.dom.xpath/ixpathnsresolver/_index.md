---
title: "IXPathNSResolver интерфейс"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.XPath.IXPathNSResolver интерфейс. Интерфейс XPathNSResolver позволяет строкам префиксов в выражении правильно связывать с строками namespaceURI. IXPathEvaluator может создать реализацию IXPathNSResolver из узла, либо интерфейс может быть реализован любым приложением."
type: docs
weight: 3330
url: /ru/net/aspose.svg.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

Интерфейс `XPathNSResolver` позволяет строкам `prefix` в выражении правильно связывать с строками `namespaceURI`. [`IXPathEvaluator`](../ixpathevaluator/) может создать реализацию `IXPathNSResolver` из узла, либо интерфейс может быть реализован любым приложением.

```csharp
public interface IXPathNSResolver
```

## Методы

| Имя | Описание |
| --- | --- |
| [LookupNamespaceURI](../../aspose.svg.dom.xpath/ixpathnsresolver/lookupnamespaceuri/)(*string*) | Найдите URI пространства имён, связанный с заданным префиксом пространства имён. Оценщик XPath никогда не должен вызывать это с аргументом `null` или пустым, потому что результат такого вызова не определён. |

### См. также

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)

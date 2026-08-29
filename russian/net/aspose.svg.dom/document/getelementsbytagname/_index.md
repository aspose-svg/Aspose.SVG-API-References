---
title: "Document.GetElementsByTagName"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Document GetElementsByTagName. Этот метод возвращает HTMLCollection элементов с указанным именем тега."
type: docs
weight: 980
url: /ru/net/aspose.svg.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

Этот метод возвращает [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) элементов с указанным именем тега.

Весь документ просматривается, включая корневой узел. Возвращаемый [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) является живым, то есть автоматически обновляется, чтобы оставаться синхронным с деревом DOM без необходимости повторного вызова этого метода.

```csharp
public HTMLCollection GetElementsByTagName(string tagname)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| tagname | String | Строка, представляющая имя элементов. Специальная строка "*" обозначает все элементы. |

### Возвращаемое значение

Живой [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) найденных элементов в порядке их появления в дереве.

## Замечания

Обратитесь к официальной [спецификации](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname).

### См. также

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

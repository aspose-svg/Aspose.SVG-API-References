---
title: "Document.GetElementsByTagNameNS"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Document GetElementsByTagNameNS. Возвращает список элементов с заданным именем тега, принадлежащих указанному пространству имен. Поиск выполняется по всему документу, включая корневой узел."
type: docs
weight: 990
url: /ru/net/aspose.svg.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

Возвращает список элементов с указанным именем тега, принадлежащих указанному пространству имён. Поиск производится по всему документу, включая корневой узел.

```csharp
public HTMLCollection GetElementsByTagNameNS(string namespaceURI, string localName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| namespaceURI | String | URI пространства имен элементов, которые нужно искать. |
| localName | String | Либо локальное имя искомых элементов, либо специальное значение *, которое соответствует всем элементам. |

### Возвращаемое значение

Живой [`NodeList`](../../../aspose.svg.collections/nodelist/) найденных элементов в порядке их появления в дереве.

## Замечания

Смотрите официальную [спецификацию](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens).

### См. также

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---
title: "Document.GetElementsByClassName"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Document GetElementsByClassName. Этот метод возвращает объект, похожий на массив, всех дочерних элементов, которые имеют все указанные имена классов"
type: docs
weight: 970
url: /ru/net/aspose.svg.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

Этот метод возвращает объект, похожий на массив, всех дочерних элементов, которые имеют все указанные имена классов.

При вызове на объекте документа производится поиск по всему документу, включая корневой узел. Вы также можете вызвать этот метод на любом элементе; он вернёт только элементы, которые являются потомками указанного корневого элемента с заданным именем(именами) класса.

```csharp
public HTMLCollection GetElementsByClassName(string classNames)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classNames | String | Строка, содержащая неупорядоченный набор уникальных токенов, разделённых пробелами, представляющих классы (имена классов) |

### Возвращаемое значение

Живая [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) найденных элементов.

## Замечания

Обратитесь к официальному [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname).

### См. также

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Aspose.SVG для .NET справочник API"
description: "Свойство INodeIterator PointerBeforeReferenceNode. Значение этого флага определяет, видны ли дочерние узлы узлов ссылок сущностей итератору. Если false, они и их потомки будут отклоняться. Обратите внимание, что это отклонение имеет приоритет над whatToShow и фильтром. Также обратите внимание, что в настоящее время это единственная ситуация, когда NodeIterators могут отклонять целое поддерево, а не пропускать отдельные узлы. Чтобы получить представление документа с развернутыми ссылками сущностей и не раскрывать сам узел ссылки сущности, используйте флаги whatToShow, чтобы скрыть узел ссылки сущности, и установите expandEntityReferences в true при создании итератора. Чтобы получить представление документа с узлами ссылок сущностей без их развертывания, используйте флаги whatToShow, чтобы показать узел ссылки сущности, и установите expandEntityReferences в false."
type: docs
weight: 10
url: /ru/net/aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

Значение этого флага определяет, видимы ли дочерние узлы ссылок на сущности для итератора. Если false, они и их потомки будут отклонены. Обратите внимание, что это отклонение имеет приоритет над whatToShow и фильтром. Также отметьте, что в настоящее время это единственная ситуация, когда NodeIterators могут отклонять целое поддерево, а не пропускать отдельные узлы. Чтобы получить представление документа с развернутыми ссылками на сущности и без раскрытия самого узла ссылки на сущность, используйте флаги whatToShow для скрытия узла ссылки на сущность и установите expandEntityReferences в true при создании итератора. Чтобы получить представление документа с узлами ссылок на сущности без их развертывания, используйте флаги whatToShow для отображения узла ссылки на сущность и установите expandEntityReferences в false.

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` если [expand entity references]; иначе, `false`.

### См. также

* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

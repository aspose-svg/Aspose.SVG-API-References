---
title: "Класс NodeFilter"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.Traversal.Filters.NodeFilter класс. Фильтры — это объекты, которые умеют отфильтровывать узлы."
type: docs
weight: 3210
url: /ru/net/aspose.svg.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Фильтры — это объекты, умеющие "отфильтровывать" узлы.

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Методы

| Имя | Описание |
| --- | --- |
| abstract [AcceptNode](../../aspose.svg.dom.traversal.filters/nodefilter/acceptnode/)(*[Node](../../aspose.svg.dom/node/)*) | Проверьте, видим ли указанный узел в логическом представлении TreeWalker или NodeIterator. Эта функция будет вызываться реализацией TreeWalker и NodeIterator; обычно она не вызывается напрямую из пользовательского кода. (Хотя вы можете вызвать её, если хотите использовать один и тот же фильтр для управления логикой вашего приложения.) |
| override [GetPlatformType](../../aspose.svg.dom.traversal.filters/nodefilter/getplatformtype/)() | Этот метод используется для получения типа объекта ECMAScript. |

## Поля

| Имя | Описание |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_accept/) | Принять узел. Навигационные методы, определённые для NodeIterator или TreeWalker, вернут этот узел. |
| const [FILTER_REJECT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_reject/) | Отклонить узел. Навигационные методы, определённые для NodeIterator или TreeWalker, не вернут этот узел. Для TreeWalker также будут отклонены дочерние узлы этого узла. NodeIterators рассматривают это как синоним FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.svg.dom.traversal.filters/nodefilter/filter_skip/) | Пропустить этот отдельный узел. Навигационные методы, определённые для NodeIterator или TreeWalker, не вернут этот узел. Для обоих, NodeIterator и TreeWalker, дочерние узлы этого узла всё равно будут учитываться. |
| const [SHOW_ALL](../../aspose.svg.dom.traversal.filters/nodefilter/show_all/) | Показать все узлы. |
| const [SHOW_ATTRIBUTE](../../aspose.svg.dom.traversal.filters/nodefilter/show_attribute/) | Показать узлы Attr. Это имеет смысл только при создании итератора или tree-walker с узлом-атрибутом в качестве корня; в этом случае атрибутный узел будет находиться в первой позиции итерации или обхода. Поскольку атрибуты никогда не являются дочерними узлами других узлов, они не появляются при обходе дерева документа. |
| const [SHOW_CDATA_SECTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_cdata_section/) | Показать узлы CDATASection. |
| const [SHOW_COMMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_comment/) | Показать узлы Comment. |
| const [SHOW_DOCUMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document/) | Показать узлы Document. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_fragment/) | Показать узлы DocumentFragment. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_type/) | Показать узлы DocumentType. |
| const [SHOW_ELEMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_element/) | Показать узлы Element. |
| const [SHOW_ENTITY](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity/) | Показать узлы Entity. Это имеет смысл только при создании итератора или обхода дерева с узлом Entity в качестве корня; в этом случае это означает, что узел Entity будет находиться в первой позиции обхода. Поскольку сущности не являются частью дерева документа, они не появляются при обходе дерева документа. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity_reference/) | Показать узлы EntityReference. |
| const [SHOW_NOTATION](../../aspose.svg.dom.traversal.filters/nodefilter/show_notation/) | Показать узлы Notation. Это имеет смысл только при создании итератора или обхода дерева с узлом Notation в качестве корня; в этом случае это означает, что узел Notation будет находиться в первой позиции обхода. Поскольку нотации не являются частью дерева документа, они не появляются при обходе дерева документа. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_processing_instruction/) | Показать узлы ProcessingInstruction. |
| const [SHOW_TEXT](../../aspose.svg.dom.traversal.filters/nodefilter/show_text/) | Показать узлы Text. |

### См. также

* class [DOMObject](../../aspose.svg.dom/domobject/)
* interface [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)
* namespace [Aspose.Svg.Dom.Traversal.Filters](../../aspose.svg.dom.traversal.filters/)
* assembly [Aspose.SVG](../../)

---
title: "Node Класс"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.Node класс. Интерфейс Node является основным типом данных для всей модели объектов Document. Он представляет отдельный узел в дереве документа."
type: docs
weight: 3140
url: /ru/net/aspose.svg.dom/node/
---
## Node class

Интерфейс Node является основным типом данных для всей модели Document Object Model. Он представляет отдельный узел в дереве документа.

```csharp
public abstract class Node : EventTarget, IXPathNSResolver
```

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | Возвращает абсолютный базовый URL документа, содержащего узел. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Возвращает живой [`NodeList`](../../aspose.svg.collections/nodelist/) дочерних узлов заданного элемента, где первый дочерний узел имеет индекс 0. Дочерние узлы включают элементы, текст и комментарии. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Возвращает первого дочернего узла в дереве, или null, если у узла нет дочерних элементов. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Возвращает последний дочерний узел. Если его родитель — элемент, то дочерний узел обычно является элементом, текстовым узлом или узлом комментария. Возвращает null, если нет дочерних элементов. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Возвращает локальную часть квалифицированного имени этого узла. Для узлов любого типа, кроме [`ELEMENT_NODE`](./element_node/) и [`ATTRIBUTE_NODE`](./attribute_node/), а также узлов, созданных методом уровня DOM 1, таким как [`CreateElement`](../document/createelement/), всегда возвращается null. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | Возвращает URI пространства имён элемента или null, если элемент не находится в пространстве имён. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Возвращает узел, непосредственно следующий за указанным, в массиве [`ChildNodes`](./childnodes/) их родителя, или возвращает null, если указанный узел является последним дочерним элементом в родительском элементе. |
| abstract [NodeName](../../aspose.svg.dom/node/nodename/) { get; } | Возвращает имя текущего узла в виде строки. |
| abstract [NodeType](../../aspose.svg.dom/node/nodetype/) { get; } | Код, представляющий тип базового объекта. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Возвращает или задаёт значение текущего узла. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Возвращает объект документа верхнего уровня узла. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Возвращает родительский [`Element`](../element/) DOM‑узла, или null, если у узла нет родителя или его родитель не является элементом DOM. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Возвращает родителя указанного узла в дереве DOM. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Возвращает префикс пространства имён указанного элемента или null, если префикс не указан. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Возвращает узел, непосредственно предшествующий указанному, в списке [`ChildNodes`](./childnodes/) его родителя, или null, если указанный узел является первым в этом списке. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | Представляет текстовое содержимое узла и его потомков. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*Node*) | Добавляет узел в конец списка дочерних элементов указанного родительского узла. Если переданный дочерний элемент является ссылкой на существующий узел в документе, [`AppendChild`](./appendchild/) перемещает его из текущего положения в новое (не требуется удалять узел из его родительского узла перед добавлением его к другому узлу). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/#clonenode)() | Возвращает дубликат узла, для которого был вызван этот метод. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/#clonenode_1)(*bool*) | Возвращает дубликат узла, для которого был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Отправляет событие Event указанному [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (синхронно) вызывая затронутые EventListeners в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправляемым вручную с помощью [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Возвращает логическое значение, указывающее, имеет ли данный `Node` дочерние узлы или нет. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*Node, Node*) | Вставляет узел перед существующим дочерним узлом child. Если child равен null, узел вставляется в конец списка дочерних узлов. Если child является объектом DocumentFragment, все его дочерние узлы вставляются в том же порядке перед child. Если дочерний узел уже находится в дереве, он сначала удаляется. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Этот метод проверяет, является ли указанный namespaceURI пространством имён по умолчанию. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*Node*) | Проверяет, равны ли два узла. Этот метод проверяет равенство узлов, а не их тождественность (т.е. являются ли два узла ссылками на один и тот же объект), что можно проверить с помощью Node.isSameNode(). Все узлы, которые тождественны, также будут равны, хотя обратное может быть неверным. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*Node*) | Метод является устаревшим псевдонимом для оператора строгого равенства ===. То есть он проверяет, являются ли два узла одинаковыми (иначе говоря, ссылаются ли они на один и тот же объект). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Ищет URI пространства имён, связанный с указанным префиксом, начиная с этого узла. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Ищет префикс, связанный с указанным URI пространства имён, начиная с этого узла. Объявления пространства имён по умолчанию игнорируются этим методом. См. Namespace Prefix Lookup для подробностей алгоритма, используемого этим методом. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Помещает все текстовые узлы на полной глубине поддерева под этим Node, включая узлы атрибутов, в "нормальную" форму, где только структура (например, элементы, комментарии, инструкции обработки, секции CDATA и ссылки на сущности) разделяет текстовые узлы, то есть нет соседних или пустых текстовых узлов. Это можно использовать, чтобы гарантировать, что представление DOM документа совпадает с тем, как оно выглядело бы после сохранения и повторной загрузки, и полезно, когда операции (например, поиск XPointer [XPointer]) зависят от определённой структуры дерева документа. Если параметр "normalize-characters" объекта DOMConfiguration, привязанного к Node.ownerDocument, имеет значение true, этот метод также полностью нормализует символы текстовых узлов. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*Node*) | Удаляет дочерний узел из DOM и возвращает удалённый узел. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Этот метод позволяет удалять обработчики событий из цели события. Если [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../eventtarget/) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Этот метод позволяет удалять обработчики событий из цели события. Если [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../eventtarget/) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Этот метод позволяет удалять обработчики событий из цели события. Если [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../eventtarget/) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*Node, Node*) | Заменяет дочерний узел oldChild узлом newChild в списке дочерних элементов и возвращает узел oldChild. Если newChild является объектом DocumentFragment, oldChild заменяется всеми дочерними элементами DocumentFragment, которые вставляются в том же порядке. Если newChild уже находится в дереве, он сначала удаляется. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [ATTRIBUTE_NODE](../../aspose.svg.dom/node/attribute_node/) | Узел атрибута |
| const [CDATA_SECTION_NODE](../../aspose.svg.dom/node/cdata_section_node/) | Узел секции CDATA |
| const [COMMENT_NODE](../../aspose.svg.dom/node/comment_node/) | Узел комментария |
| const [DOCUMENT_FRAGMENT_NODE](../../aspose.svg.dom/node/document_fragment_node/) | Узел фрагмента документа |
| const [DOCUMENT_NODE](../../aspose.svg.dom/node/document_node/) | Узел документа |
| const [DOCUMENT_TYPE_NODE](../../aspose.svg.dom/node/document_type_node/) | Узел типа документа |
| const [ELEMENT_NODE](../../aspose.svg.dom/node/element_node/) | Узел элемента |
| const [ENTITY_NODE](../../aspose.svg.dom/node/entity_node/) | Узел сущности |
| const [ENTITY_REFERENCE_NODE](../../aspose.svg.dom/node/entity_reference_node/) | Узел ссылки на сущность |
| const [NOTATION_NODE](../../aspose.svg.dom/node/notation_node/) | Узел нотации |
| const [PROCESSING_INSTRUCTION_NODE](../../aspose.svg.dom/node/processing_instruction_node/) | Узел инструкции обработки |
| const [TEXT_NODE](../../aspose.svg.dom/node/text_node/) | Текстовый узел |

### См. также

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

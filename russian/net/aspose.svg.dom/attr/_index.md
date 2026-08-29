---
title: "Класс Attr"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.Attr class. Интерфейс Attr представляет атрибут в объекте Element. Обычно допустимые значения атрибута определяются в схеме, связанной с документом."
type: docs
weight: 2350
url: /ru/net/aspose.svg.dom/attr/
---
## Attr class

Интерфейс Attr представляет атрибут в объекте Element. Обычно допустимые значения атрибута определяются в схеме, связанной с документом.

```csharp
public sealed class Attr : Node
```

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | Возвращает абсолютный базовый URL документа, содержащего узел. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Возвращает живой [`NodeList`](../../aspose.svg.collections/nodelist/) дочерних узлов заданного элемента, где первый дочерний узел имеет индекс 0. Дочерние узлы включают элементы, текст и комментарии. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Возвращает первого дочернего узла в дереве, или null, если у узла нет дочерних элементов. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Возвращает последний дочерний узел. Если его родитель — элемент, то дочерний узел обычно является элементом, текстовым узлом или узлом комментария. Возвращает null, если нет дочерних элементов. |
| override [LocalName](../../aspose.svg.dom/attr/localname/) { get; } | Возвращает локальную часть квалифицированного имени этого узла. Для узлов любого типа, кроме ELEMENT_NODE и ATTRIBUTE_NODE, а также узлов, созданных методом DOM Level 1, например Document.createElement(), всегда возвращается null. |
| [Name](../../aspose.svg.dom/attr/name/) { get; } | Возвращает имя этого атрибута. |
| override [NamespaceURI](../../aspose.svg.dom/attr/namespaceuri/) { get; } | URI пространства имён этого узла, или null, если оно не указано. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Возвращает узел, непосредственно следующий за указанным в массиве [`ChildNodes`](../node/childnodes/) его родителя, или возвращает null, если указанный узел является последним дочерним элементом в родительском элементе. |
| override [NodeName](../../aspose.svg.dom/attr/nodename/) { get; } | Имя этого узла, в зависимости от его типа. |
| override [NodeType](../../aspose.svg.dom/attr/nodetype/) { get; } | Код, представляющий тип базового объекта. |
| override [NodeValue](../../aspose.svg.dom/attr/nodevalue/) { get; set; } | Значение этого узла, в зависимости от его типа. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Возвращает объект документа верхнего уровня узла. |
| [OwnerElement](../../aspose.svg.dom/attr/ownerelement/) { get; } | Элемент‑узел, к которому прикреплен этот атрибут, или null, если атрибут не используется. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Возвращает родительский [`Element`](../element/) DOM‑узла, или null, если у узла нет родителя или его родитель не является элементом DOM. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Возвращает родителя указанного узла в дереве DOM. |
| override [Prefix](../../aspose.svg.dom/attr/prefix/) { get; } | Префикс пространства имён этого узла, или null, если он не указан. Когда он задан как null, попытка установить его не оказывает эффекта. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Возвращает узел, непосредственно предшествующий указанному в списке [`ChildNodes`](../node/childnodes/) его родителя, или null, если указанный узел является первым в этом списке. |
| [Specified](../../aspose.svg.dom/attr/specified/) { get; } | True, если этому атрибуту явно было присвоено значение в документе‑экземпляре, иначе false. |
| override [TextContent](../../aspose.svg.dom/attr/textcontent/) { get; set; } | Этот атрибут возвращает текстовое содержимое этого узла и его потомков. Когда он определён как null, попытка установить его не оказывает эффекта. При установке все возможные дочерние узлы этого узла удаляются, и если новая строка не пуста и не null, она заменяется одним текстовым узлом, содержащим эту строку. |
| [Value](../../aspose.svg.dom/attr/value/) { get; set; } | При получении значение атрибута возвращается как строка. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | Добавляет узел в конец списка дочерних узлов указанного родительского узла. Если переданный дочерний узел является ссылкой на существующий узел в документе, [`AppendChild`](../node/appendchild/) перемещает его из текущего положения в новое (не требуется предварительно удалять узел из его родителя перед добавлением к другому узлу). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Возвращает дубликат узла, для которого был вызван этот метод. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Возвращает дубликат узла, для которого был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Отправляет событие Event указанному [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (синхронно) вызывая затронутые EventListeners в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправляемым вручную с помощью [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Возвращает логическое значение, указывающее, имеет ли данный [`Node`](../node/) дочерние узлы. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | Вставляет узел перед существующим дочерним узлом child. Если child равен null, узел вставляется в конец списка дочерних узлов. Если child является объектом DocumentFragment, все его дочерние узлы вставляются в том же порядке перед child. Если дочерний узел уже находится в дереве, он сначала удаляется. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Этот метод проверяет, является ли указанный namespaceURI пространством имён по умолчанию. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | Проверяет, равны ли два узла. Этот метод проверяет равенство узлов, а не их тождественность (т.е. являются ли два узла ссылками на один и тот же объект), что можно проверить с помощью Node.isSameNode(). Все узлы, которые тождественны, также будут равны, хотя обратное может быть неверным. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | Метод является устаревшим псевдонимом для оператора строгого равенства ===. То есть он проверяет, являются ли два узла одинаковыми (иначе говоря, ссылаются ли они на один и тот же объект). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Ищет URI пространства имён, связанный с указанным префиксом, начиная с этого узла. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Ищет префикс, связанный с указанным URI пространства имён, начиная с этого узла. Объявления пространства имён по умолчанию игнорируются этим методом. См. Namespace Prefix Lookup для подробностей алгоритма, используемого этим методом. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Помещает все текстовые узлы на полной глубине поддерева под этим Node, включая узлы атрибутов, в "нормальную" форму, где только структура (например, элементы, комментарии, инструкции обработки, секции CDATA и ссылки на сущности) разделяет текстовые узлы, то есть нет соседних или пустых текстовых узлов. Это можно использовать, чтобы гарантировать, что представление DOM документа совпадает с тем, как оно выглядело бы после сохранения и повторной загрузки, и полезно, когда операции (например, поиск XPointer [XPointer]) зависят от определённой структуры дерева документа. Если параметр "normalize-characters" объекта DOMConfiguration, привязанного к Node.ownerDocument, имеет значение true, этот метод также полностью нормализует символы текстовых узлов. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | Удаляет дочерний узел из DOM и возвращает удалённый узел. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Этот метод позволяет удалять обработчики событий из цели события. Если [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../eventtarget/) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Этот метод позволяет удалять обработчики событий из цели события. Если [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../eventtarget/) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Этот метод позволяет удалять обработчики событий из цели события. Если [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../eventtarget/) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | Заменяет дочерний узел oldChild узлом newChild в списке дочерних элементов и возвращает узел oldChild. Если newChild является объектом DocumentFragment, oldChild заменяется всеми дочерними элементами DocumentFragment, которые вставляются в том же порядке. Если newChild уже находится в дереве, он сначала удаляется. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

### См. также

* class [Node](../node/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

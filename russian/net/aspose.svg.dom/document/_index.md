---
title: "Класс Document"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Dom.Document. Document представляет собой весь документ HTML, XML или SVG. Концептуально это корень дерева документа и предоставляет основной доступ к данным документа."
type: docs
weight: 2810
url: /ru/net/aspose.svg.dom/document/
---
## Document class

Document представляет весь документ HTML, XML или SVG. Концептуально это корень дерева документа и обеспечивает основной доступ к данным документа.

```csharp
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Свойства

| Имя | Описание |
| --- | --- |
| override [BaseURI](../../aspose.svg.dom/document/baseuri/) { get; } | Абсолютный базовый URI этого узла или null, если реализация не смогла получить абсолютный URI. |
| [CharacterSet](../../aspose.svg.dom/document/characterset/) { get; } | Получает кодировку документа. |
| [Charset](../../aspose.svg.dom/document/charset/) { get; } | Получает кодировку документа. |
| [ChildElementCount](../../aspose.svg.dom/document/childelementcount/) { get; } | Возвращает текущее количество узлов-элементов, являющихся дочерними для этого элемента. 0, если у этого элемента нет дочерних узлов типа nodeType 1. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Возвращает живой [`NodeList`](../../aspose.svg.collections/nodelist/) дочерних узлов заданного элемента, где первый дочерний узел имеет индекс 0. Дочерние узлы включают элементы, текст и комментарии. |
| [Children](../../aspose.svg.dom/document/children/) { get; } | Возвращает дочерние элементы. |
| [ContentType](../../aspose.svg.dom/document/contenttype/) { get; } | Получает тип содержимого документа. |
| [Context](../../aspose.svg.dom/document/context/) { get; } | Получает текущий контекст просмотра. |
| [DefaultView](../../aspose.svg.dom/document/defaultview/) { get; } | IDL-атрибут defaultView интерфейса Document при получении должен возвращать объект WindowProxy контекста просмотра этого Document, если у этого Document есть связанный контекст просмотра, иначе null. |
| [Doctype](../../aspose.svg.dom/document/doctype/) { get; } | Объявление типа документа (Document Type Declaration), связанное с этим документом. |
| [DocumentElement](../../aspose.svg.dom/document/documentelement/) { get; } | Это удобный атрибут, позволяющий прямой доступ к дочернему узлу, являющемуся элементом документа. |
| [DocumentURI](../../aspose.svg.dom/document/documenturi/) { get; } | Расположение документа или null, если неопределено или если Document был создан с помощью DOMImplementation.createDocument. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Возвращает первого дочернего узла в дереве, или null, если у узла нет дочерних элементов. |
| [FirstElementChild](../../aspose.svg.dom/document/firstelementchild/) { get; } | Возвращает первый дочерний узел-элемент этого элемента. null, если у этого элемента нет дочерних элементов. |
| [Implementation](../../aspose.svg.dom/document/implementation/) { get; } | Объект DOMImplementation, который обрабатывает этот документ. |
| [InputEncoding](../../aspose.svg.dom/document/inputencoding/) { get; } | Получает кодировку документа. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Возвращает последний дочерний узел. Если его родитель — элемент, то дочерний узел обычно является элементом, текстовым узлом или узлом комментария. Возвращает null, если нет дочерних элементов. |
| [LastElementChild](../../aspose.svg.dom/document/lastelementchild/) { get; } | Возвращает последний дочерний элементный узел этого элемента. null, если у этого элемента нет дочерних элементов. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Возвращает локальную часть квалифицированного имени этого узла. Для узлов любого типа, кроме [`ELEMENT_NODE`](../node/element_node/) и [`ATTRIBUTE_NODE`](../node/attribute_node/) и узлов, созданных методом уровня DOM 1, таким как [`CreateElement`](./createelement/), это всегда null. |
| [Location](../../aspose.svg.dom/document/location/) { get; } | Расположение документа. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | Возвращает URI пространства имён элемента или null, если элемент не находится в пространстве имён. |
| [NextElementSibling](../../aspose.svg.dom/document/nextelementsibling/) { get; } | Возвращает следующий соседний элементный узел этого элемента. null, если у этого элемента нет соседних элементных узлов, идущих после него в дереве документа. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Возвращает узел, непосредственно следующий за указанным в массиве [`ChildNodes`](../node/childnodes/) его родителя, или возвращает null, если указанный узел является последним дочерним элементом в родительском элементе. |
| override [NodeName](../../aspose.svg.dom/document/nodename/) { get; } | Имя этого узла, в зависимости от его типа. |
| override [NodeType](../../aspose.svg.dom/document/nodetype/) { get; } | Код, представляющий тип базового объекта. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Возвращает или задаёт значение текущего узла. |
| [Origin](../../aspose.svg.dom/document/origin/) { get; } | Получает источник документа. |
| override [OwnerDocument](../../aspose.svg.dom/document/ownerdocument/) { get; } | Получает документ‑владельца. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Возвращает родительский [`Element`](../element/) DOM‑узла, или null, если у узла нет родителя или его родитель не является элементом DOM. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Возвращает родителя указанного узла в дереве DOM. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Возвращает префикс пространства имён указанного элемента или null, если префикс не указан. |
| [PreviousElementSibling](../../aspose.svg.dom/document/previouselementsibling/) { get; } | Возвращает предыдущий соседний элементный узел этого элемента. null, если у этого элемента нет соседних элементных узлов, идущих перед ним в дереве документа. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Возвращает узел, непосредственно предшествующий указанному в списке [`ChildNodes`](../node/childnodes/) его родителя, или null, если указанный узел является первым в этом списке. |
| [ReadyState](../../aspose.svg.dom/document/readystate/) { get; } | Возвращает готовность документа. "loading" — пока документ загружается, "interactive" — после завершения разбора, но пока загружаются подресурсы, и "complete" — после полной загрузки. |
| [StrictErrorChecking](../../aspose.svg.dom/document/stricterrorchecking/) { get; set; } | Атрибут, указывающий, применяется ли проверка ошибок. Когда установлен в false, реализация может не проверять каждый возможный случай ошибки, обычно определённый для операций DOM, и не генерировать DOMException при операциях DOM или сообщать об ошибках при использовании Document.normalizeDocument(). В случае ошибки поведение неопределено. По умолчанию этот атрибут имеет значение true. |
| [StyleSheets](../../aspose.svg.dom/document/stylesheets/) { get; } | Список, содержащий все таблицы стилей, явно подключённые или встроенные в документ. Для HTML‑документов это включает внешние таблицы стилей, подключённые через элемент HTML LINK, и встроенные элементы STYLE. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | Представляет текстовое содержимое узла и его потомков. |
| [XmlStandalone](../../aspose.svg.dom/document/xmlstandalone/) { get; set; } | Атрибут, указывающий, как часть декларации XML, является ли документ автономным. Если не указано, значение false. |
| [XmlVersion](../../aspose.svg.dom/document/xmlversion/) { get; set; } | Атрибут, указывающий, как часть декларации XML, номер версии этого документа. Если декларации нет и документ поддерживает функцию "XML", значение равно "1.0". Если документ не поддерживает функцию "XML", значение всегда null. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | Добавляет узел в конец списка дочерних узлов указанного родительского узла. Если переданный дочерний узел является ссылкой на существующий узел в документе, [`AppendChild`](../node/appendchild/) перемещает его из текущего положения в новое (не требуется предварительно удалять узел из его родителя перед добавлением к другому узлу). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Возвращает дубликат узла, для которого был вызван этот метод. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Возвращает дубликат узла, для которого был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [CreateAttribute](../../aspose.svg.dom/document/createattribute/)(*string*) | Этот метод создаёт новый узел‑атрибут и возвращает его. Созданный объект является узлом, реализующим класс [`Attr`](../attr/). DOM не ограничивает, какие типы атрибутов могут быть добавлены к конкретному элементу таким способом. |
| [CreateAttributeNS](../../aspose.svg.dom/document/createattributens/)(*string, string*) | Этот метод создаёт новый узел‑атрибут и возвращает его. Созданный объект является узлом, реализующим класс [`Attr`](../attr/). DOM не ограничивает, какие типы атрибутов могут быть добавлены к конкретному элементу таким способом. |
| [CreateCDATASection](../../aspose.svg.dom/document/createcdatasection/)(*string*) | Создаёт узел CDATASection, значение которого равно указанной строке. |
| [CreateComment](../../aspose.svg.dom/document/createcomment/)(*string*) | Создаёт узел Comment, используя указанную строку. |
| [CreateDocumentFragment](../../aspose.svg.dom/document/createdocumentfragment/)() | Создаёт новый пустой [`DocumentFragment`](../documentfragment/), в который можно добавлять узлы DOM для построения offscreen‑дерева DOM. |
| [CreateDocumentType](../../aspose.svg.dom/document/createdocumenttype/)(*string, string, string, string*) | Метод возвращает объект [`DocumentType`](../documenttype/), который можно использовать с [`CreateDocument`](../idomimplementation/createdocument/) при создании документа или вставить в документ с помощью методов, таких как [`InsertBefore`](../node/insertbefore/) или [`ReplaceChild`](../node/replacechild/). |
| [CreateElement](../../aspose.svg.dom/document/createelement/)(*string*) | Создаёт HTML‑элемент, указанный в localName, или HTMLUnknownElement, если localName не распознан. |
| [CreateElementNS](../../aspose.svg.dom/document/createelementns/)(*string, string*) | Создаёт элемент с заданным квалифицированным именем и URI пространства имён. |
| [CreateEntityReference](../../aspose.svg.dom/document/createentityreference/)(*string*) | Создаёт объект EntityReference. Кроме того, если ссылка на сущность известна, список дочерних узлов узла EntityReference будет таким же, как у соответствующего узла Entity. |
| [CreateEvent](../../aspose.svg.dom/document/createevent/)(*string*) | Создаёт [`Event`](../../aspose.svg.dom.events/event/) типа, поддерживаемого реализацией. |
| [CreateExpression](../../aspose.svg.dom/document/createexpression/)(*string, [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/)*) | Создаёт разобранное XPath‑выражение с разрешёнными пространствами имён. Это полезно, когда выражение будет переиспользоваться в приложении, поскольку позволяет компилировать строку выражения в более эффективную внутреннюю форму и предварительно разрешать все префиксы пространств имён, встречающиеся в выражении. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator)(*[Node](../node/)*) | Создаёт новый NodeIterator для поддерева, корнем которого является указанный узел. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_1)(*[Node](../node/), long*) | Создаёт новый NodeIterator для поддерева, корнем которого является указанный узел. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_2)(*[Node](../node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | Создаёт новый NodeIterator для поддерева, корнем которого является указанный узел. |
| [CreateNSResolver](../../aspose.svg.dom/document/creatensresolver/)(*[Node](../node/)*) | Адаптирует любой DOM‑узел для разрешения пространств имён, чтобы XPath‑выражение можно было легко вычислять относительно контекста узла, где оно появилось в документе. Этот адаптер работает как метод DOM Level 3 `lookupNamespaceURI` у узлов, разрешая namespaceURI из заданного префикса, используя текущую информацию, доступную в иерархии узла в момент вызова lookupNamespaceURI, а также корректно разрешая неявный префикс xml. |
| [CreateProcessingInstruction](../../aspose.svg.dom/document/createprocessinginstruction/)(*string, string*) | Создаёт узел ProcessingInstruction, используя указанные строки имени и данных. |
| [CreateTextNode](../../aspose.svg.dom/document/createtextnode/)(*string*) | Создаёт узел Text, используя указанную строку. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker)(*[Node](../node/)*) | Создайте новый TreeWalker над поддеревом, корневым в указанном узле. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_1)(*[Node](../node/), long*) | Создайте новый TreeWalker над поддеревом, корневым в указанном узле. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_2)(*[Node](../node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | Создайте новый TreeWalker над поддеревом, корневым в указанном узле. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Отправляет событие Event указанному [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (синхронно) вызывая затронутые EventListeners в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправляемым вручную с помощью [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [Evaluate](../../aspose.svg.dom/document/evaluate/)(*string, [Node](../node/), [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/), [XPathResultType](../../aspose.svg.dom.xpath/xpathresulttype/), object*) | Выполняет оценку строки XPath‑выражения и возвращает результат указанного типа, если это возможно. |
| [GetElementById](../../aspose.svg.dom/document/getelementbyid/)(*string*) | Этот метод возвращает объект [`Element`](../element/), представляющий элемент, у которого свойство id совпадает с указанной строкой. Поскольку идентификаторы элементов должны быть уникальными, если они указаны, они являются удобным способом быстро получить доступ к конкретному элементу. |
| [GetElementsByClassName](../../aspose.svg.dom/document/getelementsbyclassname/)(*string*) | Этот метод возвращает объект, похожий на массив, всех дочерних элементов, которые имеют все указанные имена классов. |
| [GetElementsByTagName](../../aspose.svg.dom/document/getelementsbytagname/)(*string*) | Этот метод возвращает [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) элементов с указанным именем тега. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/document/getelementsbytagnamens/)(*string, string*) | Возвращает список элементов с указанным именем тега, принадлежащих указанному пространству имён. Поиск производится по всему документу, включая корневой узел. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Возвращает логическое значение, указывающее, имеет ли данный [`Node`](../node/) дочерние узлы. |
| [ImportNode](../../aspose.svg.dom/document/importnode/)(*[Node](../node/), bool*) | Импортирует узел из другого документа в текущий документ, не изменяя и не удаляя исходный узел из оригинального документа; этот метод создаёт новую копию исходного узла. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | Вставляет узел перед существующим дочерним узлом child. Если child равен null, узел вставляется в конец списка дочерних узлов. Если child является объектом DocumentFragment, все его дочерние узлы вставляются в том же порядке перед child. Если дочерний узел уже находится в дереве, он сначала удаляется. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Этот метод проверяет, является ли указанный namespaceURI пространством имён по умолчанию. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | Проверяет, равны ли два узла. Этот метод проверяет равенство узлов, а не их тождественность (т.е. являются ли два узла ссылками на один и тот же объект), что можно проверить с помощью Node.isSameNode(). Все узлы, которые тождественны, также будут равны, хотя обратное может быть неверным. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | Метод является устаревшим псевдонимом для оператора строгого равенства ===. То есть он проверяет, являются ли два узла одинаковыми (иначе говоря, ссылаются ли они на один и тот же объект). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Ищет URI пространства имён, связанный с указанным префиксом, начиная с этого узла. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Ищет префикс, связанный с указанным URI пространства имён, начиная с этого узла. Объявления пространства имён по умолчанию игнорируются этим методом. См. Namespace Prefix Lookup для подробностей алгоритма, используемого этим методом. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate)(*[RequestMessage](../../aspose.svg.net/requestmessage/)*) | Загружает документ на основе указанного объекта запроса, заменяя предыдущее содержимое. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_8)(*string*) | Загружает документ по указанному унифицированному указателю ресурса (URL) в текущий экземпляр, заменяя предыдущее содержимое. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_2)(*[Url](../../aspose.svg/url/)*) | Загружает документ по указанному унифицированному указателю ресурса (URL) в текущий экземпляр, заменяя предыдущее содержимое. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_1)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | Загружает документ на основе указанного объекта запроса, заменяя предыдущее содержимое. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_6)(*Stream, string*) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. Загрузка документа начинается с текущей позиции в потоке. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_4)(*Stream, [Url](../../aspose.svg/url/)*) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. Загрузка документа начинается с текущей позиции в потоке. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_13)(*string, CancellationToken*) | Загружает документ по указанному унифицированному указателю ресурса (URL) в текущий экземпляр, заменяя предыдущее содержимое. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_11)(*string, string*) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_9)(*string, [Url](../../aspose.svg/url/)*) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_3)(*[Url](../../aspose.svg/url/), CancellationToken*) | Загружает документ по указанному унифицированному указателю ресурса (URL) в текущий экземпляр, заменяя предыдущее содержимое. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_7)(*Stream, string, CancellationToken*) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. Загрузка документа начинается с текущей позиции в потоке. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_5)(*Stream, [Url](../../aspose.svg/url/), CancellationToken*) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. Загрузка документа начинается с текущей позиции в потоке. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_12)(*string, string, CancellationToken*) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_10)(*string, [Url](../../aspose.svg/url/), CancellationToken*) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | Асинхронно загружает документ на основе указанного объекта запроса. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_6)(*string, CancellationToken*) | Асинхронно загружает документ по указанному унифицированному указателю ресурса (URL) в текущий экземпляр. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_1)(*[Url](../../aspose.svg/url/), CancellationToken*) | Асинхронно загружает документ по указанному унифицированному указателю ресурса (URL) в текущий экземпляр. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_3)(*Stream, string, CancellationToken*) | Асинхронно загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_2)(*Stream, [Url](../../aspose.svg/url/), CancellationToken*) | Асинхронно загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_5)(*string, string, CancellationToken*) | Асинхронно загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_4)(*string, [Url](../../aspose.svg/url/), CancellationToken*) | Асинхронно загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Помещает все текстовые узлы на полной глубине поддерева под этим Node, включая узлы атрибутов, в "нормальную" форму, где только структура (например, элементы, комментарии, инструкции обработки, секции CDATA и ссылки на сущности) разделяет текстовые узлы, то есть нет соседних или пустых текстовых узлов. Это можно использовать, чтобы гарантировать, что представление DOM документа совпадает с тем, как оно выглядело бы после сохранения и повторной загрузки, и полезно, когда операции (например, поиск XPointer [XPointer]) зависят от определённой структуры дерева документа. Если параметр "normalize-characters" объекта DOMConfiguration, привязанного к Node.ownerDocument, имеет значение true, этот метод также полностью нормализует символы текстовых узлов. |
| [QuerySelector](../../aspose.svg.dom/document/queryselector/)(*string*) | Возвращает первый Element в документе, который соответствует селектору |
| [QuerySelectorAll](../../aspose.svg.dom/document/queryselectorall/)(*string*) | Возвращает NodeList всех Elements в документе, которые соответствуют селектору |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | Удаляет дочерний узел из DOM и возвращает удалённый узел. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Этот метод позволяет удалять обработчики событий из цели события. Если [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../eventtarget/) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Этот метод позволяет удалять обработчики событий из цели события. Если [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../eventtarget/) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Этот метод позволяет удалять обработчики событий из цели события. Если [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../eventtarget/) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| virtual [RenderTo](../../aspose.svg.dom/document/renderto/)(*[IDevice](../../aspose.svg.rendering/idevice/)*) | Этот метод используется для рендеринга содержимого текущего документа на указанное графическое устройство. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | Заменяет дочерний узел oldChild узлом newChild в списке дочерних элементов и возвращает узел oldChild. Если newChild является объектом DocumentFragment, oldChild заменяется всеми дочерними элементами DocumentFragment, которые вставляются в том же порядке. Если newChild уже находится в дереве, он сначала удаляется. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Возвращает строку, представляющую этот экземпляр. |
| [Write](../../aspose.svg.dom/document/write/)(*params string[]*) | Запишите строку текста в поток документа, открытый функцией open(). Обратите внимание, что функция создаст документ, который не обязательно управляется DTD, и поэтому может привести к недопустимому результату в контексте документа. |
| [WriteLn](../../aspose.svg.dom/document/writeln/)(*params string[]*) | Запишите строку текста, за которой следует символ новой строки, в поток документа, открытый функцией open(). Обратите внимание, что функция создаст документ, который не обязательно управляется DTD, и поэтому может привести к недопустимому результату в контексте документа. |

## События

| Имя | Описание |
| --- | --- |
| event [OnAbort](../../aspose.svg.dom/document/onabort/) | Получает или задаёт обработчик события OnAbort. |
| event [OnBlur](../../aspose.svg.dom/document/onblur/) | Получает или задаёт обработчик события OnBlur. |
| event [OnCancel](../../aspose.svg.dom/document/oncancel/) | Получает или задаёт обработчик события OnCancel. |
| event [OnCanplay](../../aspose.svg.dom/document/oncanplay/) | Получает или задаёт обработчик события OnCanplay. |
| event [OnCanPlayThrough](../../aspose.svg.dom/document/oncanplaythrough/) | Получает или задаёт обработчик события OnCanPlayThrough. |
| event [OnChange](../../aspose.svg.dom/document/onchange/) | Получает или задаёт обработчик события OnChange. |
| event [OnClick](../../aspose.svg.dom/document/onclick/) | Получает или задаёт обработчик события OnClick. |
| event [OnCueChange](../../aspose.svg.dom/document/oncuechange/) | Получает или задаёт обработчик события OnCueChange. |
| event [OnDblClick](../../aspose.svg.dom/document/ondblclick/) | Получает или задаёт обработчик события OnDblClick. |
| event [OnDurationChange](../../aspose.svg.dom/document/ondurationchange/) | Получает или задаёт обработчик события OnDurationChange. |
| event [OnEmptied](../../aspose.svg.dom/document/onemptied/) | Получает или задаёт обработчик события OnEmptied. |
| event [OnEnded](../../aspose.svg.dom/document/onended/) | Получает или задаёт обработчик события OnEnded. |
| event [OnError](../../aspose.svg.dom/document/onerror/) | Получает или задаёт обработчик события OnError. |
| event [OnFocus](../../aspose.svg.dom/document/onfocus/) | Получает или задает обработчик события OnFocus. |
| event [OnInput](../../aspose.svg.dom/document/oninput/) | Получает или задает обработчик события OnInput. |
| event [OnInvalid](../../aspose.svg.dom/document/oninvalid/) | Получает или задает обработчик события OnInvalid. |
| event [OnKeyDown](../../aspose.svg.dom/document/onkeydown/) | Получает или задает обработчик события OnKeyDown. |
| event [OnKeyPress](../../aspose.svg.dom/document/onkeypress/) | Получает или задает обработчик события OnKeyPress. |
| event [OnKeyUp](../../aspose.svg.dom/document/onkeyup/) | Получает или задает обработчик события OnKeyUp. |
| event [OnLoad](../../aspose.svg.dom/document/onload/) | Получает или задает обработчик события OnLoad. |
| event [OnLoadedData](../../aspose.svg.dom/document/onloadeddata/) | Получает или задает обработчик события OnLoadedData. |
| event [OnLoadedMetadata](../../aspose.svg.dom/document/onloadedmetadata/) | Получает или задает обработчик события OnLoadedMetadata. |
| event [OnLoadStart](../../aspose.svg.dom/document/onloadstart/) | Получает или задает обработчик события OnLoadStart. |
| event [OnMouseDown](../../aspose.svg.dom/document/onmousedown/) | Получает или задает обработчик события OnMouseDown. |
| event [OnMouseEnter](../../aspose.svg.dom/document/onmouseenter/) | Получает или задает обработчик события OnMouseEnter. |
| event [OnMouseLeave](../../aspose.svg.dom/document/onmouseleave/) | Получает или задает обработчик события OnMouseLeave. |
| event [OnMouseMove](../../aspose.svg.dom/document/onmousemove/) | Получает или задает обработчик события OnMouseMove. |
| event [OnMouseOut](../../aspose.svg.dom/document/onmouseout/) | Получает или задает обработчик события OnMouseOut. |
| event [OnMouseOver](../../aspose.svg.dom/document/onmouseover/) | Получает или задает обработчик события OnMouseOver. |
| event [OnMouseUp](../../aspose.svg.dom/document/onmouseup/) | Получает или задает обработчик события OnMouseUp. |
| event [OnMouseWheel](../../aspose.svg.dom/document/onmousewheel/) | Получает или задает обработчик события OnMouseWheel. |
| event [OnPause](../../aspose.svg.dom/document/onpause/) | Получает или задает обработчик события OnPause. |
| event [OnPlay](../../aspose.svg.dom/document/onplay/) | Получает или задает обработчик события OnPlay. |
| event [OnPlaying](../../aspose.svg.dom/document/onplaying/) | Получает или задает обработчик события OnPlaying. |
| event [OnProgress](../../aspose.svg.dom/document/onprogress/) | Получает или задает обработчик события OnProgress. |
| event [OnRateChange](../../aspose.svg.dom/document/onratechange/) | Получает или задает обработчик события OnRateChange. |
| event [OnReadyStateChange](../../aspose.svg.dom/document/onreadystatechange/) | Получает или задаёт обработчик события OnReadyStateChange. |
| event [OnReset](../../aspose.svg.dom/document/onreset/) | Получает или задает обработчик события OnReset. |
| event [OnResize](../../aspose.svg.dom/document/onresize/) | Получает или задает обработчик события OnResize. |
| event [OnScroll](../../aspose.svg.dom/document/onscroll/) | Получает или задает обработчик события для события OnScroll. |
| event [OnSeeked](../../aspose.svg.dom/document/onseeked/) | Получает или задает обработчик события для события OnSeeked. |
| event [OnSeeking](../../aspose.svg.dom/document/onseeking/) | Получает или задает обработчик события для события OnSeeking. |
| event [OnSelect](../../aspose.svg.dom/document/onselect/) | Получает или задает обработчик события для события OnSelect. |
| event [OnShow](../../aspose.svg.dom/document/onshow/) | Получает или задает обработчик события для события OnShow. |
| event [OnStalled](../../aspose.svg.dom/document/onstalled/) | Получает или задает обработчик события для события OnStalled. |
| event [OnSubmit](../../aspose.svg.dom/document/onsubmit/) | Получает или задает обработчик события для события OnSubmit. |
| event [OnSuspend](../../aspose.svg.dom/document/onsuspend/) | Получает или задает обработчик события для события OnSuspend. |
| event [OnTimeUpdate](../../aspose.svg.dom/document/ontimeupdate/) | Получает или задает обработчик события для события OnTimeUpdate. |
| event [OnToggle](../../aspose.svg.dom/document/ontoggle/) | Получает или задает обработчик события для события OnToggle. |
| event [OnVolumeChange](../../aspose.svg.dom/document/onvolumechange/) | Получает или задает обработчик события для события OnVolumeChange. |
| event [OnWaiting](../../aspose.svg.dom/document/onwaiting/) | Получает или задает обработчик события для события OnWaiting. |

### См. также

* class [Node](../node/)
* interface [IDocumentEvent](../../aspose.svg.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../aspose.svg.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../aspose.svg.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../aspose.svg.dom.xpath/ixpathevaluator/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

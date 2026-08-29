---
title: "Класс SVGPolygonElement"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.SVGPolygonElement. Интерфейс SVGPolygonElement соответствует элементу polygon."
type: docs
weight: 5460
url: /ru/net/aspose.svg/svgpolygonelement/
---
## SVGPolygonElement class

Интерфейс SVGPolygonElement соответствует элементу ‘polygon’.

```csharp
public class SVGPolygonElement : SVGGeometryElement, ISVGAnimatedPoints
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AnimatedPoints](../../aspose.svg/svgpolygonelement/animatedpoints/) { get; } | Обеспечивает доступ к текущему анимированному содержимому атрибута ‘points’. Если данный атрибут или свойство анимируется, содержит текущее анимированное значение атрибута или свойства. Если данный атрибут или свойство в данный момент не анимируется, содержит то же значение, что и points. |
| [Attributes](../../aspose.svg.dom/element/attributes/) { get; } | NamedNodeMap, содержащий атрибуты этого узла (если это Element), или null в противном случае. |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | Возвращает абсолютный базовый URL документа, содержащего узел. |
| [ChildElementCount](../../aspose.svg.dom/element/childelementcount/) { get; } | Возвращает текущее количество узлов-элементов, являющихся дочерними для этого элемента. 0, если у этого элемента нет дочерних узлов типа nodeType 1. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Возвращает живой [`NodeList`](../../aspose.svg.collections/nodelist/) дочерних узлов заданного элемента, где первый дочерний узел имеет индекс 0. Дочерние узлы включают элементы, текст и комментарии. |
| [Children](../../aspose.svg.dom/element/children/) { get; } | Возвращает дочерние элементы текущего элемента. |
| [ClassList](../../aspose.svg.dom/element/classlist/) { get; } | Возвращает живой DOMTokenList, содержащий токены, полученные при разборе атрибута "class". |
| [ClassName](../../aspose.svg/svgelement/classname/) { get; } | Соответствует атрибуту ‘class’ данного элемента. |
| [ClassName](../../aspose.svg.dom/element/classname/) { get; set; } | Атрибут class элемента. Этот атрибут был переименован из‑за конфликтов с ключевым словом "class", используемым во многих языках. См. определение атрибута class в HTML 4.01. |
| [FarthestViewportElement](../../aspose.svg/svggraphicselement/farthestviewportelement/) { get; } | Самый дальний предок‑элемент ‘svg’. Null, если текущий элемент является самым внешним элементом svg. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Возвращает первого дочернего узла в дереве, или null, если у узла нет дочерних элементов. |
| [FirstElementChild](../../aspose.svg.dom/element/firstelementchild/) { get; } | Возвращает первый дочерний узел-элемент этого элемента. null, если у этого элемента нет дочерних элементов. |
| [Id](../../aspose.svg/svgelement/id/) { get; set; } | Значение атрибута ‘id’ данного элемента, или пустая строка, если атрибут ‘id’ отсутствует. |
| [InnerHTML](../../aspose.svg.dom/element/innerhtml/) { get; set; } | Возвращает фрагмент HTML или XML, представляющий содержимое элемента. Можно установить, чтобы заменить содержимое элемента узлами, разобранными из заданной строки. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Возвращает последний дочерний узел. Если его родитель — элемент, то дочерний узел обычно является элементом, текстовым узлом или узлом комментария. Возвращает null, если нет дочерних элементов. |
| [LastElementChild](../../aspose.svg.dom/element/lastelementchild/) { get; } | Возвращает последний дочерний элементный узел этого элемента. null, если у этого элемента нет дочерних элементов. |
| override [LocalName](../../aspose.svg.dom/element/localname/) { get; } | Возвращает локальную часть квалифицированного имени этого узла. Для узлов любого типа, кроме ELEMENT_NODE и ATTRIBUTE_NODE, а также узлов, созданных методом DOM Level 1, например Document.createElement(), всегда возвращается null. |
| override [NamespaceURI](../../aspose.svg.dom/element/namespaceuri/) { get; } | URI пространства имён этого узла, или null, если оно не указано. |
| [NearestViewportElement](../../aspose.svg/svggraphicselement/nearestviewportelement/) { get; } | Элемент, задающий текущий viewport. Чаще всего ближайший предок‑элемент ‘svg’. Null, если текущий элемент является самым внешним элементом svg. |
| [NextElementSibling](../../aspose.svg.dom/element/nextelementsibling/) { get; } | Возвращает следующий соседний элементный узел этого элемента. null, если у этого элемента нет соседних элементных узлов, идущих после него в дереве документа. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Возвращает узел, сразу следующий за указанным в `ChildNodes` его родителя [`ChildNodes`](../../aspose.svg.dom/node/childnodes/), или возвращает null, если указанный узел является последним дочерним элементом в родительском элементе. |
| override [NodeName](../../aspose.svg.dom/element/nodename/) { get; } | Имя этого узла, в зависимости от его типа. |
| override [NodeType](../../aspose.svg.dom/element/nodetype/) { get; } | Код, представляющий тип базового объекта. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Возвращает или задаёт значение текущего узла. |
| [OuterHTML](../../aspose.svg.dom/element/outerhtml/) { get; set; } | Возвращает фрагмент HTML или XML, представляющий элемент и его содержимое. Можно установить, чтобы заменить элемент узлами, разобранными из заданной строки. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Возвращает объект документа верхнего уровня узла. |
| [OwnerSVGElement](../../aspose.svg/svgelement/ownersvgelement/) { get; } | Ближайший предок‑элемент ‘svg’. Null, если данный элемент является самым внешним элементом svg. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Возвращает родительский [`Element`](../../aspose.svg.dom/element/) DOM‑узла, или null, если у узла нет родителя или его родитель не является DOM‑элементом. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Возвращает родителя указанного узла в дереве DOM. |
| [PathLength](../../aspose.svg/svggeometryelement/pathlength/) { get; } | Соответствует атрибуту pathLength на данном элементе. |
| [Points](../../aspose.svg/svgpolygonelement/points/) { get; } | Обеспечивает доступ к базовому (т.е. статическому) содержимому атрибута ‘points’. |
| override [Prefix](../../aspose.svg.dom/element/prefix/) { get; } | Префикс пространства имён этого узла, или null, если он не указан. Когда он задан как null, попытка установить его не оказывает эффекта. |
| [PreviousElementSibling](../../aspose.svg.dom/element/previouselementsibling/) { get; } | Возвращает предыдущий соседний элементный узел этого элемента. null, если у этого элемента нет соседних элементных узлов, идущих перед ним в дереве документа. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Возвращает узел, сразу предшествующий указанному в списке [`ChildNodes`](../../aspose.svg.dom/node/childnodes/) его родителя, или null, если указанный узел является первым в этом списке. |
| [RequiredExtensions](../../aspose.svg/svggraphicselement/requiredextensions/) { get; } | Соответствует атрибуту ‘requiredExtensions’ данного элемента. |
| [RequiredFeatures](../../aspose.svg/svggraphicselement/requiredfeatures/) { get; } | Соответствует атрибуту ‘requiredFeatures’ данного элемента. |
| [ShadowRoot](../../aspose.svg.dom/element/shadowroot/) { get; } | Возвращает shadowRoot, хранящийся в этом элементе, или null, если он закрыт. |
| [Style](../../aspose.svg/svgelement/style/) { get; } | Соответствует атрибуту ‘style’ данного элемента. Если пользовательский агент не поддерживает стилизацию с помощью CSS, то этот атрибут всегда должен иметь значение null. |
| [SystemLanguage](../../aspose.svg/svggraphicselement/systemlanguage/) { get; } | Соответствует атрибуту ‘systemLanguage’ данного элемента. |
| [TagName](../../aspose.svg.dom/element/tagname/) { get; } | Имя элемента. |
| override [TextContent](../../aspose.svg.dom/element/textcontent/) { get; set; } | Этот атрибут возвращает текстовое содержимое этого узла и его потомков. Когда он определён как null, попытка установить его не оказывает эффекта. При установке все возможные дочерние узлы этого узла удаляются, и если новая строка не пуста и не null, она заменяется одним текстовым узлом, содержащим эту строку. |
| [Transform](../../aspose.svg/svggraphicselement/transform/) { get; } | Соответствует атрибуту ‘transform’ у указанного элемента. |
| [ViewportElement](../../aspose.svg/svgelement/viewportelement/) { get; } | Элемент, определяющий текущий viewport. Часто это ближайший предок‑элемент ‘svg’. Null, если данный элемент является самым внешним элементом svg. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../../aspose.svg.dom/node/)*) | Добавляет узел в конец списка дочерних элементов указанного родительского узла. Если данный дочерний узел является ссылкой на существующий узел в документе, [`AppendChild`](../../aspose.svg.dom/node/appendchild/) перемещает его из текущего положения в новое (не требуется удалять узел из его родителя перед добавлением его к другому узлу). |
| [AttachShadow](../../aspose.svg.dom/element/attachshadow/)(*[ShadowRootMode](../../aspose.svg.dom/shadowrootmode/)*) | Создаёт shadow root и присоединяет его к текущему элементу. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Возвращает дубликат узла, для которого был вызван этот метод. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Возвращает дубликат узла, для которого был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [Combine](../../aspose.svg/svggeometryelement/combine/)(*[SVGGeometryElement](../svggeometryelement/), [BooleanPathOp](../../aspose.svg.rendering/booleanpathop/)*) | Объединяет эту геометрию с другой SVG-геометрией с помощью булевой операции и возвращает новый элемент `<path>`, содержащий результат. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Отправляет событие Event указанному [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (синхронно) вызывая затронутые EventListeners в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправляемым вручную с помощью [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [GetAttribute](../../aspose.svg.dom/element/getattribute/)(*string*) | Получает значение атрибута по имени. |
| [GetAttributeNames](../../aspose.svg.dom/element/getattributenames/)() | Возвращает имена атрибутов элемента в виде массива строк. Если у элемента нет атрибутов, возвращается пустой массив. |
| [GetAttributeNode](../../aspose.svg.dom/element/getattributenode/)(*string*) | Получает узел атрибута по имени. |
| [GetAttributeNodeNS](../../aspose.svg.dom/element/getattributenodens/)(*string, string*) | Получает узел Attr по локальному имени и URI пространства имён. |
| [GetAttributeNS](../../aspose.svg.dom/element/getattributens/)(*string, string*) | Получает значение атрибута по локальному имени и URI пространства имён. |
| [GetBBox](../../aspose.svg/svggraphicselement/getbbox/)() | Возвращает плотный ограничивающий прямоугольник в текущем пользовательском пространстве (т. е. после применения атрибута ‘transform’, если он присутствует) для геометрии всех вложенных графических элементов, исключая обводку, обрезку, маскирование и эффекты фильтрации). Обратите внимание, что getBBox должен возвращать фактический ограничивающий прямоугольник в момент вызова метода, даже если элемент ещё не был отрисован. |
| [GetCTM](../../aspose.svg/svggraphicselement/getctm/)() | Возвращает матрицу преобразования из текущих пользовательских единиц (т. е. после применения атрибута ‘transform’, если он присутствует) в систему координат viewport для nearestViewportElement. |
| [GetElementsByClassName](../../aspose.svg.dom/element/getelementsbyclassname/)(*string*) | Возвращает объект [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/), содержащий все элементы внутри [`element`](../../aspose.svg.dom/element/), которые имеют все классы, указанные в аргументе. |
| [GetElementsByTagName](../../aspose.svg.dom/element/getelementsbytagname/)(*string*) | Возвращает объект [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/), содержащий все [`elements`](../../aspose.svg.dom/element/) с заданным именем тега, в порядке следования в документе. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/element/getelementsbytagnamens/)(*string, string*) | Возвращает объект [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/), содержащий все [`elements`](../../aspose.svg.dom/element/) с заданным локальным именем и строкой URI пространства имён, в порядке следования в документе. |
| [GetEquivalentPath](../../aspose.svg/svggeometryelement/getequivalentpath/)() | Возвращает новый экземпляр [`SVGPathSegList`](../../aspose.svg.paths/svgpathseglist/), который представляет [`SVGGeometryElement`](../svggeometryelement/) в виде сегментов пути. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [GetPointAtLength](../../aspose.svg/svggeometryelement/getpointatlength/)(*float*) | Возвращает координату (x,y) в пользовательском пространстве, измеренную в единицах расстояния вдоль пути, используя алгоритм distance-along-a-path пользовательского агента. |
| [GetScreenCTM](../../aspose.svg/svggraphicselement/getscreenctm/)() | Возвращает матрицу преобразования из текущих пользовательских единиц (т. е. после применения атрибута ‘transform’, если он присутствует) в представление родительского пользовательского агента о \"пикселе\". Для дисплейных устройств это, как правило, физический пиксель экрана. Для других устройств или сред, где размеры физических пикселей неизвестны, можно использовать алгоритм, аналогичный определению \"пикселя\" в CSS2. Обратите внимание, что null возвращается, если этот элемент не включён в дерево документа. Этот метод мог бы быть назван более точно как getClientCTM, но имя getScreenCTM сохраняется по историческим причинам. |
| [GetTotalLength](../../aspose.svg/svggeometryelement/gettotallength/)() | Возвращает вычисленное пользовательским агентом значение общей длины пути с использованием алгоритма distance-along-a-path, выраженное как расстояние в текущей пользовательской системе координат. |
| [HasAttribute](../../aspose.svg.dom/element/hasattribute/)(*string*) | Возвращает true, если атрибут с заданным именем указан у этого элемента или имеет значение по умолчанию, иначе false. |
| [HasAttributeNS](../../aspose.svg.dom/element/hasattributens/)(*string, string*) | Возвращает true, когда атрибут с заданным локальным именем и URI пространства имён указан на этом элементе или имеет значение по умолчанию, иначе возвращает false. |
| [HasAttributes](../../aspose.svg.dom/element/hasattributes/)() | Возвращает, имеет ли этот узел (если это элемент) какие‑либо атрибуты |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Возвращает логическое значение, указывающее, имеет ли данный [`Node`](../../aspose.svg.dom/node/) дочерние узлы. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | Вставляет узел перед существующим дочерним узлом child. Если child равен null, узел вставляется в конец списка дочерних узлов. Если child является объектом DocumentFragment, все его дочерние узлы вставляются в том же порядке перед child. Если дочерний узел уже находится в дереве, он сначала удаляется. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Этот метод проверяет, является ли указанный namespaceURI пространством имён по умолчанию. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../../aspose.svg.dom/node/)*) | Проверяет, равны ли два узла. Этот метод проверяет равенство узлов, а не их тождественность (т.е. являются ли два узла ссылками на один и тот же объект), что можно проверить с помощью Node.isSameNode(). Все узлы, которые тождественны, также будут равны, хотя обратное может быть неверным. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../../aspose.svg.dom/node/)*) | Метод является устаревшим псевдонимом для оператора строгого равенства ===. То есть он проверяет, являются ли два узла одинаковыми (иначе говоря, ссылаются ли они на один и тот же объект). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Ищет URI пространства имён, связанный с указанным префиксом, начиная с этого узла. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Ищет префикс, связанный с указанным URI пространства имён, начиная с этого узла. Объявления пространства имён по умолчанию игнорируются этим методом. См. Namespace Prefix Lookup для подробностей алгоритма, используемого этим методом. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Помещает все текстовые узлы на полной глубине поддерева под этим Node, включая узлы атрибутов, в "нормальную" форму, где только структура (например, элементы, комментарии, инструкции обработки, секции CDATA и ссылки на сущности) разделяет текстовые узлы, то есть нет соседних или пустых текстовых узлов. Это можно использовать, чтобы гарантировать, что представление DOM документа совпадает с тем, как оно выглядело бы после сохранения и повторной загрузки, и полезно, когда операции (например, поиск XPointer [XPointer]) зависят от определённой структуры дерева документа. Если параметр "normalize-characters" объекта DOMConfiguration, привязанного к Node.ownerDocument, имеет значение true, этот метод также полностью нормализует символы текстовых узлов. |
| [QuerySelector](../../aspose.svg.dom/element/queryselector/)(*string*) | Возвращает первый Element в документе, который соответствует селектору |
| [QuerySelectorAll](../../aspose.svg.dom/element/queryselectorall/)(*string*) | Возвращает NodeList всех Elements в документе, которые соответствуют селектору |
| [Remove](../../aspose.svg.dom/element/remove/)() | Удаляет этот экземпляр. |
| [RemoveAttribute](../../aspose.svg.dom/element/removeattribute/)(*string*) | Удаляет атрибут по имени. |
| [RemoveAttributeNode](../../aspose.svg.dom/element/removeattributenode/)(*[Attr](../../aspose.svg.dom/attr/)*) | Удаляет указанный узел атрибута. |
| [RemoveAttributeNS](../../aspose.svg.dom/element/removeattributens/)(*string, string*) | Удаляет атрибут по локальному имени и URI пространства имён. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../../aspose.svg.dom/node/)*) | Удаляет дочерний узел из DOM и возвращает удалённый узел. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Этот метод позволяет удалять слушатели событий из цели события. Если [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../../aspose.svg.dom/eventtarget/) во время обработки события, он не будет вызван текущими действиями. Слушатели событий никогда не могут быть вызваны после их удаления. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Этот метод позволяет удалять слушатели событий из цели события. Если [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../../aspose.svg.dom/eventtarget/) во время обработки события, он не будет вызван текущими действиями. Слушатели событий никогда не могут быть вызваны после их удаления. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Этот метод позволяет удалять слушатели событий из цели события. Если [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../../aspose.svg.dom/eventtarget/) во время обработки события, он не будет вызван текущими действиями. Слушатели событий никогда не могут быть вызваны после их удаления. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | Заменяет дочерний узел oldChild узлом newChild в списке дочерних элементов и возвращает узел oldChild. Если newChild является объектом DocumentFragment, oldChild заменяется всеми дочерними элементами DocumentFragment, которые вставляются в том же порядке. Если newChild уже находится в дереве, он сначала удаляется. |
| [SetAttribute](../../aspose.svg.dom/element/setattribute/)(*string, string*) | Добавляет новый атрибут. Если атрибут с таким именем уже присутствует в элементе, его значение изменяется на значение параметра value. |
| [SetAttributeNode](../../aspose.svg.dom/element/setattributenode/)(*[Attr](../../aspose.svg.dom/attr/)*) | Добавляет новый узел атрибута. Если атрибут с таким именем (nodeName) уже присутствует в элементе, он заменяется новым. |
| [SetAttributeNodeNS](../../aspose.svg.dom/element/setattributenodens/)(*[Attr](../../aspose.svg.dom/attr/)*) | Добавляет новый атрибут. Если атрибут с таким локальным именем и URI пространства имён уже присутствует в элементе, он заменяется новым. |
| [SetAttributeNS](../../aspose.svg.dom/element/setattributens/)(*string, string, string*) | Добавляет новый атрибут. Если атрибут с тем же локальным именем и URI пространства имён уже присутствует в элементе, его префикс изменяется на префикс из qualifiedName, а значение изменяется на значение параметра value. |
| [ToggleAttribute](../../aspose.svg.dom/element/toggleattribute/)(*string*) | Если параметр force не указан, "переключает" qualifiedName, удаляя его, если он присутствует, и добавляя, если отсутствует. Если force равно true, добавляет qualifiedName. Если force равно false, удаляет qualifiedName. |
| [ToggleAttribute](../../aspose.svg.dom/element/toggleattribute/)(*string, bool*) | Если параметр force не указан, "переключает" qualifiedName, удаляя его, если он присутствует, и добавляя, если отсутствует. Если force равно true, добавляет qualifiedName. Если force равно false, удаляет qualifiedName. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

### См. также

* class [SVGGeometryElement](../svggeometryelement/)
* interface [ISVGAnimatedPoints](../isvganimatedpoints/)
* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

---
title: "Aspose.Svg.Dom"
second_title: "Aspose.SVG для .NET справочник API"
description: "Пространство имён Document Object Model Aspose.Svg.Dom предоставляет API, который представляет и взаимодействует с любыми документами HTML, XML или SVG. DOM — это модель документа, загружаемая в браузере и представляющая документ в виде дерева узлов, где каждый узел представляет часть документа, например элемент, строку текста или комментарий."
type: docs
weight: 70
url: /ru/net/aspose.svg.dom/
---
Пространство имён **Aspose.Svg.Dom (Document Object Model)** предоставляет API, представляющее и взаимодействующее с любыми документами HTML, XML или SVG. DOM — это модель документа, загружаемая в браузере и представляющая документ в виде дерева узлов, где каждый узел соответствует части документа (например, элементу, строке текста или комментарию).

## Классы

| Класс | Описание |
| --- | --- |
| [Attr](./attr/) | Интерфейс Attr представляет атрибут в объекте Element. Обычно допустимые значения атрибута определяются в схеме, связанной с документом. |
| [CDATASection](./cdatasection/) | Разделы CDATA используются для экранирования блоков текста, содержащих символы, которые иначе рассматривались бы как разметка. |
| [CharacterData](./characterdata/) | CharacterData расширяет Node набором атрибутов и методов для доступа к символьным данным в DOM. |
| [Comment](./comment/) | Наследуется от CharacterData и представляет содержимое комментария, т.е. все символы между начальными ''. |
| [Document](./document/) | Document представляет весь документ HTML, XML или SVG. Концептуально это корень дерева документа и обеспечивает основной доступ к данным документа. |
| [DocumentFragment](./documentfragment/) | DocumentFragment — это "lightweight" или "minimal" объект Document. Очень часто требуется извлечь часть дерева документа или создать новый фрагмент документа. |
| [DocumentType](./documenttype/) | DocumentType предоставляет интерфейс к списку сущностей, определённых для документа. |
| [DOMException](./domexception/) | Интерфейс DOMException представляет аномальное событие (называемое исключением), которое происходит в результате вызова метода или доступа к свойству веб‑API. По‑сути, так описываются условия ошибок в веб‑API. |
| [DOMObject](./domobject/) | Тип DOMObject используется для представления базового объекта всей модели Document Object Model. Для Java и ECMAScript DOMObject привязан к типу Object. |
| [Element](./element/) | Интерфейс Element представляет элемент в документе HTML или XML. |
| [Entity](./entity/) | Представляет известную сущность, разобранную или неразобранную, в документе XML. |
| [EntityReference](./entityreference/) | Узлы EntityReference могут использоваться для представления ссылки на сущность в дереве. |
| [EventTarget](./eventtarget/) | The interface [`EventTarget`](../aspose.svg.dom/eventtarget/) реализуется всеми узлами в реализации, поддерживающей модель событий DOM. Поэтому этот интерфейс можно получить, используя методы привязочного приведения типов к экземпляру интерфейса Node. Интерфейс позволяет регистрировать и удалять обработчики событий на [`EventTarget`](../aspose.svg.dom/eventtarget/) и отправлять события этому [`IEventTarget`](../aspose.svg.dom.events/ieventtarget/). |
| [Node](./node/) | Интерфейс Node является основным типом данных для всей модели Document Object Model. Он представляет отдельный узел в дереве документа. |
| [Notation](./notation/) | Представляет обозначение, объявленное в DTD. |
| [ProcessingInstruction](./processinginstruction/) | ProcessingInstruction представляет "инструкцию обработки", используемую в XML как способ сохранять специфичную для процессора информацию в тексте документа. |
| [QualifiedName](./qualifiedname/) | Представляет квалифицированное имя HTML. |
| [ShadowRoot](./shadowroot/) | ShadowRoot является корневым узлом теневого дерева. |
| [Text](./text/) | Интерфейс Text наследуется от CharacterData и представляет текстовое содержимое (именуемое символьными данными в XML) элемента или атрибута. |
| [TypeInfo](./typeinfo/) | TypeInfo представляет тип, на который ссылаются узлы Element или Attr, указанный в схемах, связанных с документом. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | Контекст просмотра — это среда, в которой объекты [`Document`](../aspose.svg.dom/document/) представлены пользователю. |
| [IChildNode](./ichildnode/) | Определяет интерфейс [`IChildNode`](../aspose.svg.dom/ichildnode/), который должен быть реализован узлом [`Node`](../aspose.svg.dom/node/), способным иметь родителя. |
| [IDOMImplementation](./idomimplementation/) | Интерфейс DOMImplementation предоставляет ряд методов для выполнения операций, независимых от конкретного экземпляра модели объектного документа. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Представляет интерфейс, который должен наследоваться всеми элементами, поддерживающими обработку системных событий. |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | Определяет [`IChildNode`](../aspose.svg.dom/ichildnode/), которые не являются [`DOCUMENT_TYPE_NODE`](../aspose.svg.dom/node/document_type_node/). |
| [INonElementParentNode](./inonelementparentnode/) | Определяет [`IParentNode`](../aspose.svg.dom/iparentnode/), которые не являются типом Element. |
| [IParentNode](./iparentnode/) | Определяет интерфейс [`IParentNode`](../aspose.svg.dom/iparentnode/), который реализуется любыми возможными родителями. |
| [IStorage](./istorage/) | Этот интерфейс Web Storage API предоставляет доступ к сеансовому или локальному хранилищу конкретного домена. См. спецификацию Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | Режимы, в которых может работать ShadowRoot. |

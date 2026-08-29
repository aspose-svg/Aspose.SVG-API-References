---
title: "Класс DOMException"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Dom.DOMException. Интерфейс DOMException представляет аномальное событие, называемое исключением, которое происходит в результате вызова метода или доступа к свойству веб‑API. По сути, так описываются условия ошибок в веб‑API"
type: docs
weight: 2790
url: /ru/net/aspose.svg.dom/domexception/
---
## DOMException class

Интерфейс DOMException представляет аномальное событие (называемое исключением), которое происходит в результате вызова метода или доступа к свойству веб‑API. По‑сути, так описываются условия ошибок в веб‑API.

```csharp
public class DOMException : PlatformException
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DOMException](domexception/#constructor)(*string*) | Инициализирует новый экземпляр класса `DOMException`. |
| [DOMException](domexception/#constructor_1)(*string, string*) | Инициализирует новый экземпляр класса `DOMException`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Code](../../aspose.svg.dom/domexception/code/) { get; } | Возвращает значение, содержащее одну из констант кода ошибки, или 0, если ни одна не подходит. Это поле используется по историческим причинам. |
| virtual [Data](../../system/exception/data/) { get; } |  |
| virtual [HelpLink](../../system/exception/helplink/) { get; set; } |  |
| [HResult](../../system/exception/hresult/) { get; set; } |  |
| [InnerException](../../system/exception/innerexception/) { get; } |  |
| override [Message](../../aspose.svg.dom/domexception/message/) { get; } | Возвращает строку, представляющую сообщение или описание, связанное с указанным именем ошибки. |
| [Name](../../aspose.svg.dom/domexception/name/) { get; } | Возвращает строку, содержащую одну из строк, связанных с именем ошибки. |
| virtual [Source](../../system/exception/source/) { get; set; } |  |
| virtual [StackTrace](../../system/exception/stacktrace/) { get; } |  |
| [TargetSite](../../system/exception/targetsite/) { get; } |  |

## Поля

| Имя | Описание |
| --- | --- |
| const [ABORT_ERR](../../aspose.svg.dom/domexception/abort_err/) | Операция была прервана. |
| const [DATA_CLONE_ERR](../../aspose.svg.dom/domexception/data_clone_err/) | Объект нельзя клонировать. |
| const [DOMSTRING_SIZE_ERR](../../aspose.svg.dom/domexception/domstring_size_err/) | Если указанный диапазон текста не помещается в DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../aspose.svg.dom/domexception/hierarchy_request_err/) | Если любой Node вставлен в место, где он не принадлежит. |
| const [INDEX_SIZE_ERR](../../aspose.svg.dom/domexception/index_size_err/) | Если индекс или размер отрицательны, или превышают допустимое значение. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.svg.dom/domexception/inuse_attribute_err/) | Если попытка добавить атрибут, который уже используется в другом месте. |
| const [INVALID_ACCESS_ERR](../../aspose.svg.dom/domexception/invalid_access_err/) | Если параметр или операция не поддерживается базовым объектом. |
| const [INVALID_CHARACTER_ERR](../../aspose.svg.dom/domexception/invalid_character_err/) | Если указано недопустимое или незаконное символ, например в имени XML. |
| const [INVALID_EXPRESSION_ERR](../../aspose.svg.dom/domexception/invalid_expression_err/) | Выражение содержит синтаксическую ошибку или иначе не является допустимым выражением согласно правилам конкретного XPathEvaluator, либо содержит специализированные функции расширения или переменные, не поддерживаемые этой реализацией. |
| const [INVALID_MODIFICATION_ERR](../../aspose.svg.dom/domexception/invalid_modification_err/) | Если попытка изменить тип базового объекта. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.svg.dom/domexception/invalid_node_type_err/) | Предоставленный узел некорректен или имеет неверного предка для этой операции. |
| const [INVALID_STATE_ERR](../../aspose.svg.dom/domexception/invalid_state_err/) | Если попытка использовать объект, который не является или больше не является пригодным. |
| const [NAMESPACE_ERR](../../aspose.svg.dom/domexception/namespace_err/) | Если попытка создать или изменить объект способом, некорректным с точки зрения пространств имён. |
| const [NETWORK_ERR](../../aspose.svg.dom/domexception/network_err/) | Произошла сетевая ошибка. |
| const [NOT_FOUND_ERR](../../aspose.svg.dom/domexception/not_found_err/) | Если попытка сослаться на Node в контексте, где он не существует. |
| const [NOT_SUPPORTED_ERR](../../aspose.svg.dom/domexception/not_supported_err/) | Если реализация не поддерживает запрошенный тип объекта или операцию. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_data_allowed_err/) | Если данные указаны для Node, который не поддерживает данные. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_modification_allowed_err/) | Если попытка изменить объект, где модификации не разрешены. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.svg.dom/domexception/quota_exceeded_err/) | Квота превышена. |
| const [SECURITY_ERR](../../aspose.svg.dom/domexception/security_err/) | Операция небезопасна. |
| const [SYNTAX_ERR](../../aspose.svg.dom/domexception/syntax_err/) | Если указана недопустимая или незаконная строка. |
| const [TIMEOUT_ERR](../../aspose.svg.dom/domexception/timeout_err/) | Время выполнения операции истекло. |
| const [TYPE_ERR](../../aspose.svg.dom/domexception/type_err/) | Выражение нельзя преобразовать к возвращаемому указанному типу. |
| const [TYPE_MISMATCH_ERR](../../aspose.svg.dom/domexception/type_mismatch_err/) | Если тип объекта несовместим с ожидаемым типом параметра, связанным с объектом. |
| const [URL_MISMATCH_ERR](../../aspose.svg.dom/domexception/url_mismatch_err/) | Указанный URL не совпадает с другим URL. |
| const [VALIDATION_ERR](../../aspose.svg.dom/domexception/validation_err/) | Если вызов метода, например insertBefore или removeChild, сделает узел недействительным с точки зрения «частичной валидности», будет выброшено исключение, и операция не будет выполнена. Этот код используется в [DOM Level 3 Validation]. Обратитесь к этой спецификации для получения дополнительной информации. |
| const [WRONG_DOCUMENT_ERR](../../aspose.svg.dom/domexception/wrong_document_err/) | Если узел используется в другом документе, отличном от того, который его создал (который его не поддерживает). |

### См. также

* class [PlatformException](../../aspose.svg/platformexception/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

---
title: Class DOMException
second_title: Справочник по Aspose.SVG для .NET API
description: Aspose.Svg.Dom.DOMException сорт. Интерфейс DOMException представляет собой ненормальное событие называемое исключением которое возникает в результате вызова метода или доступа к свойству вебAPI. В основном это то как состояния ошибок описываются в вебAPI.
type: docs
weight: 790
url: /ru/net/aspose.svg.dom/domexception/
---
## DOMException class

Интерфейс DOMException представляет собой ненормальное событие (называемое исключением), которое возникает в результате вызова метода или доступа к свойству веб-API. В основном это то, как состояния ошибок описываются в веб-API.

```csharp
public class DOMException : PlatformException
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DOMException](domexception/#constructor)(string) | Инициализирует новый экземпляр`DOMException` класс. |
| [DOMException](domexception/#constructor_1)(string, string) | Инициализирует новый экземпляр`DOMException` класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Code](../../aspose.svg.dom/domexception/code/) { get; } | Возвращает значение, содержащее одну из констант кода ошибки, или 0, если ничего не совпадает. Это поле используется по историческим причинам. |
| override [Message](../../aspose.svg.dom/domexception/message/) { get; } | Возвращает строку, представляющую сообщение или описание, связанное с данным именем ошибки. |
| [Name](../../aspose.svg.dom/domexception/name/) { get; } | Возвращает строку, содержащую одну из строк, связанных с именем ошибки. |

## Поля

| Имя | Описание |
| --- | --- |
| const [ABORT_ERR](../../aspose.svg.dom/domexception/abort_err/) | Операция была прервана. |
| const [DATA_CLONE_ERR](../../aspose.svg.dom/domexception/data_clone_err/) | Объект не может быть клонирован. |
| const [DOMSTRING_SIZE_ERR](../../aspose.svg.dom/domexception/domstring_size_err/) | Если указанный диапазон текста не помещается в DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../aspose.svg.dom/domexception/hierarchy_request_err/) | Если какой-либо узел вставлен куда-то, ему не место. |
| const [INDEX_SIZE_ERR](../../aspose.svg.dom/domexception/index_size_err/) | Если индекс или размер отрицательные или превышают допустимое значение. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.svg.dom/domexception/inuse_attribute_err/) | При попытке добавить атрибут, который уже используется в другом месте. |
| const [INVALID_ACCESS_ERR](../../aspose.svg.dom/domexception/invalid_access_err/) | Если параметр или операция не поддерживаются базовым объектом. |
| const [INVALID_CHARACTER_ERR](../../aspose.svg.dom/domexception/invalid_character_err/) | Если указан недопустимый или недопустимый символ, например, в имени XML. |
| const [INVALID_EXPRESSION_ERR](../../aspose.svg.dom/domexception/invalid_expression_err/) | Выражение содержит синтаксическую ошибку или по иным причинам не является допустимым выражением в соответствии с правилами Specific XPathEvaluator или содержит специализированные функции расширения или переменные, не поддерживаемые этой реализацией. |
| const [INVALID_MODIFICATION_ERR](../../aspose.svg.dom/domexception/invalid_modification_err/) | При попытке изменить тип базового объекта. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.svg.dom/domexception/invalid_node_type_err/) | Предоставленный узел неверен или имеет неверный предок для этой операции. |
| const [INVALID_STATE_ERR](../../aspose.svg.dom/domexception/invalid_state_err/) | Если делается попытка использовать объект, который не является или больше не может использоваться. |
| const [NAMESPACE_ERR](../../aspose.svg.dom/domexception/namespace_err/) | Если предпринимается попытка создать или изменить объект способом, неверным в отношении пространств имен. |
| const [NETWORK_ERR](../../aspose.svg.dom/domexception/network_err/) | Произошла ошибка сети. |
| const [NOT_FOUND_ERR](../../aspose.svg.dom/domexception/not_found_err/) | Если делается попытка сослаться на узел в контексте, в котором он не существует. |
| const [NOT_SUPPORTED_ERR](../../aspose.svg.dom/domexception/not_supported_err/) | Если реализация не поддерживает запрошенный тип объекта или операции. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_data_allowed_err/) | Если данные указаны для узла, который не поддерживает данные. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_modification_allowed_err/) | При попытке изменить объект, изменения которого запрещены. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.svg.dom/domexception/quota_exceeded_err/) | Превышена квота. |
| const [SECURITY_ERR](../../aspose.svg.dom/domexception/security_err/) | Операция небезопасна. |
| const [SYNTAX_ERR](../../aspose.svg.dom/domexception/syntax_err/) | Если указана недопустимая или недопустимая строка. |
| const [TIMEOUT_ERR](../../aspose.svg.dom/domexception/timeout_err/) | Время ожидания операции истекло. |
| const [TYPE_ERR](../../aspose.svg.dom/domexception/type_err/) | Выражение не может быть преобразовано для возврата указанного типа. |
| const [TYPE_MISMATCH_ERR](../../aspose.svg.dom/domexception/type_mismatch_err/) | Если тип объекта несовместим с ожидаемым типом параметра, связанного с объектом. |
| const [URL_MISMATCH_ERR](../../aspose.svg.dom/domexception/url_mismatch_err/) | Указанный URL-адрес не соответствует другому URL-адресу. |
| const [VALIDATION_ERR](../../aspose.svg.dom/domexception/validation_err/) | Если вызов метода, такого как insertBefore или removeChild, сделает узел недействительным в отношении «частичной достоверности», это исключение будет возбуждено, и операция не будет выполнена. Этот код используется в [DOM Level 3 Validation]. Дополнительную информацию см. в этой спецификации. |
| const [WRONG_DOCUMENT_ERR](../../aspose.svg.dom/domexception/wrong_document_err/) | Если узел используется в документе, отличном от того, в котором он был создан (который его не поддерживает). |

### Смотрите также

* class [PlatformException](../../aspose.svg/platformexception/)
* пространство имен [Aspose.Svg.Dom](../../aspose.svg.dom/)
* сборка [Aspose.SVG](../../)



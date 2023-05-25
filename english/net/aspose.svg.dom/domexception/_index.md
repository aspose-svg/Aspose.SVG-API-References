---
title: DOMException Class
second_title: Aspose.SVG for .NET API Reference
description: Aspose.Svg.Dom.DOMException class. The DOMException interface represents an abnormal event called an exception which occurs as a result of calling a method or accessing a property of a web API. This is basically how error conditions are described in web APIs
type: docs
weight: 800
url: /net/aspose.svg.dom/domexception/
---
## DOMException class

The DOMException interface represents an abnormal event (called an exception) which occurs as a result of calling a method or accessing a property of a web API. This is basically how error conditions are described in web APIs.

```csharp
public class DOMException : PlatformException
```

## Constructors

| Name | Description |
| --- | --- |
| [DOMException](domexception/#constructor)(string) | Initializes a new instance of the `DOMException` class. |
| [DOMException](domexception/#constructor_1)(string, string) | Initializes a new instance of the `DOMException` class. |

## Properties

| Name | Description |
| --- | --- |
| [Code](../../aspose.svg.dom/domexception/code/) { get; } | Returns a value that contains one of the error code constants, or 0 if none match. This field is used for historical reasons. |
| override [Message](../../aspose.svg.dom/domexception/message/) { get; } | Returns a string representing a message or description associated with the given error name. |
| [Name](../../aspose.svg.dom/domexception/name/) { get; } | Returns a string that contains one of the strings associated with an error name. |

## Fields

| Name | Description |
| --- | --- |
| const [ABORT_ERR](../../aspose.svg.dom/domexception/abort_err/) | The operation was aborted. |
| const [DATA_CLONE_ERR](../../aspose.svg.dom/domexception/data_clone_err/) | The object can not be cloned. |
| const [DOMSTRING_SIZE_ERR](../../aspose.svg.dom/domexception/domstring_size_err/) | If the specified range of text does not fit into a DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../aspose.svg.dom/domexception/hierarchy_request_err/) | If any Node is inserted somewhere it doesn't belong. |
| const [INDEX_SIZE_ERR](../../aspose.svg.dom/domexception/index_size_err/) | If index or size is negative, or greater than the allowed value. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.svg.dom/domexception/inuse_attribute_err/) | If an attempt is made to add an attribute that is already in use elsewhere. |
| const [INVALID_ACCESS_ERR](../../aspose.svg.dom/domexception/invalid_access_err/) | If a parameter or an operation is not supported by the underlying object. |
| const [INVALID_CHARACTER_ERR](../../aspose.svg.dom/domexception/invalid_character_err/) | If an invalid or illegal character is specified, such as in an XML name. |
| const [INVALID_EXPRESSION_ERR](../../aspose.svg.dom/domexception/invalid_expression_err/) | The expression has a syntax error or otherwise is not a legal expression according to the rules of the specific XPathEvaluator or contains specialized extension functions or variables not supported by this implementation. |
| const [INVALID_MODIFICATION_ERR](../../aspose.svg.dom/domexception/invalid_modification_err/) | If an attempt is made to modify the type of the underlying object. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.svg.dom/domexception/invalid_node_type_err/) | The supplied node is incorrect or has an incorrect ancestor for this operation. |
| const [INVALID_STATE_ERR](../../aspose.svg.dom/domexception/invalid_state_err/) | If an attempt is made to use an object that is not, or is no longer, usable. |
| const [NAMESPACE_ERR](../../aspose.svg.dom/domexception/namespace_err/) | If an attempt is made to create or change an object in a way which is incorrect with regard to namespaces. |
| const [NETWORK_ERR](../../aspose.svg.dom/domexception/network_err/) | A network error occurred. |
| const [NOT_FOUND_ERR](../../aspose.svg.dom/domexception/not_found_err/) | If an attempt is made to reference a Node in a context where it does not exist. |
| const [NOT_SUPPORTED_ERR](../../aspose.svg.dom/domexception/not_supported_err/) | If the implementation does not support the requested type of object or operation. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_data_allowed_err/) | If data is specified for a Node which does not support data. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_modification_allowed_err/) | If an attempt is made to modify an object where modifications are not allowed. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.svg.dom/domexception/quota_exceeded_err/) | The quota has been exceeded. |
| const [SECURITY_ERR](../../aspose.svg.dom/domexception/security_err/) | The operation is insecure. |
| const [SYNTAX_ERR](../../aspose.svg.dom/domexception/syntax_err/) | If an invalid or illegal string is specified. |
| const [TIMEOUT_ERR](../../aspose.svg.dom/domexception/timeout_err/) | The operation timed out. |
| const [TYPE_ERR](../../aspose.svg.dom/domexception/type_err/) | The expression cannot be converted to return the specified type. |
| const [TYPE_MISMATCH_ERR](../../aspose.svg.dom/domexception/type_mismatch_err/) | If the type of an object is incompatible with the expected type of the parameter associated to the object. |
| const [URL_MISMATCH_ERR](../../aspose.svg.dom/domexception/url_mismatch_err/) | The given URL does not match another URL. |
| const [VALIDATION_ERR](../../aspose.svg.dom/domexception/validation_err/) | If a call to a method such as insertBefore or removeChild would make the Node invalid with respect to "partial validity", this exception would be raised and the operation would not be done. This code is used in [DOM Level 3 Validation]. Refer to this specification for further information. |
| const [WRONG_DOCUMENT_ERR](../../aspose.svg.dom/domexception/wrong_document_err/) | If a Node is used in a different document than the one that created it (that doesn't support it). |

### See Also

* class [PlatformException](../../aspose.svg/platformexception/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

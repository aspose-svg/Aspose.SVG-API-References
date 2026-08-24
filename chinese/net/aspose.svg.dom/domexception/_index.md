---
title: "DOMException 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.DOMException 类。DOMException 接口表示一种称为异常的异常事件，该异常是调用方法或访问 Web API 的属性时产生的。这基本上是 Web API 中错误情况的描述方式。"
type: docs
weight: 2790
url: /zh/net/aspose.svg.dom/domexception/
---
## DOMException class

DOMException 接口表示一种异常事件（称为异常），它在调用方法或访问 Web API 的属性时发生。这基本上是 Web API 中描述错误情况的方式。

```csharp
public class DOMException : PlatformException
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DOMException](domexception/#constructor)(*string*) | 初始化 `DOMException` 类的新实例。 |
| [DOMException](domexception/#constructor_1)(*string, string*) | 初始化 `DOMException` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Code](../../aspose.svg.dom/domexception/code/) { get; } | 返回一个包含错误代码常量之一的值，如果没有匹配则返回 0。此字段出于历史原因而保留。 |
| virtual [Data](../../system/exception/data/) { get; } |  |
| virtual [HelpLink](../../system/exception/helplink/) { get; set; } |  |
| [HResult](../../system/exception/hresult/) { get; set; } |  |
| [InnerException](../../system/exception/innerexception/) { get; } |  |
| override [Message](../../aspose.svg.dom/domexception/message/) { get; } | 返回一个字符串，表示与给定错误名称关联的消息或描述。 |
| [Name](../../aspose.svg.dom/domexception/name/) { get; } | 返回一个字符串，包含与错误名称关联的其中一个字符串。 |
| virtual [Source](../../system/exception/source/) { get; set; } |  |
| virtual [StackTrace](../../system/exception/stacktrace/) { get; } |  |
| [TargetSite](../../system/exception/targetsite/) { get; } |  |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [ABORT_ERR](../../aspose.svg.dom/domexception/abort_err/) | 操作已中止。 |
| const [DATA_CLONE_ERR](../../aspose.svg.dom/domexception/data_clone_err/) | 对象无法被克隆。 |
| const [DOMSTRING_SIZE_ERR](../../aspose.svg.dom/domexception/domstring_size_err/) | 如果指定的文本范围不适合放入 DOMString。 |
| const [HIERARCHY_REQUEST_ERR](../../aspose.svg.dom/domexception/hierarchy_request_err/) | 如果任何节点被插入到不属于它的位置。 |
| const [INDEX_SIZE_ERR](../../aspose.svg.dom/domexception/index_size_err/) | 如果索引或大小为负数，或大于允许的值。 |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.svg.dom/domexception/inuse_attribute_err/) | 如果尝试添加已在其他位置使用的属性。 |
| const [INVALID_ACCESS_ERR](../../aspose.svg.dom/domexception/invalid_access_err/) | 如果底层对象不支持某个参数或操作。 |
| const [INVALID_CHARACTER_ERR](../../aspose.svg.dom/domexception/invalid_character_err/) | 如果指定了无效或非法字符，例如在 XML 名称中。 |
| const [INVALID_EXPRESSION_ERR](../../aspose.svg.dom/domexception/invalid_expression_err/) | 表达式存在语法错误，或根据特定 XPathEvaluator 的规则不是合法表达式，或包含此实现不支持的专用扩展函数或变量。 |
| const [INVALID_MODIFICATION_ERR](../../aspose.svg.dom/domexception/invalid_modification_err/) | 如果尝试修改底层对象的类型。 |
| const [INVALID_NODE_TYPE_ERR](../../aspose.svg.dom/domexception/invalid_node_type_err/) | 提供的节点不正确，或其祖先节点不适用于此操作。 |
| const [INVALID_STATE_ERR](../../aspose.svg.dom/domexception/invalid_state_err/) | 如果尝试使用不可用或已不再可用的对象。 |
| const [NAMESPACE_ERR](../../aspose.svg.dom/domexception/namespace_err/) | 如果尝试以与命名空间不匹配的方式创建或更改对象。 |
| const [NETWORK_ERR](../../aspose.svg.dom/domexception/network_err/) | 发生网络错误。 |
| const [NOT_FOUND_ERR](../../aspose.svg.dom/domexception/not_found_err/) | 如果尝试在不存在的上下文中引用节点。 |
| const [NOT_SUPPORTED_ERR](../../aspose.svg.dom/domexception/not_supported_err/) | 如果实现不支持请求的对象类型或操作。 |
| const [NO_DATA_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_data_allowed_err/) | 如果为不支持数据的节点指定了数据。 |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_modification_allowed_err/) | 如果尝试修改不允许修改的对象。 |
| const [QUOTA_EXCEEDED_ERR](../../aspose.svg.dom/domexception/quota_exceeded_err/) | 已超出配额。 |
| const [SECURITY_ERR](../../aspose.svg.dom/domexception/security_err/) | 操作不安全。 |
| const [SYNTAX_ERR](../../aspose.svg.dom/domexception/syntax_err/) | 如果指定了无效或非法的字符串。 |
| const [TIMEOUT_ERR](../../aspose.svg.dom/domexception/timeout_err/) | 操作超时。 |
| const [TYPE_ERR](../../aspose.svg.dom/domexception/type_err/) | 表达式无法转换为返回指定的类型。 |
| const [TYPE_MISMATCH_ERR](../../aspose.svg.dom/domexception/type_mismatch_err/) | 如果对象的类型与与该对象关联的参数的预期类型不兼容。 |
| const [URL_MISMATCH_ERR](../../aspose.svg.dom/domexception/url_mismatch_err/) | 给定的 URL 与另一个 URL 不匹配。 |
| const [VALIDATION_ERR](../../aspose.svg.dom/domexception/validation_err/) | 如果对 insertBefore 或 removeChild 等方法的调用会导致节点在“部分有效性”方面无效，则会抛出此异常，且操作不会完成。此代码用于 [DOM Level 3 Validation]。有关更多信息，请参阅此规范。 |
| const [WRONG_DOCUMENT_ERR](../../aspose.svg.dom/domexception/wrong_document_err/) | 如果节点在与创建它的文档不同的文档中使用（该文档不支持它）。 |

### 另请参阅

* class [PlatformException](../../aspose.svg/platformexception/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

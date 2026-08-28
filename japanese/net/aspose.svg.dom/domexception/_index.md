---
title: "DOMException クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.DOMException クラス。DOMException インターフェイスは、メソッド呼び出しや Web API のプロパティアクセスの結果として発生する例外と呼ばれる異常事象を表します。これは、Web API におけるエラー状態の記述方法そのものです。"
type: docs
weight: 2790
url: /ja/net/aspose.svg.dom/domexception/
---
## DOMException class

DOMException インターフェイスは、Web API のメソッド呼び出しやプロパティへのアクセスに起因して発生する異常事象（例外と呼ばれる）を表します。これは、Web API におけるエラー状態の記述方法そのものです。

```csharp
public class DOMException : PlatformException
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DOMException](domexception/#constructor)(*string*) | `DOMException` クラスの新しいインスタンスを初期化します。 |
| [DOMException](domexception/#constructor_1)(*string, string*) | `DOMException` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Code](../../aspose.svg.dom/domexception/code/) { get; } | エラーコード定数のいずれかを含む値、または一致しない場合は 0 を返します。このフィールドは歴史的な理由で使用されています。 |
| virtual [Data](../../system/exception/data/) { get; } |  |
| virtual [HelpLink](../../system/exception/helplink/) { get; set; } |  |
| [HResult](../../system/exception/hresult/) { get; set; } |  |
| [InnerException](../../system/exception/innerexception/) { get; } |  |
| override [Message](../../aspose.svg.dom/domexception/message/) { get; } | 指定されたエラー名に関連付けられたメッセージまたは説明を表す文字列を返します。 |
| [Name](../../aspose.svg.dom/domexception/name/) { get; } | エラー名に関連付けられた文字列のいずれかを含む文字列を返します。 |
| virtual [Source](../../system/exception/source/) { get; set; } |  |
| virtual [StackTrace](../../system/exception/stacktrace/) { get; } |  |
| [TargetSite](../../system/exception/targetsite/) { get; } |  |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [ABORT_ERR](../../aspose.svg.dom/domexception/abort_err/) | 操作は中止されました。 |
| const [DATA_CLONE_ERR](../../aspose.svg.dom/domexception/data_clone_err/) | オブジェクトはクローンできません。 |
| const [DOMSTRING_SIZE_ERR](../../aspose.svg.dom/domexception/domstring_size_err/) | 指定されたテキスト範囲が DOMString に収まらない場合。 |
| const [HIERARCHY_REQUEST_ERR](../../aspose.svg.dom/domexception/hierarchy_request_err/) | ノードが所属すべきでない場所に挿入された場合。 |
| const [INDEX_SIZE_ERR](../../aspose.svg.dom/domexception/index_size_err/) | インデックスまたはサイズが負の値、または許容範囲を超えている場合。 |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.svg.dom/domexception/inuse_attribute_err/) | 既に他の場所で使用されている属性を追加しようとした場合。 |
| const [INVALID_ACCESS_ERR](../../aspose.svg.dom/domexception/invalid_access_err/) | パラメータまたは操作が基底オブジェクトでサポートされていない場合。 |
| const [INVALID_CHARACTER_ERR](../../aspose.svg.dom/domexception/invalid_character_err/) | XML 名などで無効または不正な文字が指定された場合。 |
| const [INVALID_EXPRESSION_ERR](../../aspose.svg.dom/domexception/invalid_expression_err/) | 式に構文エラーがあるか、特定の XPathEvaluator の規則に従った合法的な式でない、あるいはこの実装でサポートされていない特殊な拡張関数や変数が含まれている場合。 |
| const [INVALID_MODIFICATION_ERR](../../aspose.svg.dom/domexception/invalid_modification_err/) | 基底オブジェクトの型を変更しようとした場合。 |
| const [INVALID_NODE_TYPE_ERR](../../aspose.svg.dom/domexception/invalid_node_type_err/) | 提供されたノードが不正であるか、またはこの操作に対して不適切な祖先ノードを持つ場合。 |
| const [INVALID_STATE_ERR](../../aspose.svg.dom/domexception/invalid_state_err/) | 使用できない、またはもはや使用できなくなったオブジェクトを使用しようとした場合。 |
| const [NAMESPACE_ERR](../../aspose.svg.dom/domexception/namespace_err/) | 名前空間に関して不適切な方法でオブジェクトを作成または変更しようとした場合。 |
| const [NETWORK_ERR](../../aspose.svg.dom/domexception/network_err/) | ネットワークエラーが発生しました。 |
| const [NOT_FOUND_ERR](../../aspose.svg.dom/domexception/not_found_err/) | 存在しないコンテキストで Node を参照しようとした場合。 |
| const [NOT_SUPPORTED_ERR](../../aspose.svg.dom/domexception/not_supported_err/) | 実装が要求されたオブジェクトのタイプまたは操作をサポートしていない場合。 |
| const [NO_DATA_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_data_allowed_err/) | データをサポートしない Node にデータが指定された場合。 |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_modification_allowed_err/) | 変更が許可されていないオブジェクトを変更しようとした場合。 |
| const [QUOTA_EXCEEDED_ERR](../../aspose.svg.dom/domexception/quota_exceeded_err/) | クォータが超過しました。 |
| const [SECURITY_ERR](../../aspose.svg.dom/domexception/security_err/) | 操作が安全ではありません。 |
| const [SYNTAX_ERR](../../aspose.svg.dom/domexception/syntax_err/) | 無効または不正な文字列が指定された場合。 |
| const [TIMEOUT_ERR](../../aspose.svg.dom/domexception/timeout_err/) | 操作がタイムアウトしました。 |
| const [TYPE_ERR](../../aspose.svg.dom/domexception/type_err/) | 式を指定された型で返すように変換できません。 |
| const [TYPE_MISMATCH_ERR](../../aspose.svg.dom/domexception/type_mismatch_err/) | オブジェクトの型が、そのオブジェクトに関連付けられたパラメータの期待型と互換性がない場合。 |
| const [URL_MISMATCH_ERR](../../aspose.svg.dom/domexception/url_mismatch_err/) | 指定された URL が別の URL と一致しません。 |
| const [VALIDATION_ERR](../../aspose.svg.dom/domexception/validation_err/) | insertBefore や removeChild などのメソッド呼び出しが「部分的有効性」に関して Node を無効にする場合、この例外が発生し、操作は実行されません。このコードは [DOM Level 3 Validation] で使用されています。詳細はこの仕様を参照してください。 |
| const [WRONG_DOCUMENT_ERR](../../aspose.svg.dom/domexception/wrong_document_err/) | Node が作成したドキュメントとは異なるドキュメントで使用された場合（サポートされていない場合）。 |

### 参照

* class [PlatformException](../../aspose.svg/platformexception/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

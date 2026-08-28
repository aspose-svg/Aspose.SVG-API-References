---
title: "TypeInfo クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.TypeInfo クラス。TypeInfo は、ドキュメントに関連付けられたスキーマで指定された Element または Attr ノードから参照される型を表します。"
type: docs
weight: 3280
url: /ja/net/aspose.svg.dom/typeinfo/
---
## TypeInfo class

TypeInfo は、ドキュメントに関連付けられたスキーマで指定された、Element または Attr ノードから参照される型を表します。

```csharp
public class TypeInfo : DOMObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [TypeName](../../aspose.svg.dom/typeinfo/typename/) { get; } | 関連付けられた要素または属性に対して宣言された型の名前、または不明な場合は null です。 |
| [TypeNamespace](../../aspose.svg.dom/typeinfo/typenamespace/) { get; } | 型の名前空間を取得します。関連付けられた要素または属性に対して宣言された型の名前空間、または要素に宣言がない場合や名前空間情報が利用できない場合は null です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [IsDerivedFrom](../../aspose.svg.dom/typeinfo/isderivedfrom/)(*string, string, ulong*) | このメソッドは、参照型定義（メソッドが呼び出されている TypeInfo）と、パラメーターとして渡された他の型定義との間に派生関係があるかどうかを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.svg.dom/typeinfo/derivation_extension/) | ドキュメントのスキーマが XML スキーマ [XML Schema Part 1] の場合、この定数は拡張による派生を表します。 |
| const [DERIVATION_LIST](../../aspose.svg.dom/typeinfo/derivation_list/) | ドキュメントのスキーマが XML スキーマ [XML Schema Part 1] の場合、この定数はリストを表します。 |
| const [DERIVATION_RESTRICTION](../../aspose.svg.dom/typeinfo/derivation_restriction/) | ドキュメントのスキーマが XML スキーマ [XML Schema Part 1] の場合、この定数は、複合型が関与している場合は制限による派生、単純型が関与している場合は制限を表します。 |
| const [DERIVATION_UNION](../../aspose.svg.dom/typeinfo/derivation_union/) | ドキュメントのスキーマが XML スキーマ [XML Schema Part 1] の場合、この定数は単純型が関与している場合の合併型を表します。 |

### 参照

* class [DOMObject](../domobject/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

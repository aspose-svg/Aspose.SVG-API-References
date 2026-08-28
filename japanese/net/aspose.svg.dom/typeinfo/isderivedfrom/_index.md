---
title: "TypeInfo.IsDerivedFrom"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "TypeInfo IsDerivedFrom メソッド。このメソッドは、参照型定義（メソッドが呼び出されている TypeInfo）と、パラメータとして渡された他の型定義との間に派生関係があるかどうかを返します。"
type: docs
weight: 30
url: /ja/net/aspose.svg.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

このメソッドは、参照型定義（メソッドが呼び出されている TypeInfo）と、パラメーターとして渡された他の型定義との間に派生関係があるかどうかを返します。

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| typeNamespaceArg | String | 他の型定義の名前空間 |
| typeNameArg | String | 他の型定義の名前です。 |
| derivationMethod | UInt64 | 2 つの型間に適用される派生の種類と条件。インターフェイスで提供されている定数リストに記載されています。 |

### 戻り値

ドキュメントのスキーマが DTD であるか、ドキュメントにスキーマが関連付けられていない場合、このメソッドは常に false を返します。ドキュメントのスキーマが XML Schema の場合、参照型定義が派生パラメータに従って他の型定義から派生しているときに true を返します。パラメータの値が 0（derivationMethod パラメータのビットがすべて 0）である場合、参照型定義から {base type definition}、{item type definition}、または {member type definitions} の任意の組み合わせを再帰的にたどって他の型定義に到達できるときに true を返します。

### 参照

* class [TypeInfo](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

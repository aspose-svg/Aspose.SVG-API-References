---
title: "MutationObserverInit クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Mutations.MutationObserverInit クラス。このクラスは MutationObserver を構成するために使用されるオプションコレクションを表します。"
type: docs
weight: 3120
url: /ja/net/aspose.svg.dom.mutations/mutationobserverinit/
---
## MutationObserverInit class

このクラスは、[`MutationObserver`](../mutationobserver/) を構成するために使用されるオプションコレクションを表します。

```csharp
public class MutationObserverInit : IDictionary<string, object>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MutationObserverInit](mutationobserverinit/)() | `MutationObserverInit` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AttributeFilter](../../aspose.svg.dom.mutations/mutationobserverinit/attributefilter/) { get; set; } | すべての属性変異を観測する必要がなく、attributes が true または省略されている場合は、属性ローカル名（名前空間なし）のリストに設定します。 |
| [AttributeOldValue](../../aspose.svg.dom.mutations/mutationobserverinit/attributeoldvalue/) { get; set; } | attributes が true または省略され、かつ変異前のターゲットの属性値を記録する必要がある場合は true に設定します。 |
| [Attributes](../../aspose.svg.dom.mutations/mutationobserverinit/attributes/) { get; set; } | ターゲットの属性への変異を観測する場合は true に設定します。attributeOldValue および/または attributeFilter が指定されている場合は省略できます。 |
| [CharacterData](../../aspose.svg.dom.mutations/mutationobserverinit/characterdata/) { get; set; } | ターゲットのデータへの変異を観測する場合は true に設定します。characterDataOldValue が指定されている場合は省略できます。 |
| [CharacterDataOldValue](../../aspose.svg.dom.mutations/mutationobserverinit/characterdataoldvalue/) { get; set; } | characterData が true に設定されているか省略され、かつ変異前のターゲットのデータを記録する必要がある場合は true に設定します。 |
| [ChildList](../../aspose.svg.dom.mutations/mutationobserverinit/childlist/) { get; set; } | ターゲットの子要素への変異を観測する場合は true に設定します。 |
| [Count](../../aspose.svg.dom.mutations/mutationobserverinit/count/) { get; } | `MutationObserverInit` コレクションに含まれるキー/値ペアの数を取得します。 |
| [IsReadOnly](../../aspose.svg.dom.mutations/mutationobserverinit/isreadonly/) { get; } | `MutationObserverInit` コレクションが変更可能かどうかを判断します。 |
| [Item](../../aspose.svg.dom.mutations/mutationobserverinit/item/) { get; set; } | 指定されたキーを持つ要素を取得または設定します。 |
| [Keys](../../aspose.svg.dom.mutations/mutationobserverinit/keys/) { get; } | `MutationObserverInit` コレクション内のキーを含むコレクションを取得します。 |
| [Subtree](../../aspose.svg.dom.mutations/mutationobserverinit/subtree/) { get; set; } | ターゲットだけでなく、その子孫への変異も観測する場合は true に設定します。 |
| [Values](../../aspose.svg.dom.mutations/mutationobserverinit/values/) { get; } | `MutationObserverInit` コレクション内の値を含むコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.svg.dom.mutations/mutationobserverinit/add/#add)(*KeyValuePair&lt;string, object&gt;*) | `MutationObserverInit` コレクションに要素を追加します。 |
| [Add](../../aspose.svg.dom.mutations/mutationobserverinit/add/#add_1)(*string, object*) | 指定されたキーと値を `MutationObserverInit` コレクションに追加します。 |
| [Clear](../../aspose.svg.dom.mutations/mutationobserverinit/clear/)() | `MutationObserverInit` コレクションからすべての要素を削除します。 |
| [Contains](../../aspose.svg.dom.mutations/mutationobserverinit/contains/)(*KeyValuePair&lt;string, object&gt;*) | `MutationObserverInit` が指定されたキー/値ペアを含むかどうかを判断します。 |
| [ContainsKey](../../aspose.svg.dom.mutations/mutationobserverinit/containskey/)(*string*) | `MutationObserverInit` コレクションが指定されたキーを含むかどうかを判断します。 |
| [CopyTo](../../aspose.svg.dom.mutations/mutationobserverinit/copyto/)(*KeyValuePair&lt;string, object&gt;[], int*) | `MutationObserverInit` の要素を既存の一次元配列にコピーし、指定された配列インデックスから開始します。 |
| [GetEnumerator](../../aspose.svg.dom.mutations/mutationobserverinit/getenumerator/)() | `MutationObserverInit` の要素を反復処理する列挙子を返します。 |
| [Remove](../../aspose.svg.dom.mutations/mutationobserverinit/remove/#remove)(*KeyValuePair&lt;string, object&gt;*) | `MutationObserverInit` コレクションから指定されたキー/値ペアを削除します。 |
| [Remove](../../aspose.svg.dom.mutations/mutationobserverinit/remove/#remove_1)(*string*) | `MutationObserverInit` コレクションから指定されたキーに関連付けられた値を削除します。 |
| [TryGetValue](../../aspose.svg.dom.mutations/mutationobserverinit/trygetvalue/)(*string, out object*) | 指定されたキーに関連付けられた値を取得します。 |

### 参照

* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)

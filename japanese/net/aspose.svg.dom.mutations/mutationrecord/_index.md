---
title: "MutationRecord クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Mutations.MutationRecord クラス。MutationRecord は個々の DOM 変異を表します。これは MutationObserver の MutationCallback に渡されるオブジェクトです。"
type: docs
weight: 3130
url: /ja/net/aspose.svg.dom.mutations/mutationrecord/
---
## MutationRecord class

MutationRecord は個々の DOM 変異を表します。これは [`MutationObserver`](../mutationobserver/) の [`MutationCallback`](../mutationcallback/) に渡されるオブジェクトです。

```csharp
public class MutationRecord : DOMObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AddedNodes](../../aspose.svg.dom.mutations/mutationrecord/addednodes/) { get; } | 追加されたノードを返します。 |
| [AttributeName](../../aspose.svg.dom.mutations/mutationrecord/attributename/) { get; } | 変更された属性のローカル名を返し、そうでない場合は null を返します。 |
| [AttributeNamespace](../../aspose.svg.dom.mutations/mutationrecord/attributenamespace/) { get; } | 変更された属性の名前空間を返し、そうでない場合は null を返します。 |
| [NextSibling](../../aspose.svg.dom.mutations/mutationrecord/nextsibling/) { get; } | 追加または削除されたノードの次の兄弟ノードを返します。null の場合もあります。 |
| [OldValue](../../aspose.svg.dom.mutations/mutationrecord/oldvalue/) { get; } | 戻り値はタイプに依存します。"attributes" の場合、変更前の属性の値が返されます。"characterData" の場合、変更前のノードのデータが返されます。"childList" の場合、null が返されます。 |
| [PreviousSibling](../../aspose.svg.dom.mutations/mutationrecord/previoussibling/) { get; } | 追加または削除されたノードの前の兄弟ノードを返します。null の場合もあります。 |
| [RemovedNodes](../../aspose.svg.dom.mutations/mutationrecord/removednodes/) { get; } | 削除されたノードを返します。 |
| [Target](../../aspose.svg.dom.mutations/mutationrecord/target/) { get; } | 変異が影響したノードを返します。タイプに応じて異なります。"attributes" の場合、属性が変更された要素が返されます。"characterData" の場合、CharacterData ノードが返されます。"childList" の場合、子が変更されたノードが返されます。 |
| [Type](../../aspose.svg.dom.mutations/mutationrecord/type/) { get; } | "attributes" は属性変異の場合に返され、"characterData" は CharacterData ノードへの変異の場合に返され、"childList" はノードツリーへの変異の場合に返されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |

### 参照

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)

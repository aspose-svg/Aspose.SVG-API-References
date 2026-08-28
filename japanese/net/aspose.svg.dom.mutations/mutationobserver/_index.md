---
title: "MutationObserver クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Mutations.MutationObserver クラス。MutationObserver オブジェクトは Node ツリーへの変異を監視するために使用できます。"
type: docs
weight: 3110
url: /ja/net/aspose.svg.dom.mutations/mutationobserver/
---
## MutationObserver class

`MutationObserver` オブジェクトは [`Node`](../../aspose.svg.dom/node/) ツリーへの変異を監視するために使用できます。

```csharp
public class MutationObserver : DOMObject
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MutationObserver](mutationobserver/)(*[MutationCallback](../mutationcallback/)*) | MutationObserver オブジェクトを構築し、その [`MutationCallback`](../mutationcallback/) を callback に設定します。コールバックは第一引数に MutationRecord オブジェクトのリスト、第二引数に構築された MutationObserver オブジェクトが渡されて呼び出されます。これは [`Observe`](./observe/) メソッドで登録されたノードが変異した後に呼び出されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Disconnect](../../aspose.svg.dom.mutations/mutationobserver/disconnect/)() | オブザーバーが変異の監視を停止します。observe() メソッドが再度使用されるまで、オブザーバーのコールバックは呼び出されません。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe)(*[Node](../../aspose.svg.dom/node/)*) | ユーザーエージェントに対し、指定された対象（ノード）を監視し、options（オブジェクト）で指定された基準に基づいて変異を報告するよう指示します。options 引数はオブジェクトのメンバーを通じて変異監視オプションを設定できるようにします。 |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe_1)(*[Node](../../aspose.svg.dom/node/), [MutationObserverInit](../mutationobserverinit/)*) | ユーザーエージェントに対し、指定された対象（ノード）を監視し、options（オブジェクト）で指定された基準に基づいて変異を報告するよう指示します。options 引数はオブジェクトのメンバーを通じて変異監視オプションを設定できるようにします。 |
| [TakeRecords](../../aspose.svg.dom.mutations/mutationobserver/takerecords/)() | このメソッドはレコードキューのコピーを返し、その後キューを空にします。 |

### 参照

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)

---
title: "IWindow.Opener"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IWindow Opener プロパティ。Window オブジェクトの opener IDL 属性を取得すると、現在の閲覧コンテキストが作成された元の閲覧コンテキスト（オープナー閲覧コンテキスト）が存在し、かつ利用可能で、現在の閲覧コンテキストがオープナーを放棄していない場合は、その WindowProxy オブジェクトを返します。そうでない場合は null を返します。設定時に新しい値が null の場合、現在の閲覧コンテキストはオープナーを放棄しなければなりません。新しい値がそれ以外の場合、ユーザーエージェントは Window オブジェクトの内部メソッド DefineOwnProperty を呼び出し、プロパティ名 opener をプロパティキーとして、プロパティ記述子 { value: <new value>, writable: true, enumerable: true, configurable: true } を渡します。"
type: docs
weight: 60
url: /ja/net/aspose.svg.window/iwindow/opener/
---
## IWindow.Opener property

Window オブジェクトの opener IDL 属性は、取得時に、現在のブラウジングコンテキストが作成された元のブラウジングコンテキスト（その opener ブラウジングコンテキスト）の WindowProxy オブジェクトが存在し、かつ利用可能で、かつ現在のブラウジングコンテキストがその opener を放棄していない場合にそれを返す必要があります。そうでない場合は null を返さなければなりません。設定時に新しい値が null の場合、現在のブラウジングコンテキストはその opener を放棄しなければなりません。新しい値がそれ以外の場合、ユーザーエージェントは Window オブジェクトの [[DefineOwnProperty]] 内部メソッドを呼び出し、プロパティ名 \"opener\" をプロパティキーとして、プロパティ記述子 { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } を渡し、ここで value は新しい値です。

```csharp
public IWindow Opener { get; }
```

### Property Value

オープナー。

### 参照

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)

---
title: "IWindow.Parent"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IWindow Parent プロパティ。Document の Window オブジェクトの parent IDL 属性は、閲覧コンテキスト b が子閲覧コンテキストである場合は親閲覧コンテキストの WindowProxy オブジェクトを、そうでない場合（トップレベル閲覧コンテキストまたは分離された入れ子閲覧コンテキスト）では閲覧コンテキスト b 自身の WindowProxy オブジェクトを返す必要があります。"
type: docs
weight: 70
url: /ja/net/aspose.svg.window/iwindow/parent/
---
## IWindow.Parent property

ブラウジングコンテキスト b 内の Document の Window オブジェクトの parent IDL 属性は、親ブラウジングコンテキストが存在する場合（すなわち b が子ブラウジングコンテキストである場合）にはその WindowProxy オブジェクトを返し、存在しない場合（すなわちトップレベルのブラウジングコンテキストまたは分離された入れ子ブラウジングコンテキストである場合）にはコンテキスト b 自身の WindowProxy オブジェクトを返さなければなりません。

```csharp
public IWindow Parent { get; }
```

### Property Value

親。

### 参照

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)

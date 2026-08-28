---
title: "IWindow.Top"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IWindow Top プロパティ。Document の Window オブジェクトの top IDL 属性は、閲覧コンテキスト b のトップレベル閲覧コンテキストの WindowProxy オブジェクトを返す必要があります。b がトップレベル閲覧コンテキストであればそれ自身の WindowProxy オブジェクトを、そうでなければ（例：分離された入れ子閲覧コンテキストの場合）自身の WindowProxy オブジェクトを返します。"
type: docs
weight: 90
url: /ja/net/aspose.svg.window/iwindow/top/
---
## IWindow.Top property

ブラウジングコンテキスト b 内の Document の Window オブジェクトの top IDL 属性は、トップレベルのブラウジングコンテキストが存在する場合（それがトップレベルのブラウジングコンテキストであればその自身の WindowProxy オブジェクトになります）にはその WindowProxy オブジェクトを返し、存在しない場合（例：分離された入れ子ブラウジングコンテキストである場合）には自身の WindowProxy オブジェクトを返さなければなりません。

```csharp
public IWindow Top { get; }
```

### 参照

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)

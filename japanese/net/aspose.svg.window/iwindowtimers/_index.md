---
title: "IWindowTimers インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Window.IWindowTimers インターフェイス。著者がタイマーベースのコールバックをスケジュールできるようにします"
type: docs
weight: 5940
url: /ja/net/aspose.svg.window/iwindowtimers/
---
## IWindowTimers interface

作者がタイマーに基づくコールバックをスケジュールできるようにします。

```csharp
public interface IWindowTimers
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ClearInterval](../../aspose.svg.window/iwindowtimers/clearinterval/)(*int*) | handle によって識別される setInterval() で設定されたタイムアウトをキャンセルします |
| [ClearTimeout](../../aspose.svg.window/iwindowtimers/cleartimeout/)(*int*) | handle によって識別される setTimeout() で設定されたタイムアウトをキャンセルします。 |
| [SetInterval](../../aspose.svg.window/iwindowtimers/setinterval/)(*object, int, params object[]*) | timeout ミリ秒ごとにハンドラを実行するタイムアウトをスケジュールします。すべての引数はハンドラにそのまま渡されます。 |
| [SetTimeout](../../aspose.svg.window/iwindowtimers/settimeout/)(*object, int, params object[]*) | timeout ミリ秒後にハンドラを実行するタイムアウトをスケジュールします。すべての引数はハンドラにそのまま渡されます。 |

### 参照

* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)

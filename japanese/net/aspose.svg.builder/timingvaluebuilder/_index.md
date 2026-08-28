---
title: "TimingValueBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.TimingValueBuilder クラス。アニメーションやトランジションのタイミングを指定するために使用されるタイミング値を構築します。"
type: docs
weight: 1870
url: /ja/net/aspose.svg.builder/timingvaluebuilder/
---
## TimingValueBuilder class

アニメーションまたはトランジションのタイミングを指定するために使用されるタイミング値を構築します。

```csharp
public class TimingValueBuilder
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TimingValueBuilder](timingvaluebuilder/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddAccessKey](../../aspose.svg.builder/timingvaluebuilder/addaccesskey/)(*char, TimeSpan?*) | アクセスキーに基づくタイミング値を追加します。 |
| [AddEvent](../../aspose.svg.builder/timingvaluebuilder/addevent/)(*string, string, TimeSpan?*) | イベントに基づくタイミング値を追加します。 |
| [AddIndefinite](../../aspose.svg.builder/timingvaluebuilder/addindefinite/)() | 不定のタイミング値を追加します。 |
| [AddOffset](../../aspose.svg.builder/timingvaluebuilder/addoffset/)(*TimeSpan*) | タイミング値に時間オフセットを追加します。 |
| [AddRepeat](../../aspose.svg.builder/timingvaluebuilder/addrepeat/)(*string, int, TimeSpan?*) | 繰り返しに基づくタイミング値を追加します。 |
| [AddSyncbase](../../aspose.svg.builder/timingvaluebuilder/addsyncbase/)(*string, string, TimeSpan?*) | 別の要素のタイミングと同期する syncbase タイミング値を追加します。 |
| [AddWallclock](../../aspose.svg.builder/timingvaluebuilder/addwallclock/)(*DateTime*) | 壁時計タイミング値を追加します。 |
| [Build](../../aspose.svg.builder/timingvaluebuilder/build/)() | 追加されたコンポーネントから最終的なタイミング値文字列を構築します。 |
| static [FormatTimeSpan](../../aspose.svg.builder/timingvaluebuilder/formattimespan/)(*TimeSpan*) | TimeSpan をタイミング値に適した文字列表現にフォーマットします。 |

### 参照

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)

---
title: "SVGException クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.SVGException クラス。この例外は、特定の SVG 操作を実行できない場合に発生します。"
type: docs
weight: 5300
url: /ja/net/aspose.svg/svgexception/
---
## SVGException class

特定の SVG 操作を実行できない場合にこの例外がスローされます。

```csharp
public class SVGException : PlatformException
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGException](svgexception/)(*ushort*) | `SVGException` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Code](../../aspose.svg/svgexception/code/) { get; } | 要求された操作を実行できなかった理由を識別するコードです。このメンバーの値は SVGException コード グループの定数のいずれかになります。 |
| virtual [Data](../../system/exception/data/) { get; } |  |
| virtual [HelpLink](../../system/exception/helplink/) { get; set; } |  |
| [HResult](../../system/exception/hresult/) { get; set; } |  |
| [InnerException](../../system/exception/innerexception/) { get; } |  |
| virtual [Message](../../system/exception/message/) { get; } |  |
| virtual [Source](../../system/exception/source/) { get; set; } |  |
| virtual [StackTrace](../../system/exception/stacktrace/) { get; } |  |
| [TargetSite](../../system/exception/targetsite/) { get; } |  |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [SVG_INVALID_VALUE_ERR](../../aspose.svg/svgexception/svg_invalid_value_err/) | 操作に無効な値が渡されたり属性に割り当てられたときにスローされます。 |
| const [SVG_MATRIX_NOT_INVERTABLE](../../aspose.svg/svgexception/svg_matrix_not_invertable/) | 可逆でない行列の逆行列を求めようとしたときにスローされます。 |
| const [SVG_WRONG_TYPE_ERR](../../aspose.svg/svgexception/svg_wrong_type_err/) | 操作に誤った型のオブジェクトが渡されたときにスローされます。 |

### 参照

* class [PlatformException](../platformexception/)
* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

---
title: Enum Sandbox
second_title: Aspose.SVG for .NET API リファレンス
description: Aspose.Svg.Sandbox 列挙. サンドボックス フラグ セットは次のフラグの 0 個以上のセットであり信頼されていない可能性のあるリソースの機能を制限するために使用されます
type: docs
weight: 3610
url: /ja/net/aspose.svg/sandbox/
---
## Sandbox enumeration

サンドボックス フラグ セットは、次のフラグの 0 個以上のセットであり、信頼されていない可能性のあるリソースの機能を制限するために使用されます。

```csharp
[Flags]
public enum Sandbox
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| None | `0` | フラグは設定されていません。すべてのサンドボックス機能が受け入れられます |
| Navigation | `1` | このフラグは、コンテンツが、サンドボックス化されたブラウジング コンテキスト自体 (またはその内部にさらにネストされたブラウジング コンテキスト)、補助ブラウジング コンテキスト (次に定義されたサンドボックス化された補助ナビゲーション ブラウジング コンテキスト フラグによって保護されている)、およびトップレベル以外のブラウジング コンテキストをナビゲートすることを防ぎます。ブラウジング コンテキスト (以下で定義する、サンドボックス化されたトップレベル ナビゲーションのブラウジング コンテキスト フラグによって保護されます)。 サンドボックス補助ナビゲーション ブラウジング コンテキスト フラグが設定されていない場合でも、特定のケースでは、制限によってポップアップ (新しいトップレベルのブラウジング コンテキスト) を開くことが許可されます。これらのブラウジング コンテキストには、常に 1 つの許可されたサンドボックス ナビゲーターがあり、ブラウジング コンテキストの作成時に設定されます。これにより、それらを作成したブラウジング コンテキストが実際にナビゲートできるようになります。 (そうしないと、サンドボックス ナビゲーション ブラウジング コンテキスト フラグにより、それらが開かれてもナビゲートできなくなります。 |
| AuxiliaryNavigation | `2` | このフラグは、たとえば target 属性や window.open() メソッドを使用して、コンテンツが新しい補助ブラウジング コンテキストを作成するのを防ぎます。 |
| TopLevelNavigation | `4` | このフラグは、コンテンツがトップレベルのブラウジング コンテキストをナビゲートできないようにし、コンテンツがトップレベルのブラウジング コンテキストを閉じないようにします。 サンドボックス化されたトップレベル ナビゲーション ブラウジング コンテキスト フラグが設定されていない場合、コンテンツはそのトップレベル ブラウジング コンテキストをナビゲートできますが、他のブラウジング コンテキストは、サンドボックス化されたナビゲーション ブラウジング コンテキスト フラグと、場合によってはサンドボックス化された補助ナビゲーション ブラウジング コンテキスト フラグによって引き続き保護されます。 |
| Plugins | `8` | このフラグは、embed 要素、object 要素、applet 要素を使用するか、ネストされたブラウジング コンテキストのナビゲーションを介してコンテンツがプラグインをインスタンス化できないようにします。 |
| Origin | `10` | このフラグは、コンテンツを一意のオリジンに強制するため、同じオリジンから他のコンテンツにアクセスできなくなります. |
| Forms | `20` | このフラグはフォームの送信をブロックします. |
| PointerLock | `40` | このフラグは Pointer Lock API を無効にします。 |
| Scripts | `80` | このフラグは、スクリプトの実行をブロックします。 |
| AutomaticFeatures | `100` | このフラグは、ビデオの自動再生やフォーム コントロールの自動フォーカスなど、自動的にトリガーされる機能をブロックします。 |
| Fullscreen | `200` | このフラグは、コンテンツが requestFullscreen() メソッドを使用できないようにします。 |
| DocumentDomain | `400` | このフラグは、コンテンツが document.domain 機能を使用して有効なスクリプトのオリジンを変更するのを防ぎます. |
| Images | `800` | このフラグは画像の読み込みを無効にします. |

### 関連項目

* 名前空間 [Aspose.Svg](../../aspose.svg/)
* 組み立て [Aspose.SVG](../../)


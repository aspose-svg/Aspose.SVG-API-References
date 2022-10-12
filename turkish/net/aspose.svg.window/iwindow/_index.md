---
title: IWindow
second_title: Aspose.SVG for .NET API Referansı
description: Pencere nesnesi bir DOM belgesi içeren bir pencereyi temsil eder.
type: docs
weight: 3740
url: /tr/net/aspose.svg.window/iwindow/
---
## IWindow interface

Pencere nesnesi, bir DOM belgesi içeren bir pencereyi temsil eder.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Document](../../aspose.svg.window/iwindow/document) { get; } | Document özelliği, Window nesnesinin en yeni Document nesnesini döndürmelidir. |
| [FrameElement](../../aspose.svg.window/iwindow/frameelement) { get; } | Bir Belgenin frameElement nesnesi. |
| [Location](../../aspose.svg.window/iwindow/location) { get; } | Pencere arabiriminin konum özniteliği, o Pencere nesnesinin Belgesi için Konum nesnesini döndürmelidir. |
| [Name](../../aspose.svg.window/iwindow/name) { get; set; } | Window nesnesinin name özniteliği, alınırken, tarama bağlamının geçerli adını döndürmeli ve ayar sırasında, tarama bağlamının adını yeni değere ayarlamalıdır. |
| [Opener](../../aspose.svg.window/iwindow/opener) { get; } | Window nesnesindeki açıcı IDL özniteliği, alınırken, mevcut gözatma bağlamının (açıcı gözatma bağlamı) oluşturulduğu gözatma bağlamının WindowProxy nesnesini, eğer varsa, hala kullanılabilir durumdaysa ve varsa mevcut tarama bağlamı, açıcısını reddetmedi; aksi halde null döndürmesi gerekir. Ayarda, yeni değer null ise, mevcut tarama bağlamı, açıcısını reddetmelidir; yeni değer başka bir değerse, kullanıcı aracısının Window nesnesinin [[DefineOwnProperty]] dahili yöntemini çağırması, özellik anahtarı olarak "opener" özellik adını ve Özellik Tanımlayıcısı { [[Value]]: value öğesini çağırması gerekir. , [[Yazılabilir]]: true, [[Sayılandırılabilir]]: true, [[Configurable]]: true } özellik tanımlayıcısı olarak, burada değer yeni değerdir. |
| [Parent](../../aspose.svg.window/iwindow/parent) { get; } | Gözatma bağlamında b bir Belgenin Window nesnesindeki üst IDL özniteliği, varsa (yani b bir alt gözatma bağlamıysa) üst gözatma bağlamının WindowProxy nesnesini veya gözatmanın WindowProxy nesnesini döndürmelidir. bağlam b'nin kendisi, aksi takdirde (yani, üst düzey bir tarama bağlamı veya ayrılmış bir iç içe tarama bağlamıysa). |
| [Self](../../aspose.svg.window/iwindow/self) { get; } | Window nesnesinin gözatma bağlamının WindowProxy nesnesini döndürür. |
| [Top](../../aspose.svg.window/iwindow/top) { get; } | Gözatma bağlamındaki bir Belgenin Window nesnesindeki en üst IDL özniteliği, üst düzey gözatma bağlamının WindowProxy nesnesini döndürmelidir (bu, üst düzey bir göz atma bağlamının kendisi olsaydı, kendi WindowProxy nesnesi olurdu), eğer bunun dışında bir tane veya kendi WindowProxy nesnesi vardır (örneğin, ayrılmış iç içe gözatma bağlamıysa). |
| [Window](../../aspose.svg.window/iwindow/window) { get; } | Window nesnesinin gözatma bağlamının WindowProxy nesnesini döndürür. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Alert](../../aspose.svg.window/iwindow/alert)(string) | Verilen mesajla kalıcı bir uyarı görüntüler ve kullanıcının onu kapatmasını bekler |
| [Confirm](../../aspose.svg.window/iwindow/confirm)(string) | Verilen mesajla kalıcı bir Tamam/İptal istemi görüntüler, kullanıcının bunu kapatmasını bekler ve kullanıcı Tamam'ı tıklatırsa true ve kullanıcı İptal'i tıklatırsa false döndürür. |
| [Prompt](../../aspose.svg.window/iwindow/prompt)(string, string) | Verilen mesajla kalıcı bir metin alanı istemi görüntüler, kullanıcının onu kapatmasını bekler ve kullanıcının girdiği değeri döndürür. Kullanıcı istemi iptal ederse, bunun yerine null döndürür. İkinci argüman mevcutsa, verilen değer varsayılan olarak kullanılır. |

### Ayrıca bakınız

* interface [IDocumentView](../../aspose.svg.dom.views/idocumentview)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget)
* interface [IGlobalEventHandlers](../../aspose.svg.dom/iglobaleventhandlers)
* interface [IWindowEventHandlers](../iwindoweventhandlers)
* interface [IWindowTimers](../iwindowtimers)
* ad alanı [Aspose.Svg.Window](../../aspose.svg.window)
* toplantı [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
---
title: Class XpsDevice
second_title: Aspose.SVG for .NET API Referansı
description: Aspose.Svg.Rendering.Xps.XpsDevice sınıf. Bir xps belgesine dönüştürmeyi temsil eder.
type: docs
weight: 3050
url: /tr/net/aspose.svg.rendering.xps/xpsdevice/
---
## XpsDevice class

Bir xps belgesine dönüştürmeyi temsil eder.

```csharp
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | Yeni bir örneğini başlatır.`XpsDevice` sınıf. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | Yeni bir örneğini başlatır.`XpsDevice` sınıf. |
| [XpsDevice](xpsdevice/#constructor_5)(string) | Yeni bir örneğini başlatır.`XpsDevice` sınıf. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Yeni bir örneğini başlatır.`XpsDevice` oluşturma seçeneklerine ve akış sağlayıcısına göre sınıf. |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | Yeni bir örneğini başlatır.`XpsDevice` işleme seçeneklerine ve çıktı akışına göre sınıf. |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, string) | Yeni bir örneğini başlatır.`XpsDevice` işleme seçeneklerine ve çıktı dosyası adına göre sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } |  |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [AddRect](../../aspose.svg.rendering.xps/xpsdevice/addrect/)(RectangleF) | Geçerli yola eksiksiz bir alt yol olarak bir dikdörtgen ekler. |
| override [BeginDocument](../../aspose.svg.rendering.xps/xpsdevice/begindocument/)(Document) | Belgenin işlenmesine başlar. |
| override [BeginElement](../../aspose.svg.rendering.xps/xpsdevice/beginelement/)(Element, RectangleF) | Öğenin işlenmesine başlar. |
| override [BeginPage](../../aspose.svg.rendering.xps/xpsdevice/beginpage/)(SizeF) | Yeni sayfanın oluşturulmasına başlar. |
| override [Clip](../../aspose.svg.rendering.xps/xpsdevice/clip/)(FillMode) | Doldurulacak bölgeyi belirlemek için FillMode kuralını kullanarak geçerli kırpma yolunu geçerli yolla kesiştirerek değiştirir. Bu yöntem geçerli yolu sonlandırır. |
| override [ClosePath](../../aspose.svg.rendering.xps/xpsdevice/closepath/)() | Mevcut noktadan alt yolun başlangıç noktasına düz bir çizgi parçası ekleyerek mevcut alt yolu kapatır. Mevcut alt yol zaten kapalıysa, "ClosePath" hiçbir şey yapmaz. Bu işleç mevcut alt yolu sonlandırır. Geçerli yola başka bir parça eklemek yeni bir alt yol başlatır, yeni bölüm "ClosePath" yöntemiyle ulaşılan bitiş noktasında başlasa bile . |
| override [CubicBezierTo](../../aspose.svg.rendering.xps/xpsdevice/cubicbezierto/)(PointF, PointF, PointF) | Geçerli yola kübik bir Bézier eğrisi ekler. Eğri, pt1 ve pt2'yi Bézier kontrol noktaları olarak kullanarak mevcut noktadan pt2, noktasına kadar uzanır. Yeni geçerli nokta pt3. |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.svg.rendering.xps/xpsdevice/drawimage/)(byte[], ImageType, RectangleF) | Belirtilen görüntüyü çizer. |
| virtual [EndDocument](../../aspose.svg.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.svg.rendering.xps/xpsdevice/endelement/)(Element) | Öğenin işlenmesini sonlandırır. |
| override [EndPage](../../aspose.svg.rendering.xps/xpsdevice/endpage/)() | Geçerli sayfanın görüntülenmesini sonlandırır. |
| override [Fill](../../aspose.svg.rendering.xps/xpsdevice/fill/)(FillMode) | Geçerli yolun çevrelediği tüm bölgeyi doldurur. Yol birkaç bağlantısız alt yoldan oluşuyorsa, birlikte ele alınan tüm alt yolların içini doldurur. Bu yöntem geçerli yolu sonlandırır. |
| override [FillText](../../aspose.svg.rendering.xps/xpsdevice/filltext/)(string, PointF) | Belirtilen metin dizesini belirtilen konumda doldurur. |
| override [Flush](../../aspose.svg.rendering.xps/xpsdevice/flush/)() | Tüm verileri çıkış akışına boşaltır. |
| override [LineTo](../../aspose.svg.rendering.xps/xpsdevice/lineto/)(PointF) | Geçerli noktadan noktaya (pt) bir düz çizgi parçası ekler. Yeni geçerli nokta pt. |
| override [MoveTo](../../aspose.svg.rendering.xps/xpsdevice/moveto/)(PointF) | Geçerli noktayı pt parametresinin koordinatlarına taşıyarak yeni bir alt yol başlatır, herhangi bir bağlantı çizgisi parçasını atlar. Geçerli yoldaki önceki yol oluşturma yöntemi de "MoveTo" ise, yeni "MoveTo" onu geçersiz kılar; yolda önceki "MoveTo" işleminin hiçbir izi kalmaz. |
| override [RestoreGraphicContext](../../aspose.svg.rendering.xps/xpsdevice/restoregraphiccontext/)() | Tüm grafik bağlamını yığından çıkararak önceki değerine geri yükler. |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device-2/savegraphiccontext/)() |  |
| override [Stroke](../../aspose.svg.rendering.xps/xpsdevice/stroke/)() | Geçerli yol boyunca bir çizgi çizer. Konturlu çizgi, yoldaki her bir düz veya kavisli parçayı takip eder, , kenarları ona paralel olan parçanın üzerinde ortalanır. Yolun alt yollarının her biri ayrı ayrı ele alınır. Bu yöntem geçerli yolu sonlandırır. |
| override [StrokeAndFill](../../aspose.svg.rendering.xps/xpsdevice/strokeandfill/)(FillMode) | Mevcut yolu konturlar ve doldurur. Bu yöntem mevcut yolu sonlandırır. |
| override [StrokeText](../../aspose.svg.rendering.xps/xpsdevice/stroketext/)(string, PointF) | Belirtilen metin dizesini belirtilen konumda okşar. |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| class [XpsGraphicContext](xpsdevice.xpsgraphiccontext/) | XpsDevice için geçerli grafik kontrol parametrelerini tutar. Bu parametreler, grafik işleçlerinin yürüttüğü genel çerçeveyi tanımlar. |

### Ayrıca bakınız

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.svg.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* ad alanı [Aspose.Svg.Rendering.Xps](../../aspose.svg.rendering.xps/)
* toplantı [Aspose.SVG](../../)



---
title: Interface ICSSStyleDeclaration
second_title: Aspose.SVG for .NET API Referansı
description: Aspose.Svg.Dom.Css.ICSSStyleDeclaration arayüz. CSSStyleDeclaration arabirimi tek bir CSS bildirim bloğunu temsil eder. Bu arabirim şu anda bir blokta ayarlanan stil özelliklerini belirlemek veya blok içinde açıkça stil özelliklerini ayarlamak için kullanılabilir.
type: docs
weight: 640
url: /tr/net/aspose.svg.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

CSSStyleDeclaration arabirimi, tek bir CSS bildirim bloğunu temsil eder. Bu arabirim, şu anda bir blokta ayarlanan stil özelliklerini belirlemek veya blok içinde açıkça stil özelliklerini ayarlamak için kullanılabilir.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssstyledeclaration/csstext/) { get; set; } | Bildirim bloğunun ayrıştırılabilir metinsel temsili (çevreleyen kaşlı ayraçlar hariç). Bu özniteliğin ayarlanması, yeni değerin ayrıştırılmasına ve bildirim bloğundaki özelliklerin kaldırılması veya eklenmesi de dahil olmak üzere tüm özelliklerin sıfırlanmasına neden olacaktır. |
| [Item](../../aspose.svg.dom.css/icssstyledeclaration/item/) { get; } | Bu bildirim bloğunda açıkça ayarlanmış olan özellikleri almak için kullanılır. Bu yöntem kullanılarak alınan özelliklerin sırası, ayarlanma sıraları olmak zorunda değildir. Bu yöntem, bu bildirim bloğundaki tüm özellikleri yinelemek için kullanılabilir. |
| [Length](../../aspose.svg.dom.css/icssstyledeclaration/length/) { get; } | Bu bildirim bloğunda açıkça ayarlanmış olan özelliklerin sayısı. Geçerli dizin aralığı 0 ila uzunluk-1'dir. |
| [ParentRule](../../aspose.svg.dom.css/icssstyledeclaration/parentrule/) { get; } | Bu bildirim bloğunu içeren CSS kuralı veya bu CSSStyleDeclaration bir CSSRule. dosyasına eklenmemişse null |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | Bu bildirim bloğu içinde açıkça ayarlanmışsa, bir CSS özelliğinin değerinin nesne gösterimini almak için kullanılır. Özellik bir steno özelliğiyse, bu yöntem null değerini döndürür. Shorthand özellik değerlerine getPropertyValue ve setProperty yöntemleri kullanılarak yalnızca dizeler olarak erişilebilir ve değiştirilebilir. |
| [GetPropertyPriority](../../aspose.svg.dom.css/icssstyledeclaration/getpropertypriority/)(string) | Özellik bu bildirim bloğunda açıkça ayarlanmışsa, bir CSS özelliğinin (örn. "önemli" niteleyicisi) önceliğini almak için kullanılır. |
| [GetPropertyValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | Bu bildirim bloğu içinde açıkça ayarlanmışsa bir CSS özelliğinin değerini almak için kullanılır. |
| [RemoveProperty](../../aspose.svg.dom.css/icssstyledeclaration/removeproperty/)(string) | Bu bildirim bloğu içinde açıkça ayarlanmışsa bir CSS özelliğini kaldırmak için kullanılır. |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | Bu bildirim bloğu içinde varsayılan önceliğe sahip bir özellik değeri ayarlamak için kullanılır. Varsayılan öncelik "önemli" değildir, yani String.Empty |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | Bu bildirim bloğu içinde bir özellik değeri ve öncelik ayarlamak için kullanılır. |

### Ayrıca bakınız

* interface [ICSS2Properties](../icss2properties/)
* ad alanı [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* toplantı [Aspose.SVG](../../)



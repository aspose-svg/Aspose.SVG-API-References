---
title: TypeInfo
second_title: Aspose.SVG for .NET API Referansı
description: TypeInfo belgeyle ilişkili şemalarda belirtilen Öğe veya Attr düğümlerinden başvurulan bir türü temsil eder.
type: docs
weight: 1280
url: /tr/net/aspose.svg.dom/typeinfo/
---
## TypeInfo class

TypeInfo, belgeyle ilişkili şemalarda belirtilen Öğe veya Attr düğümlerinden başvurulan bir türü temsil eder.

```csharp
public class TypeInfo : DOMObject
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [TypeName](../../aspose.svg.dom/typeinfo/typename) { get; } | İlişkili öğe veya öznitelik için bildirilen bir türün adı veya bilinmiyorsa null. |
| [TypeNamespace](../../aspose.svg.dom/typeinfo/typenamespace) { get; } | Ad alanı türünü alır. İlişkili öğe veya öznitelik için bildirilen türün ad alanı veya öğenin bildirimi yoksa veya ad alanı bilgisi yoksa null. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Bu yöntem, ECMAScript nesnesini almak için kullanılırType . |
| [IsDerivedFrom](../../aspose.svg.dom/typeinfo/isderivedfrom)(string, string, ulong) | Bu yöntem, referans türü tanımı, yani yöntemin çağrıldığı TypeInfo ile diğer tür tanımı, yani parametre olarak geçirilen tür arasında bir türetme varsa döner. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.svg.dom/typeinfo/derivation_extension) | Belgenin şeması bir XML Şemasıysa [XML Şeması Bölüm 1], bu sabit, uzantıya göre türetmeyi temsil eder. |
| const [DERIVATION_LIST](../../aspose.svg.dom/typeinfo/derivation_list) | Belgenin şeması bir XML Şemasıysa [XML Şeması Bölüm 1], bu sabit listeyi temsil eder. |
| const [DERIVATION_RESTRICTION](../../aspose.svg.dom/typeinfo/derivation_restriction) | Belgenin şeması bir XML Şemasıysa [XML Şeması Bölüm 1], bu sabit karmaşık türler söz konusuysa kısıtlamaya göre türetmeyi veya basit türler söz konusuysa bir kısıtlamayı temsil eder. |
| const [DERIVATION_UNION](../../aspose.svg.dom/typeinfo/derivation_union) | Belgenin şeması bir XML Şemasıysa [XML Şeması Bölüm 1], basit türler söz konusuysa bu sabit birliği temsil eder. |

### Ayrıca bakınız

* class [DOMObject](../domobject)
* ad alanı [Aspose.Svg.Dom](../../aspose.svg.dom)
* toplantı [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
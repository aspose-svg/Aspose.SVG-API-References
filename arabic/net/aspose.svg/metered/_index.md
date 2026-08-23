---
title: "فئة Metered"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Metered. توفر طرقًا لتعيين المفتاح المقيس."
type: docs
weight: 4270
url: /ar/net/aspose.svg/metered/
---
## Metered class

يوفر طرقًا لتعيين المفتاح المقاس.

```csharp
public class Metered
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [Metered](metered/)() | ينشئ مثيلًا جديدًا لهذه الفئة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SetMeteredKey](../../aspose.svg/metered/setmeteredkey/)(*string, string*) | يضبط المفتاح العام والخاص المقيس. إذا قمت بشراء ترخيص مقيس، عند بدء التطبيق يجب استدعاء هذه الواجهة البرمجية، عادةً يكون ذلك كافيًا. ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوز 24 ساعة، سيتم تعيين الترخيص إلى حالة التقييم؛ لتجنب ذلك، يجب عليك فحص حالة الترخيص بانتظام، وإذا كانت في حالة التقييم، استدعِ هذه الواجهة البرمجية مرة أخرى. |
| static [GetConsumptionCredit](../../aspose.svg/metered/getconsumptioncredit/)() | يحصل على رصيد الاستهلاك |
| static [GetConsumptionQuantity](../../aspose.svg/metered/getconsumptionquantity/)() | يحصل على حجم ملف الاستهلاك |
| static [IsMeteredLicensed](../../aspose.svg/metered/ismeteredlicensed/)() | تحقق مما إذا كان المتري مرخصًا |

## أمثلة

في هذا المثال، سيتم محاولة تعيين المفتاح العام والخاص للعداد

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

ملف jar المكوّن:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### انظر أيضًا

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

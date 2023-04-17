---
title: Class Metered
second_title: Aspose.SVG لمرجع .NET API
description: Aspose.Svg.Metered فصل. يوفر طرقًا لتعيين المفتاح المقنن .
type: docs
weight: 2200
url: /ar/net/aspose.svg/metered/
---
## Metered class

يوفر طرقًا لتعيين المفتاح المقنن .

```csharp
public class Metered
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Metered](metered/)() | تهيئة مثيل جديد لهذه الفئة. |

## طُرق

| اسم | وصف |
| --- | --- |
| [SetMeteredKey](../../aspose.svg/metered/setmeteredkey/)(string, string) | مجموعات المفاتيح العامة والخاصة التي تم قياسها . إذا قمت بشراء ترخيص مقنن ، عند بدء التطبيق ، يجب استدعاء واجهة برمجة التطبيقات هذه ، عادةً ، هذا يكفي. ومع ذلك ، إذا فشلت دائمًا في تحميل بيانات الاستهلاك وتجاوزت 24 ساعة ، فسيتم تعيين الترخيص على حالة التقييم ، لتجنب مثل هذه الحالة ، يجب عليك التحقق بانتظام من حالة الترخيص ، إذا كانت حالة التقييم ، فاتصل بواجهة برمجة التطبيقات هذه مرة أخرى. |
| static [GetConsumptionCredit](../../aspose.svg/metered/getconsumptioncredit/)() | يحصل على ائتمان الاستهلاك |
| static [GetConsumptionQuantity](../../aspose.svg/metered/getconsumptionquantity/)() | يحصل على حجم ملف الاستهلاك |

### أمثلة

في هذا المثال ، ستُبذل محاولة لتعيين المفتاح العام والخاص الذي تم قياسه

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

ملف جرة المكون:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### أنظر أيضا

* مساحة الاسم [Aspose.Svg](../../aspose.svg/)
* المجسم [Aspose.SVG](../../)



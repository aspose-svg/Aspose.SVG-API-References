---
title: "فئة License"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.License فئة. يوفر طرقًا لترخيص المكوّن."
type: docs
weight: 4260
url: /ar/net/aspose.svg/license/
---
## License class

يوفر طرقًا لترخيص المكوّن.

```csharp
public class License
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [License](license/)() | ينشئ مثيلًا جديدًا لهذه الفئة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense)(*Stream*) | يرخص المكوّن. |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense_1)(*string*) | يرخص المكوّن. |

## أمثلة

في هذا المثال، سيتم محاولة العثور على ملف ترخيص يُدعى MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المدمجة للتجميع المستدعي.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

ملف jar المكوّن:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### انظر أيضًا

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

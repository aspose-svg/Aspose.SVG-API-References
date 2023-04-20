---
title: Class Metered
second_title: .NET API संदर्भ के लिए Aspose.SVG
description: Aspose.Svg.Metered कक्ष. मटर्ड कुंज सेट करने के तरके प्रदन करत है
type: docs
weight: 2200
url: /hi/net/aspose.svg/metered/
---
## Metered class

मीटर्ड कुंजी सेट करने के तरीके प्रदान करता है।

```csharp
public class Metered
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Metered](metered/)() | इस वर्ग का एक नया उदाहरण आरंभ करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [SetMeteredKey](../../aspose.svg/metered/setmeteredkey/)(string, string) | मीटर्ड सार्वजनिक और निजी कुंजी सेट करता है। यदि आप मीटर्ड लाइसेंस खरीदते हैं, तो आवेदन शुरू करते समय, इस एपीआई को कॉल किया जाना चाहिए, सामान्य रूप से, यह पर्याप्त है। हालांकि, यदि खपत डेटा अपलोड करने में हमेशा विफल रहता है और 24 घंटे से अधिक हो जाता है, तो लाइसेंस मूल्यांकन स्थिति पर सेट हो जाएगा, ऐसे मामले से बचने के लिए, आपको नियमित रूप से लाइसेंस स्थिति की जांच करनी चाहिए, यदि यह मूल्यांकन स्थिति है, तो इस एपीआई को फिर से कॉल करें। |
| static [GetConsumptionCredit](../../aspose.svg/metered/getconsumptioncredit/)() | उपभोग क्रेडिट प्राप्त करता है |
| static [GetConsumptionQuantity](../../aspose.svg/metered/getconsumptionquantity/)() | उपभोग फ़ाइल आकार प्राप्त करता है |

### उदाहरण

इस उदाहरण में, मीटर्ड सार्वजनिक और निजी कुंजी सेट करने का प्रयास किया जाएगा

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

घटक जार फ़ाइल:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### यह सभी देखें

* नाम स्थान [Aspose.Svg](../../aspose.svg/)
* सभा [Aspose.SVG](../../)



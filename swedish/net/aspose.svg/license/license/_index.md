---
title: "Licens"
second_title: "Aspose.SVG för .NET API-referens"
description: "Licenskonstruktör. Initierar en ny instans av den här klassen"
type: docs
weight: 10
url: /sv/net/aspose.svg/license/license/
---
## License constructor

Initierar en ny instans av denna klass.

```csharp
public License()
```

## Exempel

I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande sammansättningen, i mappen för startsammanställningen och sedan i de inbäddade resurserna för den anropande sammansättningen.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

komponent‑jar‑filen:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Se även

* class [License](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

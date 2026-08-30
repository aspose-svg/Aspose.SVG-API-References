---
title: "License.SetLicense"
second_title: "Aspose.SVG för .NET API-referens"
description: "Metoden License SetLicense. Licensierar komponenten."
type: docs
weight: 20
url: /sv/net/aspose.svg/license/setlicense/
---
## SetLicense(*string*) {#setlicense_1}

Licensierar komponenten.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseName | String | Kan vara ett fullständigt eller kort filnamn eller namn på en inbäddad resurs. Använd en tom sträng för att växla till evalueringsläge. |

## Anmärkningar

Försöker hitta licensen på följande platser:

1. Explicit sökväg.

2. Mappen som innehåller Aspose-komponentens assembly.

3. Mappen som innehåller klientens anropande assembly.

4. Mappen som innehåller entry (startup)-assemblyn.

5. En inbäddad resurs i klientens anropande assembly.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Explicit sökväg.

2. En inbäddad resurs i klientens anropande assembly.

2. Mappen som innehåller Aspose-komponentens JAR‑fil.

3. Mappen som innehåller klientens anropande JAR‑fil.

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

---

## SetLicense(*Stream*) {#setlicense}

Licensierar komponenten.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | En ström som innehåller licensen. |

## Anmärkningar

Använd den här metoden för att läsa in en licens från en ström.

## Exempel

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);
```

### Se även

* class [License](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

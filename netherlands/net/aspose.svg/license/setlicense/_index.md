---
title: "License.SetLicense"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "License SetLicense-methode. Licentieert het component"
type: docs
weight: 20
url: /nl/net/aspose.svg/license/setlicense/
---
## SetLicense(*string*) {#setlicense_1}

Licentieert de component.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licenseName | String | Kan een volledige of korte bestandsnaam of de naam van een ingebedde resource zijn. Gebruik een lege tekenreeks om over te schakelen naar evaluatiemodus. |

## Opmerkingen

Probeert de licentie te vinden op de volgende locaties:

1. Expliciet pad.

2. De map die de Aspose‑componentassembly bevat.

3. De map die de aanroepende assembly van de client bevat.

4. De map die de entry‑ (opstart‑)assembly bevat.

5. Een ingebedde resource in de aanroepende assembly van de client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Expliciet pad.

2. Een ingebedde resource in de aanroepende assembly van de client.

2. De map die het Aspose‑component‑JAR‑bestand bevat.

3. De map die het JAR‑bestand van de aanroepende client bevat.

## Voorbeelden

In dit voorbeeld wordt geprobeerd een licentiebestand met de naam MyLicense.lic te vinden in de map die de component bevat, in de map die de aanroepende assembly bevat, in de map van de entry-assembly en vervolgens in de ingebedde resources van de aanroepende assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

het component‑jar‑bestand:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Zie ook

* class [License](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SetLicense(*Stream*) {#setlicense}

Licentieert de component.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | Een stream die de licentie bevat. |

## Opmerkingen

Gebruik deze methode om een licentie uit een stream te laden.

## Voorbeelden

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);
```

### Zie ook

* class [License](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

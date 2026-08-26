---
title: "License Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.License Klasse. Stellt Methoden bereit, um die Komponente zu lizenzieren"
type: docs
weight: 4260
url: /de/net/aspose.svg/license/
---
## License class

Stellt Methoden zur Lizenzierung der Komponente bereit.

```csharp
public class License
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [License](license/)() | Initialisiert eine neue Instanz dieser Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense)(*Stream*) | Lizenziert die Komponente. |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense_1)(*string*) | Lizenziert die Komponente. |

## Beispiele

In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg‑Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

die Komponenten‑Jar‑Datei:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Siehe auch

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

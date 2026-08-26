---
title: "License"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "License-Konstruktor. Initialisiert eine neue Instanz dieser Klasse"
type: docs
weight: 10
url: /de/net/aspose.svg/license/license/
---
## License constructor

Initialisiert eine neue Instanz dieser Klasse.

```csharp
public License()
```

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

* class [License](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

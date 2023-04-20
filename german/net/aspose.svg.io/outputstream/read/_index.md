---
title: OutputStream.Read
second_title: Aspose.SVG für .NET-API-Referenz
description: OutputStream methode. Liest eine Folge von Bytes aus dem umschlossenen Ausgabestream und erhöht die Position innerhalb des Streams um die Anzahl der gelesenen Bytes.
type: docs
weight: 100
url: /de/net/aspose.svg.io/outputstream/read/
---
## OutputStream.Read method

Liest eine Folge von Bytes aus dem umschlossenen Ausgabestream und erhöht die Position innerhalb des Streams um die Anzahl der gelesenen Bytes.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | Byte[] | Ein Array von Bytes. Wenn diese Methode zurückkehrt, enthält der Puffer das angegebene Byte-Array mit den Werten zwischen Offset und (Offset + Anzahl - 1), ersetzt durch die Bytes, die aus dem umschlossenen Ausgabestrom gelesen werden. |
| offset | Int32 | Der nullbasierte Byte-Offset im Puffer, bei dem mit dem Speichern der Daten read aus dem umschlossenen Ausgabestream begonnen werden soll. |
| count | Int32 | Die maximale Anzahl von Bytes, die aus dem verpackten Ausgabestream gelesen werden sollen. |

### Rückgabewert

Die Gesamtzahl der in den Puffer gelesenen Bytes. Dies kann weniger als die Anzahl der angeforderten Bytes sein, wenn derzeit nicht so viele Bytes verfügbar sind, oder null (0) , wenn das Ende des Streams erreicht wurde.

### Siehe auch

* class [OutputStream](../)
* namensraum [Aspose.Svg.IO](../../outputstream/)
* Montage [Aspose.SVG](../../../)



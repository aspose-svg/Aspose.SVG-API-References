---
title: "IDOMImplementation Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.IDOMImplementation Schnittstelle. Die DOMImplementation-Schnittstelle stellt eine Reihe von Methoden bereit, um Vorgänge auszuführen, die unabhängig von einer bestimmten Instanz des Document Object Model sind."
type: docs
weight: 3040
url: /de/net/aspose.svg.dom/idomimplementation/
---
## IDOMImplementation interface

Das DOMImplementation‑Interface stellt eine Reihe von Methoden bereit, um Vorgänge auszuführen, die von keiner konkreten Instanz des Document Object Model abhängig sind.

```csharp
public interface IDOMImplementation
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateDocument](../../aspose.svg.dom/idomimplementation/createdocument/)(*string, string, [DocumentType](../documenttype/)*) | Erstellt ein DOM Document-Objekt des angegebenen Typs mit seinem Dokument-Element. |
| [CreateDocumentType](../../aspose.svg.dom/idomimplementation/createdocumenttype/)(*string, string, string*) | Erstellt einen leeren DocumentType-Knoten. Entity-Deklarationen und Notationen werden nicht bereitgestellt. Entity-Referenzerweiterungen und das Hinzufügen von Standardattributen finden nicht statt. |
| [CreateHTMLDocument](../../aspose.svg.dom/idomimplementation/createhtmldocument/)(*string*) | Gibt ein Dokument zurück, dessen Grundstruktur bereits ein Titel-Element enthält, sofern das title-Argument nicht weggelassen wird. |
| [HasFeature](../../aspose.svg.dom/idomimplementation/hasfeature/)() | Prüft, ob die DOM-Implementierung ein bestimmtes Feature und eine bestimmte Version implementiert, wie in DOM Features angegeben. |

### Siehe auch

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)

---
title: "Aspose.Svg.Dom"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Der Aspose.Svg.Dom Document Object Model-Namespace stellt eine API bereit, die beliebige HTML-, XML- oder SVG-Dokumente repräsentiert und mit ihnen interagiert. Das DOM ist ein im Browser geladenes Dokumentenmodell, das das Dokument als Knotbaum darstellt, wobei jeder Knoten einen Teil des Dokuments repräsentiert, z. B. ein Element, eine Textzeichenfolge oder einen Kommentar."
type: docs
weight: 70
url: /de/net/aspose.svg.dom/
---
Der **Aspose.Svg.Dom (Document Object Model)** Namensraum stellt eine API bereit, die beliebige HTML-, XML‑ oder SVG‑Dokumente darstellt und mit ihnen interagiert. Das DOM ist ein im Browser geladenes Dokumentenmodell, das das Dokument als Knotbaum darstellt, wobei jeder Knoten einen Teil des Dokuments repräsentiert (z. B. ein Element, eine Textzeichenfolge oder ein Kommentar).

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Attr](./attr/) | Das Attr-Interface repräsentiert ein Attribut in einem Element-Objekt. Typischerweise werden die zulässigen Werte für das Attribut in einem dem Dokument zugehörigen Schema definiert. |
| [CDATASection](./cdatasection/) | CDATA-Abschnitte werden verwendet, um Textblöcke zu maskieren, die Zeichen enthalten, die sonst als Markup betrachtet würden. |
| [CharacterData](./characterdata/) | Das CharacterData erweitert Node um eine Reihe von Attributen und Methoden zum Zugriff auf Zeichendaten im DOM. |
| [Comment](./comment/) | Erbt von CharacterData und stellt den Inhalt eines Kommentars dar, d. h. alle Zeichen zwischen dem startenden ''. |
| [Document](./document/) | Das Document repräsentiert das gesamte HTML-, XML- oder SVG-Dokument. Konzeptionell ist es die Wurzel des Dokumentbaums und bietet den primären Zugriff auf die Daten des Dokuments. |
| [DocumentFragment](./documentfragment/) | DocumentFragment ist ein "leichtgewichtiges" oder "minimalistisches" Document-Objekt. Es ist sehr üblich, einen Teil des Dokumentbaums extrahieren oder ein neues Fragment eines Dokuments erstellen zu wollen. |
| [DocumentType](./documenttype/) | Der DocumentType stellt ein Interface zur Liste der für das Dokument definierten Entitäten bereit. |
| [DOMException](./domexception/) | Das DOMException-Interface repräsentiert ein abnormales Ereignis (eine Ausnahme), das als Ergebnis eines Methodenaufrufs oder des Zugriffs auf eine Eigenschaft einer Web-API auftritt. Dies ist im Wesentlichen die Art und Weise, wie Fehlbedingungen in Web-APIs beschrieben werden. |
| [DOMObject](./domobject/) | Der DOMObject-Typ wird verwendet, um ein Basisobjekt für das gesamte Document Object Model zu repräsentieren. Für Java und ECMAScript ist DOMObject an den Object-Typ gebunden. |
| [Element](./element/) | Das Element-Interface repräsentiert ein Element in einem HTML- oder XML-Dokument. |
| [Entity](./entity/) | Stellt eine bekannte Entität, entweder geparst oder ungeparst, in einem XML-Dokument dar. |
| [EntityReference](./entityreference/) | EntityReference-Knoten können verwendet werden, um eine Entitätsreferenz im Baum darzustellen. |
| [EventTarget](./eventtarget/) | Das [`EventTarget`](../aspose.svg.dom/eventtarget/) Interface wird von allen Nodes in einer Implementierung, die das DOM‑Ereignismodell unterstützt, implementiert. Daher kann dieses Interface durch bindungsspezifische Cast‑Methoden auf einer Instanz des Node‑Interfaces erhalten werden. Das Interface ermöglicht die Registrierung und das Entfernen von Event‑Listenern auf einem [`EventTarget`](../aspose.svg.dom/eventtarget/) sowie das Senden von Ereignissen an dieses [`IEventTarget`](../aspose.svg.dom.events/ieventtarget/). |
| [Node](./node/) | Das Node-Interface ist der primäre Datentyp für das gesamte Document Object Model. Es repräsentiert einen einzelnen Knoten im Dokumentbaum. |
| [Notation](./notation/) | Stellt eine im DTD deklarierte Notation dar. |
| [ProcessingInstruction](./processinginstruction/) | Das ProcessingInstruction repräsentiert eine "Verarbeitungsanweisung", die in XML verwendet wird, um prozessorspezifische Informationen im Text des Dokuments zu speichern. |
| [QualifiedName](./qualifiedname/) | Stellt einen qualifizierten HTML-Namen dar. |
| [ShadowRoot](./shadowroot/) | ShadowRoot ist ein Wurzelknoten des Shadow-Baums. |
| [Text](./text/) | Die Text-Schnittstelle erbt von CharacterData und stellt den Textinhalt (in XML als Zeichendaten bezeichnet) eines Elements oder Attr dar. |
| [TypeInfo](./typeinfo/) | Die TypeInfo repräsentiert einen Typ, der von Element- oder Attr-Knoten referenziert wird und in den mit dem Dokument verknüpften Schemata angegeben ist. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | Ein Browsing-Context ist eine Umgebung, in der [`Document`](../aspose.svg.dom/document/)‑Objekte dem Benutzer präsentiert werden. |
| [IChildNode](./ichildnode/) | Definiert das [`IChildNode`](../aspose.svg.dom/ichildnode/)‑Interface, das von [`Node`](../aspose.svg.dom/node/) implementiert werden sollte, das einen Elternknoten haben kann. |
| [IDOMImplementation](./idomimplementation/) | Das DOMImplementation‑Interface stellt eine Reihe von Methoden bereit, um Vorgänge auszuführen, die von keiner konkreten Instanz des Document Object Model abhängig sind. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Repräsentiert ein Interface, das von allen Elementen, die systemweite Ereignisbehandlung unterstützen, geerbt werden muss. |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | Definiert [`IChildNode`](../aspose.svg.dom/ichildnode/), die nicht [`DOCUMENT_TYPE_NODE`](../aspose.svg.dom/node/document_type_node/) sind. |
| [INonElementParentNode](./inonelementparentnode/) | Definiert [`IParentNode`](../aspose.svg.dom/iparentnode/), die nicht vom Typ Element sind. |
| [IParentNode](./iparentnode/) | Definiert das [`IParentNode`](../aspose.svg.dom/iparentnode/)‑Interface, das von allen möglichen Eltern implementiert wird. |
| [IStorage](./istorage/) | Dieses Interface der Web-Storage-API bietet Zugriff auf die Sitzungs- oder Local-Storage einer bestimmten Domain. Siehe Web-Storage-Spezifikation: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | Modi, in denen ShadowRoot betrieben werden kann. |

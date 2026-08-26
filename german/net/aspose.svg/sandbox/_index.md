---
title: "Sandbox‑Enum"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Sandbox‑Enum. Ein Sandbox‑Flag‑Set ist eine Menge von null oder mehr der folgenden Flags, die verwendet werden, um die Fähigkeiten potenziell nicht vertrauenswürdiger Ressourcen einzuschränken."
type: docs
weight: 5680
url: /de/net/aspose.svg/sandbox/
---
## Sandbox enumeration

Ein Sandbox-Flag-Set ist eine Menge von null oder mehr der folgenden Flags, die verwendet werden, um die Fähigkeiten potenziell nicht vertrauenswürdiger Ressourcen einzuschränken.

```csharp
[Flags]
public enum Sandbox
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Kein Flag ist gesetzt, jedes Sandbox‑Feature wird akzeptiert. |
| Navigation | `1` | Dieses Flag verhindert, dass Inhalte Browsing‑Kontexte navigieren, die nicht der sandboxed browsing context selbst (oder weiter darin verschachtelte Browsing‑Kontexte) sind, Hilfs‑Browsing‑Kontexte (die durch das im Folgenden definierte sandboxed auxiliary navigation browsing context‑Flag geschützt sind) und der Top‑Level‑Browsing‑Kontext (der durch das unten definierte sandboxed top-level navigation browsing context‑Flag geschützt ist). Wenn das sandboxed auxiliary navigation browsing context‑Flag nicht gesetzt ist, erlauben die Beschränkungen in bestimmten Fällen dennoch das Öffnen von Pop‑ups (neuen Top‑Level‑Browsing‑Kontexten). Diese Browsing‑Kontexte haben stets einen zulässigen sandboxed Navigator, der beim Erzeugen des Browsing‑Kontexts festgelegt wird und dem erstellenden Browsing‑Kontext erlaubt, sie tatsächlich zu navigieren. (Andernfalls würde das sandboxed navigation browsing context‑Flag sie selbst dann verhindern, wenn sie geöffnet wurden.) |
| AuxiliaryNavigation | `2` | Dieses Flag verhindert, dass Inhalte neue Hilfs‑Browsing‑Kontexte erstellen, z. B. durch die Verwendung des target‑Attributs oder der window.open()-Methode. |
| TopLevelNavigation | `4` | Dieses Flag verhindert, dass Inhalte ihren Top‑Level‑Browsing‑Kontext navigieren und verhindert, dass Inhalte ihren Top‑Level‑Browsing‑Kontext schließen. Wenn das Sandbox‑Top‑Level‑Navigations‑Browsing‑Kontext‑Flag nicht gesetzt ist, können Inhalte ihren Top‑Level‑Browsing‑Kontext navigieren, aber andere Browsing‑Kontexte bleiben weiterhin durch das Sandbox‑Navigations‑Browsing‑Kontext‑Flag und ggf. das Sandbox‑Hilfs‑Navigations‑Browsing‑Kontext‑Flag geschützt. |
| Plugins | `8` | Dieses Flag verhindert, dass Inhalte Plugins instanziieren, sei es über das embed‑Element, das object‑Element, das applet‑Element oder durch Navigation eines verschachtelten Browsing‑Kontexts, es sei denn, diese Plugins können gesichert werden. |
| Origin | `10` | Dieses Flag zwingt Inhalte in einen eindeutigen Ursprung, wodurch verhindert wird, dass sie auf andere Inhalte desselben Ursprungs zugreifen. |
| Forms | `20` | Dieses Flag blockiert das Absenden von Formularen. |
| PointerLock | `40` | Dieses Flag deaktiviert die Pointer‑Lock‑API. |
| Scripts | `80` | Dieses Flag blockiert die Skriptausführung. |
| AutomaticFeatures | `100` | Dieses Flag blockiert Funktionen, die automatisch ausgelöst werden, wie das automatische Abspielen eines Videos oder das automatische Fokussieren einer Formularkontrolle. |
| Fullscreen | `200` | Dieses Flag verhindert, dass Inhalte die requestFullscreen()-Methode verwenden. |
| DocumentDomain | `400` | Dieses Flag verhindert, dass Inhalte die document.domain‑Funktion nutzen, um den effektiven Skript‑Ursprung zu ändern. |
| Images | `800` | Dieses Flag deaktiviert das Laden von Bildern. |

### Siehe auch

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

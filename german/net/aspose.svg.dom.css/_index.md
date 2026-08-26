---
title: "Aspose.Svg.Dom.Css"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Der Aspose.Svg.Dom.Css-Namespace dient allen CSS-bezogenen Manipulationen. Er konzentriert sich auf CSS‑Eigenschafts‑Name‑Wert‑Paare, die in den offiziellen CSS-Dokumenten festgelegt sind."
type: docs
weight: 90
url: /de/net/aspose.svg.dom.css/
---
Der **Aspose.Svg.Dom.Css** Namensraum dient allen CSS‑bezogenen Manipulationen. Er konzentriert sich auf von offiziellen CSS‑Dokumenten festgelegte CSS‑Eigenschafts‑Name‑Wert‑Paare.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Counter](./counter/) | Das Counter-Interface wird verwendet, um einen beliebigen Counter‑ oder Counters‑Funktionswert darzustellen. Dieses Interface spiegelt die Werte in der zugrunde liegenden Style‑Property wider. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | Das CSSPrimitiveValue-Interface repräsentiert einen einzelnen CSS‑Wert. Dieses Interface kann verwendet werden, um den Wert einer bestimmten Style‑Property, die derzeit in einem Block gesetzt ist, zu bestimmen oder um eine bestimmte Style‑Property explizit innerhalb des Blocks zu setzen. Eine Instanz dieses Interfaces kann über die getPropertyCSSValue‑Methode des CSSStyleDeclaration-Interfaces erhalten werden. Ein CSSPrimitiveValue‑Objekt tritt nur im Kontext einer CSS‑Property auf. |
| [CSSValue](./cssvalue/) | Stellt einen einfachen oder komplexen Wert dar. Ein CSSValue‑Objekt tritt nur im Kontext einer CSS‑Property auf. |
| [CSSValueList](./cssvaluelist/) | Das CSSValueList-Interface bietet die Abstraktion einer geordneten Sammlung von CSS-Werten. |
| [Rect](./rect/) | Das Rect-Interface wird verwendet, um einen beliebigen Rechteckwert darzustellen. Dieses Interface spiegelt die Werte in der zugrunde liegenden Style-Eigenschaft wider. Daher ändern Änderungen an den CSSPrimitiveValue-Objekten die Style-Eigenschaft. |
| [RGBColor](./rgbcolor/) | Das RGBColor-Interface wird verwendet, um einen beliebigen RGB-Farbwert darzustellen. Dieses Interface spiegelt die Werte in der zugrunde liegenden Style-Eigenschaft wider. Daher ändern Änderungen an den CSSPrimitiveValue-Objekten die Style-Eigenschaft. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | Bietet ein Interface zur Manipulation von CSS2-Eigenschaftsset-Werten im Kontext eines bestimmten HTML-Elements. |
| [ICSSCharsetRule](./icsscharsetrule/) | Das CSSCharsetRule-Interface repräsentiert eine @charset-Regel in einem CSS-Stylesheet. Der Wert des encoding-Attributs beeinflusst nicht die Kodierung von Textdaten in den DOM-Objekten; diese Kodierung ist stets UTF-16. Nachdem ein Stylesheet geladen wurde, ist der Wert des encoding-Attributs der in der @charset-Regel gefundene Wert. Wenn im Originaldokument keine @charset vorhanden war, wird kein CSSCharsetRule erstellt. Der Wert des encoding-Attributs kann auch als Hinweis für die bei der Serialisierung des Stylesheets verwendete Kodierung dienen. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | Die @counter-style-Regel ermöglicht es Autoren, einen benutzerdefinierten Zählerstil zu definieren. |
| [ICSSFontFaceRule](./icssfontfacerule/) | Das CSSFontFaceRule-Interface repräsentiert eine @font-face-Regel in einem CSS-Stylesheet. Die @font-face-Regel wird verwendet, um einen Satz von Schriftbeschreibungen zu halten. |
| [ICSSImportRule](./icssimportrule/) | Das CSSImportRule-Interface repräsentiert eine @import-Regel innerhalb eines CSS-Stylesheets. Die @import-Regel wird verwendet, um Stilregeln aus anderen Stylesheets zu importieren. |
| [ICSSKeyframeRule](./icsskeyframerule/) | Das CSSKeyframeRule-Interface repräsentiert die Stilregel für einen einzelnen Schlüssel. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | Das CSSKeyframesRule-Interface repräsentiert einen vollständigen Satz von Keyframes für eine einzelne Animation. |
| [ICSSMarginRule](./icssmarginrule/) | Das CSSMarginRule-Interface repräsentiert eine margin-At-Regel. |
| [ICSSMediaRule](./icssmediarule/) | Das CSSMediaRule-Interface repräsentiert eine @media-Regel in einem CSS-Stylesheet. Eine @media-Regel kann verwendet werden, um Stilregeln für bestimmte Medientypen abzugrenzen. |
| [ICSSPageRule](./icsspagerule/) | Das CSSPageRule-Interface repräsentiert eine @page-Regel innerhalb eines CSS-Stylesheets. Die @page-Regel wird verwendet, um die Abmessungen, Ausrichtung, Ränder usw. einer Seitenbox für paginierte Medien festzulegen. |
| [ICSSRule](./icssrule/) | Das CSSRule-Interface ist das abstrakte Basisschnittstelle für jede Art von CSS-Anweisung. Dies umfasst sowohl Regelsets als auch At-Regeln. Von einer Implementierung wird erwartet, dass sie alle im CSS-Stylesheet angegebenen Regeln beibehält, selbst wenn die Regel vom Parser nicht erkannt wird. Nicht erkannte Regeln werden mittels des ICSSUnknownRule-Interfaces dargestellt. |
| [ICSSRuleList](./icssrulelist/) | Das CSSRuleList-Interface bietet die Abstraktion einer geordneten Sammlung von CSS-Regeln. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | Das CSSStyleDeclaration-Interface repräsentiert einen einzelnen CSS-Deklarationsblock. Dieses Interface kann verwendet werden, um die derzeit in einem Block gesetzten Stil-Eigenschaften zu ermitteln oder um Stil-Eigenschaften explizit innerhalb des Blocks festzulegen. |
| [ICSSStyleRule](./icssstylerule/) | Das CSSStyleRule-Interface repräsentiert ein einzelnes Regelset in einem CSS-Stylesheet. |
| [ICSSStyleSheet](./icssstylesheet/) | Das CSSStyleSheet-Interface ist ein konkretes Interface, das verwendet wird, um ein CSS-Stylesheet zu repräsentieren, d. h. ein Stylesheet, dessen Inhaltstyp "text/css" ist. |
| [ICSSUnknownRule](./icssunknownrule/) | Die CSSUnknownRule-Schnittstelle stellt eine At-Regel dar, die von diesem User-Agent nicht unterstützt wird. |
| [ICSSValueList](./icssvaluelist/) | Die Schnittstelle bietet die Abstraktion einer geordneten Sammlung von CSS-Werten. |
| [IDocumentCSS](./idocumentcss/) | Diese Schnittstelle stellt ein Dokument mit einer CSS-Ansicht dar. |
| [IDocumentStyle](./idocumentstyle/) | Die DocumentStyle-Schnittstelle bietet einen Mechanismus, mit dem die in ein Dokument eingebetteten Stylesheets abgerufen werden können. Es wird erwartet, dass eine Instanz der DocumentStyle-Schnittstelle durch bindungsspezifische Cast-Methoden auf einer Instanz der Document-Schnittstelle erhalten werden kann. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | Inline-Stilinformationen, die an Elementen angehängt sind, werden über das style-Attribut bereitgestellt. Dies stellt den Inhalt des STYLE-Attributs für HTML-Elemente (oder Elemente in anderen Schemata oder DTDs, die das STYLE-Attribut auf dieselbe Weise verwenden) dar. |
| [ILinkStyle](./ilinkstyle/) | Die LinkStyle-Schnittstelle bietet einen Mechanismus, mit dem ein Stylesheet von dem Knoten abgerufen werden kann, der für das Verknüpfen in ein Dokument verantwortlich ist. Eine Instanz der LinkStyle-Schnittstelle kann mittels bindungsspezifischer Cast-Methoden auf einer Instanz eines verknüpfenden Knotens (HTMLLinkElement, HTMLStyleElement oder ProcessingInstruction in DOM Level 2) erhalten werden. |
| [IMediaList](./imedialist/) | Die MediaList-Schnittstelle bietet die Abstraktion einer geordneten Sammlung von Medien, ohne zu definieren oder einzuschränken, wie diese Sammlung implementiert wird. Eine leere Liste ist dasselbe wie eine Liste, die das Medium "all" enthält. |
| [IStyleSheet](./istylesheet/) | Die StyleSheet-Schnittstelle ist die abstrakte Basisschnittstelle für jede Art von Stylesheet. Sie stellt ein einzelnes Stylesheet dar, das mit einem strukturierten Dokument verknüpft ist. |
| [IStyleSheetList](./istylesheetlist/) | Die StyleSheetList-Schnittstelle bietet die Abstraktion einer geordneten Sammlung von Stylesheets. |
| [IViewCSS](./iviewcss/) | Diese Schnittstelle stellt eine CSS-Ansicht dar. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | Gibt den CSSEngine-Modus an |

---
title: "Document.GetElementById"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Document GetElementById‑Methode. Diese Methode gibt ein Element‑Objekt zurück, das das Element darstellt, dessen id‑Eigenschaft dem angegebenen String entspricht. Da Element‑IDs, falls angegeben, eindeutig sein müssen, ist dies ein nützlicher Weg, um schnell auf ein bestimmtes Element zuzugreifen."
type: docs
weight: 960
url: /de/net/aspose.svg.dom/document/getelementbyid/
---
## Document.GetElementById method

Diese Methode gibt ein [`Element`](../../element/)‑Objekt zurück, das das Element darstellt, dessen id‑Eigenschaft dem angegebenen String entspricht. Da Element‑IDs, falls angegeben, eindeutig sein müssen, sind sie ein nützlicher Weg, um schnell auf ein bestimmtes Element zuzugreifen.

Wenn Sie Zugriff auf ein Element benötigen, das keine ID hat, können Sie [`QuerySelector`](../queryselector/) verwenden, um das Element mit einem beliebigen Selektor zu finden.

```csharp
public Element GetElementById(string elementId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| elementId | String | Die ID des zu findenden Elements. Die ID ist ein case‑sensitiver String, der innerhalb des Dokuments eindeutig ist; nur ein Element kann eine bestimmte ID besitzen. |

### Rückgabewert

Ein [`Element`](../../element/)‑Objekt, das das DOM‑Element beschreibt, das der angegebenen ID entspricht, oder null, falls kein passendes Element im Dokument gefunden wurde.

## Hinweise

Siehe die offizielle [Spezifikation](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid).

### Siehe auch

* class [Element](../../element/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

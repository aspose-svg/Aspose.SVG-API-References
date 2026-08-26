---
title: "SvgRenderer.Render"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος Render του SvgRenderer. Ορίζει μέθοδο για την απόδοση πολλαπλών SVGDocuments σε συγκεκριμένο IDevice"
type: docs
weight: 20
url: /el/net/aspose.svg.rendering/svgrenderer/render/
---
## Render(*[IDevice](../../idevice/), TimeSpan, params SVGDocument[]*) {#render_6}

Ορίζει μέθοδο για την απόδοση πολλαπλών [`SVGDocument`](../../../aspose.svg/svgdocument/)s σε συγκεκριμένο [`IDevice`](../../idevice/).

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή εξόδου. |
| timeout | TimeSpan | Ένα TimeSpan που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή ένα TimeSpan που αντιπροσωπεύει -1 χιλιοστέ του δευτερολέπτου για απεριόριστη αναμονή. |
| πηγές | SVGDocument[] | Τα έγγραφα SVG για απόδοση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params SVGDocument[]*) {#render_5}

Ορίζει μέθοδο για την απόδοση πολλαπλών [`SVGDocument`](../../../aspose.svg/svgdocument/)s σε συγκεκριμένο [`IDevice`](../../idevice/), χρησιμοποιώντας ένα token ακύρωσης για να ζητήσει την ακύρωση της λειτουργίας.

```csharp
public override void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή εξόδου. |
| cancellationToken | CancellationToken | Ένα token ακύρωσης για παρακολούθηση ενώ περιμένετε να ολοκληρωθεί η εργασία. |
| πηγές | SVGDocument[] | Τα έγγραφα SVG για απόδοση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

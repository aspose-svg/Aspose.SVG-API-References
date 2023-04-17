---
title: IEventTarget.RemoveEventListener
second_title: Référence de l'API Aspose.SVG pour .NET
description: IEventTarget méthode. Cette méthode permet de supprimer les écouteurs dévénement de la cible de lévénement. Si unIEventListener est retiré dunEventTarget pendant quil traite un événement il ne sera pas déclenché par les actions en cours. Les écouteurs dévénement ne peuvent jamais être invoqués après avoir été supprimés.
type: docs
weight: 30
url: /fr/net/aspose.svg.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(string, IEventListener) {#removeeventlistener}

Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../../ieventlistener/) est retiré d'un[`EventTarget`](../../../aspose.svg.dom/eventtarget/) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| type | String | Spécifie le type d'événement du[`IEventListener`](../../ieventlistener/) en cours de suppression. |
| listener | IEventListener | Le[`IEventListener`](../../ieventlistener/) paramètre indique le[`IEventListener`](../../ieventlistener/) à supprimer. |

### Voir également

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* espace de noms [Aspose.Svg.Dom.Events](../../ieventtarget/)
* Assemblée [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_1}

Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../../ieventlistener/) est retiré d'un[`EventTarget`](../../../aspose.svg.dom/eventtarget/) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| type | String | Spécifie le type d'événement du[`IEventListener`](../../ieventlistener/) en cours de suppression. |
| listener | IEventListener | Le[`IEventListener`](../../ieventlistener/) paramètre indique le[`IEventListener`](../../ieventlistener/) à supprimer. |
| useCapture | Boolean | Spécifie si l'EventListener en cours de suppression a été enregistré en tant qu'écouteur de capture ou non. Si un écouteur a été enregistré deux fois, un avec capture et un sans, chacun doit être supprimé séparément. La suppression d'un écouteur de capture n'affecte pas une version sans capture du même auditeur, et vice versa. |

### Voir également

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* espace de noms [Aspose.Svg.Dom.Events](../../ieventtarget/)
* Assemblée [Aspose.SVG](../../../)



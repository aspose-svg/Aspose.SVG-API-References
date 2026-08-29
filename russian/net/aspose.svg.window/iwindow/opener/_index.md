---
title: "IWindow.Opener"
second_title: "Aspose.SVG для .NET справочник API"
description: "Свойство IWindow Opener. Атрибут opener IDL у объекта Window при чтении должен возвращать объект WindowProxy контекста просмотра, из которого был создан текущий контекст просмотра, его opener‑контекст, если такой существует, доступен и текущий контекст просмотра не отказался от своего opener, иначе он должен возвращать null. При установке, если новое значение равно null, текущий контекст просмотра должен отказаться от своего opener; если новое значение отличается от null, пользовательский агент должен вызвать внутренний метод DefineOwnProperty объекта Window, передавая имя свойства opener в качестве ключа свойства и дескриптор свойства Property Descriptor со значениями Value = new value, Writable = true, Enumerable = true, Configurable = true."
type: docs
weight: 60
url: /ru/net/aspose.svg.window/iwindow/opener/
---
## IWindow.Opener property

IDL‑атрибут opener у объекта Window при чтении должен возвращать объект WindowProxy контекста просмотра, из которого был создан текущий контекст просмотра (его открывающий контекст), если такой существует, он всё ещё доступен и текущий контекст просмотра не отказался от своего открывателя; в противном случае он должен возвращать null. При установке, если новое значение равно null, текущий контекст просмотра должен отказаться от своего открывателя; если новое значение отличается от null, пользовательский агент должен вызвать внутренний метод [[DefineOwnProperty]] объекта Window, передавая имя свойства "opener" в качестве ключа свойства и дескриптор свойства { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true }, где value — новое значение.

```csharp
public IWindow Opener { get; }
```

### Property Value

Опенер.

### См. также

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)

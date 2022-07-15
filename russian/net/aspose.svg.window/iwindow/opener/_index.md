---
title: Opener
second_title: Справочник по Aspose.SVG для .NET API
description: IDL-атрибут открывателя объекта Window при получении должен возвращать объект WindowProxy контекста просмотра из которого был создан текущий контекст просмотра его контекст просмотра открывателя если есть один если он все еще доступен и если текущий контекст просмотра не отказался от его открывателя в противном случае он должен возвращать значение null. При настройке если новое значение равно null текущий контекст просмотра должен отказаться от открывающего если новое значение является чем-то другим то пользовательский агент должен вызвать внутренний метод DefineOwnProperty объекта Window передав имя свойства opener в качестве ключа свойства и дескриптор свойства  Value value  Writable true Enumerable true Configurable true  в качестве дескриптора свойства где value  это новое значение.
type: docs
weight: 50
url: /ru/net/aspose.svg.window/iwindow/opener/
---
## IWindow.Opener property

IDL-атрибут открывателя объекта Window при получении должен возвращать объект WindowProxy контекста просмотра, из которого был создан текущий контекст просмотра (его контекст просмотра открывателя), если есть один, если он все еще доступен, и если текущий контекст просмотра не отказался от его открывателя; в противном случае он должен возвращать значение null. При настройке, если новое значение равно null, текущий контекст просмотра должен отказаться от открывающего; если новое значение является чем-то другим, то пользовательский агент должен вызвать внутренний метод [[DefineOwnProperty]] объекта Window, передав имя свойства «opener» в качестве ключа свойства и дескриптор свойства { [[Value]]: value , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } в качестве дескриптора свойства, где value — это новое значение.

```csharp
public IWindow Opener { get; }
```

### Стоимость имущества

Новичок.

### Смотрите также

* interface [IWindow](../../iwindow)
* пространство имен [Aspose.Svg.Window](../../iwindow)
* сборка [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
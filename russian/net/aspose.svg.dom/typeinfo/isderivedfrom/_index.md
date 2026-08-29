---
title: "TypeInfo.IsDerivedFrom"
second_title: "Aspose.SVG для .NET справочник API"
description: "TypeInfo IsDerivedFrom method. Этот метод возвращает, существует ли наследование между определением ссылочного типа, т.е. TypeInfo, на котором вызывается метод, и другим определением типа, т.е. переданным в параметрах"
type: docs
weight: 30
url: /ru/net/aspose.svg.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Этот метод возвращает, существует ли наследование между определением ссылочного типа, т.е. TypeInfo, на котором вызывается метод, и другим определением типа, т.е. переданным в параметрах.

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| typeNamespaceArg | String | пространство имён другого определения типа |
| typeNameArg | String | имя другого определения типа. |
| derivationMethod | UInt64 | тип производного и условия, применяемые между двумя типами, как описано в списке констант, предоставленном в этом интерфейсе. |

### Возвращаемое значение

Если схема документа является DTD или к документу не привязана схема, этот метод всегда возвращает false. Если схема документа — XML Schema, метод вернёт true, если определение типа ссылки выводится из другого определения типа в соответствии с параметром derivation. Если значение параметра равно 0 (ни один бит не установлен в 1 для параметра derivationMethod), метод вернёт true, если другое определение типа может быть достигнуто рекурсивным обходом любой комбинации {base type definition}, {item type definition} или {member type definitions} из определения типа ссылки.

### См. также

* class [TypeInfo](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

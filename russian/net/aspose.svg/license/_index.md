---
title: Class License
second_title: Справочник по Aspose.SVG для .NET API
description: Aspose.Svg.License сорт. Предоставляет методы лицензирования компонента.
type: docs
weight: 2190
url: /ru/net/aspose.svg/license/
---
## License class

Предоставляет методы лицензирования компонента.

```csharp
public class License
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [License](license/)() | Инициализирует новый экземпляр этого класса. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense)(Stream) | Лицензирует компонент. |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense_1)(string) | Лицензирует компонент. |

### Примеры

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей  компонент в папке, содержащей вызывающую сборку, в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

файл jar компонента:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Смотрите также

* пространство имен [Aspose.Svg](../../aspose.svg/)
* сборка [Aspose.SVG](../../)



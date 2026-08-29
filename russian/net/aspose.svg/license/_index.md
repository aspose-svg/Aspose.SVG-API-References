---
title: "Класс License"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.License. Предоставляет методы для лицензирования компонента."
type: docs
weight: 4260
url: /ru/net/aspose.svg/license/
---
## License class

Предоставляет методы для лицензирования компонента.

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
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense)(*Stream*) | Лицензирует компонент. |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense_1)(*string*) | Лицензирует компонент. |

## Примеры

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке основной сборки, а затем во встроенных ресурсах вызывающей сборки.

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

### См. также

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)

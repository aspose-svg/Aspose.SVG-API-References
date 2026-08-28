---
title: "License.SetLicense"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "License の SetLicense メソッドです。コンポーネントにライセンスを適用します。"
type: docs
weight: 20
url: /ja/net/aspose.svg/license/setlicense/
---
## SetLicense(*string*) {#setlicense_1}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(string licenseName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| licenseName | String | 完全なファイル名または短縮ファイル名、あるいは埋め込みリソースの名前を指定できます。空文字列を使用すると評価モードに切り替わります。 |

## 備考

次の場所でライセンスを検索します：

1. 明示的なパス。

2. Aspose コンポーネント アセンブリが含まれるフォルダー。

3. クライアントの呼び出し側アセンブリが含まれるフォルダー。

4. エントリ (スタートアップ) アセンブリが含まれるフォルダー。

5. クライアントの呼び出しアセンブリに埋め込まれたリソースです。

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 明示的なパス。

2. クライアントの呼び出しアセンブリに埋め込まれたリソースです。

2. Aspose コンポーネント JAR ファイルを含むフォルダーです。

3. クライアントの呼び出し JAR ファイルを含むフォルダーです。

## 例

この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で、MyLicense.lic という名前のライセンスファイルを検索しようとします。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

コンポーネントの jar ファイル:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### 参照

* class [License](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SetLicense(*Stream*) {#setlicense}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(Stream stream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | Stream | ライセンスを含むストリームです。 |

## 備考

このメソッドを使用して、ストリームからライセンスをロードします。

## 例

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);
```

### 参照

* class [License](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

# MAUIBlazorCrossPlatformTemplate
MAUI Blazor Cross Platform アプリ を作成するためのテンプレート

## 使用法

### テンプレートの取得
[MAUIBlazorXplat.nupkg](https://github.com/kznagamori/MAUIBlazorCrossPlatformTemplate/releases/download/v1.0.0/kznagamori.MAUIBlazorXplat.1.0.0.nupkg)
をダウンロードします。

### テンプレートのインストール
ダウンロードしたnugetパッケージをインストールします。
```
dotnet new install kznagamori.MAUIBlazorXplat.1.0.0.nupkg
```

### MAUI Blazor Cross Platform アプリプロジェクトの作成
```
 dotnet new  maui-blazor-xplat -n <プロジェクト名>
```
**例:** `dotnet new maui-xplat -n MyMauiXPlat`

### テンプレートのアンインストール
```
dotnet new  maui-blazor-xplat -n MyMauiBlazorXPlat
```

### ターゲット

net8.0のみをターゲットとしています。

### ビルド

```
dotnet build
```

### リリースビルド

```
publish_windows.bat
```

### kznagamori.MAUIBlazorXplat.X.X.X.nupkgの作成

```
nuget pack .\MAUIBlazorCrossPlatformTemplate.nuspec
```


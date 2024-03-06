<img src="https://github.com/LazyIonEs/AndroidToolsKit/blob/main/composeApp/launcher/icon.png" width="64" align="left" />

## AndroidToolsKit

![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/LazyIonEs/AndroidToolsKit/build-release.yml)
![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/LazyIonEs/AndroidToolsKit/total)
![GitHub Downloads (all assets, latest release)](https://img.shields.io/github/downloads/LazyIonEs/AndroidToolsKit/latest/total)
![GitHub Release](https://img.shields.io/github/v/release/LazyIonEs/AndroidToolsKit)
![GitHub License](https://img.shields.io/github/license/LazyIonEs/AndroidToolsKit)

适用于安卓开发的桌面工具，支持 Windows 和 Mac  :tada:

### 主要功能
- [x] 签名信息 - 分析(APK/签名)的签名信息（modulus、md5、sha-1、sha-256等）
- [x] APK信息 - 解析`AndroidManifest.xml`，提取部分信息
- [x] APK签名 - 对APK进行签名
- [ ] 签名生成 - 生成签名证书

### 下载安装
- [Github Releases](https://github.com/LazyIonEs/AndroidToolsKit/releases)

| 设备 | 芯片 | 下载 |
|:----:|:----:|:----:|
| windows | amd/intel | AndroidToolsKit-版本号-windows-x64.msi |
| macos | apple | AndroidToolsKit-版本号-macos-arm64.dmg |
| macos | intel | AndroidToolsKit-版本号-macos-x64.dmg |

遇到问题可以看看 [FAQ](FAQ.md) 

### 使用示例

#### 签名信息
> 支持文件拖拽
<div align="center">
  <img src=https://github.com/LazyIonEs/AndroidToolsKit/blob/main/screenshots/signature_information.gif width=100% />
</div>

#### APK信息
> 支持文件拖拽、使用前请先设置`aapt`路径
<div align="center">
  <img src=https://github.com/LazyIonEs/AndroidToolsKit/blob/main/screenshots/apk_information.gif width=100% />
</div>

#### APK签名
> 支持文件拖拽、签名校验
<div align="center">
  <img src=https://github.com/LazyIonEs/AndroidToolsKit/blob/main/screenshots/apk_signature.gif width=100% />
</div>

#### 深色模式
<div align="center">
  <img src=https://github.com/LazyIonEs/AndroidToolsKit/blob/main/screenshots/exterior.gif width=100% />
</div>

### 技术栈
- [Kotlin Multiplatform](https://kotlinlang.org/lp/multiplatform/)
- [Kotlin Coroutines](https://github.com/Kotlin/kotlinx.coroutines)
- [Compose Multiplatform](https://www.jetbrains.com/lp/compose-multiplatform/)
- [SQLDelight](https://github.com/cashapp/sqldelight)

有关所使用依赖项的完整列表，请查看 [catalog](/gradle/libs.versions.toml) 文件

### License

AndroidToolsKit is licensed under the MIT license.

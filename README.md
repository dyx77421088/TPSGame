# TPSGame
第三人称射击类的游戏[相关脚本](https://github.com/dyx77421088/TPSGameScript)
### 💻 开发软件

[![xcode-version](https://img.shields.io/badge/xcode-14.2%20-brightgreen?style=flat-square)](https://developer.apple.com/cn/xcode)
[![IDEA-version](https://img.shields.io/badge/IDEA-2022.3.3%20-brightgreen?style=flat-square)](https://www.jetbrains.com.cn/idea)
[![pycharm-version](https://img.shields.io/badge/pycharm-2022.3.3%20-brightgreen?style=flat-square)](https://www.jetbrains.com.cn/pycharm)

### 💻 开发环境

[![MacOS 13.2.1](https://img.shields.io/badge/MacOS%2013.2.1-4F4F4F?style=flat-square&logo=apple&logoColor=FFFFFF&labelColor=4F4F4F)](https://www.apple.com.cn/macos/ventura)

[![Flutter 3.7.7](https://img.shields.io/badge/Flutter%203.7.7-4F4F4F?style=flat-square&logo=flutter&logoColor=70CEF8&labelColor=4F4F4F)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart%202.19.4-4F4F4F?style=flat-square&logo=dart&logoColor=5BB3F0&labelColor=4F4F4F)](https://dart.dev)
[![SwiftUI 4.0](https://img.shields.io/badge/SwiftUI%204.0-4F4F4F?style=flat-square&logo=swift&logoColor=61D4E7&labelColor=4F4F4F)](https://developer.apple.com/cn/xcode/swiftui)
[![Swift 5.7](https://img.shields.io/badge/Swift%205.7-4F4F4F?style=flat-square&logo=swift&labelColor=4F4F4F)](https://developer.apple.com/cn/swift)
[![Django 4.14](https://img.shields.io/badge/Django%204.14-4F4F4F?style=flat-square&logo=Django&labelColor=4F4F4F)](https://www.djangoproject.com)
[![Python 3.9](https://img.shields.io/badge/Python%203.9-4F4F4F?style=flat-square&logo=Python&labelColor=4F4F4F)](https://www.python.org)

### 💻 测试环境

[![iPad 16.3.1](https://img.shields.io/badge/iPad%2016.3.1-4F4F4F?style=flat-square&logo=apple&logoColor=FFFFFF&labelColor=4F4F4F)](https://www.apple.com.cn/ipados/ipados-16)
[![iOS 16.3.1](https://img.shields.io/badge/iOS%2016.3.1-4F4F4F?style=flat-square&logo=apple&logoColor=FFFFFF&labelColor=4F4F4F)](https://www.apple.com.cn/ios/ios-16)
[![Android 13](https://img.shields.io/badge/Android%2013-00C000?style=flat-square&logo=android&logoColor=FFFFFF&labelColor=00C000)](https://www.android.com/android-13)


# 加载界面
## 进入游戏首先检测更新
![更新](https://github.com/dyx77421088/TPSGame/assets/46596598/e9fe9ba5-8baa-4cf6-8c9e-cffce3d14b95)
![更新2](https://github.com/dyx77421088/TPSGame/assets/46596598/acdb1ee4-ded2-409c-8654-c8fd59766b5c)
![更新2](https://github.com/dyx77421088/TPSGame/assets/46596598/acdb1ee4-ded2-409c-8654-c8fd59766b5c)

[![Now in Android: 55](https://i.ytimg.com/vi/BRjFy6ViTvE/maxresdefault.jpg)](https://youtu.be/BRjFy6ViTvE "加载")
# 角色状态机
## 角色主要有三种状态，为无武器状态、枪、剑。
![角色控制器1](https://github.com/dyx77421088/TPSGame/assets/46596598/3771308f-1b0a-49f1-a406-b862118f703a)
## 在枪状态中包括有，行走的混合树、跑状态的混合树、跳跃状态
![角色控制器2](https://github.com/dyx77421088/TPSGame/assets/46596598/4d05bdf7-14cf-4b13-a85a-0146477edb33)
### 通过输入横轴和纵轴控制角色的移动
![混合树1](https://github.com/dyx77421088/TPSGame/assets/46596598/be59f882-50e6-4087-988e-d8b8f2b0b5fb)  ![混合树2](https://github.com/dyx77421088/TPSGame/assets/46596598/c4bed4ae-926d-4091-85ac-7fad9be05b81)

## 在剑状态中包括有，行走的混合树、跑状态的混合树、跳跃状态、攻击状态
![剑攻击1](https://github.com/dyx77421088/TPSGame/assets/46596598/473b7177-f65d-4fd9-ade5-c3b729807fb6)
### 攻击状态中，包括有普通攻击、跑状态下点击攻击、技能攻击
![剑攻击2](https://github.com/dyx77421088/TPSGame/assets/46596598/a2e1656d-cf7e-428f-a4cf-925ac458f30b)
### 普通攻击分为三段、在短时间内点击攻击会连续打出三段攻击
![剑攻击3](https://github.com/dyx77421088/TPSGame/assets/46596598/f29feb78-3893-41f3-b9bb-09e26c5108a2)


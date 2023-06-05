## 怎么选择使用哪个版本SDK？
标准版本SDK支持全部游戏；Lite版本SDK只支持部分游戏. [详细支持游戏列表](https://docs.sud.tech/zh-CN/app/Client/StartUp.html)
## 安装方式：
### 1. 手动方式集成：
#### 下载 [SudMGP](https://github.com/SudTechnology/sud-mgp-ios/releases)
#### 下载 [SudMGPWrapper](https://github.com/SudTechnology/SudMGPWrapper)
### 2. 通过CocoaPods安装

在工程目录中的`Podfile`文件中键入以下依赖项：
#### 依赖标准版本SudMGP SDK
```ruby
pod 'SudMGPWrapper', '~> 1.3.3.2'
```
#### 依赖Lite版本SudMGP SDK
```ruby
pod 'SudMGPWrapper_Lite', '~> 1.3.3.2'
```

## 集成Demo 
### [QuickStart](https://github.com/SudTechnology/hello-sud-plus-ios/blob/master/project/QuickStart/README.md)

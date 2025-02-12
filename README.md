[English](README_en.md)
## 怎么选择使用哪个版本SDK？
标准版本SDK支持全部游戏；Lite版本SDK只支持部分游戏. [详细支持游戏列表](https://docs.sud.tech/zh-CN/app/Client/StartUp.html)
## 安装方式：

### 1. 通过CocoaPods安装

在工程目录中的`Podfile`文件中键入以下依赖项：
#### 依赖标准版本SudMGP SDK
```ruby
pod 'SudMGP', '~> 1.4.9'
pod 'SudMGPWrapper'
```
#### 依赖Lite版本SudMGP SDK
```ruby
pod 'SudMGP_Lite', '~> 1.4.9'
pod 'SudMGPWrapper_Lite'
```
### 2. 手动方式集成：
#### 下载 [SudMGP](https://github.com/SudTechnology/sud-mgp-ios/releases)
#### 下载 [SudMGPWrapper](https://github.com/SudTechnology/SudMGPWrapper)
###### 手动集成详细步骤请看 [QuickStart](https://github.com/SudTechnology/hello-sud-plus-ios/blob/master/project/Example/QuickStart/README.md)

### ASR语音识别依赖（可选）
#### 说明：
- 只有部分游戏，如你画我猜等需要通过语音命中答案时才需依赖该库
- 请参照以下pod依赖指令，请勿引用其它版本
```ruby
pod 'MicrosoftCognitiveServicesSpeech-iOS', '1.40.0'
```

## 集成Demo
### [QuickStart](https://github.com/SudTechnology/hello-sud-plus-ios/blob/master/project/Example/QuickStart/README.md)

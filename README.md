[English](README_en.md)

## 怎么选择使用哪个版本 SDK？

标准 版本 SDK 更轻量化但极小部分游戏不支持, pro 版本 SDK 支持全部游戏； [详细支持游戏列表](https://docs.sud.tech/zh-CN/app/Client/StartUp.html)

## 安装方式：

### 1. 通过 CocoaPods 安装

在工程目录中的`Podfile`文件中键入以下依赖项：

#### 依赖 标准版本 SudGIP SDK

```ruby
pod 'SudGIP', '~> 1.6.1'
pod 'SudGIPWrapper'
```

##### 依赖 pro 版本 SudGIP SDK

```ruby
pod 'SudGIP-pro', '~> 1.6.1'
pod 'SudGIPWrapper-pro'
```

### 2. 手动方式集成：

#### 下载 [SudGIP](https://github.com/SudTechnology/sud-mgp-ios/releases)

#### 下载 [SudGIPWrapper](https://github.com/SudTechnology/SudMGPWrapper)

###### 手动集成详细步骤请看 [QuickStart](https://github.com/SudTechnology/hello-sud-plus-ios/blob/master/project/Example/QuickStart/README.md)

### ASR 语音识别依赖（可选，v1.6.0 以上版本）

#### 说明：

- 只有部分游戏，如你画我猜等需要通过语音命中答案时才需依赖该库
- 请参照以下 pod 依赖指令，请勿引用其它版本

```ruby
pod 'SudASR'
```

## 集成 Demo

### [QuickStart](https://github.com/SudTechnology/hello-sud-plus-ios/blob/master/project/Example/QuickStart/README.md)

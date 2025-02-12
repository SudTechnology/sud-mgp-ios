## How do I choose which version of the SDK to use? 
The standard version of the SDK supports all games, while the Lite version of the SDK only supports some games. For a detailed list of supported games, please refer to the [Supported Games List](https://docs.sud.tech/zh-CN/app/Client/StartUp.html). 
## Installation Methods: 
### 1. Installation via CocoaPods 
 
Enter the following dependencies in the  Podfile  file in the project directory: 
#### Dependency on the Standard Version of SudMGP SDK
```ruby
pod 'SudMGP', '~> 1.4.9'
pod 'SudMGPWrapper'
```
#### Dependency on the Lite Version of SudMGP SDK
```ruby
pod 'SudMGP_Lite', '~> 1.4.9'
pod 'SudMGPWrapper_Lite'
```

### 2. Manual Integration: 
#### Download [SudMGP](https://github.com/SudTechnology/sud-mgp-ios/releases) 
#### Download [SudMGPWrapper](https://github.com/SudTechnology/SudMGPWrapper) 
###### For detailed steps on manual integration, please refer to the [QuickStart](https://github.com/SudTechnology/hello-sud-plus-ios/blob/master/project/Example/QuickStart/README.md). 

### ASR Speech Recognition Dependency (Optional)

#### Note:
- Only some games, such as Draw Something, require this library to hit the answer through voice.
- Please refer to the following pod dependency instructions. Do not refer to other versions.
```ruby
pod 'MicrosoftCognitiveServicesSpeech-iOS', '1.40.0'
```

## Integration Demo 
### [QuickStart](https://github.com/SudTechnology/hello-sud-plus-ios/blob/master/project/Example/QuickStart/README_en.md)

## How to Choose Which Version of the SDK to Use?

The standard version of the SDK is more lightweight but supports only a small number of games. The pro version of the SDK supports all games. [Detailed list of supported games](https://docs.sud.tech/en-US/app/Client/StartUp.html).

## Installation Methods:

### 1. Install via CocoaPods

In the `Podfile` file in your project directory, type the following dependencies:

#### Dependency for Standard Version SudGIP SDK

```ruby
pod 'SudGIP', '~> 1.6.1'
pod 'SudGIPWrapper'
```

##### Dependency for Pro Version SudGIP SDK

```ruby
pod 'SudGIP-pro', '~> 1.6.1'
pod 'SudGIPWrapper-pro'
```

### 2. Manual Integration:

#### Download [SudGIP](https://github.com/SudTechnology/sud-mgp-ios/releases)

#### Download [SudGIPWrapper](https://github.com/SudTechnology/SudMGPWrapper)

###### For detailed steps on manual integration, please refer to [QuickStart](https://github.com/SudTechnology/hello-sud-plus-ios/blob/master/project/Example/QuickStart/README.md).

### ASR Speech Recognition Dependency (Optional)

#### Note:

- This library is only required for certain games, such as "Guess What I Draw," when answers need to be hit through voice.
- Please refer to the following pod dependency instruction and do not reference other versions.

```ruby
pod 'SudASR'
```

## Integration Demo

### [QuickStart](https://github.com/SudTechnology/hello-sud-plus-ios/blob/master/project/Example/QuickStart/README.md)

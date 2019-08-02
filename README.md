# SingleLink
SingleLink é um framework iOS para monitorar eventos em suas aplicações.

- [Instalação](#Instalação)

## Instalação

### CocoaPods

[CocoaPods](https://cocoapods.org) é um gerenciador de dependencias para projetos Cocoa. Para uso e instalação visite o site. Para integrar o SingleLink em seu projeto Xcode usando CocoaPods, Adicione isso ao `Podfile`:

```ruby
pod 'SingleLink'
```

### Usage

Tracking on instalation
```swift

SingleLink.sharedInstance()?.trackOnInstall()

```

Tracking on create
```swift

SingleLink.sharedInstance()?.trackOnCreate()

```

Tracking  events
```swift

let dict = ["key": "Go getmo!"]
        SingleLink.sharedInstance()?.trackEvent("CLICK", withDict: dict)

```

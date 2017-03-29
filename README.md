# swviper
Swift VIPER Template for Rambler's Generamba

This is a fork from a template "swifty_viper" originally developed by Valeriy Popov.

The main differences are:
* Now all module classes have a prefix specified in Rambafile
* All protocol conformances are separated with extensions, i.e.:
```swift
// MARK: - ProtocolName
extension ClassName: ProtocolName {

}
```
* Fixed filename in the comment header section

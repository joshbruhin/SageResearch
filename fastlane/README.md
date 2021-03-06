fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
## iOS
### ios keychains
```
fastlane ios keychains
```
Create keychains to store certificates
### ios certificates
```
fastlane ios certificates
```
Fetches provisioning profile and certificates from github repo
### ios test
```
fastlane ios test
```
Execute tests
### ios build
```
fastlane ios build
```
Build target
### ios archive
```
fastlane ios archive
```
Archive and export app
### ios ci_archive
```
fastlane ios ci_archive
```
This lane is for CI bots to archive and export
### ios bump_all
```
fastlane ios bump_all
```
Bump both the framework projects
### ios bump_framework
```
fastlane ios bump_framework
```
Bump Framework Version
### ios beta
```
fastlane ios beta
```
Submit a new Build to appstore

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).

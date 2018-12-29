RxPhotos
======================================

[![CocoaPods Compatible](https://img.shields.io/cocoapods/v/RxSwiftUtilities.svg)](https://cocoapods.org/pods/RxSwiftUtilities)
[![Carthage Compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![Platform](https://img.shields.io/cocoapods/p/RxSwiftUtilities.svg?style=flat)](http://cocoadocs.org/docsets/RxSwiftUtilities)
[![Build Status](https://travis-ci.org/RxSwiftCommunity/RxSwiftUtilities.svg?branch=master)](https://travis-ci.org/RxSwiftCommunity/RxSwiftUtilities)
[![codecov](https://codecov.io/gh/RxSwiftCommunity/RxSwiftUtilities/branch/master/graph/badge.svg)](https://codecov.io/gh/RxSwiftCommunity/RxSwiftUtilities)


## About

N/A

## Usage

N/A

## Example App

N/A

## Requirements

* Xcode 10
* Swift 4.2

## Installation

### [CocoaPods](https://guides.cocoapods.org/using/using-cocoapods.html)

**Tested with `pod --version`: `1.1.1`**

In your `Podfile`:

```ruby
use_frameworks!

target "YOUR_TARGET_NAME" do
  pod "RxPhotos"
end
```

Replace `YOUR_TARGET_NAME` and then, in the same directory, run:

```shell
pod install
```

### [Carthage](https://github.com/Carthage/Carthage#installing-carthage)

**Tested with `carthage version`: `0.18`**

Add this to `Cartfile`

```
github "rpassis/RxPhotos"
```

In the same directory, run:

```shell
carthage update
```

Link/Embed frameworks as explained [here](https://github.com/Carthage/Carthage#adding-frameworks-to-an-application). Besides linking `RxPhotos`, you will also need to link `RxSwift` and `RxCocoa`.

## Contributing

Help is always appreciated!

```shell
git clone git@github.com:rpassis/RxPhotos.git
cd RxPhotos
```
> Or use your own forked repo.

```shell
carthage bootstrap
```
> This is necessary in order to be able to build the framework on its own and run tests.
However, if you prefer, you can instead develop it while it's within another project.

Before submitting a PR, please make sure that the tests pass.

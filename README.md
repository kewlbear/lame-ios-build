# lame-ios-build

script to build lame for iOS

## Usage

* build fat library for all architectures
```
./build-lame.sh
```

* build libraries for specified architectures
```
./build-lame.sh arm64 x86_64
```

* build fat library from thin libraries
```
./build-lame.sh lipo
```

## Configuration

Change variables at the beginning to suit your needs.

## Tested with

* lame 3.99.5
* Xcode 7.2

## License

Apache V2

## Feedback

Feedbacks are appreciated.

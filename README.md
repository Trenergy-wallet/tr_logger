# Logger TR.ENERGY Wallet

[TR.ENERGY Wallet](https://tr.energy/)

## Features

- log different events

## Getting started

1. Add the latest version of package to your `pubspec.yaml` and run `flutter pub get`:

```
dependencies:
  tr_logger:
```

2. Import the package in your Flutter App.

```dart
import 'package:tr_logger/tr_logger.dart';
```

## Usage

```
  InAppLogger().logInfoMessage('example', 'example message');
```
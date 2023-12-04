<!--
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages).

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages).
-->

![Screenshot](https://github.com/berkaycatak/flutter_easy_faq/assets/34205493/b26b89c8-d5ee-4c0e-b7c7-6632fe6c4932)


## Features
Prepare your animated faq list easily.

## Installation


Add package to the the pubspec.yaml.

```dart
flutter_easy_faq:
```

Import the package.

```dart
import 'package:flutter_easy_faq/easy_faq.dart';
```

## Usage

```dart
EasyFaq(
    question: "question?",
    answer: "answer.",
),
```

## Properties

```dart
  required String question;
  required String answer;
  TextStyle? questionTextStyle;
  TextStyle? anserTextStyle;
  Duration? duration = const Duration(milliseconds: 100);
  Widget? expandedIcon;
  Widget? collapsedIcon;
  Color? backgroundColor;
  BorderRadiusGeometry? borderRadius;
  EdgeInsetsGeometry? padding = const EdgeInsets.symmetric(
    horizontal: 16,
    vertical: 10,
  );
```
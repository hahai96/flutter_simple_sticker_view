# flutter_simple_sticker_view

Flutter plugin for attach stickers on image, as you want. scalable, movable. attached image can also be export.

<img src="https://img.shields.io/pub/v/flutter_simple_sticker_view.svg" />
<img src="https://img.shields.io/github/license/myriky/flutter_simple_sticker_view" />

<img width="200" src="https://user-images.githubusercontent.com/581861/68270186-e29d9680-009f-11ea-943e-50dc511c0858.png"><img width="200" src="https://user-images.githubusercontent.com/581861/68270188-e29d9680-009f-11ea-8729-a1ed7f4befa2.png"><img width="200" src="https://user-images.githubusercontent.com/581861/68270221-f812c080-009f-11ea-9be2-18d5bbf8f3b7.png">

## Getting Started

Add [flutter_simple_sticker_view](https://pub.dev/packages/flutter_simple_sticker_view) as a [dependency in your pubspec.yaml file](https://flutter.io/platform-plugins/).

Check out the example directory for a sample app.

## Usage

Import the library via

```dart
import 'package:flutter_simple_sticker_view/flutter_simple_sticker_view.dart';
```

Example :

```dart
FlutterSimpleStickerView(
    Container(
      child: Center(child: Text("Hello, World!")),
    ),
    [
      Image.asset("assets/icons8-super-mario-50.png"),
      Image.asset("assets/icons8-superman-50.png"),
      Image.asset("assets/icons8-captain-america-50.png"),
      Image.asset("assets/icons8-avengers-50.png"),
      Image.asset("assets/icons8-iron-man-50.png"),
      Image.asset("assets/icons8-batman-50.png"),
      Image.asset("assets/icons8-thor-50.png"),
      Image.asset("assets/icons8-venom-head-50.png"),
      Image.asset("assets/icons8-homer-simpson-50.png"),
      Image.asset("assets/icons8-spider-man-head-50.png"),
      Image.asset("assets/icons8-harry-potter-50.png"),
      Image.asset("assets/icons8-genie-lamp-50.png"),
      Image.asset("assets/icons8-cyborg-50.png"),
      Image.asset("assets/icons8-one-ring-50.png"),
      Image.network("https://img.icons8.com/emoji/2x/wolf-emoji.png"),
      Image.network("https://img.icons8.com/emoji/2x/tiger-emoji.png"),
    ],
  )
```

---

### Required paramsters

- **source**: The screen to attach the sticker.
- **stickerList** : List of sticker.

### Optional parameters

- **stickerSize**: default sticker size. width/height. (default is `100.0`)

- **stickerMaxScale**: maximum scale of sticker. (default is `2.0`)

- **stickerMinScale**: minimum scalof of sticker (default is `0.5`)

- **panelHeight**: sticker panel height. (default is `200`)

- **panelBackgroundColor**: background color of sticker panel.

- **panelStickerBackgroundColor**: background color of sticker in panel.

- **panelStickercrossAxisCount**: axis count of sticker (default is `4`)

- **panelStickerAspectRatio**: ratio of sticker in sticker panel. (default is `1.0`)

- **devicePixelRatio**: device pixel ratio for exporting image. (eg. `MediaQuery.of(context).devicePixelRatio`)

enjoy! 💃

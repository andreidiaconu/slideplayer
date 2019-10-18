# What is this fork?
This is a fork of [Flutter Slides](https://github.com/flutter/slideplayer), which is a Flutter App used as a slideshow for Flutter Live '18. The whole thing was a very impressive proof of concept, as the audience did not expect the presentation itself to be a flutter app running on macOS. This fork contains different slides, made by me for my own conference talks about Flutter. 

If you're still not sure what this is, I made a quick video with the slides here: [YouTube video of this project](https://youtu.be/PGb658pROWo).

- If you are interested in my slides, feel free to open up `flutter_presentation`. 
- If you want to study the code for the slides engine (yes, it's a presentation agnostic engine), then you should probably use the original for that as it might get updates as time passes: [Flutter Slides](https://github.com/flutter/slideplayer).

# Here is the original Readme

Flutter Slides utilizes [Flutter's in-progress support for Desktop](https://flutter.dev/desktop) to provide a simple slide presentation app.  Presentations are data driven from files on the disk, so users can create their own presentations without needing to update any code in the project. 

For more details on the [presentation file structure](https://github.com/flutter/slideplayer/wiki/Slide-Presentation-JSON-Structure), [animations](https://github.com/flutter/slideplayer/wiki/Slide-Presentation-JSON-Structure#animation-object), [content types](https://github.com/flutter/slideplayer/wiki/Content-Types), and [exporting and sharing a presentation](https://github.com/flutter/slideplayer/wiki/Exporting-and-Sharing-a-Presentation), see the [wiki page](https://github.com/flutter/slideplayer/wiki).

![\_](https://i.imgur.com/n3o7OZM.png)

## Features
- Supports any properly formatted presentation.  See the [wiki](https://github.com/flutter/slideplayer/wiki) for details on the file format.
- Live updates when presentation file is updated and saved
- Advancement steps
- Reveal animations
- Custom Flutter content (requires code changes)

# Getting Started

**Currently only macOS is supported.**  

## Building

### Requirements
- Flutter on the `master` channel.

### Running
Change your dir to `flutter_app` and run `flutter run`.

Once it's running, you can open the file `flutter_live.json` in the `example_presentation` folder of the root of the project as a sample.

## Running the app
1. Go to File -> Open (or tap the Open button if it is visible)
2. Select a Flutter Slides file.  An example is supplied with `flutter_live.json`  in the `example_presentation` folder located in the root of the project.  The next time you run the app, it will automatically attempt to open this file.
3. Use the controls listed below to navigate through the app.

**To advance:**
- right arrow
- or, spacebar

**To go back:**
- left arrow

**To toggle slide selector sidebar:**
- `]` to show
- `[` to hide

**To change to a new slide in sidebar:**
- `z + click` on the slide

**To present fullscreen**
- `cmd + ctl + F`
- or, select the green "full screen" button in the upper left of the window

**To leave fullscreen**
- `cmd + ctl + F`
- or, move your cursor to the top of the screen and tap the green button in upper left

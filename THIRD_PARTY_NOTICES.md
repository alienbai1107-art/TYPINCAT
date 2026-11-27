# Third-party notices

TYPING WITH LOVE uses the following third-party work. Keep this list in the shipped game
(e.g. a "Credits / Licenses" screen or a text file next to the executable).

## UniWindowController
- Source: https://github.com/kirurobo/UniWindowController
- Licence: MIT, Copyright (c) 2020 Kirurobo. Full text: [`licenses/MIT_UniWindowController.txt`](licenses/MIT_UniWindowController.txt)
- Used for the transparent, always-on-top, click-through window.

## Material Icons (Round)
- Source: https://github.com/google/material-design-icons
- Licence: Apache License 2.0. Full text: [`licenses/Apache-2.0_MaterialIcons.txt`](licenses/Apache-2.0_MaterialIcons.txt)
- File: `Assets/Resources/Fonts/MaterialIconsRound.otf` (unmodified)
- Used for the icons in the cat editor.

## Painting technique: IRCSS/TexturePaint
- Source: https://github.com/IRCSS/TexturePaint
- Licence: MIT, Copyright 2019 Shahriar Shahrabi. Full text: [`licenses/MIT_TexturePaint.txt`](licenses/MIT_TexturePaint.txt)
- The brush shader (`Assets/Resources/TWLPaintBrush.shader`) follows its approach of drawing a mesh
  into its own texture space with a brush placed on the model.

## Keyboard sound
- Source: Pixabay, "mechanical keyboard" by freesound_community
  (file `freesound_community-mechanical-keyboard-44701.mp3`)
- Licence: Pixabay Content License (free for commercial use; may not be sold or redistributed as a
  standalone sound). Cut into `Assets/Resources/KeyClicks/key_01.wav` .. `key_07.wav`.
- Keep the original download page link with the project.

## LZMA SDK (C#)
- Source: https://www.7-zip.org/sdk.html (version 26.06), by Igor Pavlov
- Licence: public domain
- Files: `Assets/Plugins/LzmaSDK/*.cs` (unmodified). Used to pack the painting of a cat shared in the Workshop.

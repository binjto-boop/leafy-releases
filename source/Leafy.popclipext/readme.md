# LeafyApp

Adds four actions for [LeafyApp](https://leafyapp.uk), a vocabulary app for macOS.

Select a word anywhere on your Mac and PopClip offers:

- **Define** &mdash; look the word up and show the definition in place
- **Translate** &mdash; translate the selection into your chosen language
- **Save** &mdash; save it straight to your Leafy library without opening a window
- **Add to Anki** &mdash; save it and make an Anki card from it

The Anki action needs Leafy connected to Anki first (Leafy &rsaquo; Settings &rsaquo;
Anki). If Anki is closed when you use it, the card is made the next time you
open Anki.

Leafy reads the sentence around the word rather than the word on its own, so the
meaning you get is the one that fits where you found it. Everything is saved to a
searchable library on your Mac.

Nothing is sent anywhere by this extension. Each action opens a `leafy://` URL,
which hands the selected text to the Leafy app running on the same machine.

## Requirements

Leafy must be installed. Free while in beta, macOS 14 or later. Download it from
[leafyapp.uk](https://leafyapp.uk).

## Author

Jtobin, <https://leafyapp.uk>

## Changelog

- 10 Aug 2026: Added the **Add to Anki** action.
- 9 Aug 2026: First submission.

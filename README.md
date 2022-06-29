# 🎨 Anki Styles

## What is Anki?

"Anki is a program which makes remembering things easy. Because it's a lot more efficient than traditional study methods, you can either greatly decrease your time spent studying, or greatly increase the amount you learn." - [apps.ankiweb.net](https://apps.ankiweb.net)

## What is included?

- Global stylesheet for all cards, used by importing stylesheet.

- Styles for cloze and basic (front and back) card types.

- Light and dark mode support

## Usage notes

Create symbolic link at %APPDATA%\Anki2\User 1\collection.media\.

`mklink %APPDATA%\Anki2\User 1\collection.media\_global.css ./src/_global.css`

Underline used to force Anki to keep and sync file despite it not being used on a note.

# 🎨 Anki Styles

## What is Anki?

"Anki is a program which makes remembering things easy. Because it's a lot more efficient than traditional study methods, you can either greatly decrease your time spent studying, or greatly increase the amount you learn." - [apps.ankiweb.net](https://apps.ankiweb.net)

## What is included?

- Global stylesheet for all cards, used by importing stylesheet.

- Styles and templates for cloze and basic (front and back) card types.

- Light and dark mode support

### Pygments syntax highlighting

```bash
python -m venv venv
pip install pygments
# Install pygments
pygmentize -S one-dark -f html -a .codehilite > _syntax.css
```

move \_syntax.css to anki media collection folder

## Usage notes

All files can be found in ./src folder.

Create symbolic link from %APPDATA%\Anki2\User 1\collection.media\ to global stylesheet in this repository for easy editing and version control.

`mklink %APPDATA%\Anki2\User 1\collection.media\_global.css ./src/_global.css`

Underline used to force Anki to keep and sync file despite it not being used on a note.

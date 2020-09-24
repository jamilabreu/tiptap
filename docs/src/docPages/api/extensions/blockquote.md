# Blockquote
The Blockquote extension enables you to use the `<blockquote>` HTML tag in the editor. This is great – you might have guessed – to use quotes in the editor.

Type <code>>&nbsp;</code> at the beginning of a new line and it will magically transform to a blockquote.

## Installation
```bash
# With npm
npm install @tiptap/extension-blockquote

# Or: With Yarn
yarn add @tiptap/extension-blockquote
```

## Settings
| Option | Type   | Default | Description                                  |
| ------ | ------ | ------- | -------------------------------------------- |
| class  | string | –       | Add a custom class to the rendered HTML tag. |

## Commands
| Command    | Options | Description                   |
| ---------- | ------- | ----------------------------- |
| blockquote | —       | Wrap content in a blockquote. |

## Keyboard shortcuts
* Windows & Linux: `Control` + `Shift` + `9`
* macOS: `Command` + `Shift` + `9`

## Source code
[packages/extension-blockquote/](https://github.com/ueberdosis/tiptap-next/blob/main/packages/extension-blockquote/)

## Usage
<demo name="Extensions/Blockquote" highlight="3-5,17,36" />
# Forge UI Snippets

This extension for Visual Studio Code adds snippets for [Forge UI](https://developer.atlassian.com/platform/forge/ui-components/). Supports .jsx file extension.

# Usage

Type part of a snippet, press enter, and the snippet unfolds.

| Shortcut Identifier | Component                                                                                       | Code                             |
| ------------------: | ----------------------------------------------------------------------------------------------- | -------------------------------- |
|             `fbtn→` | [Button component](https://developer.atlassian.com/platform/forge/ui-components/button/)        | [Button code](#ButtonCode)       |
|            `fbtns→` | [ButtonSet component](https://developer.atlassian.com/platform/forge/ui-components/button-set/) | [ButtonSet code](#ButtonSetCode) |

Alternatively, press Ctrl+Space to activate snippets from within the editor.

## Installation

1. Install Visual Studio Code 1.45.1 or higher
2. Launch VS Code
3. From the command palette Ctrl-Shift-P (Windows, Linux) or Cmd-Shift-P (macOS)
4. Select Install Extension
5. Choose the extension Forge Snippets
6. Reload VS Code

## ButtonCode

**Shortcut**: _fbtn→_

```jsx
<Button
  text="button text"
  onClick={() => console.log('perform button click action')}
/>
```

## ButtonSetCode

```jsx
<ButtonSet>
  <Button
    text="button text 1"
    onClick={() => console.log('perform button 1 click action')}
  />
  <Button
    ext="button text 2"
    onClick={() => console.log('perform button 2 click action')}
  />
</ButtonSet>
```

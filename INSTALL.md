### [Neiki's Page Editor](https://github.com/neikiri/neiki-page-editor)

#### Install

Dracula ships as a built-in theme starting with `neiki-page-editor@0.4.0` — no separate package or CSS file needed.

```bash
npm install neiki-page-editor
```

#### Activating theme

1. Pass `theme: 'dracula'` when creating the editor.

```js
import NeikiPageEditor from 'neiki-page-editor';

const editor = new NeikiPageEditor('#editor', {
  theme: 'dracula'
});
```

2. Or switch to it at runtime.

```js
editor.setTheme('dracula');
```

3. Boom! It's working ✨

You can also cycle through all built-in themes (including Dracula) with `editor.toggleTheme()`, or read the current theme with `editor.getTheme()`. See the [Themes section](https://github.com/neikiri/neiki-page-editor#themes) of the main README for the full theme API.

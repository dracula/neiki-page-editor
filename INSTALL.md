### [Neiki's Page Editor](https://github.com/neikiri/neiki-page-editor)

The Dracula Theme ships with Neiki's Page Editor 0.4.0 and later — no separate theme install is required. Clone or download this repository only if you want the theme source.

#### Install using Git

If you use Git, clone the repository and keep it up to date:

```bash
git clone https://github.com/dracula/neiki-page-editor.git
```

#### Install manually

Download the [GitHub `.zip` archive](https://github.com/dracula/neiki-page-editor/archive/main.zip) and unzip it.

#### Activating the theme

1. Make sure you are using Neiki's Page Editor 0.4.0 or later, which includes the Dracula theme.
2. Enable Dracula in one of these ways:
   - Pass `theme: 'dracula'` when creating the editor
   - Open the toolbar's **More** menu and use **Change Theme** to cycle to **Dracula**
   - Switch at runtime with `editor.setTheme('dracula')`

```js
const editor = new NeikiPageEditor("#editor", {
  theme: "dracula",
});
```

> **Note:** The selected theme is stored globally in `localStorage` only when `persistTheme: true` is enabled. If a user previously chose a different theme, that saved choice overrides the `theme` option on later loads — the config value is only the initial default.

3. Boom! It's working ✨

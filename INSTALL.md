### [Neiki's Page Editor](https://github.com/neikiri/neiki-page-editor)

The Dracula Theme ships with Neiki's Page Editor 0.4.0 and later — no separate theme install is required. Clone or download this repository only if you want the theme source.

#### Install using Git

If you are a Git user, you can clone the repo and keep it up to date:

```bash
git clone https://github.com/dracula/neiki-page-editor.git
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/dracula/neiki-page-editor/archive/main.zip) option and unzip it.

#### Activating theme

1. Make sure you're using Neiki's Page Editor 0.4.0 or later, which ships with the Dracula theme built in.
2. Pass `theme: 'dracula'` when creating the editor, open the toolbar's **More** menu and use **Change Theme** to cycle to **Dracula**, or switch to it at runtime with `editor.setTheme('dracula')`.

```js
const editor = new NeikiPageEditor("#editor", {
  theme: "dracula",
});
```

> **Note:** the selected theme is remembered globally in `localStorage` only when you enable `persistTheme: true`. If a user previously picked a different theme, that saved choice takes precedence over the `theme` option on subsequent loads — the config value only applies as the initial default.

3. Boom! It's working ✨

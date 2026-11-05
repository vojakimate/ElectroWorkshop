# Settings

Edit **ElectroWorkshop.ini** next to **ElectroWorkshop.exe** with a text editor.
Close the launcher first, save the file, then start the launcher again.
Changing these values does **not** require a new executable or repackaging.

```ini
[app]
default_language=en
remember_language=true
open_browser=true
```

| Setting | Allowed values | Default | Meaning |
|---|---|---|---|
| `default_language` | `en`, `hu` | `en` | Language used when there is no applicable remembered choice |
| `remember_language` | `true`, `false` | `true` | Whether a saved browser language takes priority |
| `open_browser` | `true`, `false` | `true` | Whether the launcher opens the browser automatically |

## Always start in English

```ini
[app]
default_language=en
remember_language=false
open_browser=true
```

This also overrides an earlier remembered Hungarian choice when opening the
starting address. You can still switch language manually while using the app.

## Start in Hungarian

Set `default_language=hu`. To enforce Hungarian on every new start regardless
of an earlier saved language, also set `remember_language=false`.

## Open the browser manually

Set `open_browser=false`, then use the launcher's **Open / Megnyitás** button.

## Missing or invalid file

If the INI is missing, the defaults are English, remembered language enabled,
and automatic browser opening enabled. Invalid values or unknown settings
produce a startup error. Preserve the `[app]` section and setting names.
Lines beginning with `;` or `#` are comments. Use a plain text file, not a Word
document, and retain the `.ini` extension.

The settings do not move or modify saved circuits. The local address remains
`127.0.0.1:18743`; the port is not configurable in this version.

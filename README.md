# blank

An empty Lumen app: one bare `<root>` and a `lumen.toml`.

Build up from here:

- Add children inside `<root>` in `src/main.lmn`.
- Add a `src/main.css` next to it; it is picked up automatically.
- Attach a script with `<script src="main.cdl" />` (or `.rhai` / `.lua`),
  written beside the markup in `src/`.

Run it:

```sh
lumenc run .
```

# prettier-astro

Configures Astro project to successfully use `prettier` and `prettier-plugin-astro` to format Astro files.

Make sure you're running the prerelease version of the Astro VSCode extension.

Files will format using the Astro VSCode extension when you save them.

You can also format files using the prettier CLI using `pnpm format`.

If you want to format `.astro` files in VSCode, remove

```json
  "[astro]": {
    "editor.defaultFormatter": "astro-build.astro-vscode"
  }
```

in the [vscode settings](./.vscode/settings.json).

# fulgurite registry

What fulgurite offers to install, as GitHub repositories released as `v<version>` tags. The app reads each one's
package.json on its default branch for the newest version.

- [`plugins.json`](plugins.json): Settings › Plugins. Each repository has a package.json and a built main.js.
  [api](https://github.com/fulgurite-plugin/fulgurite-api) says how to make and publish one.
- [`themes.json`](themes.json): Settings › Theme. Each repository has a package.json with `"theme": true` and a
  theme.json; any `fulgurite-theme-*` repository here shows how (its README describes the format).

The two lists stay apart: the app shows only plugins from `plugins.json` and only themes from `themes.json`, and refuses
to install a theme as a plugin or a plugin as a theme.

To add one, open a pull request that appends its repository URL to the list it belongs in.

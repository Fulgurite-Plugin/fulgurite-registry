# fulgurite plugin registry

[`plugins.json`](plugins.json) lists the plugins fulgurite offers in Settings › Plugins: GitHub repositories, each with
a package.json and a built main.js, released as `v<version>` tags. The app reads each one's package.json on its default
branch for the newest version. [api](https://github.com/fulgurite-plugin/fulgurite-api) says how to make and publish one.

To add a plugin, open a pull request that appends its repository URL.

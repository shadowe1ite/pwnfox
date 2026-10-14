# PwnFoxy

Caido plugin for the [PwnFoxy](https://github.com/la1n23/PwnFoxy) browser extension.

Colors HTTP request rows based on the `X-PwnFoxy-Color` header that PwnFoxy injects per Firefox container.

All 8 Firefox container colors are supported: blue, turquoise, green, yellow, orange, red, pink, purple.

## Install

Build the plugin and load `dist/plugin_package.zip` in Caido under Plugins.

## Usage

Enable the passive workflow from the Workflows page. Requests with `X-PwnFoxy-Color` headers will be colored automatically.

## Build

```
pnpm install
pnpm build
```

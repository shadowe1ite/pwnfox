# PwnFoxy for Caido

Caido plugin for [PwnFoxy](https://github.com/la1n23/PwnFoxy), a maintained fork of PwnFox with improved UX and extra features.

Automatically colors HTTP request rows based on the `X-PwnFoxy-Color` header that PwnFoxy injects per Firefox container.

### Supported colors

blue, turquoise, green, yellow, orange, red, pink, purple (all 8 Firefox container colors).

### Not PwnFox

This plugin is for **PwnFoxy**, not PwnFox. PwnFoxy uses different headers (`X-PwnFoxy-Color` instead of `X-PwnFox-Color`) and supports all 8 container colors. If you're using the original PwnFox extension, use the [PwnFox Caido plugin](https://github.com/caido-community/pwnfox) instead.

## Install

Install from the Caido plugin store, or build manually and load `dist/plugin_package.zip` under Plugins.

## Usage

Enable the passive workflow from the Workflows page. Requests from PwnFoxy containers will be colored automatically.

## Build

```
pnpm install
pnpm build
```

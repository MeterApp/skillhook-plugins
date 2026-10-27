# Skillhook plugin

Webhook in, agent out. Set up secure webhooks on your own machine, write Agent Skills, and operate your Skillhook Cloud organisation.

## Install

```text
/plugin marketplace add MeterApp/skillhook-plugins
/plugin install skillhook@meterapp-skillhook
```

The plugin launches the pinned npm package `@meterapp/skillhook@0.14.2` with npx and includes three skills and two MCP servers (local and cloud). Node.js 22 or later is required. Cloud access is optional; run `skillhook cloud login` to sign in.

[Website](https://skillhook.dev) · [Documentation](https://skillhook.dev/docs) · [Source and support](https://github.com/MeterApp/skillhook) · [Privacy](https://skillhook.dev/privacy) · [Terms](https://skillhook.dev/terms)

This repository is generated from [MeterApp/skillhook](https://github.com/MeterApp/skillhook) with `scripts/publish-plugins.mjs`. Make changes there and republish; do not edit this mirror. Only plugin assets and supporting documentation are published here.

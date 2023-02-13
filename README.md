# Renovate Config

This repository contains my shared [renovate-bot](https://docs.renovatebot.com) configuration for all my projects. You are welcome to use this in your own projects or copy my configurations, though you may want to override the timezone and schedule.

## Usage

See [here](https://docs.renovatebot.com/getting-started/installing-onboarding) for information on adding renovate-bot to a repository.

Once set up it will create an onboarding PR and a default `renovate.json` file for you. I usually move this file to `.github/renovate.json` if possible.

Example `renovate.json`:

```json
{
  "extends": ["github>jcwillox/renovate-config"]
}
```

You can add the following to enable one of the more specific presets.

```json
{
  "extends": ["github>jcwillox/renovate-config:js-lib"]
}
```

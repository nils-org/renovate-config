# renovate-config

This is a [shared preset](https://docs.renovatebot.com/config-presets/) to be used across the organization.
It will be auto-selected as a preset when onboarding new projects in the organization.

Alternatively, use it like so:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [ "github>nils-org/renovate-config:minimal" ]
}
```

## Existing presets

Name | Description
---------|-------
 minimal | This is the minimal base configuration.
 default | This is the default: For legacy reasons it points to "legacy".
 legacy  | This is the old or legacy config. Better move away from it.

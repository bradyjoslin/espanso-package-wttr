# espanso-package-wttr

An espanso package for getting the weather from [Igor Chubin's](https://github.com/chubin) console-oriented weather service [wttr.in](https://wttr.in).

For more information about espanso packages, read the [documentation](https://espanso.org/docs/).

## Usage

Available replacement examples:

```text
  :wttr                 Spring, United States: ⛅️  +80°F
  :moonphase            🌕
  :wttrat/dallas/      dallas: ☀️ +88°F
```

`:wttrat` uses [passive replacement](https://espanso.org/docs/passive-mode/), so it is triggered by highlighting the text and double tapping your configured passive key.

## Dependencies

Passive replacement should be enabled in the espanso `default.yaml` configuration file:

```yaml
enable_passive: true
passive_key: CTRL
```

Requires `curl`.

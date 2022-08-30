# A temporary alternative for HomeAssistant `feedreader` component

See https://github.com/home-assistant/core/pull/77547 for details.

## Install

- Clone the component to your custom_components/ dir

```sh
$ cd path/to/config/custom_components
$ git clone https://github.com/likeablob/hass-feedreader-tempfix.git feedreader_tempfix
```

- Open your `configuration.yaml` and prefix `feedreader` with `_tempfix` as follows.

```yaml
feedreader_tempfix:
  urls:
    - https://example.com/feed.xml
```

- Restart your HA instance and have fun!
  - You may also want to edit your automation triggers to use `feedreader_tempfix`.

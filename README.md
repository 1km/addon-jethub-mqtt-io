![alt text][logo]

# Home Assistant Add-on: JetHome JetHub peripheral exposer

## About

Expose [JetHub](http://jethome.ru) resources (relays,inputs,etc..) to
Home Assistant via [mqtt-io](https://github.com/flyte/mqtt-io)

**Note**: _All used GPIOs will **disappear** from **/sys/class/gpio** during addon run_

[:books: Read the full add-on documentation][docs]

## Supported devices:

### [JetHome JetHub D1](http://jethome.ru/jethub-d1) (Basic version with 3 relays, 4 inputs and 1-wire).

**Exposed peripheral:**

- 3 relays
- 4 inputs
- internal stat LED (green/red)

- added zigbee boot and reset 

**Note**: _You still need to use native Home Assistant [1-Wire](https://www.home-assistant.io/integrations/onewire/) integration to expose 1-Wire device
like temperature sensors `DS18B20`_

## Installation

Add the repository URL under **Supervisor → Add-on store → ⋮ → Manage add-on repositories**:

    https://github.com/jethome-hassio-addons/repository

# Issues

If you find any issues with the add-on, please check the
[issue tracker](https://github.com/jethome-hassio-addons/addon-jethub-mqtt-io/issues)
or similar issues before creating one.

## JetHome resources:

- Documentation - https://wiki.jethome.ru
- Official website - http://jethome.ru
- Telegram news channel - https://t.me/jethome_news
- Telegram official chat - https://t.me/jethomeru
- GitHub: https://github.com/jethome-ru

[docs]: https://github.com/jethome-hassio-addons/addon-jethub-mqtt-io/blob/main/jethub-mqtt-io/DOCS.md
[logo]: jethub-mqtt-io/logo.png "JetHub mqtt-io"

[![Build Status](https://travis-ci.com/OpenXbox/xboxone-home-assistant.svg?branch=master)](https://travis-ci.com/OpenXbox/xboxone-home-assistant)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)
[![homeassistant community](https://img.shields.io/badge/support-homeassistant-blue)](https://community.home-assistant.io/t/hass-io-add-on-xbox-one/63750)
[![Discord](https://img.shields.io/discord/338946086775554048)](https://openxbox.org/discord)


# Xbox One Smartglass integration for Home Assistant

This repo includes the custom media player integration and a
dockerized version of the Xbox One Smartglass REST server to
use with HASS.io.

## IMPORTANT
- You need both, HACS addon and HASS.io ADDDON
- Yes, this addon / plugin currently is in a miserable state. Either fix it yourself and send a Pull Request or wait for the rewrite.

## General

The component is based on the python library [xbox-smartglass-core](https://github.com/OpenXbox/xbox-smartglass-core-python)
by [Team OpenXbox](https://openxbox.org).

Cheers to [Jason Hunter](https://github.com/hunterjm) for developing and maintaining the `Xbox One -> Home Assistant`
integration.

Home Assistant community thread: [Forum](https://community.home-assistant.io/t/hass-io-add-on-xbox-one/63750).

## Custom component

* Install via [HACS](https://hacs.xyz/docs/publish/start) or manually: see [Custom component info](info.md).

The component currently still requires an installed/running daemon of **Xbox Smartglass REST server**.

## Hass.io addon

The hass.io-dockerized version of the required **Xbox Smartglass REST server** service.

Check out: [Addon README](hassio/README.md).

## Credits

- Jason Hunter ([@hunterjm](https://github.com/hunterjm)) - Creator of custom component & Hass.io addon
- Eric Leblanc ([@ericleb010](https://github.com/ericleb010)) and [@jmhill1287](https://github.com/jmhill1287) - Maintaining & giving user support

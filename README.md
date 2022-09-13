[![GitHub Release](https://img.shields.io/github/release/Vaskivskyi/ha-chroma.svg?style=for-the-badge&color=blue)](https://github.com/Vaskivskyi/ha-chroma/releases) [![License](https://img.shields.io/github/license/Vaskivskyi/ha-chroma.svg?style=for-the-badge&color=yellow)](LICENSE)<a href="https://github.com/Vaskivskyi/ha-chroma/actions/workflows/build.yaml"><img src="https://img.shields.io/github/workflow/status/Vaskivskyi/ha-chroma/Build?style=for-the-badge" alt="Build Status" align="right" /></a><br/>
<!--[![HACS Default](https://img.shields.io/badge/HACS-default-blue.svg?style=for-the-badge)](https://hacs.xyz) [![Community forum discussion](https://img.shields.io/badge/COMMUNITY-FORUM-success?style=for-the-badge&color=yellow)](https://community.home-assistant.io/t/custom-component-asusrouter-integration/416111)--><a href="https://www.buymeacoffee.com/vaskivskyi" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee" style="height: 28px !important;" align="right" /></a>

## Control your Chroma-enabled devices from Home Assistant

`Chroma` is a custom integration for Home Assistant to control your Razer Chroma-enabled devices using the [AIOChroma](https://github.com/Vaskivskyi/aiochroma) python library.

## Installation

#### HACS

You can add this repository (https://github.com/Vaskivskyi/ha-chroma) to your HACS as a custom repository.

#### Manual

Copy content of `custom_components/chroma/` to `custom_components/chroma/` in your Home Assistant folder.

## Usage

After Chroma is installed, you can add your device from Home Assistant UI.

[![Open your Home Assistant instance and start setting up a new integration.](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start/?domain=chroma)

To connect you need to provide the following data:
- IP address or hostname
- Which devices you want to control (e.g. `chromalink`, `headset`, `keyboard`, `keypad`, `mouse`, `mousepad`)
- Layout of your keyboard (if the `keyboard` option is selected)

[![Open your Home Assistant instance and show your integrations.](https://my.home-assistant.io/badges/integrations.svg)](https://my.home-assistant.io/redirect/integrations/)

#### Lights

Integration provides a light entity per each device selected during the configuration process. Every entity supports `rgb_color` and `brightness` attributes.

## Support the integration

This integration is a free-time project. If you like it, you can support me by buying a coffee.

<a href="https://www.buymeacoffee.com/vaskivskyi" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee" style="height: 60px !important;"></a>

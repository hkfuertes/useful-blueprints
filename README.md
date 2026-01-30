# Useful Blueprints

A collection of [Home Assistant](https://www.home-assistant.io/) automation blueprints for controlling IKEA smart home devices via [Zigbee2MQTT](https://www.zigbee2mqtt.io/).

## Blueprints

### IKEA Symfonisk GEN2 - Media Controller

**File:** `blueprints/symfonisk_z2m.yml`

Controls a media player using the IKEA Symfonisk sound remote GEN2 (E2123). Supports play/pause, next/previous track, volume control (single press and hold), and configurable actions for the single and double dot buttons (single press, double press, long press).

### IKEA BILRESA E2490 - Scroll Wheel Remote

**File:** `blueprints/bilresa_wheel_z2m.yaml`

Multi-mode controller for the IKEA BILRESA E2490 scroll wheel remote. The scroll wheel can operate in different modes: brightness, volume, color temperature, and hue. Double-pressing the ON button cycles through modes. Includes an optional auto-reset to a default mode after a configurable inactivity timeout.

### IKEA Dual Button Remote - Light Control

**File:** `blueprints/ikea_dual_remote_light_z2m.yaml`

Simple light control using IKEA dual-button remotes. Press ON to turn on (with optional forced brightness), press OFF to turn off, and hold to gradually dim up or down. Supports multiple compatible remotes controlling the same light:

- IKEA RODRET wireless dimmer
- IKEA SOMRIG shortcut button (E2213)
- IKEA TRADFRI on/off switch (E1743)
- IKEA BILRESA remote control (E2489)

## Usage

Import a blueprint into Home Assistant by navigating to **Settings > Automations & Scenes > Blueprints** and using the import URL pointing to the raw YAML file in this repository.

# homeassistant

This repository contains blueprints for lights management.

## Principle

1. Each room is independant, and must have a Dimmer and a motion sensor
2. Light will depend on cloud cover, window, and sun
3. Manual override is possible

## How it works

TBD

## How to setup

TBD

## Blueprints

### Light management

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Ffrancois09%2FHA_BP_light%2Fblob%2Fmain%2Fcontrol.yaml)

This blueprint manage light intensity, light on and light off depending on multiple factors, like occupancy detection, blind room (no window), button pressed, etc.


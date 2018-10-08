***************
WARNING: THIS REPOSITORY IS DEPRECATED
====================================
This component has been merged into [Home Assistant](https://github.com/home-assistant/home-assistant/blob/dev/homeassistant/components/light/opple.py) and this repository is no longer being maintained.
***************

[Home Assistant](https://www.home-assistant.io/) component of [opple](http://www.opple.com/) devices

# Supported Devices

All opple light with WIFI support (mobile control)

e.g.
![demo](https://img.alicdn.com/imgextra/i2/138006397/TB2mgp_XSOI.eBjSspmXXatOVXa_!!138006397.jpg)
![demo2](https://img.alicdn.com/imgextra/i3/138006397/TB2etN_XHOJ.eBjy1XaXXbNupXa_!!138006397.jpg)

# Install
copy the `custom_components` to your home-assistant config directory.

# config
Add the following to your configuration.yaml file:
```yaml
light:
  - platform: opple
    name: light_1
    host: 192.168.0.101
  - platform: opple
    name: light_2
    host: 192.168.0.102
```

CONFIGURATION VARIABLES:

- name
  (string)(Optional)The display name of the light

- host
  (string)(Required)The host/IP address of the light.

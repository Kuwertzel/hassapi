## [Home Assistant](https://www.home-assistant.io/) Web API Client for Python
[![PyPI - Downloads](https://img.shields.io/pypi/dm/hassapi?style=flat-square)](https://pypistats.org/packages/hassapi)

## Examples
```python
from hassapi import Hass

hass = Hass(hassurl="http://IP_ADDRESS:8123/", token="YOUR_HASS_TOKEN")

hass.turn_on("light.bedroom_light")
hass.run_script("good_morning")
```
## Installation
The following command installs the base version of hassapi (https://github.com/hass-api/hassapi/), not this extended version. This version is not available via pip.
```
pip install hassapi
```

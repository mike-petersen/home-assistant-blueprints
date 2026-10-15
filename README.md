# Home Assistant Blueprints

Some Home Assistant Blueprints I use

## Motion Light

This triggers a light depending on a motion sensor.
It uses a Night Mode to define the color (Night = red, Day = White)

[Import Blueprint to Home Assistant: Motion Light](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fmike-petersen%2Fhome-assistant-blueprints%2Fblob%2Fmain%2Fblueprints%2Fmike%2Fmotion-light.yaml)

## Motion Light White

This triggers a light depending on a motion sensor.

[Import Blueprint to Home Assistant: Motion Light White](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fmike-petersen%2Fhome-assistant-blueprints%2Fblob%2Fmain%2Fblueprints%2Fmike%2Fmotion-light-white.yaml)

## Window Control

One automation per room for everything around a window: turns the heater off while the
window is open and back on with the set point after it closes, raises a cold warning
(helper, notification, sound) while the window is open and both room and outside are cold,
and gives open/close hints based on the absolute humidity difference to the outside.
Notifications and sounds only play within the active hours.
Replaces the combination of Heater Window and Notify Humidity.

[Import Blueprint to Home Assistant: Window Control](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fmike-petersen%2Fhome-assistant-blueprints%2Fblob%2Fmain%2Fblueprints%2Fmike%2Fwindow-control.yaml)

## Heater Window

Disables the heater if window is opened and reenables it afterwords.
We have a heat pump and due to that we want to turn on the heater everytime after the window closes.

[Import Blueprint to Home Assistant: Heater Window](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fmike-petersen%2Fhome-assistant-blueprints%2Fblob%2Fmain%2Fblueprints%2Fmike%2Fheater-window.yaml)

## Notify Humidity

This triggers open/close window notification depending on the humidity difference.

[Import Blueprint to Home Assistant: Notify Humidity](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fmike-petersen%2Fhome-assistant-blueprints%2Fblob%2Fmain%2Fblueprints%2Fmike%2Fnotify-humidity.yaml)

## Warning Light

This triggers a warning light (blinking) if a condition is met.

[Import Blueprint to Home Assistant: Warning Light](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fmike-petersen%2Fhome-assistant-blueprints%2Fblob%2Fmain%2Fblueprints%2Fmike%2Fwarning-light.yaml)

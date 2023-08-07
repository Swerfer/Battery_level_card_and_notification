# Battery level card and notification
This Home Assistant card shows the battery levels below a slider-adjustable percentage of all battery powered devices and sends a notification if one or more battery levels are 10% or less.

![alt Battery level card and notification](https://github.com/Swerfer/Battery_level_card_and_notification/blob/main/images/battery%20level%20card.png?raw=true)

## Prerequisites

•	[Auto-entities card](https://github.com/thomasloven/lovelace-auto-entities )

## How to install

•	Copy the YAML from binary_sensor.yaml and past it in your binary_sensor.yaml file.

•	Copy the YAML from input_number_helpers.yaml and past it in your input_number_helpers.yaml file.

•	Create a new empty automation, go in the YAML editor and past the YAML from the automations.yaml file.

•	Change the entity of the service to the notify entity of your choice.

•	Do a quick reload of the YAML configurations (Settings --> Restart Home Assistant --> Quick reload)

•	Go to the dashboard of your choice, add a new manual card and past the YAML from card.yaml in the YAML editor.

•	Save the card and you’re done.

## Buy me a coffee
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/Swerfer)

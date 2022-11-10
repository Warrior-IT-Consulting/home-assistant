# Home-Assistant

A collection of yaml `templates` to use with [Home Assistant](https://www.home-assistant.io)

## Templates

- A custom sensor to report the current kWh rate for an Economy 7 electricity meter 
  - `sensor-template_economy-7-rates.yaml`
  - __NOTE__: This does not take into account any daily standing charges.

- A set of custom sensor to report the current usage and cost of an Economy 7 electricity meter
  - `sensor-template_smart-meter-economy-7.yaml`
  - Additional sensors to track the cost savings using electricity during the off-peak rate over the peak rate.
  - Another sensor added to track the cost of usage using a single rate electricity meter
    - This helps to see if an Economy 7 meter is more cost effective optio for you usage.

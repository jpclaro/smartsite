# smartsite
text
# header 1
text 1
## header 2
text 2
### header 3

Is this an autolink? #1
@jpclaro
bli bla blubb#1
#1  

```yaml
esp32_touch:
  setup_mode: false
  id: touch_id
  sleep_duration: 400ms
  #measurement_duration: 1ms
  iir_filter: 10ms
  high_voltage_reference: 2.4V

binary_sensor:
  - platform: esp32_touch
    name: "below 100"
    id: "capacity_100"
    pin: GPIO15
    threshold: 650
```

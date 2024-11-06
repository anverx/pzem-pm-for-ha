# pzem-pm-for-ha
Instuctions for assembly of a power monitor device and integrating it with the Home Assistant

![Alt text](./images/pzem1.jpg "Overview")
## Intro

## BOM

| Component | Part name | Estimated Price (€) |
| --- | --- | --- |
| PZEM |  PZEM-004T | 6 |
| ESP32 | LOLIN32 | 3 |
| 3V power supply|Hi Link HLK-2M03 | 1.8 |


## Assembly


## Configuration and integration
Initialize the device as normal in ESPHome, then paste the following configuration.  Mind the secrets.
https://github.com/anverx/pzem-pm-for-ha/blob/8432b941a5b6da3bcee31511ecdca133065c0c4d/power_monitor.yaml#L1-L6

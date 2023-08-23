![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
```
Topic: v1cdti/hw/get/6310301006/Get hardware level/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301006",
    "model"     : "Top-load washing machine",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "118"
}
```

## Get firmware version
```
Topic: v1cdti/hw/set/6310301006/firmware/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301006",
    "model"     : "firmware",
    "serial"    : "WSH-SN01",
    "name"      : "firmware version",
    "value"     : "24.0"
}
```

## Get manufacture id and geo-location or location placement
```
Topic: v1cdti/hw/set/6310301006/manufacture id/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301006",
    "model"     : "Top-load washing machine",
    "serial"    : "WSH-SN01",
    "name"      : "manufacture id",
    "value"     : "114.114"
}
```

## Set geo-location or location placement
```
Topic: v1cdti/hw/set/6310301006/location placement/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301006",
    "model"     : "Top-load washing machine",
    "serial"    : "WSH-SN01",
    "name"      : "location_placement",
    "value"     : "Bangkok"
}
```

## Monitor machine sensor
```
Topic: v1cdti/hw/set/6310301006/Monitor machine sensor/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301006",
    "model"     : "Top-load washing machine",
    "serial"    : "WSH-SN01",
    "name"      : "Monitor_machine_sensor",
    "value"     : "25"
}
```

## Set machie status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1cdti/hw/set/6310301006/Monitor machine sensor/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301006",
    "model"     : "Top-load washing machine",
    "serial"    : "WSH-SN01",
    "name"      : "maint",
    "value"     : "67"
}
```

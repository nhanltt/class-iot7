![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
```
Topic: v1cdti/hw/get/6310301021/model-01/SN001
Payload: {
    "action"    : "get",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"      : "wash_count",
    "value"     : "114"
}
```

## Get firmware version
```
Topic: v1cdti/hw/get/6310301021/model-01/SN001
Payload: {
    "action"    : "get",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"      : "firmware",
    "value"     : "01"
}
```

## Get manufacture id and geo-location or location placement
```
Topic: v1cdti/hw/get/6310301021/model-01/SN001
Payload: {
    "action"    : "get",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"      : "manufacture_id",
    "value"     : "LG0001",
    "lattitude" : "16.01",
    "longitude" : "100.056"
}
```

## Set geo-location or location placement
```
Topic: v1cdti/hw/set/6310301021/model-01/SN001
Payload: {
    "action"    : "set",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "lattitude"  : "16.01",
    "longitude"  : "100.056"
}
```

## Monitor machine sensor
```
Topic: v1cdti/app/monitor/6310301021/model-01/SN001/wash_mode
Payload: {
    "action"    : "monitor",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"      : "wash_mode"
    "value" : "wool/silk"
}

Topic: v1cdti/app/monitor/6310301021/model-01/SN001/job_mode
Payload: {
    "action"    : "monitor",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"      : "job_mode"
    "value"     : "running"
}

Topic: v1cdti/app/monitor/6310301021/model-01/SN001/water_fresh
Payload: {
    "action"    : "monitor",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"      : "water_fresh"
    "value"     : "90"
}

Topic: v1cdti/app/monitor/6310301021/model-01/SN001/water_flow
Payload: {
    "action"    : "monitor",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"      : "water_flow"
    "value"     : "on"
}

Topic: v1cdti/app/monitor/6310301021/model-01/SN001/water_level
Payload: {
    "action"    : "monitor",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"      : "water_level"
    "value"     : "10"
}

Topic: v1cdti/app/monitor/6310301021/model-01/SN001/weight
Payload: {
    "action"    : "monitor",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"      : "weight"
    "value"     : "15"
}

Topic: v1cdti/app/monitor/6310301021/model-01/SN001/door_status
Payload: {
    "action"    : "monitor",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"      : "door_status"
    "value"     : "locked"
}

Topic: v1cdti/app/monitor/6310301021/model-01/SN001/motor_speed
Payload: {
    "action"    : "monitor",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"      : "motor_speed"
    "value"     : "100.50"
}

Topic: v1cdti/app/monitor/6310301021/model-01/SN001/motor_direction
Payload: {
    "action"    : "monitor",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"      : "motor_direction"
    "value"     : "clock-wise"
}

Topic: v1cdti/app/monitor/6310301021/model-01/SN001/vibration
Payload: {
    "action"    : "monitor",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"      : "vibration"
    "value"     : "10"
}

Topic: v1cdti/app/monitor/6310301021/model-01/SN001/temperature
Payload: {
    "action"    : "monitor",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"      : "temperature"
    "value"     : "30"
}

Topic: v1cdti/app/monitor/6310301021/model-01/SN001/usage_count
Payload: {
    "action"    : "monitor",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"      : "usage_count"
    "value"     : "110"
}

Topic: v1cdti/app/monitor/6310301021/model-02/SN003/balance
Payload: {
    "action"    : "monitor",
    "project"   : "63010301021",
    "model"     : "model-02",
    "serial"    : "SN003",
    "name"      : "balance"
    "value"     : "1"
}

```

## Set machine status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1cdti/hw/set/6310301021/model-01/SN001
Payload: {
    "action"    : "set",
    "project"   : "63010301021",
    "model"     : "model-01",
    "serial"    : "SN001",
    "name"  : "status",
    "value"  : "maint"
}
```

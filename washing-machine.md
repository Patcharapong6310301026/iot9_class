# Washing machine state

## START
topic:v1cdti/app/get/1212312121/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301026",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "START"
}

## READY
topic:v1cdti/app/get/1212312121/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301026",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "READY"
}

## FILLWATER
topic:v1cdti/app/get/1212312121/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301026",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "FILLWATER"    
}

## HEATWATER
topic:v1cdti/app/get/1212312121/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301026",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "HEATWATER"    
}

## WASH
topic:v1cdti/app/get/1212312121/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301026",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "WASH"   
}

## RINSE
topic:v1cdti/app/get/1212312121/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301026",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "RINSE"    
}

## SPIN
topic:v1cdti/app/get/1212312121/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301026",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "SPIN"    
}

# Operation state

## DOORCLOSE
topic:v1cdti/app/set/1212312121/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301026",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "DOORCLOSE"    
}

## WATERFULLLEVEL
topic:v1cdti/app/set/1212312121/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301026",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "WATERFULLLEVEL"    
}

## TEMPERATUREREACHED
topic:v1cdti/app/set/1212312121/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301026",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "TEMPERATUREREACHED"    
}


# FAULT state

## TIMEOUT
topic:v1cdti/app/get/1212312121/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301026",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "TIME_OUT"   
}

## OUTOFBALANCE
topic:v1cdti/app/set/1212312121/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301026",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "OUT_OF_BALANCE"    
}

## MOTORFAILURE
topic:v1cdti/app/set/1212312121/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301026",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "MOTOR_FAILURE"    
}

## FAULTCLEARED
topic:v1cdti/app/set/1212312121/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301026",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "FAULT_CLEARED"    
}
---
title: "Rules_GetRuleDevicesID"
description: ''
---调用该接口。



## Request


```
get /rules/{id}/devices_id_array
```

| Name | Located in | Type | Description | 
| ---- | ---------- | ----------- | ----------- | 
| id | path | string |  |  

## Response

### Response  200 
| Code2 | Description | Type | Schema |
| ---- | ----------- | ------ | ------ |
| 200 | A successful response. | Object | [ruleRuleDevicesIDResp](#ruleRuleDevicesIDResp) |

#### ruleRuleDevicesIDResp

| Name | Type | Description | 
| ---- | ---- | ----------- |        
| devices_ids | Array[ string ] |  |    



### Response  default 
| Code2 | Description | Type | Schema |
| ---- | ----------- | ------ | ------ |
| default | An unexpected error response. | Object | [rpcStatus](#rpcStatus) |

#### rpcStatus

| Name | Type | Description | 
| ---- | ---- | ----------- |     
| code | integer |  |          
| details | Array[protobufAny] |  [ 具体参数可见下面 [protobufAny](#protobufAny) ] |       
| message | string |  |   

### protobufAny
| Name | Type | Description | 
| ---- | ---- | ----------- |     
| @type | string |  |   




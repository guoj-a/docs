---
title: "OauthAuthenticate"
description: 'oauth authenticate with header Authorization'
---调用该接口oauth authenticate with header Authorization。



## Request


```
get \oauth\authenticate
```

## Response

### Response  200 
| Code2 | Description | Type | Schema |
| ---- | ----------- | ------ | ------ |
| 200 | OK | Object | [apioauthv1AuthenticateResponse](#apioauthv1AuthenticateResponse) |

#### apioauthv1AuthenticateResponse

| Name | Type | Description | 
| ---- | ---- | ----------- |     
| avatar | string |  |      
| expires_in | string |  |      
| external_id | string |  |      
| nick_name | string |  |      
| tenant_id | string |  |      
| user_id | string |  |      
| username | string |  |   



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




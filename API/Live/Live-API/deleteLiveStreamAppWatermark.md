# deleteLiveStreamAppWatermark


## 描述
删除app水印配置

## 请求方式
DELETE

## 请求地址
https://live.jdcloud-api.com/v1/watermarkApps/{publishDomain}/appNames/{appName}/templates/{template}

|名称|类型|是否必需|默认值|描述|
|---|---|---|---|---|
|**appName**|String|True| |直播流所属应用名称|
|**publishDomain**|String|True| |推流加速域名|
|**template**|String|True| |转码模版|

## 请求参数
无


## 返回参数
|名称|类型|描述|
|---|---|---|
|**requestId**|String|ruquestId|
|**result**|Result| |

### Result
|名称|类型|描述|
|---|---|---|
|**feedback**|Boolean|返回结果|

## 返回码
|返回码|描述|
|---|---|
|**400**|Invalid parameter|
|**401**|Authentication failed|
|**404**|Not found|
|**503**|Service unavailable|
|**200**|OK|
|**500**|Internal server error|
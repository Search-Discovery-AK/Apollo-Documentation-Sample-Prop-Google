# User Registered

### 

## Javascript Code
```js
window.dataLayerGoogle = window.dataLayerGoogle || [];
dataLayerGoogle.push({
  "event": "sign_up",
  "detailed_event": "User Registered",
    "user_data": {
        "user_attributes": "<user_attributes>",
        "user_id": "<user_id>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user_data.user_attributes|string|Attributes of the application user|homeStore\~234\|loyaltyTier\~gold\|memberSince\~2002|||||||
|user_data.user_id|string|The id of the user currently logged in to the site, if the site offers authentication and the user is authenticated.|123456, abc123|||||||





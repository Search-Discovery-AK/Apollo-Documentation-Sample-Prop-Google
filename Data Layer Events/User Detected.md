# User Detected

### 

## Javascript Code
```js
window.dataLayerGoogle = window.dataLayerGoogle || [];
dataLayerGoogle.push({
  "event": "detect_user",
  "detailed_event": "User Detected",
    "user_data": {
        "anonymous_user_id": "<anonymous_user_id>",
        "user_id": "<user_id>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user_data.anonymous_user_id|string|When a user is not logged in, this captures an anonymous user ID.||||||||
|user_data.user_id|string|The id of the user currently logged in to the site, if the site offers authentication and the user is authenticated.|123456, abc123|||||||





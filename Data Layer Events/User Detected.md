# User Detected

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "detect_user",
  "apollo_event": "User Detected",
    "user": {
        "affiliateCustomerID": "<affiliateCustomerID>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliateCustomerID|string|The user ID of user who arrived at the website via a third party partner.||||||||





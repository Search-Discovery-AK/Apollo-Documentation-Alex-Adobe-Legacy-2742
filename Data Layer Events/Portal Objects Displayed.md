# Portal Objects Displayed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "view_component",
  "apollo_event": "Portal Objects Displayed",
    "portalDisplayed": {
        "portalObject": [
            {
                "isDisplayed": <isDisplayed>,
                "portalObjectId": "<portalObjectId>"
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|isDisplayed|boolean|Helper node used by AA Product String Builder to set product scoped events|true|||||||
|portalObjectId|string|Unique identifier of a portal object|My Accounts, Transactions, Messages, My Reports|||||||





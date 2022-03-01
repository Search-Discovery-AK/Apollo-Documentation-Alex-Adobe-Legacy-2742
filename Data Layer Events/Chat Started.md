# Chat Started

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "chat_start",
  "apollo_event": "Chat Started",
    "chat": {
        "portalID": "<portalID>",
        "serviceLine": "<serviceLine>",
        "sessionID": "<sessionID>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|portalID|string|Identifies the specific chat portal used||||||||
|serviceLine|string|Identifies the specific chat portal used||||||||
|sessionID|string|Identifies the specific chat session||||||||





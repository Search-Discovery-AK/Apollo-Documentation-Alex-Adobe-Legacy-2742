# Order Confirmation Interaction Occurred

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "order_confirmation_interaction",
  "apollo_event": "Order Confirmation Interaction Occurred",
    "orderConfirmationInteraction": {
        "interactionType": "<interactionType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|interactionType|string|Type of click event engaged with by the user on the order confirmaton page.||||||||





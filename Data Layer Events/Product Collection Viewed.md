# Product Collection Viewed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "view_item_list",
  "apollo_event": "Product Collection Viewed",
    "product": [
        {
            "productInfo": {
                "productID": "<productID>"
            }
        }
    ],
    "productCollection": {
        "name": "<name>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|name|string|The name of the product collection|Back to School, New Grad, Gifts for Her|||||||
|productID|string|Unique Identifier of a product or offering.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level above SKU for products with SKU variants. |155, 65588, 987764448|||||||





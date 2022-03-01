# Cart Viewed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "view_cart",
  "apollo_event": "Cart Viewed",
    "cart": {
        "cartID": "<cartID>",
        "item": [
            {
                "productInfo": {
                    "brand": "<brand>",
                    "isBackOrdered": <isBackOrdered>,
                    "productID": "<productID>"
                }
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|brand|string|Describes the brand of a product or offering.|Ford, Chevrolet, Dodge, Levis, Columbia, Patagonia|||||||
|cartID|string|Back-end identifier for a shopping cart|12345, 435678, 34567, XCV456, XCV876|||||||
|isBackOrdered|boolean|Boolean flag indicating that an inventoried product is on backorder|TRUE, FALSE|||||||
|productID|string|Unique Identifier of a product or offering.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level above SKU for products with SKU variants. |155, 65588, 987764448|||||||





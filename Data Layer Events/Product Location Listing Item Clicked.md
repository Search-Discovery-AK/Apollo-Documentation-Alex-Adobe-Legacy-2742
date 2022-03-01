# Product Location Listing Item Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "select_item",
  "apollo_event": "Product Location Listing Item Clicked",
    "listingItemClicked": {
        "filterList": "<filterList>",
        "listing": [
            {
                "productInfo": {
                    "brand": "<brand>",
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
|filterList|string|A twice delimited string of filterType and filterValue pairs.  Use \~ between type and value.  Use \| between pairs|sort\~price ascending\|color\~green\|size\~medium|||||||
|productID|string|Unique Identifier of a product or offering.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level above SKU for products with SKU variants. |155, 65588, 987764448|||||||





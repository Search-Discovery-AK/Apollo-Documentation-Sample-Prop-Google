# Internal Campaign Clicked

### 

## Javascript Code
```js
window.dataLayerGoogle = window.dataLayerGoogle || [];
dataLayerGoogle.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayerGoogle.push({
  "event": "select_promotion",
  "detailed_event": "Internal Campaign Clicked",
    "ecommerce": {
        "creative_slot": "<creative_slot>",
        "items": [
            {
                "item_id": "<item_id>",
                "item_name": "<item_name>",
                "location_id": "<location_id>"
            }
        ],
        "promotion_id": "<promotion_id>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|ecommerce.creative_slot|string|The name of the promotional creative slot associated with the event.||||||||
|ecommerce.items[n].item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\)|SKU\_12345|||||||
|ecommerce.items[n].item_name|string|Item Name \(context-specific\).|jeggings|||||||
|ecommerce.items[n].location_id|string|Captures a unique ID of a physical location such as a store, banking branch, atm, hotel, office, or other.|155, 65588, 987764448|||||||
|ecommerce.promotion_id|string|Captures the ID associated with internal campaigns. Used for internal campaign impressions and clicks only.|2345, 56789, 9876|||||||





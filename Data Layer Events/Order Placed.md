# Order Placed

### 

## Javascript Code
```js
window.dataLayerGoogle = window.dataLayerGoogle || [];
dataLayerGoogle.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayerGoogle.push({
  "event": "purchase",
  "detailed_event": "Order Placed",
    "ecommerce": {
        "cart_id": "<cart_id>",
        "coupon": "<coupon>",
        "currency": "<currency>",
        "items": [
            {
                "item_id": "<item_id>",
                "item_name": "<item_name>"
            }
        ],
        "transaction_id": "<transaction_id>",
        "value": <value>
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|ecommerce.cart_id|string|Captures the name or ID of the region within which CTA links are used.|12345, 435678, 34567, XCV456, XCV876|||||||
|ecommerce.coupon|string|Order-level coupon code used for a purchase.|summer\_fun|||||||
|ecommerce.currency|string|The currency, in 3-letter ISO 4217 format.||||||||
|ecommerce.items[n].item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\)|SKU\_12345|||||||
|ecommerce.items[n].item_name|string|Item Name \(context-specific\).|jeggings|||||||
|ecommerce.transaction_id|string|The unique identifier of a transaction.|T\_12345, 19283j2nm9jdjs|^[a-zA-Z0-9]{6,20}$|6|20||||
|ecommerce.value|number|The monetary value of the event.|7.77, 239.55, 659|||||||





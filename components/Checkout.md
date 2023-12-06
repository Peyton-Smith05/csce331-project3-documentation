# Checkout

## Methods

<!-- @vuese:Checkout:methods:start -->
|Method|Description|Parameters|
|---|---|---|
|toggle|Toggles the translation of checkout details between English and Spanish.|-|
|confirmOrder|Confirms the order, posts it to a server, and redirects to the home page.|-|
|translateES|Translates checkout details to Spanish.|-|
|originalValue|Reverts the checkout details to their original values (English).|-|

<!-- @vuese:Checkout:methods:end -->


## Computed

<!-- @vuese:Checkout:computed:start -->
|Computed|Type|Description|From Store|
|---|---|---|---|
|total|-|Computes the total cost of the order including the subtotal, tax, and tip.|No|

<!-- @vuese:Checkout:computed:end -->


## Data

<!-- @vuese:Checkout:data:start -->
|Name|Type|Description|Default|
|---|---|---|---|
|currentState|`Boolean`|Represents the current state for language translation.|false|
|checkoutDetails|`Array`|Details and labels used in the checkout process.|[Checkout,Your Cart,Subtotal,Tax,Total,Tip,Pickup Time,Please select one,Confirm Order]|
|cartItems|`Array`|The list of items in the cart.|-|
|subtotal|`Number`|Subtotal of the cart items.|0|
|tax|`Number`|Tax applicable on the cart items.|0|
|tip|`Number`|Tip amount entered by the user.|0|
|empid|`Number`|Employee ID handling the order.|0|
|selectedPickupTime|`String`|Selected pickup time for the order.|-|
|pickupTimes|`Array`|Available pickup times for the order.|[9:00 AM,10:00 AM,11:00 AM,12:00 PM,1:00 PM,2:00 PM,3:00 PM,4:00 PM]|

<!-- @vuese:Checkout:data:end -->



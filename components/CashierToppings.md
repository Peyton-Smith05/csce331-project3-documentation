# CashierToppings

## Events

<!-- @vuese:CashierToppings:events:start -->
|Event Name|Description|Parameters|
|---|---|---|
|sendOrder|-|-|

<!-- @vuese:CashierToppings:events:end -->


## Methods

<!-- @vuese:CashierToppings:methods:start -->
|Method|Description|Parameters|
|---|---|---|
|fetchToppings|Fetches topping options from the server.|whatToFetch - The API endpoint to fetch toppings from.|
|closeToppingInterface|Closes the topping selection interface.|-|
|submitOrder|Submits the selected order options and navigates back to the menu items page.|-|

<!-- @vuese:CashierToppings:methods:end -->


## Computed

<!-- @vuese:CashierToppings:computed:start -->
|Computed|Type|Description|From Store|
|---|---|---|---|
|toppingsOptions|-|Computes and returns the topping options available for selection.|No|

<!-- @vuese:CashierToppings:computed:end -->


## Data

<!-- @vuese:CashierToppings:data:start -->
|Name|Type|Description|Default|
|---|---|---|---|
|selectedSize|`String`|Selected options for the order.|-|
|sizeOptions|`Array`|Available options for each category.|[Medium,Large]|

<!-- @vuese:CashierToppings:data:end -->



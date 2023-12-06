# CustomerToppings

## Props

<!-- @vuese:CustomerToppings:props:start -->
|Name|Description|Type|Required|Default|
|---|---|---|---|---|
|options|An array of strings representing the labels for different customization options and buttons.|`Array`|`false`|["Order Details","Size","Temperature","Sugar Level","Ice Level","Toppings","Done"]|
|optionDetails|An array of strings detailing the options available for size, temperature, ice level, etc.|`Array`|`false`|["Medium","Large","Hot","Cold","None","Less","Regular"]|

<!-- @vuese:CustomerToppings:props:end -->


## Events

<!-- @vuese:CustomerToppings:events:start -->
|Event Name|Description|Parameters|
|---|---|---|
|sendOrder|-|-|

<!-- @vuese:CustomerToppings:events:end -->


## Methods

<!-- @vuese:CustomerToppings:methods:start -->
|Method|Description|Parameters|
|---|---|---|
|fetchToppings|Fetches available toppings from the provided API endpoint.|-|
|closeToppingInterface|Closes the topping interface and navigates back to the menu items page.|-|
|submitOrder|Submits the customized order and navigates back to the menu items page.|-|

<!-- @vuese:CustomerToppings:methods:end -->


## Computed

<!-- @vuese:CustomerToppings:computed:start -->
|Computed|Type|Description|From Store|
|---|---|---|---|
|toppingsOptions|-|Computes the options for toppings based on the data fetched from the API.|No|

<!-- @vuese:CustomerToppings:computed:end -->


